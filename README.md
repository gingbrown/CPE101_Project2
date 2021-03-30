# CPE101_Project2

Project Description: 
You are part of a team writing a program that simulates landing the Lunar Module (LM) from the Apollo
space program on the moon. The simulation picks up when the retrorockets cut off and the
pilot/astronaut takes over control of the LM. The user of the simulator specifies the initial amount of fuel
and initial altitude. The LM starts at a user-specified altitude with an initial velocity of zero meters per
second and has a user-specified amount of fuel on board.
The manual thrusters are off and the LM is in free-fall -- meaning that lunar gravity is causing the LM to
accelerate toward the surface according to the gravitational constant for the moon. The pilot can control
the rate of descent using the thrusters of the LM. The thrusters are controlled by entering integer values
from 0 to 9 which represent the rate of fuel flow. A value of 5 maintains the current velocity, 0 means
free-fall, 9 means maximum thrust -- all other values are a variation of those possibilities and can be
calculated with an equation that is provided below.
To make things interesting (and to reflect reality) the LM has a limited amount of fuel -- if you run out of
fuel before touching down you have lost control of the LM and it freefalls to the surface.
The goal is to land the LM on the surface with a velocity between 0 and -1 meters per second, inclusive,
using the least amount of fuel possible. A landing velocity between -1 meters per second and -10 meters
per second (exclusive) means you survive but the LM is damaged and will not be able to leave the
surface of the moon -- you will be able to enjoy the surface of the moon as long as your oxygen lasts but
you will not leave the moon alive. Velocities faster than (less than) or equal to -10 meters per second
mean the LM sustains severe damage and you die immediately.
The initial conditions of 1300 meters altitude and 500 liters of fuel were used in the original, and were
chosen so that an optimal landing should use approximately 300 liters of fuel. It's a considerable
challenge at first, and you may enjoy trying it.
FYI: This program is modeled after a version that was popular on HP-28S programmable calculators in
the 1970s. It is interesting to note that the desktop computers you are working on cost about the same
amount (unadjusted for inflation) as the calculators did but are quite a bit more powerful (more memory,
storage, computational power, not to mention more sophisticated display, keyboard, mouse, et cetera).
This program took approximately 90 seconds to load on the calculator -- virtually instantaneous on the
machines you are running on today. Credits to Dick Nungester of HP for the provided equations.
