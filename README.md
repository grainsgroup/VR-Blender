# VR Blender
A python addon for Blender to animate in Virtual Reality

![alt text](/architecture.png)

      
To use the script:

- Unzip the content of the VR-Blender.zip file
- Copy the two folders and the Python file, namely openvr, space_view3d_virtual_reality and interface_configurator.py into the Blender's "script" folder
- Open Blender's User Preference and navigate to Add-ons tab
- Enable the script "3D View: Virtual Reality Viewport" 
- Choose the "HTC Vive" option as Display Backend in the Preference field
- Enable the script "Development: Interface Configurator"

More details about this version are provided in Is Immersive Virtual Reality the Ultimate Interface for 3D Animators?[[1]](#1)

A new version of the script has been released (folder ['New Functionalities'](/New%20functionalities)) providing support for virtual character animation (Rigging & Skinning) and VR functionalities customization.
The extended architecture is illustrated below. 

![alt text](/architecture-new-functionalities.png)

Details about this extended version are discussed in Immersive Virtual Reality-Based Interfaces for Character Animation[[2]](#2).

Recently, Logitech has provided us with a sample of their [VR Ink Pilot Edition](https://www.logitech.com/en-roeu/promo/vr-ink.html). 
Free-hand drawing functionalities with this device have been integrated in the VR Blender addon. 
Code could be found in folder ['VR Ink support'](/VR%20Ink%20support). 


#### References
* <a id="1">[1]</a> Fabrizio Lamberti, Alberto Cannavò and Paolo Montuschi, "Is Immersive Virtual Reality the Ultimate Interface for 3D Animators?" in Computer, vol. 53, no. 4, pp. 36-45, April 2020.
doi: [10.1109/MC.2019.2908871](https://doi.org/10.1109/MC.2019.2908871)
* <a id="2">[2]</a> Alberto Cannavò, Claudio Demartini, Lia Morra and Fabrizio Lamberti, "Immersive Virtual Reality-Based Interfaces for Character Animation" in IEEE Access, vol. 7, pp. 125463-125480, 2019.
doi: [10.1109/ACCESS.2019.2939427](https://doi.org/10.1109/ACCESS.2019.2939427)
