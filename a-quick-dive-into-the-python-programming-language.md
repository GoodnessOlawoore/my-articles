Python is a very popular general-purpose programming language and has some of the world's largest products built on it. Google, Netflix, Uber, Spotify, Pinterest, Reddit, and Instagram are examples of great sites that are built on the python programming language. 

## PYTHON PHILOSOPHY 
Python is said to be the most beginner-friendly programming language anyone could learn. This philosophy was established way long ago, and as much as I am aware of, it hasn’t been challenged with a countering opinion. 
 
While I wouldn’t say python is the easiest programming language to learn, it sure is one of the pretty easy programming languages you could pick up at any point in time.
 
## PYTHON IS AN OBJECT-ORIENTED PROGRAMMING LANGUAGE 
Object-Oriented Programming is a programming pattern that focuses on the concept of classes and objects. Python allows us to develop application softwares using this approach.  
 
These objects are likened to real-world entities like cars, schools, books etc. Take for instance, an object could be a car with properties like colour, maker, model or a school with properties like classes, teachers, students, courses. 

## PYTHON IS A DYNAMICALLY TYPED LANGUAGE
Python doesn't require you to declare the type of a variable while assigning a value to it, unlike some languages where you are compelled to declare the type of a variable before assigning it a value.

For example, if you are going to declare a variable that will contain a string value in C#, you need to declare the type of that variable as a string before assigning it a value, otherwise, the program will return an error.
#### Example Below:
In C#:
```
string language = "Python";
``` 
Whereas in python you don't need to declare the type at all.
#### Python:
```
language = "Python"
``` 
## PYTHON IS A GENERAL-PURPOSE LANGUAGE
This basically means that python could be used for a wide range of things, ranging from web application development, mobile application development, desktop application development, game development, machine learning, artificial intelligence, data science, automation etc. 
 
While Python doesn’t singularly support all these variants/platforms, it has built-in libraries and frameworks that make working on these platforms possible and seamless. 
 
### Below are a few Python Frameworks/Libraries that you can leverage to suit your desired goal: 
 
- Web Development - Django, flask, Falcon, Web2py
- Data Science - Numpy, Pandas, Scrapy 
- Mobile Development - Kivy 
- Machine Learning and Artificial Intelligence - TensorFlow, PyTorch, Keras, Scikit-learn 
- Desktop Development - Kivy, Tkinter, PyQT 
- Game Development - Pygame, Pykyra, PyOpenGl, Kivy, Pyglet 

## PYTHON IS VERY BEGINNER-FRIENDLY 
Python is written in pure English language and emphasises readability, unlike some programming languages that are somewhat naturally complex and would really take the grace of God for a beginner to understand the code that outputs "Hello World" (Hello to C++😊) 
 
## A LITTLE COMPARISON 
While curly brackets { } are only used to indicate the beginning and the ending of a code block in most programming languages, indentation is used instead in python.  
 
And while indentations are mainly for styling purposes in other languages, it is a strict requirement for your code to get compiled and executed here. It basically tells the python interpreter that a series of code statements belongs to a particular block of code. 
 
## READABILITY 
Python programs are faster to write and much easier to read compared to other programming languages, and you can literally read a python code the way you’d read an English text. 
 
## PYTHON VERSIONS 
There are currently two versions of Python, which are version 2 and version 3. 
While Python version 2 passes for an older and legacy version of Python, Python version 3 is the current and actively supported version of the language. 

# GET STARTED WITH PYTHON 
### 1. INTEGRATED DEVELOPMENT ENVIRONMENT (IDE) - 
An IDE basically provides developers with an interface to write code. There are a couple of IDEs **(Integrated Development Environment)** that support the Python programming language. Anaconda, Sublime Texts, Atom, Visual Studio Code, PyCharm, Vim are good examples. 
 
Python also has a default IDLE **(Integrated Development and Learning Environment)** which is automatically installed when you install python on your PC. It is an interactive window where you can type in python codes and see the result. This is very beginner-friendly and easy to use. 
 
I will be using the Visual Studio code IDE and the Python IDLE for the purpose of this article. You can  [download VS code](https://code.visualstudio.com/download) if you don’t already have it, follow the instructions on the site to correctly install and get it running. 

### 2. INSTALL PYTHON -  

 - Download the latest version of python at  [www.python.org/downloads](http://www.python.org/downloads). Note that this guide is focused on the Windows Operating System.

 ![download VS code](https://res.cloudinary.com/dclfepekx/image/upload/v1619549980/download_python_q6jjx1.png)

 - To check if python is now installed, open the command prompt window on your computer, you can easily do this by pressing the **Win + R** keys, this would automatically open a quick search window. 

 ![Win + R](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/1._win_R_c0ukyz.png)

 - Type “cmd” in the search box and press Enter, your command prompt window will open afterwards. 

 ![cmd](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/2._command_promt_window_opens_bonk0g.png)

 - Type the word “python” or “py” in your command prompt. 

Input:
```
python
``` 
**OR**
```
py
``` 
#### Desired result:
 ![checks if python is installed](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/2.1._checks_if_python_is_installed_wcctfy.png)
 
  *This would check if python is installed and if yes, it would return the version of python that you’re running, also the version of your system OS, plus some additional information.This is said to be the easiest way to check if Python is installed on a windows PC.*

 - But if you are sure that python is installed and you just want to check for the version that you’re running, you could type ```python --version```. This would return the version of python installed on your computer. 

Input:
```
python --version
```
#### Desired result:
 ![python --version](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/4._python_--version_rzkvyd.png)

 -  ```py --version``` would also work.

Input:
```
py --version
```
#### Desired result:
 ![py --version](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/3._py_--version_ak6gnc.png)
   
 *As you can see, I am running on the latest version of Python (Python 3.9).*

 - Now that you have confirmed that python is successfully installed on your machine, I know that you are eager to write your first Python code. This can be done in three different ways: 
  1. Open Visual Studio Code 
  2.  Switch to a python interactive environment by typing ```python``` in your command prompt interface. 
  3.  Close the command prompt and open the built-in Interactive Development and Learning Environment (IDLE), that was installed with python by default. 

 Let’s go with the 3rd option.

 - Head over to the folder that contains your Python installation packages. My directory looks like this, 

 ![my directory](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/5._run_python_application_udtf5v.png)  

 - Run the Python application. This will open a Python IDLE where you can play around with python codes. 

 ![open IDLE](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/6._opens_IDLE_ytnzzy.png) 

 - Alternatively, you can hit the **Win + S** keys and type "python" into the search box. 

 ![Win + S](https://res.cloudinary.com/dclfepekx/image/upload/v1619550246/7._win_S_ja0orc.png) 

 - Click on the **IDLE (Python 3.9 64-bit)**. If you are running another version of python other than version 3.9 or 64-bit, you won’t see **“Python 3.9 64-bit”**, you will see the exact version that you are running. 

 > Now that you are in your python interactive environment, you might want to type “help( )” to gain insight into the environment, available python modules etc. 

Input:
```
help()
```
#### Desired result:
 ![Help](https://res.cloudinary.com/dclfepekx/image/upload/v1619550246/8._help_xaqqfe.png) 
 > You will see a couple of instructions like the one above. You can follow on if you wish. 

### 3. RUN YOUR FIRST PYTHON PROGRAM - 
 > You are about to write your first ever python code, fasten your seatbelt. 

 What first statement could we print if not the message that welcomes everyone to the world of programming😊.  
 - In python, the ```print()``` function is used to display a message to the screen. Let’s go ahead and display “Hello World”. 
 - To display an “Hello World” text in Python, we type ```print(“Hello World”)``` 

in C++, this same code is written as 

```
#include<iostream>     
using namespace std;  

int main(){ 
    cout<<"Hello World"; 
    return 0; 
}
``` 
with each line having certain functions they do. But since you already said “Yes” to python, I urge you to be focused and not be distracted. 

 - Now you can switch back to your Python IDLE. Type “print(“Hello World)” and see your first python program run before your eyes. 

 ![print hello world in the IDLE](https://res.cloudinary.com/dclfepekx/image/upload/v1619550245/9._print_hello_world_yotsux.png) 

 > Did you get a result like the one above? If yes, then **Congratulations!** You just successfully ran your first python program.

 - Note that the print( ) function is case sensitive, and ``` Print()```  will not work as ``` print()``` . 

Notice how we didn’t use the Visual Studio Code? It’s all good, as you won't need to install it again when you want to start writing codes on an IDE. 

Now that you’ve written your first ever python program, go rejoicing, for you shall now be called a Python Programmer 💃🕺.

I officially launched this blog last week, and I wrote about it, you can [check it out here](https://goodnessolawoore.codes/i-am-starting-a-technical-blog).



