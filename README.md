![logo](img/logo.png)
# &nbsp; Orchid
  
![commit](https://img.shields.io/github/last-commit/erfajo/orchidfordynamo)
![commit activity](https://img.shields.io/github/commit-activity/y/erfajo/orchidfordynamo)
[![License](https://img.shields.io/badge/License-Freeware-red)](license.md)  
Orchid is a solution designed for use in the [Dynamo](http://dynamobim.org) environment. The solution is designed to support practical, technical, geometrical, logical, and mathematical issues. The solution contains functions to solve data handling in Revit projects, Revit families, and materials in Revit. Besides this, also functions to solve common data handling like geometry, printing, exporting, and system actions. Orchid is probably the largest and most coherent solutions besides what Autodesk releases for Dynamo.  
  
**Software environment**  
Built for Dynamo 3.3 (Revit 2025), Dynamo 2.19 (Revit 2024), Dynamo 2.16 (Revit 2023), Dynamo 2.12 (Revit 2022), and Dynamo 2.6 (Revit 2021).  
  
**Orchid Samples**  
In the [samples](Samples) folder are examples using the Orchid package placed.  
  
**History/Change Log**  
Check the [change log](changeLog.md) to see the history of the Orchid package.  
  
**Limitations**  
In general, the Orchid package is free to use by everyone, unless you are either Danish or located in Denmark, which implies, that you need to be registered to be able to obtain a license. Please see the limitations in the license (or as stated at the bottom of this document). To obtain a license, please contact the author of the package!  
  
---
## Install or Update the package for Dynamo
Download the **[OrchidForDynamo](Builds/OrchidForDynamo.exe)** executable installer in the [Builds](Builds) folder to install the Orchid package. Likewise if needed, download the [OrchidSamples](Builds/OrchidSamples.exe) executable installer for the sample collection, and/or download the [data files](Builds/OrchidSampleDataFiles.exe) for the sample collection.
  
<span style="color: red">**REVIT AND DYNAMO MUST BE CLOSED DURING INSTALLATION!**</span>  
  
### Manually installation
The Orchid package may also be installed by manually copying files from the **[Zipped](Zipped)** folder. This is only recommendable for experienced users! To install/update this way, please unzip the zip-file of the chosen version into your dynamo package folder, into a folder named **Orchid**. Download may be handled either by downloading a single file, or by cloning or zipping the repository. The package folder path can be found in Dynamo via the menu item 'Settings' -> 'Manage Node and Package Paths'.  
  
Select the zip-file according to your dynamo version!  
Orchid_330_? &nbsp;&nbsp;&nbsp; (for the dynamo 3.3.x branch)  
Orchid_219_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.19.x branch)  
Orchid_216_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.16.x branch)  
Orchid_212_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.12.x branch)  
Orchid_206_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.6.x branch)  
Orchid_203_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.3.x branch, however archived and not maintained!)  
Orchid_200_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.0.x branch, however archived and not maintained!)  
  
The individual version is avalible both for the Core (Sandbox) application and for the Revit application.  
?_Revit &nbsp;&nbsp;&nbsp; (the Revit application)  
?_Core &nbsp;&nbsp;&nbsp; (the Sandbox application)  
  
### Error handling
If Orchid dosnt work after installation, then try to see if you have one of these [errors](Error.md)!  
  
---
## Node description and organization
Nodes are generally arranged in assemblies directed towards the [Dynamo](http://dynamobim.org) application. One assembly cover all the basic in the Orchid package, two assemblies cover either the Core (Sandbox) application, or the Dynamo for Revit application. Next, two assemblies that cover the [Autodesk IFC exporter](http://github.com/Autodesk/revit-ifc). Lastly, some assemblies cover third-party functions. The 'node' assemblies is a 'set' of two assemblies for base/standard functions and extensible functions, mainly dropdown nodes.  
The functions may also be used as textual scripted functions in code blocks and custom nodes, example when using design script in code blocks as the Dynamo nodes.  
  
Inside Dynamo are the Orchid package functions arranged into four main branches: Core, RevitFamily, RevitMaterial, and RevitProject. The Core branch is subdivided into About, Autodesk, Common, and Geometry. The About branch covers functions for information about the Orchid package. The Autodesk branch covers functions for the present Autodesk application. The Common and Geometry branch covers functions that are used for generic purposes. These functions are those that are usable in the Core (Sandbox) application. The branches starting named 'Revit' covers functions to be used inside Revit. Functions for MEP System are included in the RevitProject branch.  
  
Nodes in the four Revit driven branches can be recognized by their icon ribbon/edge color:  
Core -> yellow &nbsp;|&nbsp; Revit -> yellow &nbsp;|&nbsp; RevitFamily -> blue &nbsp;|&nbsp; RevitMaterial -> green &nbsp;|&nbsp; RevitProject -> red ... MEPSystem -> purple  
  
---
## License
Copyright(c) 2014  
Erik Falck Jørgensen  
  
All content in this repository is part of the Orchid package.  
  
This work is licensed as a freeware product with an alike license as CC BY-ND 4.0, however, with geographical and behavioral limitations. To view the Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0), visit http://creativecommons.org/licenses/by-nd/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.  
In short terms does the CC BY-ND license state: This license allows for redistribution, commercial and non-commercial, as long as it is passed along unchanged and in whole, with credit to the author.  
  
The geographical and behavioral limitation applied in this work implies if you are either Danish or located in Denmark, you need to be registered to be able to obtain a license. However, not everyone will be able to obtain a license if a scenario exists where a professional work-related conflict of interest may arise with the author. Such a case may be in the geographical vicinity (Denmark), where the author acts professionally and must live off the intellectual property rights in the form of job security/consultancy. It will also be seen as a conflict of interest if the author experiences personal bothering or other harassment from any user or company. In case of conflict of interest, no license will be granted to the Orchid solution for the user/company.  
