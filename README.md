# Robot Control Panel

This project is a web-based control panel for a robot, allowing users to send commands to the robot.

Enviorment:
- Visual Studio Code (HTML)
- XAMPP


***

## <img src="https://github.com/user-attachments/assets/7048b800-1b5b-463d-8adf-ef861e6d376c" width="20" height="20"> XAMPP Setup

if you have not alredy donlowade it, follow these steps:

1. install XAMPP:
     - [ XAMPP download page](https://www.apachefriends.org/index.html).
     - Select your OS (Windows, macOS, Linux), Then Click on it.

2. Run the downloaded installer:
    - Allow the app to make changes.
    - click _Next_.

3. Leve the _Default settings_.
    - click _Next_.

4. Choose a Folder Path:
    - Choose the path where you want to install XAMPP.
    - click _Next_.

5.  Choose your Language :
    - Change your language if you want.
    - click _Next_.

6. Install it
    - Lunch The Control Panel.

7.  Start _Apache_:
To Test it:
    > Actions  ->  Start Button
    - it should be started on port ``80.443``.

  - If you encouterd an Error:
    - Close the window.
    - _Right Click_ on XAMPP Icon, Then choose _Quit_.
    - Then re-do the above steps.

8. Start _MySQL_:
To Test it:
    > Actions  ->  Start Button
    - it should be started on port ``3306``.

  <img src="https://github.com/user-attachments/assets/0ea6bfa1-bfcd-484f-8783-0ed49d82cf01" width="430" height="280">


***

## <img src="https://github.com/user-attachments/assets/c8739dce-5f53-4660-93b3-3ebc8d686cd5" width="20" height="20"> Database Setup
To see you Database 

1. Go to your broswer & Open ``phpMyAdmin ``:
   - by navigating to ``http://localhost/phpmyadmin``.
  <img src="https://github.com/user-attachments/assets/14946b21-b986-439a-aa33-a3571d91bc92" width="430" height="280">

2. Create a new Database named ``robot_control``:
     > Databases  ->  Create Database  ->  Create

3. Create a table named ``controls``:
   - Table will have 2 columns for the ID & Directions.


***

## Project Directory and Files
I used VS Code, created a project with 3 files and commited them to this repo (you can find the codes for each):


*** 

## How to Run
Start Apache and MySQL from the XAMPP Control Panel
Open your browser and navigate to http://localhost/RobotControlPanel/index.html
Use the control panel to send commands to the robot. A pop-up window will display success or error messages
