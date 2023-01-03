# Flow Menu Components

## **What is this?**

BGE (Blender Game Engine) add-on with utility menu for game development workflow mainly focused on using external scripts for game components (KX_PythonComponent)

## **Tutorials**

### **Download**

You can download of version 1.0.0 here: [release](https://github.com/misael-s/flow-menu-components/releases/tag/v1.0.0)

### **Install**
To install addon is simple, basicly you need enter in User Preferences of the [UPBGE](https://upbge.org/#/) or [RangeEngine](https://rangeengine.tech/) and navegate to addon tab and to click in import addon to find the zip file of this addon.

>To init the addon after you installed use **shortcut ALT + Q** on the **View 3D** or **Logic Editor**.

### **Usage**

The using of this addon is simple, but if you want a better know how it works follow the below steps.

**Step-01:** Save you **.blender** or **.ranger** file in a folder will be you root dir for all files in you game.

![Save you file](/readme-files/screenshot_01.png)

**Step-02:** The first time on you use create component in Game Component tab of addon its be create a folder called scripts if not exists a folder with this name in root dir. Now you can create many modules and classes.

![Need create component](/readme-files/screenshot_02.png)
![Open create component](/readme-files/screenshot_03.png)
![Created the scripts folder](/readme-files/screenshot_04.png)

**Step-03** Creating a module

**INFO:** when you go create a module or python class you should pay attention at one thing: **what module it's selected because that's where it will be created a new module with class or a just class**.

>Below you can see scripts module is selected and a new module called player with a class called movement will be created.

![Create a module and class](/readme-files/screenshot_05.png)
![Create a module and class](/readme-files/screenshot_06.png)

**Step-04** Creating a class

To create a only class you just need leave module textfield empty. **But again, pay attention what module is selected**.

![Create a module and class](/readme-files/screenshot_07.png)
![Create a module and class](/readme-files/screenshot_08.png)

### **Others tabs of addon**
**Tab Object:** contain many object operators that often you use in game engine.

![Create a module and class](/readme-files/screenshot_09.png)

**Tab Logic:** contain many logic operators that often you use in game engine and  Expanded Only Select option that expand the Sensor and your Controllers and Actuators linked on the Logic Editor.

![Create a module and class](/readme-files/screenshot_10.png)