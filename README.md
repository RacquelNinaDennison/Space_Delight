# Space_Delight
My first ever GameJam with Sozolabs. This game was build in unity using C# to adjust and control the game mechanics 

## Link to the game :)
https://racquelninadennison.itch.io/sallys-delightful-adventures


# Project Title

The aim of this project was to create a robot machine that could beat all the other robots in robocode. 

## Description

** The Architecture of the agent ** 
The robot is designed to be able to use all of the components of its body. 
The gun arm moves freely of the robot body and the body moves freely of the gun. 
The gun is caculated to point in the direction of the enemy, that it came into contact with upon scanning it. 

The body moves away from the enemy or towards the enemy based on whether the enemy robot is shooting at the other robot. 
The body is also programmed to zig zag in between the enemy shooting bullets to make it hard to move. 

** The strategies and tactics employeed ** 

The strategy for Beast the robot was the act of continuious movement. My robot always kept moving in order to 
avoid the other robots bullets. Because there was always a delay with the bullets shot, it is possible to move 
away from the other enemies bullets in an adequte time and this was what I leveraged on. 

Another implementation for the bot was redirecting towards the enemy. When a shot was detected coming towards the 
bot, it would aim its gun at the other bots and then fire towards them, while moving away from the enemy. If Beast's energy levels were too low, 
it would avoid the enemy and then shoot from a different angle. This was detected by monitoring it's energy level.


## Getting Started

### Dependencies

* JAVA JDK, JRE
* Windows 10 on windows 
* macOS 12 for Apple
* Robocode application - link: https://sourceforge.net/projects/robocode/files/
* It is adviced to download a version lower as it works better :)  

### Installing

* In order to use the BeastPackage robot, move the downloaded java file from the download files to the 
* robocode file found in the OS directory
* Store the Beast package under robots in the robocode directory 


```

## Authors

Contributors names and contact info

Racquel Dennison  
racquelnina@gmail.com

## Problems experienced

There were a bit of problems faced while doing this assignment.  Loadshedding was a problem. Although I was adviced on the 
time of the assignment, loadshedding was still an issue with connectivity, unfortunately. 

The general game mechanics were something to wrap my head around. I felt quite overwhelmed by the task and I 
think I over complicated it for myself and as a results affect my quality of work delivered. 

Overall, it was a very enjoyable task and I am definitely going to come back to it to try an better my bot. 




Thank you for taking the time to review my code and my application for the BDD bursary. 
