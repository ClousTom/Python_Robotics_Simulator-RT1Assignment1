Python Robotics Simulator (Assignment 1)
================================
This is a simple, portable robot simulator developed by [Student Robotics](https://studentrobotics.org).

In the simulator, the robot goes in search of the gold cubes, picks them up and brings them close to the silver cubes.

Installing and Running
----------------------
Install python2:
```bash
$ sudo apt update
$ sudo apt install python2
```

Open a shell and execute the following command:
```bash
$ sudo apt-get udpate
$ sudo apt-get install git
$ git clone https://github.com/S5630055/Research-Track---Assignment-1
```

You have downloaded a simple robotic simulator. In order to run it, you should first install:
```bash
$ sudo apt-get install python-dev python-pip python-pygame
$ sudo pip install pypybox2d
```

Indeed, the simulator requires three libraries: pygame, PyPyBox2D, and PyYAML. The easiest way to install these
is through your distribution’s package manager (but PyPyBox2D is only available through pip).

Now open a terminal shell, move to the robot-sim directory and run:
```bash
$ python2 run.py assignment.py
```
If everything works, you should see a mobile robot and some boxes.

If you get some <strong>errors</strong>, try in this way:

-download and install pip for python2:
```bash
$ curl https://bootstrap.pypa.io/pip/2.7/get-pip.py --output get-pip.py
$ sudo python2 get-pip.py
```
-now, install pypybox2d using pip2:
```bash
$ sudo pip2 install pypybox2d
```

Pseudocode
----------------------
![Screenshot from 2022-11-02 20-03-46](https://user-images.githubusercontent.com/117213899/199579402-8467d252-ae96-4d0c-b437-538268a7a320.png)

Flowchart
----------------------
![Flowchart](https://user-images.githubusercontent.com/117213899/199577692-37a57df5-8024-41dd-95b6-675b38e8669f.png)

Research Track II
================================
- Statistical analysis report added.
