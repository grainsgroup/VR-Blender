# VR Blender
A python addon for Blender to animate in Virtual Reality

![alt text](https://github.com/grainsgroup/VR-Blender/blob/master/architecture.png)

      
To use the script:

- Unzip the content of the VR-Blender.zip file
- Copy the two folders and the Python file, namely openvr, space_view3d_virtual_reality and interface_configurator.py into the Blender's "script" folder
- Open Blender's User Preference and navigate to Add-ons tab
- Enable the script "3D View: Virtual Reality Viewport" 
- Choose the "HTC Vive" option as Display Backend in the Preference field
- Enable the script "Development: Interface Configurator"

More details about this version are provided in [Is Immersive Virtual Reality the Ultimate Interface for 3D Animators?](https://doi.org/10.1109/MC.2019.2908871)

A new version of the script has been released (folder 'New Functionalities') providing support to virtual characters animation (Rigging & Skinning) and VR functionalities customization.
The extended architecture is illustrated below. 

![alt text](https://github.com/grainsgroup/VR-Blender/blob/master/architecture-new-functionalities.png)


Details about this extended version are discussed in [Immersive Virtual Reality-Based Interfaces for Character Animation](https://doi.org/10.1109/ACCESS.2019.2939427).

Recently, Logitech has provided us with a sample of their [VR Ink Pilot Edition](https://www.logitech.com/en-roeu/promo/vr-ink.html). 
Free-hand drawing functionalities have been integrated in the VR Blender addon. 
Code could be found in folder 'VR Ink support'. 