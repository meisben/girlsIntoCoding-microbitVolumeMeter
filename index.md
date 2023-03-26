---
layout: page
title: Volume Meter using the MicroBit
---

<!--Comment: Above here is the header, we need this to generate the web page-->

<!--Comment: This section is markdown-->

[![logoPicture](images/girlsIntoCodingLogo.jpg)](https://www.girlsintocoding.com/)

A project activity for [Girls Into Coding](https://www.girlsintocoding.com/)

This session is designed to be fun! The idea is that we can follow it together in a class, but that we can also be free to move at our own pace. We're going to be doing some basic python programming in this activity. You also have the opportunity to use the make code block based programming language. So whatever your level, you have lots of options! 

The idea with this acitivity isn't to become an ACE programmer inside 2 hours, but it's just to get an **appreciation** of programming robots. So that you can use this knowledge for good in the future :)! 

<!--Comment: End of markdown section-->

<!--Comment: This code here is html-->

<!--Comment: This is html paragraph spacing <br>-->
<br>

<!--Comment: This is html bootstrap-->
<div class="container p-3 my-3 bg-primary">
<h2>Contents</h2>
<ul class="list-group">
  <li class="list-group-item"><a href="#Begin">Begin: Check you have the right equipment</a></li>
  <li class="list-group-item"><a href="#Activity1">Activity 1: Let's boot up the microbit and check it is working</a></li>
  <li class="list-group-item"><a href="#Activity2">Activity 2: How do we measure a sound?</a></li>
  <li class="list-group-item"><a href="#Activity3">Activity 3: Display a chart displaying the volume of the sound</a></li>
  <li class="list-group-item"><a href="#Activity4">Activity 4: Let’s make a motor move</a></li>
  <li class="list-group-item"><a href="#Activity5">Activity 5: The definition of angles</a></li>
  <li class="list-group-item"><a href="#Activity6">Activity 6: Creating a volume meter - step 1</a></li>
  <li class="list-group-item"><a href="#Activity7">Activity 7: Creating a volume meter - step 2</a></li>
</ul>
</div>

<div id="resourcesPanel" class="container p-3 my-3 bg-info">
<h2>Resources</h2> 
  <p>Here's some resources that may help with the activity</p>
<ul class="list-group">
  <a href="https://www.w3schools.com/python/" target="_blank" class="list-group-item list-group-item-action">Python tutorials at W3 Schools</a>
  <a href="https://www.pythoncheatsheet.org/" target="_blank" class="list-group-item list-group-item-action">Python cheatsheet</a>
</ul>
</div>

<!--Comment: This is the end of html bootstrap-->


<!--Comment: Paragrpah spacing-->
<br>
<br>

<!--Comment: This section is markdown again-->

# Let's begin
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Begin" class="container p-3 my-3 bg-primary text-primary">
<h2>Begin</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

## First lets check you have the right equipment, you should find the following items in your box

* 1 x Micro:bit
* 1 x USB cable
* 1 x Kitronik robotics board
* 1 x Battery pack
* 1 x Sound level indicator (wooden laser cut)
* 1 x Servo motor and stand
* 1 x Servo motor arm

## About the Micro:bit
If you haven't used one before then take a look at this video

<iframe width="852" height="479" src="https://www.youtube.com/embed/u2u7UJSRuko" title="Introduction to the BBC micro:bit" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
</iframe>

## Go to Microsoft MakeCode
* Plug your microbit into the computer using the supplied usb lead
* Browse to the website [https://makecode.microbit.org/](https://makecode.microbit.org/)
* Click on *New Project*
* Name it 'helloWorld' or something else you choose

## Tour of Microsoft MakeCode
* Simulator - on the left side of the screen, you will see a virtual micro:bit that will show what your program will look like running on a micro:bit. This is helpful for debugging, and instant feedback on program execution. 
* Toolbox - in the middle of the screen, there are a number of different categories, each containing a number of blocks that can be dragged into the programming workspace on the right.
* Workspace - on the right side of the screen is the Programming Workspace where you will create your program. Programs are constructed by snapping blocks together in this area.

[![ideTour](images/ide-tour.png)](https://makecode.microbit.org/)

The features highlighted here are:

1. Go to the Home Screen to start a new project or open an existing project
2. Simulator shows what your program will look like when running on a micro:bit
3. Hide or Show the simulator pane
4. Program in either Blocks or JavaScript
5. Programming Workspace where you will build you program
6. Blocks Toolbox
7. Download your program to the micro:bit
8. Name your project and Save it on your computer


*Note: in all of the following activities you can choose to use python or MakeCode blocks for programming the micro:bit. Choose whatever you feel is the right language for your level*

[![languageChange](images/change_makeCode_language.png)](https://makecode.microbit.org/)

## How to download your code to your micro:bit
There are two options (explained on this [page](https://microbit.org/get-started/first-steps/set-up/)). If you don't know - just ask a mentor

<!--Comment: End of markdown-->

<!--Comment: Paragrpah spacing-->
<br>
<br>

<!--Comment: This section is markdown again-->

# Let's boot up the microbit and check it is working
---

<!--Comment: End of markdown-->


<!--Comment: Back to html bootstrap -->

<div id="Activity1" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #1</h2>
</div>

<!--Comment: End of html bootstrap -->


<!--Comment: Back to markdown -->

### Let's write our first program

* You can select you programming language from the top of the page. To select python click on the dropdown and select python.
* Let's write some code to make the microbit display a smiley face when the program starts
* When you have finished - download it to you micro:bit (follow the instructions here)

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_WPcUfoRfpUpg" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
<br>

### Let's make the face change
* Microcontrollers work using a 'forever loop'
* Let's write a function to make the face switch between sad and happy in the forever loop

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_8e016aKRbcUx" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
<br>

### Let's program a button input
* We can use buttons as inputs
* Let's use the following to nake the face switch between happy and sad:
  * Buttons
  * An if statement
  * A variable called 'state'

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_JRh2FkicqE9U" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
<br>
  

<!--Comment: This section is markdown again-->

# How do we measure a sound?
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity2" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #2</h2>
</div>

<!--Comment: End of html bootstrap -->


<!--Comment: Back to markdown -->

### Measure sound using the microbit
* Write the program below
   * This uses serial communication to send the sound value the micro:bit measures back to the computer so that we can look at the value it on the computer screen. (We can imagine this like the microbit having a conversation with the computer)

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_H2MCuTK7gUHt" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
<br>

### Now check the program works!
* There are some instructions in the image below
   * Try it out in the simulator first
   * Then try it out for real on your micro:bit
      * **Note** *you need to be [connected](https://microbit.org/get-started/first-steps/set-up/) to the micro:bit for this to work*
* Make a note
   * What sound values did you see in real life?
   * What was the maximum? What was the minimum?

<div class="container">
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#demo7a">Question</button>
  <div id="demo7a" class="collapse" markdown="1">
  * What sound values did you see in real life?
  * What was the maximum? What was the minimum?
  </div>
</div>

[![serial_data_on_microBit](images/serial_data.png)]()

### Now lets visualise the sound measurement on the micro:bit
* Write the program below
* This program allows us to plot a graph on the micro:bit leds to show how loud the sound is!
* Check it is working correctly, you can check how it works in the simulator





<!--Comment: This section is markdown again-->

# Let's get familiar with our robot
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity3" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #3</h2>
</div>

<!--Comment: End of html bootstrap -->


<!--Comment: Back to markdown -->

* We'll be using the [robotbenchmark](https://robotbenchmark.net/) website.
* Click on the **Start** button next to the **Wall Following** activity
* Click on **Start programming this benchmark**
* You should see the scene below


![image1](images/image1.png)


First we're going to get familiar with how we control our view of the 3D simulation. We need to find how many ultrasonic sensors there are! Let's control the viewpoint to count how many ultrasonic sensors there are on the robot.

**Use the mouse to move the viewpoint and count the number of sensors**
* **Rotate:** click on a 3D object in the scene with the left mouse button and drag the mouse pointer. The viewpoint will rotate around the object.
* **Translate:** click in the scene with the right mouse button and drag the mouse pointer.
* **Zoom:** click in the 3D scene and roll the mouse wheel. It is also possible to zoom by pressing the mouse wheel and dragging the mouse forward or backwards.
* **Tilt:** press the mouse wheel over the 3D scene and drag the mouse to the left or to the right. Pressing simultaneously the left and right mouse buttons is equivalent to pressing the mouse wheel.


<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->



<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo3">Answer</button>
  <div id="demo3" class="collapse" markdown="1">
  There are 16 ultrasonic sensors, 4 at the front of the robot and 4 at the back!
  </div>
</div>

<br>

<!--Comment: End of html bootstrap -->

<!--Comment: This section is markdown again-->

# Let's make our robot move using python functions
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity4" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #4</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* We're still going to be using the [Wall Following](https://robotbenchmark.net/benchmark/wall_following/simulation.php) activity at the [robotbenchmark](https://robotbenchmark.net/) website. So you can keep this open all the time!
* We're going to get our robot moving!!
* When you're ready to program the robot, right click on it, and select **Edit controller**

![image2](images/image2.png)

* A window will pop up with python code in it! This is how we program our virtual robot.
* Delete all the code in the robot controller window, by hightlighting it all (or pressing **ctrl-A**) and then pressing **delete**
* Copy and paste the **'Activity Base Code'** code from below (click the green button) into the robot controller window, by hightlighting it all then right clicking and pressing **copy** (or pressing **ctrl+C**)
  
![image3](images/image3.png)

* Start the simulation by following the instrucitons in the image above
* You should see the robot approach the wall, but then reverse quickly when it senses it!
* Have a look at the python functions that are making the robot move in the 'Start of main program' section of the code. We'll discuss these together!

<div class="container">
  <button type="button" class="btn btn-primary" data-toggle="collapse" data-target="#demo4a">Activity Base Code</button>
  <div id="demo4a" class="collapse" markdown="1">

```python
"""
Purpose: Sample base code controller for the 'finite state machine' girls into coding activity

Notes: Hi! we're going to be editing this program together to make the robot move. It's important 
that this is a fun activity! If anything is unclear please ask! We're really happy to help. A lot
of the code is already written to make this activity possible. The parts of the code that you 
should edit are the parts betweeen the squigly lines! like this...

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*

# some edits that we make together

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
"""

#---------------------
# Python library imports
#---------------------

from controller import Robot # imports the language of the robot ! 

#---------------------
# Starting up the robot
#---------------------

# Get pointer to the robot. So that we can talk to it!
robot = Robot()

# Get pointer to the robot wheels motors.
leftWheel = robot.getMotor('left wheel')
rightWheel = robot.getMotor('right wheel')

# We will use the velocity parameter of the wheels, so we need to
# set the target position to infinity. This means they will keep turning
# for ever unless we set their velocity to zero
leftWheel.setPosition(float('inf'))
rightWheel.setPosition(float('inf'))

# Put all the ultrasonic sensors in an array
sensors = []
sensors.append(robot.getDistanceSensor("so0"))
sensors.append(robot.getDistanceSensor("so1"))
sensors.append(robot.getDistanceSensor("so2"))
sensors.append(robot.getDistanceSensor("so3"))
sensors.append(robot.getDistanceSensor("so4"))
sensors.append(robot.getDistanceSensor("so5"))
sensors.append(robot.getDistanceSensor("so6"))
sensors.append(robot.getDistanceSensor("so7"))

# Get the time step of the current world (the smallest time unit)
timestep = int(robot.getBasicTimeStep())

# Switch all the sensors on
for sensor in sensors:
    sensor.enable(timestep)


#---------------------
# Helpful functions for controling the robot (for the girls into coding activity)
#---------------------

def stopRobotWheels():
    """
    Purpose: stop the robot
    Notes: mySpeed -> can take values from 1-9
    """
    leftWheel.setVelocity(0.0)
    rightWheel.setVelocity(0.0)
        
        
def startMoveForward(mySpeed):
    """
    Purpose: move the robot forward
    Notes: mySpeed -> can take values from 1-9
    """
    leftWheel.setVelocity(mySpeed)
    rightWheel.setVelocity(mySpeed)
    
def startMoveBackward(mySpeed):
    """
    Purpose: move the robot backward
    Notes: mySpeed -> can take values from 1-9
    """
    leftWheel.setVelocity(-mySpeed)
    rightWheel.setVelocity(-mySpeed)
    
def startTurnLeft(mySpeed):
    """
    Purpose: turn the robot left
    Notes: mySpeed -> can take values from 1-9
    """
    leftWheel.setVelocity(-mySpeed)
    rightWheel.setVelocity(mySpeed)
    
def startTurnRight(mySpeed):
    """
    Purpose: turn the robot right
    Notes: mySpeed -> can take values from 1-9
    """
    leftWheel.setVelocity(mySpeed)
    rightWheel.setVelocity(-mySpeed)
    
    

def getClosestObjectToRobot():
    """
    Purpose: Return the direction and distance for the closest object to the robot
    
    Notes: Refer to the diagrams on the girls into coding webpage for the distance
    convention. The distance is returned in meters. The value returned by the getValue() 
    method of the distance sensors corresponds to a physical value (here we have a sonar, 
    so it is the strength of the sonar ray). This function makes a conversion to a
    distance value in meters.
    """
    
    # Make local variables
    maxSensorRange = 1.6 # in meters
    currentSensorID = -1
    lowestSensorDistance = maxSensorRange
    lowestSensorID = None
    
    # Find the closest object to the robot and save the direction and distance (in m)
    for sensor in sensors:
        # calculate the distance in m (this formula is provided by the sensor manufacturer)
        currentSensorDistance = ((1000 - sensor.getValue()) / 1000) * 5
        currentSensorID = currentSensorID + 1
        
        if currentSensorDistance < lowestSensorDistance:
            lowestSensorDistance = currentSensorDistance
            lowestSensorID = currentSensorID
    
    # If no object is found, then return 'None' otherwise return the value       
    if lowestSensorID != None:
        currentDirection = lowestSensorID -3
    else:
        currentDirection = None
        lowestSensorDistance = None
        
    return currentDirection, lowestSensorDistance

#---------------------
# Start of main program
#---------------------

# Our starting message for the program
print("--------------")
print("Here is an example of how we write a message to the console")
print("Program starting !!")
print("--------------")


# Move forward 
startMoveForward(5)
# Keep going until we are 20cm away from the wall
while True:
    robot.step(500) # keep going for 0.5 seconds (value is in milli seconds (ms))
    direction, distance = getClosestObjectToRobot() # Get the info on the closest object
    print("direction = {}, distance = {}").format(direction, distance)  # Print the info on the closest object
    # If there is an object too close, then stop moving forward!
    if distance != None and distance < 0.2:
        break
    

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello :)")
    
# Move backward 
startMoveBackward(5)
# Keep going until we are 1m away from the wall
while True:
    robot.step(500)
    direction, distance = getClosestObjectToRobot()
    print("direction = {}, distance = {}").format(direction, distance) 
    # If the object is too far, then stop moving backward!
    if distance != None and distance > 1:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
stopRobotWheels()
```

  </div>
</div>

<br>


# Let's see how the robot is sensing objects
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity5" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #5</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* We're still going to be using the [Wall Following](https://robotbenchmark.net/benchmark/wall_following/simulation.php) activity
* Let's have a look at how the robot is sensing the wall
* Open up the console by following the instructions in the image below, then run the simulation
![image4](images/image4.png)
* The console is where the robot prints messages to us!
* Let's discuss what it is saying
* Every 0.5 seconds we are asking the robot to tell us the distance of any objects from it's ultrasonic sensors
* It is telling us the distance by printing this to the console
* The diagram below shows how they work!

[![image6](images/image6.png)](images/image6.png)


**Questions**
*Let's answer these questions as a group*
* Can you see the moment at which the robot detects the distance to the wall? 
* How does the robot detect the wall?
* What should the robot do when it detects a wall?


<div class="container">
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#demo5a">Hint</button>
  <div id="demo5a" class="collapse" markdown="1">
  Try having a look at the function **getClosestObjectToRobot()** to see what it does!
  </div>
</div>

<br>

<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo5b">Answer</button>
  <div id="demo5b" class="collapse" markdown="1">

  * The robot detects the wall when it is 1.5 meters away
  * The robot detects the wall using the ultrasonic sensors
  * When the robot detects the wall we need it to change behaviour (e.g. stop, or turn, or move backwards!)
  
  </div>
</div>

<br>


# Let's change the robot's behaviour
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity6" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #6</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* What would we do if we wanted to change the behaviour of the robot when it reaches the wall? 
* Let's alter the code together to make this happen! Our goal is to make the robot move backwards, but not as far.
* Open the 'controller' (code editor) for the robot

![image2](images/image2.png)

* Scroll to the section of the code which looks like this (it should be lines 168-189):

```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello :)")
    
# Move backward 
startMoveBackward(5)
# Keep going until we are 1m away from the wall
while True:
    robot.step(500)
    direction, distance = getClosestObjectToRobot()
    print("direction = {}, distance = {}").format(direction, distance) 
    # If the object is too far, then stop moving backward!
    if distance != None and distance > 1:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
```

* Let's discuss this code together.
* How would we change the code so that when the robot changes direction (from fowards to backwards) then it prints our name e.g. "hello there ..."?
* How would we make the robot move backwards less far?
* Take a look at the hint and example answers if you're stuck!

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div class="container">
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#demo6a">Hint</button>
  <div id="demo6a" class="collapse" markdown="1">
  For printing to the console, try having a look at the code line: print("hello :)")

  For the movement, try having a look at the "if statement"!
  </div>
</div>

<br>

<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo6b">Example Answer</button>
  <div id="demo6b" class="collapse" markdown="1">

  ```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello there Nikita")
    
# Move backward 
startMoveBackward(5)
# Keep going until we are 1m away from the wall
while True:
    robot.step(500)
    direction, distance = getClosestObjectToRobot()
    print("direction = {}, distance = {}").format(direction, distance) 
    # If the object is too far, then stop moving backward!
    # We change this value to 0.5 so the robot travels on 0.5m backwards from the wall
    if distance != None and distance > 0.75:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
  ```

  </div>
</div>

<br>


<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

# Making the robot respond to time instead of distance
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity7" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #7</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* What would we do if we wanted to change the movement so the robot changes behaviour after a time period?
* Let's alter the code together to make this happen! Our goal is to make the robot stop moving backwards after 2 seconds has elapsed
* Open the 'controller' (code editor) for the robot


![image2](images/image2.png)


* Scroll to the section of the code which looks like this (it should be lines 168-189):

```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello there Nikita")
    
# Move backward 
startMoveBackward(5)
# Keep going until we are 1m away from the wall
while True:
    robot.step(500)
    direction, distance = getClosestObjectToRobot()
    print("direction = {}, distance = {}").format(direction, distance) 
    # If the object is too far, then stop moving backward!
    # We change this value to 0.5 so the robot travels on 0.5m backwards from the wall
    if distance != None and distance > 0.75:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
```

* Let's discuss this code together.
* How would we change the code so that robot stops after 2 seconds has elapsed
* Have a look at the hint to make a start!

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<br>

<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo7b">Example Answer</button>
  <div id="demo7b" class="collapse" markdown="1">

```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello there Nikita")
    
# Move backward 
startMoveBackward(5)
# Keep going for 2 seconds
milliSeconds = 0
while True:
    robot.step(500)
    milliSeconds = milliSeconds + 500
    direction, distance = getClosestObjectToRobot()
    print("time = {}").format(milliSeconds) 
    # If the time is longer than 2 seconds, then stop moving!
    if milliSeconds > 2000:
        break
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
```

  </div>
</div>

<br>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

# Avoiding the walls!
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity8" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #8</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* What would we do if we wanted to change the movement of the robot so that it starts to avoid walls? 
* Let's alter the code together to make this happen! Our goal is to make the robot turn after it has moved backwards
* Open the 'controller' (code editor) for the robot
* Scroll to the section of the code which looks like this (it should be lines 168-189):

```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
    
print("hello there Nikita")
    
# Move backward 
startMoveBackward(5)
# Keep going for 2 seconds
milliSeconds = 0
while True:
    robot.step(500)
    milliSeconds = milliSeconds + 500
    direction, distance = getClosestObjectToRobot()
    print("time = {}").format(milliSeconds) 
    # If the time is longer than 2 seconds, then stop moving!
    if milliSeconds > 2000:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
```

* Let's discuss this code together.
* How would we change the code so that robot turns when it has finished going backwards?
* Have a look at the hint to make a start!

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div class="container">
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#demo2">Hint</button>
  <div id="demo2" class="collapse" markdown="1">
  Try having a look at the function called 'startTurnRight(mySpeed)'. How would you add this to the code to make the robot turn right.
  </div>
</div>

<br>

<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo8">Example Answer</button>
  <div id="demo8" class="collapse" markdown="1">
  
```python
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
    
        
print("hello there Nikita")
    
# Move backward 
startMoveBackward(5)
# Keep going for 2 seconds
milliSeconds = 0
while True:
    robot.step(500)
    milliSeconds = milliSeconds + 500
    direction, distance = getClosestObjectToRobot()
    print("time = {}").format(milliSeconds) 
    # If the time is longer than 2 seconds, then stop moving!
    if milliSeconds > 2000:
        break

# Turn 
startTurnRight(5)
# Keep going for 2 seconds
milliSeconds = 0
while True:
    robot.step(500)
    milliSeconds = milliSeconds + 500
    print("time = {}").format(milliSeconds) 
    # If the time is too long, then stop moving!
    if milliSeconds > 2000:
        break
    
    
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
```

  </div>
</div>

<br>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

# State machines
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity9" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #9</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* Our goal is to make the robot behaviour so that it randomly explores the map!
* To keep going for ever it will need to avoid walls, and keep repeating behaviours
* We could do this with loops! But it can get a bit complicated.
* A really powerful idea for robot behaviours are state machines
* It might sound scary but it's really not!! Let's take a look at what a state machine is together ! 
  
[![image7](images/image7.png)](images/image7.png)

* As we can see in the images, we just have some robot behaviours, and we call them states!
* We've already created these robot behaviours, so there's not much more to do
* Let's have a look at one kind of program structure for a state machine in python
* Here is some pseudo code which shows how it works

[![image8](images/image8.png)](images/image8.png)

* So let's implement this for the robot simulation together!
* Delete all the code in the robot controller window, by hightlighting it all (or pressing **ctrl-A**) and then pressing **delete**
* Copy and paste the **'State Machine Code'** code from below (click the green button) into the robot controller window, by hightlighting it all then right clicking and pressing **copy** (or pressing **ctrl+C**)
  
![image3](images/image3.png)

* Start the simulation by following the instrucitons in the image above
* You should see the robot have the behaviours we programmed in the state machine
* Have a look at the python functions that are making the robot move in the **'Our States'** and **'Our State Machine'** section of the code

<div class="container">
  <button type="button" class="btn btn-primary" data-toggle="collapse" data-target="#demo9">State Machine Code</button>
  <div id="demo9" class="collapse" markdown="1">

```python
"""
Purpose: State machine controller for the 'finite state machine' girls into coding activity

Notes: Hi! we're going to be editing this program together to make the robot move. It's important 
that this is a fun activity! If anything is unclear please ask! We're really happy to help. A lot
of the code is already written to make this activity possible. The parts of the code that you 
should edit are the parts betweeen the squigly lines! like this...

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*

# some edits that we make together

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
"""

#---------------------
# Python library imports
#---------------------

from controller import Robot # imports the language of the robot ! 

#---------------------
# Starting up the robot
#---------------------

# Get pointer to the robot. So that we can talk to it!
robot = Robot()

# Get pointer to the robot wheels motors.
leftWheel = robot.getMotor('left wheel')
rightWheel = robot.getMotor('right wheel')

# We will use the velocity parameter of the wheels, so we need to
# set the target position to infinity. This means they will keep turning
# for ever unless we set their velocity to zero
leftWheel.setPosition(float('inf'))
rightWheel.setPosition(float('inf'))

# Put all the ultrasonic sensors in an array
sensors = []
sensors.append(robot.getDistanceSensor("so0"))
sensors.append(robot.getDistanceSensor("so1"))
sensors.append(robot.getDistanceSensor("so2"))
sensors.append(robot.getDistanceSensor("so3"))
sensors.append(robot.getDistanceSensor("so4"))
sensors.append(robot.getDistanceSensor("so5"))
sensors.append(robot.getDistanceSensor("so6"))
sensors.append(robot.getDistanceSensor("so7"))

# Get the time step of the current world (the smallest time unit)
timestep = int(robot.getBasicTimeStep())

# Switch all the sensors on
for sensor in sensors:
  sensor.enable(timestep)


#---------------------
# Helpful functions for controling the robot (for the girls into coding activity)
#---------------------

def stopRobotWheels():
  """
  Purpose: stop the robot
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(0.0)
  rightWheel.setVelocity(0.0)
      
      
def startMoveForward(mySpeed):
  """
  Purpose: move the robot forward
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(mySpeed)
  rightWheel.setVelocity(mySpeed)
  
def startMoveBackward(mySpeed):
  """
  Purpose: move the robot backward
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(-mySpeed)
  rightWheel.setVelocity(-mySpeed)
  
def startTurnLeft(mySpeed):
  """
  Purpose: turn the robot left
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(-mySpeed)
  rightWheel.setVelocity(mySpeed)
  
def startTurnRight(mySpeed):
  """
  Purpose: turn the robot right
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(mySpeed)
  rightWheel.setVelocity(-mySpeed)
  
def getClosestObjectToRobot():
  """
  Purpose: Return the direction and distance for the closest object to the robot
  
  Notes: Refer to the diagrams on the girls into coding webpage for the distance
  convention. The distance is returned in meters. The value returned by the getValue() 
  method of the distance sensors corresponds to a physical value (here we have a sonar, 
  so it is the strength of the sonar ray). This function makes a conversion to a
  distance value in meters.
  """
  
  # Make local variables
  maxSensorRange = 1.6 # in meters
  currentSensorID = -1
  lowestSensorDistance = maxSensorRange
  lowestSensorID = None
  
  # Find the closest object to the robot and save the direction and distance (in m)
  for sensor in sensors:
      # calculate the distance in m (this formula is provided by the sensor manufacturer)
      currentSensorDistance = ((1000 - sensor.getValue()) / 1000) * 5
      currentSensorID = currentSensorID + 1
      
      if currentSensorDistance < lowestSensorDistance:
          lowestSensorDistance = currentSensorDistance
          lowestSensorID = currentSensorID
  
  # If no object is found, then return 'None' otherwise return the value       
  if lowestSensorID != None:
      currentDirection = lowestSensorID -3.5
  else:
      currentDirection = None
      lowestSensorDistance = None
      
  return currentDirection, lowestSensorDistance


#---------------------
# Our States
#---------------------   
  
def goForwardsToWall():
  """
  Purpose: make the robot reach the wall and then change state
  Notes: robot stops 20cm from the wall
  """
  global robotState
  # Move forward 
  startMoveForward(5)
  # Keep going until we are 20cm away from the wall
  while True:
      robot.step(500) # keep going for 0.5 seconds (value is in milli seconds (ms))
      direction, distance = getClosestObjectToRobot() # Get the info on the closest object
      print("direction = {}, distance = {}").format(direction, distance)  # Print the info on the closest object
      # If there is an object too close, then stop moving forward!
      if distance != None and distance < 0.2:
          break
  robotState = 1
  
  

def goBackwardsFromWall():
  """
  Purpose: make the robot move away from the wall and then change state
  Notes: robot stops 1m from the wall
  """
  global robotState
  # Move backward 
  startMoveBackward(5)
  # Keep going until we are 1m away from the wall
  while True:
      robot.step(500)
      direction, distance = getClosestObjectToRobot()
      print("direction = {}, distance = {}").format(direction, distance) 
      # If the object is too far, then stop moving backward!
      if distance != None and distance > 1:
          break
  robotState = 2
  
  
def robotSpin():
  """
  Purpose: make the robot spin around 1 time :)
  Notes: you need to edit this function to make it work
  """
  # we want the robot to do a spin but it should end up facing the wall !
  
  global robotState
  # Start spining with speed = 5
  startTurnRight(5)
  # Keep going for 2 seconds
  timePassed = 0
  while True:
      robot.step(500) # 500 milli seconds
      timePassed = timePassed + 500
      direction, distance = getClosestObjectToRobot()
      print("direction = {}, distance = {}").format(direction, distance)
      print("time passed = {}").format(timePassed)
      
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
      # If the the time is too big, then stop spinning!
      if timePassed > 2000: # 2 seconds!
          break

      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ END OF YOUR CODE EDITS ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
  robotState = 0

#---------------------
# Our State Machine
#--------------------- 

# The robot state is passed to the switcher object
switcher = {
  0: goForwardsToWall,
  1: goBackwardsFromWall,
  2: robotSpin
  }

# Create our state machine
def ourStateMachine(robotState):

  # Defines error message if incorrect state is requested
  func = switcher.get(robotState, "Invalid State") 
  func()


#---------------------
# Start of main program
#---------------------

# Our starting message for the program
print("--------------")
print("Here is an example of how we write a message to the console")
print("Program starting !!")
print("--------------")

robotState = 0
NumberMovementsCount = 0

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*

  
while True:
    ourStateMachine(robotState)
    print("robotState = {}").format(robotState)
  
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
  
stopRobotWheels()
```

  </div>
</div>

<br>


<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

# Changing the state machine behaviours
---

<!--Comment: End of markdown-->

<!--Comment: Back to html bootstrap -->

<div id="Activity10" class="container p-3 my-3 bg-primary text-primary">
<h2>Activity #10</h2>
</div>

<!--Comment: End of html bootstrap -->

<!--Comment: Back to markdown -->

* The state machine allows us to very easily change the behaviour of the robot!
* Let's change the behaviour to make a state machine that does the following
* (1) Go towards wall (2) Make a 360 degree spin (3) Go backwards away from wall (4) Repeat
* How would we change the code to do this? 
* First let's make the spin happen!
* Have a look at the robotSpin() function, you can see this below
* How can you change the time value to make the robot spin 360 degree (one complete turn?)

```python

def robotSpin():
  """
  Purpose: make the robot spin around 1 time :)
  Notes: you need to edit this function to make it work
  """
  # we want the robot to do a spin but it should end up facing the wall !
  
  global robotState
  # Start spining with speed = 5
  startTurnRight(5)
  # Keep going for 2 seconds
  timePassed = 0
  while True:
      robot.step(500) # 500 milli seconds
      timePassed = timePassed + 500
      direction, distance = getClosestObjectToRobot()
      print("direction = {}, distance = {}").format(direction, distance)
      print("time passed = {}").format(timePassed)
      
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
      # If the the time is too big, then stop spinning!
      if timePassed > 2000: # 2 seconds!
          break

      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ END OF YOUR CODE EDITS ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
  robotState = 0

```


* Now lets look at the state machine
* How can we change the transition conditions to change the order of behaviours? 
* What we want to achieve is shown in the image below
* Notice the change in arrow directions !!

[![image9](images/image9.png)](images/image9.png)

<div class="container">
  <button type="button" class="btn btn-danger" data-toggle="collapse" data-target="#demo10">Example Answer</button>
  <div id="demo10" class="collapse" markdown="1">

```python

"""
Purpose: State machine controller for the 'finite state machine' girls into coding activity

Notes: Hi! we're going to be editing this program together to make the robot move. It's important 
that this is a fun activity! If anything is unclear please ask! We're really happy to help. A lot
of the code is already written to make this activity possible. The parts of the code that you 
should edit are the parts betweeen the squigly lines! like this...

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*

# some edits that we make together

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
"""

#---------------------
# Python library imports
#---------------------

from controller import Robot # imports the language of the robot ! 

#---------------------
# Starting up the robot
#---------------------

# Get pointer to the robot. So that we can talk to it!
robot = Robot()

# Get pointer to the robot wheels motors.
leftWheel = robot.getMotor('left wheel')
rightWheel = robot.getMotor('right wheel')

# We will use the velocity parameter of the wheels, so we need to
# set the target position to infinity. This means they will keep turning
# for ever unless we set their velocity to zero
leftWheel.setPosition(float('inf'))
rightWheel.setPosition(float('inf'))

# Put all the ultrasonic sensors in an array
sensors = []
sensors.append(robot.getDistanceSensor("so0"))
sensors.append(robot.getDistanceSensor("so1"))
sensors.append(robot.getDistanceSensor("so2"))
sensors.append(robot.getDistanceSensor("so3"))
sensors.append(robot.getDistanceSensor("so4"))
sensors.append(robot.getDistanceSensor("so5"))
sensors.append(robot.getDistanceSensor("so6"))
sensors.append(robot.getDistanceSensor("so7"))

# Get the time step of the current world (the smallest time unit)
timestep = int(robot.getBasicTimeStep())

# Switch all the sensors on
for sensor in sensors:
  sensor.enable(timestep)


#---------------------
# Helpful functions for controling the robot (for the girls into coding activity)
#---------------------

def stopRobotWheels():
  """
  Purpose: stop the robot
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(0.0)
  rightWheel.setVelocity(0.0)
      
      
def startMoveForward(mySpeed):
  """
  Purpose: move the robot forward
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(mySpeed)
  rightWheel.setVelocity(mySpeed)
  
def startMoveBackward(mySpeed):
  """
  Purpose: move the robot backward
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(-mySpeed)
  rightWheel.setVelocity(-mySpeed)
  
def startTurnLeft(mySpeed):
  """
  Purpose: turn the robot left
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(-mySpeed)
  rightWheel.setVelocity(mySpeed)
  
def startTurnRight(mySpeed):
  """
  Purpose: turn the robot right
  Notes: mySpeed -> can take values from 1-9
  """
  leftWheel.setVelocity(mySpeed)
  rightWheel.setVelocity(-mySpeed)
  
def getClosestObjectToRobot():
  """
  Purpose: Return the direction and distance for the closest object to the robot
  
  Notes: Refer to the diagrams on the girls into coding webpage for the distance
  convention. The distance is returned in meters. The value returned by the getValue() 
  method of the distance sensors corresponds to a physical value (here we have a sonar, 
  so it is the strength of the sonar ray). This function makes a conversion to a
  distance value in meters.
  """
  
  # Make local variables
  maxSensorRange = 1.6 # in meters
  currentSensorID = -1
  lowestSensorDistance = maxSensorRange
  lowestSensorID = None
  
  # Find the closest object to the robot and save the direction and distance (in m)
  for sensor in sensors:
      # calculate the distance in m (this formula is provided by the sensor manufacturer)
      currentSensorDistance = ((1000 - sensor.getValue()) / 1000) * 5
      currentSensorID = currentSensorID + 1
      
      if currentSensorDistance < lowestSensorDistance:
          lowestSensorDistance = currentSensorDistance
          lowestSensorID = currentSensorID
  
  # If no object is found, then return 'None' otherwise return the value       
  if lowestSensorID != None:
      currentDirection = lowestSensorID -3.5
  else:
      currentDirection = None
      lowestSensorDistance = None
      
  return currentDirection, lowestSensorDistance


#---------------------
# Our States
#---------------------   
  
def goForwardsToWall():
  """
  Purpose: make the robot reach the wall and then change state
  Notes: robot stops 20cm from the wall
  """
  global robotState
  # Move forward 
  startMoveForward(5)
  # Keep going until we are 20cm away from the wall
  while True:
      robot.step(500) # keep going for 0.5 seconds (value is in milli seconds (ms))
      direction, distance = getClosestObjectToRobot() # Get the info on the closest object
      print("direction = {}, distance = {}").format(direction, distance)  # Print the info on the closest object
      # If there is an object too close, then stop moving forward!
      if distance != None and distance < 0.2:
          break
  robotState = 2
  
  

def goBackwardsFromWall():
  """
  Purpose: make the robot move away from the wall and then change state
  Notes: robot stops 1m from the wall
  """
  global robotState
  # Move backward 
  startMoveBackward(5)
  # Keep going until we are 1m away from the wall
  while True:
      robot.step(500)
      direction, distance = getClosestObjectToRobot()
      print("direction = {}, distance = {}").format(direction, distance) 
      # If the object is too far, then stop moving backward!
      if distance != None and distance > 1:
          break
  robotState = 0
  
  
def robotSpin():
  """
  Purpose: make the robot spin around 1 time :)
  Notes: you need to edit this function to make it work
  """
  # we want the robot to do a spin but it should end up facing the wall !
  
  global robotState
  # Start spining with speed = 5
  startTurnRight(5)
  # Keep going for 2 seconds
  timePassed = 0
  while True:
      robot.step(500) # 500 milli seconds
      timePassed = timePassed + 500
      direction, distance = getClosestObjectToRobot()
      print("direction = {}, distance = {}").format(direction, distance)
      print("time passed = {}").format(timePassed)
      
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
      # If the the time is too big, then stop spinning!
      if timePassed > 1500: # 2 seconds!
          break

      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      # ~~~~ END OF YOUR CODE EDITS ~~~
      # ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
      
  robotState = 1

#---------------------
# Our State Machine
#--------------------- 

# The robot state is passed to the switcher object
switcher = {
  0: goForwardsToWall,
  1: goBackwardsFromWall,
  2: robotSpin
  }

# Create our state machine
def ourStateMachine(robotState):

  # Defines error message if incorrect state is requested
  func = switcher.get(robotState, "Invalid State") 
  func()


#---------------------
# Start of main program
#---------------------

# Our starting message for the program
print("--------------")
print("Here is an example of how we write a message to the console")
print("Program starting !!")
print("--------------")

robotState = 0
NumberMovementsCount = 0

# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ MAKE YOUR EDITS BELOW HERE ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*

  
while True:
    ourStateMachine(robotState)
    print("robotState = {}").format(robotState)
  
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
# ~~~~ END OF YOUR CODE EDITS ~~~
# ~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*
  
stopRobotWheels()

```

  </div>
</div>