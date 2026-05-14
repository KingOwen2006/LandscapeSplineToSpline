# LandscapeSplineToSpline
This is a plugin for **Unreal Engine 5.7.x** that turns any landscape spline into a spline component.

# How to install
There are two methods to install this plugin. Make sure your editor is closed before starting. 

## Project Install (Recommended)
This method makes the plugin only accessible to a single project. 

1. Download and extract the archive.
2. Move it into the plugins folder. Create it if needed. Folder structure should look like `[Project Name]\Plugins\LandscapeSplineToSpline`.

<img width="623" height="348" alt="image" src="https://github.com/user-attachments/assets/02ac21d4-02a3-40ab-8b81-f3244a0ca814" />

4. Now launch your project. 

## Engine Install
This method makes it available to all projects loaded with that specific Unreal Engine version. 

1. Download and extract the archive.
2. Navigate to your Unreal Engine installation, usually located in `C:\Program Files (x86)\Epic Games\Engine\Plugins`
3. Create a new folder called `Marketplace`, and drag the `LandscapeSplineToSpline` folder into it. 

Folder structure should be `[UE Install Folder]\Engine\Plugins\Marketplace\LandscapeSplineToSpline`.

# How to use
1. Open your project and go to Edit -> Plugins and look for **LandscapeSplineToSpline**, then enable it. You may need to restart your editor. 
2. Once your engine has restarted, press the Add Actor button (cube with a plus icon) and look for **Landscape Spline To Spline Component**.
   
   <img width="827" height="280" alt="image" src="https://github.com/user-attachments/assets/8f5696b3-6707-4f08-b4f7-cb2e7a4969ea" />
    Click it and it'll add the actor into your level.
4. Click on the actor and adjust the values in the Details panel until you get your desired settings.

# Support
It supports many spline actors in one level. It supports overlapping splines. 
