# SSEModdingGuide

# Skyrim Special Edition: Introduction to Modding
## Preface
This document will intruct you on setting up and modding the Steam version of Skyrim Special Edition (SSE). This document is intended for beginners, so it is vital that you read and follow all instructions carefully.

By the end of this document you should be able to:
* Setup your copy of Skyrim to function with mods.
* Learn the functions of Mod Organizer 2(MO2), a program designed to organize and activate mods.
* Navigate and use Nexus Mods (Nexus for short), a website that hosts mods for Skyrim.
* Download and Install mods using the aformentioned program and website.
* Build a stable Skyrim experience with essential mods.

### Requirements/Assumptions
While previous modding experience is not necessary for this document, you are expected to be knowledgable on basic computer functions. This document will require:
* The Steam edition of SSE
* Windows 7 or higher (64-bit)
* A text editor (Notepad or Notepad++)
* [Microsoft VC++ 2015-2019](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64)
* The latest GPU drivers
* A file archiver (7-Zip, WinRAR, etc.) 


## Preparations 
This section will teach you how to prepare SSE for modding.

Before adding any mods to your game, you will need to do the following:
1. Install SSE outside of a Windows protected folder (Program Files, Program Files (x86), etc.).
2. Setup a Nexus Account.
3. Download and install Mod Organizer 2.


### Setting up Skyrim Special Edition
You will need to ensure that your copy of SSE is outside of a Windows protected folder. Windows is very protective when you try to edit anything inside of it.

#### Moving your Steam Directory
By default, your Steam directory will be placed in:

**C:\Program Files(x86)\Steam\SteamApps\Common**

To move your Steam directory:

1. In your Steam client, click **Steam** > **Settings**.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Steam%20home%20Setting%20Highlight.png)

2. Click **Downloads** > **Steam Library Folder**.
3. Click **Add Library Folder**. You will open a Steam file explorer 
4. Navigate the explorer to a location not protected by Windows, preferably in the root directory of your hard drive.
5. Click **New Folder**.
6. Enter the name of your new folder, then click **OK**.
7. Click the **folder you created**, then click **Select**.

Your Steam games are now placed in a new location.

#### Installing the Game
```
NOTE: If you have already installed and played Skyrim, skip this section.
```
1. Open Steam and go to your **Library**
2. Download and install **Skyrim Special Edition** 
3. Run SSE 
4. Exit the game once you reach the main menu. (This will generate a configuration(ini) file for SSE)

### Creating a Nexus Mods Account

Most of your mods and tools will come from Nexus Mods (Nexus), a website that hosts thousands of community made mods. You cannot download anything from the website without a Nexus account.

To create a Nexus account:
1. Navigate to the [Nexus Mods](https://www.nexusmods.com/) website.
2. Click **Register** in the top right corner of the website.
3. Follow the instructions provided by the website.

### Installing Mod Organizer 2

Mod Organizer 2 (MO2) is a program that will download and manage mod files for you. See [Introduction to Nexus Mods](https://github.com/CDimang/SSEModdingGuide/edit/main/README.md#introduction-to-nexus-mods) for more info.

1. Navigate to MO2's [page on Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/6194?tab=files).
2. Click the **Files** tab.
3. Look for **Mod Organizer 2**, then click **Manual Download**. 
4. Click **Slow Download**.
5. Navigate to the download location and double click the installer.
6. Follow the procedures provided by the installer.  

## Overview of Mod Organizer 2 (MO2)

MO2 is a program used to organize, install, and manage mods for popular games such as Fallout or The Elder Scrolls.

Rather than adding mod files to the game's directory, MO2 manages mods by separating them into an isolated folder, functioning as a virtual directory. The game will read files from MO2 rather than its own directory, tricking the game into thinking it's loading its own directory. With this isolated file system, users can enable or disable mods with a click of a button. In short, the program is designed to streamline the modding process so that users of all experience can mod their own game. 

The features available in MO2 are:

* Isolate mods from the game directory.
* Enable or Disable mods with a click of a button.
* Sort mods through numerous criteria.
* Download content from Nexus through MO2.
* Present notifications such as updates or warnings for mods.
* Swap mod configurations seamlessly.
* Add additional tools or addons for a centralized modding program.

By the end of this section, you should know:

* How to setup your game for MO2
* How each user-interface (UI) element functions
* How to apply each UI element into your modding.

### Setting Up MO2

This section will explain the virtual directory, and how to set up your game for MO2.

#### Instances, a Virtual Game Directory

A **Instance** will need to be created everytime you add a game to MO2. Instances are folders where mods and configurations for your games are stored. In normal circumstances, a game will read it's own directory to load the content and mods installed. However, with MO2, the program will redirect the game towards the Instance folder, making the game think that it is reading its own directory. The reason for the Instance is to keep the game's directory as clean as possible, allowing users to add or delete mods with ease. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Virtual.png)

#### Adding your Game to MO2

The following procedures will guide you on setting up your game for MO2:

1. Open MO2
2. You will be asked to create an Instance. Click **Create a Global Instance**
3. Supported MO2 games will be displayed in a list. Select a game manage, then click **Next**. 
   If your game does not appear like in the image below, click **Browse** and navigate to your game's executable (.exe) file.
   
   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%203%20Game%20manage%20HIGHLIGHT.png)

4. Enter the name of your Instance, then click **Next**.
5. Select or create a folder to serve as the Instance folder. Click **Next**
```
TIP: For ease of access, it is recommended to create an Instance folder in the same directory as your MO2.
```
6. You will need to link your Nexus account to MO2. Click **Connect to Nexus**, your browser will be redirected to a confirmation page.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%204%20Link%20Nexus%20Account.png)

7. Click **Authorize** on the confirmation page 

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/mo2%20nexus%20confirmation.png)

8. After you receive a confirmation that Nexus and MO2 are linked, click **Next**.  
9. A window with all the information you entered (Game choice, Instance location, Nexus account, etc.) will be displayed in a list. After confirming that all the provided information is correct, click **Finish**.


### The Interface

The interface consists of four sections:

* Toolbar
* Installation Panel
* Executables
* Plugins

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Label%20UI%20nolog.png)

The sections below will explain the functionally of each element.

### Toolbar

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Highlight.png)

The Toolbar is a 12 button menu that can:

* Change the functionality of MO2
* Customize the UI to the users liking
* Add additional tools or executables to MO2
* Inform the user of updates, errors, or general information.


#### Instane Manager

The Instance Manager is where you can create and manage multiple Instances for MO2. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Instance%20ui.png)

| Field |Description|   
|---|---|
|   |   |   
|   |   |   
|   |   |  


#### Install from Archive
#### Nexus Mods Link
#### Refresh
#### Tools
#### Profiles
#### Configuration
#### Executables
#### Endorsement
#### Notification
#### Update Mod Organizer
#### Help

## Introduction to Nexus Mods
## Downloading and Installing Mods
## Essential Mods for Skyrim
## Closing Thoughts 
