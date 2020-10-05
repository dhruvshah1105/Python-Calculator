# python_calc
This assignement was assigned to learn different GUI features of python and which is quite good for lerning how to use GUI feastures work in python. Also this will show you how to upload your files on GITHUB using Git CMD and Git Bash.  

## Steps of creating the calculator in python:  
(NOTE: This is just overview not explaining whole code)  

### Step-1:  
Create test.py, import sys package. Now import QApplication, QLabel and Qwidget into test.py from PyQt5.QtWidgets.
1. QApplication()-This is used to create a application
2. QWidget()-This is used to define the dimension of the pop-up window
3. Trying printing any demo message and then end the window using show().

### Step-2:
Create view.py, import Ot, QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout and Qwidget into test.py from PyQt5.QtWidgets.
1. QMainWindow-Construct class GUI which calls constructor of QMainWindow.
2. By using different widget and layout functions, define the calculator's look and layout as per your requirements.
3. Now create a display bar that shows that digits that you have typed for calculation.
4. Define position of each and every button of the calculator using tuples.
5. Now finally verify that the layout that you have defined has been configured properly or not.

### Step-3:
Create main.py and import sys package.	
1. Define the main function.
2. Create and call an instance of QApplication.
3. Show the GUI using GUI() and show() methods.

### Step-4:
Create model.py and add the following in the module.
1. Define evaluateExpression method in it.
2. If there is an exception thrown then the result won't be printed else the result will be printed.

### Step-5:
Create controller.py. In this module add the following things:
1. Define a class named Controller.
2. Build a constructor which calls model and view parameters in it.
3. Define 3 functions in it:
	1. calculateResult: for evaluating result of expression.
	2. buildExpression: for validating and building the expression.
	3. connectSignals: to connect the expression through the buttons we defined in Step-3.

### Now install the pyqt5 using 'pip install pyqt5' command and install Git on your local PC using 'pip install python-git' command.
Thereafter redirect to the directory where you have saved all the python files.
In the repository open Git Bash and enter the below given command:
1. git clone
3. (optional) If you get the error message that username has not been defined the kindly follow the steps and follow the steps that are shown to set up user name and email-Id.
2. git status
(After this step you will get the file names in Red which means that files are left to be uploaded to Github.)
3. git add file_name.py
4. git commit -m "Any Message that you want to print"
5. git push origin master

Now on refreshing your repository page you will be able to see that file you have uploaded.
Follow this procedure to upload all the files that you want to upload to github.

#### Now, try to run to the main.py file, it will show you a layout like a basic calculator and then by entering values you can do your calculations on your newly created basic calculator.
#### On a perfect execution of this calculator, you should the following output in your screen
![Output Screen](/Outputs/Output1.png)
