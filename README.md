# Intorduction to Using Python for Image Analysis
## Setting up your Enviroment
To get started using python the first step is the installation and there are several ways you can do it. To make it easier for your future self it's a good idea to set up a virtual environment. You can think of this as a virtual installation folder where you install all your python libraries (basically just functions that other people have written).
One way to manage these environments is [anaconda](https://www.anaconda.com/products/individual)
This will not only install anaconda, the software to manage your environments but also a lot of libraries commonly needed for scientific python programs. 

Once installed you can manage your environments via the command line. Every operating system has one and they differ slightly.
I'm using Windows and to open it you just need to search for 'cmd' and will find it.
The basic functionality and use of conda in it can be found in this [great explanation of command line and conda](https://youtu.be/MOEPe9TGBK0?t=1161), created by my supervisor.
Another nice explanation of the command line can be found by Sreeni [here](https://www.youtube.com/watch?v=AzuajQnRuGI&list=PLZsOBAyNTZwbIjGnolFydAN33gyyGP7lT&index=5&ab_channel=DigitalSreeni) and he also explains what an integrated development environment (in short IDE) is and why it is needed for coding [here](https://www.youtube.com/watch?v=BxebisJKWBg&list=PLZsOBAyNTZwbIjGnolFydAN33gyyGP7lT&index=7&ab_channel=DigitalSreeniDigitalSreeni).

To get Started with your first programs in python I would suggest you follow the tutorial on setting up an environment after installing anaconda. I can offer a bonus tip for creating conda environments and that is to install a specific python version (some libraries won't work with the newest python version but you may find that out yourself) and how to install all the essential scientific libraries included in anaconda. To do this you need to initialise a conda environment as follows:

```sh
C:\Users\yourusername> conda create -n your_environment_name python=3.8 anaconda 
```

You have to replace 'your_environment_name' with a name of your choosing and can choose any python version that works with your libraries. For now you can omit the line 'python=3.8' but if you run into problems you can use this line to install any python version you wish to. 

## The Basics
To be frank I cannot teach all the basics of python anywhere near as well as the plethora of people on youtube and various blogs and sites across the internet. What I can do is give you some of the resources I have used to get into python, which you might also like. If you are starting completely from scratch I would advise you to watch [this](https://www.youtube.com/watch?v=rfscVS0vtbw&ab_channel=freeCodeCamp.org) video but if you have some basic understanding of coding the introduction to pythonic programming by [Sreeni](https://www.youtube.com/watch?v=qgJLeDPT8UM&list=PLZsOBAyNTZwbIjGnolFydAN33gyyGP7lT&index=6&ab_channel=DigitalSreeniDigitalSreeni) might be more suited. The video series by Sreeni covers a large part of image analysis and python programming and is a resource I often like to come back to myself. The third option
