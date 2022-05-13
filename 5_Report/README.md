# ABSTRACT

A wiper is an important part of a vehicle's windscreen that removes rain or any other liquid. Manual wiper activation was required in the old approach,
and elevating the wiper was difficult. As a result, this approach is being promoted as a potential solution to these issues. 
The project's objectives are to provide wiping systems for older cars, improve the system by employing actuators and pull switches
(using the same switch for many purposes by stepwise switching), and manage engine and wiper speed with a single switch. In reaction to the amount of rain, 
this system controls the wiper's working speed. The major function of the Wiper Speed Control System is to remove rain air drops from the windshield of all types
of vehicles.

# INTRODUCTION

Wipers are mounted on all heavy motor vehicles, including cars, trucks, railroad locomotives, and some aircraft.
After reading various research articles, I realised that safety standards for motor vehicles in inclement weather are important even at low speeds, 
therefore I began developing a wiper control system employing arm-based microcontrollers.
Rubber blades are affixed to the metal arms, while pivot magnets are attached to the other ends.
Finally, this project application assists users in their daily lives by preventing accidents and allowing for safe and healthy travel.

# DESCRIPTION 

In cars, a wiper control system replaces the standard wiper blade with an electrical component. In this setup, the ignition button (on the motor) will be 
controlled by a single switch in the ACC position. Switch on the wiper system with a second press, then vary the wiper speed with a third press, and finally
turn off the motor with a fourth press. All of this was done with the help of LEDs and a simulation tool.

# FEATURES

For a specified frequency, blue, green, and orange LEDs turn on and off alternately. The RED led will be on in state A. Circuit design is simple and straightforward. 
The car will be locked when the button is pressed ONCE.
The car will open when the button is pressed TWICE.
It will turn on and move clockwise after being pressed three times.
It will wiper off and move in an anticlockwise direction after being pressed FOUR times.
The wiper will finish one cycle if the button is pressed FIVE times.

# SWOT ANALYSIS

![image](https://user-images.githubusercontent.com/101012637/168273783-f0ec54bc-2bd7-4729-a057-01b1e7a7ed67.png)

## STRENGTH 

There is no requirement for human interaction.
Viper systems from many vehicles can be interfaced and managed.
A basic User Button allows for easy control and usage of functions.
Cost-effective.

## WEAKNESSES

Instead of employing Delays, Timers/Interrupts may be a better option.
Limited range of application.
User privacy and security are compromised.


## OPPORTUNITIES

Viper Management and Control System has a broad scope in the future of automobiles. Because advanced features can raise the value of a car.

## THREATS 

In the automobile development industry, there are now many new emerging gadgets for competition.


# 4W'S AND 1H

## WHAT ?

A wireless key controls the Viper of an automobile under the Viper Control system. LEDs will indicate the state of the viper
.
## WHY ?

To understand the idea underlying a Viper system and to modify its speed according to the needs of the user.

## WHO?

People who all own automobiles. Everyone who drives a motor vehicle and needs a good view of the road.

## WHERE ?

The user can use the features supplied anywhere they wish.

## HOW ?

Through the use of a single button. The location of the wiper is shown by an LED, which returns to its original position after cleaning the windsheet of a car.


#  LOWLEVEL REQUIREMENTS

<html>
<body>
<!--StartFragment-->

ID | Low Level Requirements 
-- | --
LLR1 | Press button 2 seconds RED LED will ON 
LLR2 | Press button 2 seconds RED LED will OFF
LLR3 | Wipers movement at 1 hertz
LLR4 | Wipers movement at 4 hertz
LLR5 | Wipers movement at 8 hertz
  

<!--EndFragment-->
</body>
</html>

# HIGHLEVEL REQUIREMENTS

<html>
<body>
<!--StartFragment-->

ID | Description | status
-- | -- | --
HLR 1 | Car Lock | Applied
HLR2  | Wipers Control speed | Applied
HLR3 | Wiper System ON | Applied
HLR4 |  Wiper System. OFF | Applied

<!--EndFragment-->
</body>
</html>


# BLOCK DIAGRAM

![Block Diagram](https://user-images.githubusercontent.com/101012637/168311862-3216ab87-81e1-405e-a5f0-5bc22c9f768b.png)

# INPUT

![LED OFF](https://user-images.githubusercontent.com/101012637/168314188-834491ef-a954-4c32-9f40-f62edd7bedff.jpeg)

# BEHAVIOURAL DIAGRAM


## LOWLEVEL FLOW CHART 

![Lowlevel flow chart](https://user-images.githubusercontent.com/101012637/168312274-fd059ca9-d8fc-40bf-aeb5-06bd9a62c2d8.png)


## HIGHLEVEL FLOW CHART

![Highlevel flow chart](https://user-images.githubusercontent.com/101012637/168312504-929c95c4-35d8-41d9-83ca-d72640107a20.png)





