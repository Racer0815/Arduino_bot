# Arduino_bot
Ein Arduino gesteurtes Fahrzeug mit HC SR-04 Sensoren.


Das Arduino Fahrzeug besitzt 3 Ultraschall Hc-SR-04 Sensoren, welche vorne und hinten
angebracht sind, und somit ein sehr großes Sichtfeld des Fahrzeuges ermöglichen. Diese
Sensoren führen ca. 9 Messungen pro Sekunde aus um die Bewegung von sich schnell
bewegenden Objekte optimal zu erfassen. Zwischen den Messungen überprüft das Fahrzeug,
ob sich Objekte in der geplanten Fahrstrecke befinden. Wenn ein Objekt sich in einer
Distanz von 15 bis 30 cm Entfernung befindet, wird automatisch ein Ausweichmanöver in
eine andere Richtung gestartet. Wenn sich ein Objekt in einer Reichweite von unter 15 cm
befindet, versucht das Fahrzeug nach hinten auszuweichen. Sollte sich aber hinter dem
Fahrzeug keine 15cm Platz befinden, so bleibt das Fahrzeug stehen, und muss durch einen
Knopfdruck wieder entsichert werden. Die Status LED auf dem Fahrzeug, zeigt zudem den
Status des Fahrzeuges an. Ist diese grün, so bedeutet dies, dass das Fahrzeug ohne Probleme
funktioniert. Ist die Status LED rot bedeutet dies, dass das Fahrzeug entweder keinen
Ausweg aus einer Situation gefunden hat, oder dass es durch Knopfdruck in den sicheren
Modus gesetzt wurde.