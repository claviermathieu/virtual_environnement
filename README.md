# Virtual environnement

## Goal

One way to manage python environnement is to create virtual environnement. Most of the time, a python developper work on several projects. All projects don't require the same packages.

So, it's useless and confusing to have unused packages install in the work environnement of the project.

To solve this problem, virtual environnement is a good practice.



## What is virtual environnement?

Basically, a virtual environnement replicate a new Python environnement as if you have just installed Python.

> C:\Users\Mathieu\AppData\Local\Programs\Python\Python38\python.exe -m venv MyEnvironnementName



If you have Python38 in your virtual environnement and you want to create a virtual env from this Python version. You only need to type

> python -m venv MyEnvironnmentName



## How to use it?

After creating your Python environnment, you have now a folder in your work folder named "MyEnvinnementName"

When you open a command prompt in your work folder you can activate your virtual env with the command :
>MyEnvironnementName\Scripts\activate.bat

Jupyter Notebook will detect autommatically the new environnement as VScode(you can force vs code to go on this environnement).

```{tip}
A good practice is to name your virtual environnement ".venv
```
