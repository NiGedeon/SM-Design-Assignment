NIBYAYO Gedeon  26016
Gishushu Traffic Lights State Machine


specification (narration) of Gishushu Traffic Lights

The state diagram for this scenario is designed using the timer-based state-dependent dynamic interaction model (SDDIM).There are four states in this scenario and the four states with their explanations are as follows:


State 1: North-South straight & Left Turn and South-North straight & right Turn

Duration: 30 seconds

Allowed Movements: Vehicles moving from North-South direction and they can also turn left as well as vehicles moving from South-North direction and they can also turn to their right.

Traffic Light Status:
Green light for north-south straight and left turns as well as for south-north straight and right turns.
Red light for all other directions.

Transition: After 30 seconds, transition to State 2.




State 2: West-East straight, West-North Turn and West-South turn

Duration: 30 seconds

Allowed Movements: Vehicles moving from West-East direction and they can also turn from west to north or turn from west to south.

Traffic Light Status:
Green light for West-East straight and West-north turns as well as for West-south turns.

Red light for all other directions.

Transition: After 30 seconds, transition to State 3.



State 3: East-West straight & East-North Turn and East-South turn

Duration: 30 seconds

Allowed Movements: Vehicles moving from East-West direction and they can also turn from east to north or turn from east to south.

Traffic Light Status:
Green light for East-West straight and East-north turns as well as for East-south turns.
Red light for all other directions.

Transition: After 30 seconds, transition to State 4.




State 4: North-East turn and South-West turn

Duration: 30 seconds

Allowed Movements: Vehicles moving from the North-East direction and the ones moving from South-West direction.

Traffic Light Status:
Green light for the North-East direction and the South-West direction.
Red light for all other directions.

Transition: After 30 seconds, transition to State 1.
