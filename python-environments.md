**Python Environment**

It is a seperate and isolated environment for python projects.

In the python environment we can manage dependencies, versions and packages without any conflicts across different python projects.

For example we have two python projects: `project1` and `project2`. 

Where project1 uses the Fast API 1.4v and project2 uses the Fast API 2.0v. 

And let suppose in your system Fast API 2.0v is installed. If you try to run project1, it may not work properly because it requires Fast API 1.4v.

By using the python environment we can run these projects seperately without conflicting each other.

Virtual environment solved this issue by allowing each project to have its own set of installed packages and dependencies independednt of what installed globally or in other environments.


**Steps for Creating Python Environment (Windows)**
1. Go to your vs code terminal
```bash
python -m venv enviornment_name
```

2. After creating the python environment activate it using the following command:
```bash
enviornment_name/bin/activate
```

and similarly you can use below command to deactivate the environment:
```bash
deactivate
```