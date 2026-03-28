# BackendTalonFX Util
### This Util aims to help ease new FRC rookies into the field by automating motor configuration and control until they have built enough knowledge and expierence to learn the basics and contribute.
### The primary features of this util include: Automatic configuration initialization, simplified configuration editing, easy configuration application, condensed motor controlling methods, and more to come. 

## Setup
### 1. Download the 'BackendTalonFX.java' file and the 'PhoenixUtil.java' file
### 2. Accept/trust any warnings for viruses 
### 3. Go into your WPILib project
### 4. Create a new folder called 'utils' 
### 5. Place the two files into the new folder
### 6. Go into the file where you will be using the util to replace TalonFX motors 
#### Note: For rookies this will probably be a differential drive or outtake subsystem. 
### 7. Define your motor(s) as 'Backend _motor_name' in the at top of the class but outside the constructor 
### 8. Inside the constructor, initialize these motors with '_motor_name = new Backend(_id_number)' or _motor_name = new Backend(_id_number, _canbus)' 
### 9. Also in the constructor, set up your configurators for each motor with the '.configure____' methods or the 'defaultConfigure' method 
### 10. Afterwards, apply your configs by running the 'applyConfiguration' method. 

## Usage 
### 1. Now that you have set up your motors, you can now control them through the condensed commands. 
### 2. You can make a command in your class/subsystem and use the following: 'runMaxForward', 'runMaxReverse', 'runSpeed', 'runVoltage', 'runSpeedBreak', and 'runVoltageBreak' 
#### Note: The use of these commands has been documented in the file and will appear when you hover over them. 
### 3. After you link the commands to the various methods, you can link these commands to the controller inputs in the robotContainer file 

## Disclaimer + Help
### VERY IMPORTANT: This util has not been tested in the slightest. 
### There is a very high chance this does not work or breaks/damages the motors/robot
### This is still incomplete and will be updated when possible 
### If you have any questions/comments/cocerns/advice/etc, please contact me on the Blue Cheese Discord and I will respond as soon as I have the time.

