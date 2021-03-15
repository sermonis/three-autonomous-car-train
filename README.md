Simulator
Car “Simulator use the fuzzy control system, genetic algorithm and particle swarm
optimization to simulate the movement of the autonomous car on the” map.
Input contains the car's “three distance sensors (front, 45 degrees left and right),
which can be achieved from the defined equation of motion, the car's position and
the angle between the car and” the horizontal axis. Output is steering wheel rotation
angle.
The goal is to “hit the end line without hitting the wall and output the trajectory of
motion (including the position of each point in time , the value of the sensor and
the angle of rotation of the steering wheel) as a text file, then display” on the
graphical interface.
Fuzzy control system:
Fuzzy “control system uses the custom seven fuzzy rules and discrete center of
gravity” defuzzifier.
Function:
• fuzzyStart()
• fuzzyControl()
• discreteCenterOfMass()
• fuzzyRulesCenter()
• fuzzyRulesRight()
• fuzzyRulesLeft()

Genetic algorithm:
Car Simulator “uses the real-evaluated Genetic Algorithm (GA) to train the Radial
Base Function Network (RBFN) and RBFN controls” the vehicle. The gene is
defined as three parameters of mixed-dimensional vector RBFN (w, m, σ). The
fitness “function in the input case is the mean variance of the predicted output of the
data” set and the RBFN” value. The lowest ifitness value is the best RBFN” parameter.
Particle Swarm Optimization:
Car Simulator “can also use PSO (Particle Swarm Optimization) for RBFN”
preparation. The PSO “coordinate is defined as the three mixed dimension vector
parameters of” RBFN (w, m, σ). For the input case, the fitness function “is the mean
variance of the predicted value of the data collection and the RBFN” value. The
lowest fitness rating is the good parameter for RBFN.Buttons:
1. Status
2. Control button
3. Camera first person / third person switch
4. Rotation angle of steering wheel and moving speed
5. Start the fuzzy control system
6. RBFN parameters setting
7. GA parameters setting
8. PSO parameters setting
9. Save the trajectory and data
10. Operating instructions
11. Graphic interface
