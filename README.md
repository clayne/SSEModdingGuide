# Skyrim Special Edition: Introduction to Modding

## Table of Content 
* [Preface](https://github.com/CDimang/SSEModdingGuide#preface)
	* [Requirements and Assumptions](https://github.com/CDimang/SSEModdingGuide#requirements-and-assumptions)
* [Preparations](https://github.com/CDimang/SSEModdingGuide#preparations)
	* [Setting up Skyrim Special Edition](https://github.com/CDimang/SSEModdingGuide#setting-up-skyrim-special-edition)
		* [Moving your Steam Directory](https://github.com/CDimang/SSEModdingGuide#moving-your-steam-directory)
		* [Installing the Game](https://github.com/CDimang/SSEModdingGuide#installing-the-game)
	* [Creating a Nexus Mods Account](https://github.com/CDimang/SSEModdingGuide#creating-a-nexus-mods-account)
	* [Installing Mod Organizer 2](https://github.com/CDimang/SSEModdingGuide#installing-mod-organizer-2)
* [Overview of Mod Organizer 2](https://github.com/CDimang/SSEModdingGuide#overview-of-mod-organizer-2-mo2)
	* [Setting Up MO2](https://github.com/CDimang/SSEModdingGuide#setting-up-mo2)
		* [Instances, a Virtual Game Directory](https://github.com/CDimang/SSEModdingGuide#instances-a-virtual-game-directory) 
		* [Adding Skyrim to MO2](https://github.com/CDimang/SSEModdingGuide#adding-your-game-to-mo2)
	* [The Interface](https://github.com/CDimang/SSEModdingGuide#the-interface)
	* [Toolbar](https://github.com/CDimang/SSEModdingGuide#toolbar)
		* [Instance Manager](https://github.com/CDimang/SSEModdingGuide#instance-manager)
		* [Install From Archive](https://github.com/CDimang/SSEModdingGuide#install-from-archive)
		* [Browse Mod Page](https://github.com/CDimang/SSEModdingGuide#browse-mod-page)
		* [Refresh](https://github.com/CDimang/SSEModdingGuide#refresh)
		* [Tools](https://github.com/CDimang/SSEModdingGuide#tools)
		* [Profiles](https://github.com/CDimang/SSEModdingGuide#profiles)
		* [Configuration](https://github.com/CDimang/SSEModdingGuide#configuration)
		* [Executables](https://github.com/CDimang/SSEModdingGuide#executables)
		* [Endorsement](https://github.com/CDimang/SSEModdingGuide#endorsement)
		* [Notification](https://github.com/CDimang/SSEModdingGuide#notification)
		* [Update Mod Organizer](https://github.com/CDimang/SSEModdingGuide#update-mod-organizer)
		* [Help](https://github.com/CDimang/SSEModdingGuide#help)
	* [Installation Panel](https://github.com/CDimang/SSEModdingGuide#installation-panel)
		* [Interface Elements](https://github.com/CDimang/SSEModdingGuide#interface-elements)
		* [Sorting the Modlist](https://github.com/CDimang/SSEModdingGuide#sorting-the-modlist)
			* [Flags](https://github.com/CDimang/SSEModdingGuide#flags)
			* [Assigning Custom Categories to Mods](https://github.com/CDimang/SSEModdingGuide#assigning-custom-categories-to-mods)
		* [Modlist Color Highlights](https://github.com/CDimang/SSEModdingGuide#modlist-color-highlights)
		* [Mod Priority/Load Order](https://github.com/CDimang/SSEModdingGuide#mod-priorityload-order)
		* [Overwrite Folder](https://github.com/CDimang/SSEModdingGuide#overwrite-folder)
	* [Executable Menu](https://github.com/CDimang/SSEModdingGuide#executable-menu)
	* [Plugin Panel](https://github.com/CDimang/SSEModdingGuide#plugin-panel)
		* [Plugins Tab](https://github.com/CDimang/SSEModdingGuide#plugins-tab)
			* [Using the Load Order Optimization Tool](https://github.com/CDimang/SSEModdingGuide#using-the-load-order-optimization-tool-loot)
			* [Good Plugin Practices](https://github.com/CDimang/SSEModdingGuide#good-plugin-practices)
		* [Downloads Tab](https://github.com/CDimang/SSEModdingGuide#downloads-tab)
* [Introduction to Nexus Mods](https://github.com/CDimang/SSEModdingGuide#introduction-to-nexus-mods)
	* [Navigating Nexus Mods](https://github.com/CDimang/SSEModdingGuide#navigating-nexus-mods)
		* [Searching the Modlist](https://github.com/CDimang/SSEModdingGuide#searching-the-modlist)
			* [Find a Specific Mod](https://github.com/CDimang/SSEModdingGuide#find-a-specific-mod)
			* [Find Mods Based on Categories](https://github.com/CDimang/SSEModdingGuide#find-mods-based-on-categories)
	* [Blocking Content on Nexus](https://github.com/CDimang/SSEModdingGuide#block-content-on-nexus)
	* [Understanding the Modpage](https://github.com/CDimang/SSEModdingGuide#understanding-the-mod-page) 
		* [Mod Page Information Tabs](https://github.com/CDimang/SSEModdingGuide#mod-page-information-tabs)
* [Downloading and Installing Mods](https://github.com/CDimang/SSEModdingGuide#downloading-and-installing-mods)
* [Essential Mods for Skyrim](https://github.com/CDimang/SSEModdingGuide#essential-mods-for-skyrim)
	* [Skyrim Script Extender](https://github.com/CDimang/SSEModdingGuide#skyrim-script-extender-skse)
		* [Installing SKSE](https://github.com/CDimang/SSEModdingGuide#installing-skse)
	* [Unofficial Skyrim Special Edition Patch](https://github.com/CDimang/SSEModdingGuide#unofficial-skyrim-special-edition-patch-ussep)
		* [Installing USSEP](https://github.com/CDimang/SSEModdingGuide#installing-ussep)
	* [Skyrim Special Edition Engine Fixes](https://github.com/CDimang/SSEModdingGuide#skyrim-special-edition-engine-fixes-sse-engine-fixes)
		* [Installing SSE Engine Fixes](https://github.com/CDimang/SSEModdingGuide#installing-sse-engine-fixes)
	* [SkyUI](https://github.com/CDimang/SSEModdingGuide#skyui)
		* [Installing SkyUI](https://github.com/CDimang/SSEModdingGuide#installing-skyui)



# Preface
This document will provide instructions for setting up and modding the Steam version of Skyrim Special Edition (SSE). The information presented below will be  intended for those who are new to modding, so it is important that you carefully read and follow all instructions.

By the end of this document, you should be able to:
* Setup your copy of Skyrim to function with mods.
* Learn the functions of Mod Organizer 2 (MO2), a program designed to organize and activate mods.
* Navigate and use Nexus Mods (Nexus for short), a website that hosts mods for Skyrim.
* Download and Install mods using the aforementioned program and website.
* Build a stable Skyrim experience with essential mods.

## Requirements and Assumptions
While previous modding experience is not necessary for this document, you are expected to be knowledgeable on basic computer functions. This document will require:
* The Steam edition of SSE
* Windows 7 or higher (64-bit)
* A text editor (Notepad or Notepad++)
* [Microsoft VC++ 2015-2019](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64)
* The latest drivers for your GPU
* A file archiver (7-Zip, WinRAR, etc.) 


# Preparations 
This section will explain the preparations needed to mod SSE.

Before adding any mods to your game, you will need to do the following:
1. Install SSE outside of a Windows protected folder (e.g. Program Files, Program Files (x86), etc.).
2. Setup a Nexus Account.
3. Download and install Mod Organizer 2.


## Setting up Skyrim Special Edition
Windows will prevent some mods from making changes to the SSE folder if it is saved in a Windows protected location, so you will need to ensure that your copy of SSE is outside of any Windows protected folder.

### Moving your Steam Directory

> NOTE: If your Steam directory is not located in **Program Files(x86)**, skip the instructions below.

By default, your Steam directory will be placed in: **C:\Program Files(x86)\Steam\SteamApps\Common**. You will need to move your Steam directory before modding Skyrim.

To move your Steam directory:

1. In your Steam client, click **Steam** > **Settings**.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Steam%20home%20Setting%20Highlight.png)

2. Click **Downloads** > **Steam Library Folder**.
3. Click **Add Library Folder**. You will open a Steam file explorer. 
4. Navigate the explorer to a location not protected by Windows, preferably in the root directory of your hard drive.
5. Click **New Folder**.
6. Enter the name of your new folder, then click **OK**.
7. Click the **folder you created**, then click **Select**.

Your Steam directory has been moved to a new location.

### Installing the Game

> NOTE: If you have already installed and played Skyrim, skip this section.

To install SSE:

1. Open Steam and go to your **Library**
2. Download and install **Skyrim Special Edition** 
3. Run SSE (This is needed to generate a configuration(ini) file for SSE).
4. Exit the game once you reach the main menu. 

## Creating a Nexus Mods Account

Most of your mods and tools will come from Nexus Mods (Nexus), a website that hosts thousands of community-made mods. You cannot download anything from the website without a Nexus account.

To create a Nexus account:
1. Navigate to the [Nexus Mods](https://www.nexusmods.com/) website.
2. In the top right corner of the website, Click **Register** 
3. Follow the instructions provided by the website.

## Installing Mod Organizer 2

Mod Organizer 2 (MO2) is a program that will download and manage mod files for you. See [Introduction to Nexus Mods](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#introduction-to-nexus-mods) for more info.

To install MO2:

1. Navigate to MO2's [page on Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/6194?tab=files).
2. Click the **Files** tab.
3. Look for the **Mod Organizer 2** section, then click **Manual Download**. 
4. Click **Slow Download**.
5. Navigate to the download location and execute the installer.
6. Follow the procedures provided by the installer.  

# Overview of Mod Organizer 2

MO2 is a program used to organize, install, and manage mods for popular games such as Fallout or The Elder Scrolls.

Rather than adding mod files to the game's directory, MO2 manages mods by separating them into an isolated folder, functioning as a virtual directory. The game will read files from MO2 rather than its own directory, tricking the game into thinking it's loading its own directory. With this isolated file system, users can enable or disable mods with a click of a button. In short, the program is designed to streamline the modding process so that users of all experience can mod their own game. 

The features available in MO2 are:

* Isolate mod files from the game directory.
* Enable or Disable mods with a click of a button.
* Sort mods through numerous criteria.
* Download content from Nexus through MO2.
* Provide useful notifications such as updates or warnings for mods.
* Swap mod configurations seamlessly.
* Add additional tools or addons to MO2 for a centralized modding program.

By the end of this section, you should know:

* How to setup your game for MO2
* How each user-interface (UI) element functions
* How to apply each UI element into your modding.

## Setting Up MO2

This section will explain the virtual directory and how to set up your game for MO2.

### Instances, a Virtual Game Directory

An _Instance_ will need to be created every time you add a game to MO2. Instances are folders where mods and configurations for specified games are stored. In normal circumstances, a game will read its own directory to load the contents for the game. However, with MO2, the program will redirect the game towards the Instance folder, making the game think that it is reading its own directory. Because of the Instance folder, mod files will not clutter the game's directory and users can add, delete, or edit mods without messing up the original files for the game. The image below is an illustration of MO2 redirecting the Skyrim.exe to the MO2 folder.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Virtual.png)
|:--:| 
| *MO2 executing Skyrim and redirecting the game to the MO2 directory* |

### Adding SSE to MO2

To add SSE to MO2:

1. Open MO2.
2. You will be asked to create an Instance. Click **Create a Global Instance**.
3. Supported MO2 games will be displayed in a list. Select **Skyrim Special Edition**, then click **Next**. 

   If SSE does not appear like in the image below, click **Browse** and navigate to the SSE directory to select the **Skyrim Special Edition.exe** file.
   
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
9. A review of all options you selected (game choice, Instance location, Nexus account, etc.) will be displayed. After confirming that the provided information is correct, click **Finish**.

SSE has been added to MO2. 

## The Interface

The interface consists of four sections:

* Toolbar
* Installation Panel
* Executables
* Plugins

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Label%20UI%20nolog.png)
|:--:| 
| *The 4 main sections of MO2's interface* |

The sections below will explain the functionally of each element.

## Toolbar

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Highlight.png)

The Toolbar is a 12-button menu that can:

* Change the functionality of MO2
* Customize the UI to the users liking
* Add additional tools or executables to MO2
* Inform the user of updates, errors, or general information.

This section will explain each button and how to use them.

### Instance Manager
![alt next](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Instance%20Icon.png)

The _Instance Manager_ for creating and managing Instances in MO2. This feature is required whenever you want to add or switch games in MO2. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Instance%20ui.png)
|:--:| 
| *Instance Manager window with two games added* |

The left panel lists all the Instances that you've made. Clicking an item in the list will display additional information regarding the Instance; the table below represents the information that will be displayed.

| Field |Description|   
|---|---|
|**Name**   | Name of the selected Instance. You cannot rename the Instance if it is active.  |   
| **Location**  | Location of the Instance's folder. Clicking **Explore** will direct your file explorer the displayed location. |   
| **Base Folder**  |  The directory of the Instance. |  
| **Game**  |  The title of the Instance's game.| 
| **Game Location**  |  The install location of the managed game. | 

The options to manage your Instances include:

* _Create New Instance_ - Adds another game to manage (refer to [Adding your Game to MO2](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#adding-your-game-to-mo2) for the procedures). This will be required every time you want to manage another game with MO2.
* _Open INI_ - Opens the configuration file for the Instance. This option should be left alone.
* _Delete Instance_ - Deletes the selected Instance. A window displaying all associated files will be shown before you can remove the Instance.
* _Switch to this Instance_ - MO2 will restart and switch to the selected Instance.

### Install From Archive

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Install%20mod%20ICON.png)

The _Install From Archive_ button will open your file explorer to select and install downloaded mods. Only mods compressed into a ZIP file can be installed.

```
TIP: Alternatively, you can click and drag ZIP files into the MO2 window to install.
```


### Browse Mod Page

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20Nexus%20Mod%20Link%20ICON.png)

The _Browse Mod Page_ button will direct your web browser to the managed game's section on Nexus Mods (e.g., managing a Skyrim Instance will make the button direct the web browser to the Skyrim section on Nexus Mods). 

### Refresh
![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20refresh%20ICON.png)

The _Refresh_ button will reload MO2. Use this if any changes made to MO2 (load order change, installed or removed mods, etc.) are not immediately reflected.

### Tools

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Tools%20ICON.png)

The _Tools_ button is for executing additional MO2 plugins and addons. These features expand the functionality of MO2 by providing extra options to modify your games.

The tools available by default are:

* _Bethesda Software Archive (BSA) Packer_: Creates BSA files using resources from the managed game or mods. For general modding, this plugin is not needed. 
* _Fores New Idles in Skyrim_ (FNIS): A tool that allows Skyrim to have more animations. As of 2020, this plugin has been made obsolete by [Nemesis](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases), a more up to date animation tool.
* _INI Editor_: A built-in text editor that opens the game's configuration (ini) files. This will be important for editing the appearance of your game for either performance or visual reasons. The image below is an example of the editor viewing the Skyrim INI files.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20ini%20window.png)
   |:--:| 
   | *INI Editor accessing the three configuration files for Skyrim* |
   
As of the making of this document, most tools are now managed by the [Executables](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#executables) feature.

### Profiles

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Profile%20ICON.png)

Multiple mod and game configurations are managed by profiles. Much like how Instances manage multiple games, profiles will manage multiple configurations for a single game. The purpose of this feature is to allow users to playtest and experiment with numerous mod configurations. 

The following information will be unique to each profile:
* Installed mods and their status (installed/disabled).
   *  Mods that are enabled in one profile will be disabled in another.
   *  Mods in new profiles are disabled by default.
* Priority/Load order for installed mods and plugins.
* Configuration files (if checked in profile settings).
* Save files for managed game (if checked in profile settings).

The image below is the _Profile Manager_ which allows you to create, delete, and edit your profiles. Select any of the profiles in the list, then clicking **Select** will swap MO2 to the selected profile, mirroring any configurations set in the selected profile. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Profile%20Window.png)
|:--:| 
| *Profile list with 4 profiles* |

The options to manage your profile include:

* _Create_ - Create a new profile. Installed mods will be disabled by default in the profile.
* _Copy_ - Copy the selected profile
* _Remove_ - Delete the selected profile. This function cannot be used on the active profile.
* _Rename_ - Change the name of an existing profile.
* _INI and Save Games setting_ - Options to make the INI and Save Game files unique to each profile. By default, Save Games is disabled and INI is enabled.

### Configuration

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20config%20ICOn.png)

The _Configuration_ settings have 8 tabs that controls the functionality of MO2 (e.g., languages, mod color coordination, folder directory, etc.). Use this window to tailor MO2 to your liking. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20config%20window.png)
|:--:| 
| *Configuration window |

The table below represents what each tab controls.

| Tab |Description|   
|---|---|
|**General**   | Options for changing the displayed language, updating MO2, and setting miscellaneous options such as centering text. |   
| **Theme**  | Color settings that will highlight enabled mods based on specific conditions. For more information, see [Modlist Color Highlights](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#modlist-color-highlights) |   
| **ModList**  | Additional settings for the Installation Panel such as checking for mod updates, sorting the modlist, and displaying icons based on specific conditions. |  
| **Paths**  | View and change the directories setup for MO2 | 
| **Nexus**  | Displays information for the linked Nexus Mod's account. You may also link and unlink your Nexus account from here.  | 
| **Plugins**  | Lists all games and plugins that are supported in MO2  | 
| **Workaround**  | Game settings such as forced offline mode to disable online features, or always enabling the games default files when playing. New users should ignore this setting.  | 
| **Diagnostic**  | Settings for crash logs, a text file that is automatically generated by MO2 when your game closes due to a crash. The log will contain the mods or scripts that were running at the time of the crash, this is to help you diagnose the potential problem. This file can be accessed by opening the **Overwrite** folder at the bottom of the Installation Panel.  | 

### Executables

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20Execute%20ICON.png)

The _Executables_ is for managing programs added to MO2. When adding a program to MO2, the added program will automatically direct itself to the folders of the managed game (e.g., modding tools that edit files will automatically edit files from the game's directory). The usage of Executables is meant to make MO2 be the center of modding, making it a central hub that contains all your tools and programs. These additional programs can include:

* Games 
* Tools (editing programs such as Skyrim Special Edition Edit (SSEEdit)
* Patchers
* Virtual Folders

The figure below is an example of the Executables window on a fresh SSE Instance. The left side lists all programs added to MO2 and the right side displays information associated with the selected program such as the file location. These programs are shared between all profiles. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20execute%20menu.png)
|:--:| 
| *Three executables for a fresh Instance* |


The options to manage your programs is located above the list. These functions are:

* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Execute%20Add.png) _Add_ - Opens the file explorer to add a supported executable to MO2.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Execute%20Remove.png) _Remove_ - Remove the selected executable from MO2.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Execute%20move%20ex.png) _Rearrange List_ - Move the selected executable up or down the list.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/execute%20add%20default%20plugin.png) _Add Default Plugins_ - Adds executables based on the Instance's game (e.g., adds the Skyrim executable file if the Instance is based on Skyrim). By default, the Instance will have the managed game's executables setup.

To access your executables, see [Executable Menu](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#executable-menu).

The image below highlights additional settings for the executables. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20execute%20menu%20high.png)
|:--:| 
| *Extra settings for Instances* |

These additional settings include:

* _Overwrite Steam AppID_ - Allows the game's Steam ID to be overwritten (If applicable).
* _Create Files in mod instead of overwrite_ - Files that are generated by mods will be placed into their respective mod folders instead of the Overwrite folder.
* _Force Load Libraries_ - The program will automatically execute configuration libraries (DLL files) when running the executable.
* _Use application's icon for desktop shortcut_ - Use the executable's icon when creating shortcuts
* _Hide in user interface_ - The selected executable will be hidden in MO2.

For this guide, the aforementioned settings should be kept on their default settings.

### Endorsement

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20endorse.png)

Nexus Mods uses an endorsement system which influences how much exposure a mod will get on the website. This button is only for endorsing MO2 on Nexus. 

### Notification

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20warning%20high%202.png)

The _Notifications_ icon will inform you of any potential problems in your MO2 configuration. Click the icon to open a window that will explain why there is a warning and how to fix for it. The image below is an example of the notification window explaining the issue. Having a notification doesn't always mean there is an error, but you should try to resolve issues as they appear.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20warning%20desc.png)
|:--:| 
| *Notification warning you about the Overwrite folder* |

### Update Mod Organizer

![alt text](https://github.com/CDimang/SSE-Images/blob/main/toolbar%20update%20not%20ICON.png)

If available, clicking the Update Mod Organizer button will update MO2 to the latest version.

### Help

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Toolbar%20help%20ICON.png)

The _Help_ button is a menu that will provide resources to teach you about MO2. The table below represents the resources available. 

| Resource |Description|   
|---|---|
|**Help on UI**   | Provides a quick overview of MO2's user-interface.  |   
| **Documentation**  | Directs your web browser to MO2's website to view the documentation available for MO2|   
| **Chat on Discord**  | Provides a link to the MO2 official Discord server. Here you can communicate with developers and other users for help. |  
| **Report Issue**  | Directs the web browser to MO2's bug report forum. | 
| **Tutorial**  | Starts the built-in tutorial that will explain MO2 to you. You cannot stop the tutorial once it starts.  | 
| **About**  | Displays copyright information, contributors, and software used in MO2.  | 
| **About Qt**  | Copyright and general information for Qt, a C++ toolkit used to develop MO2.  | 

## Installation Panel

The _Installation Panel_ is where all installed mods will be listed. You will be able to enable, disable, organize, and sort mods in this panel. This section of the document will explain each UI element of the panel and how to use each element for your mods.

### Interface Elements

The figure below highlights the important components of the panel.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Installation%20panel%20highlight%20labels%202.png)
|:--:| 
| *The main components of the Installation Panels* |

The highlighted elements in the figure above is for the following:

* _Profile Menu_ - A dropdown menu to quickly swap profiles.
* _Mod Options_ - Modlist options that includes installing a mod, dividing the modlist by categories, and enabling or disabling mods.
* _File Explorer_ - Opens the file explorer for the Instance or managed game.
* _Restore/Create Backup_ - Save the profile's modlist to be loaded at a future date. Loading a saved modlist will overwrite your active modlist. The information saved includes:
   *  All installed mods.
   *  The order of the installed mods.
   *  The status (enabled or disabled) of the mods at the time of saving.
   *  The flags and notes that were active at the time of saving. 
* _Active Mod Count_ - Displays the number of enabled mods.
* _ModList_ - Lists all installed mods. Mods listed here will display their name, conflicts, flags, category, version number, and priority number. The checkboxes to the left of the mod's name will indicate the mods status via checkmark for active or blank for disabled. More information on the list will be explained in the [Sorting the Modlist](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#sorting-the-modlist) section.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Modlist%20mods.png)
   |:--:| 
   | *Example of a modlist with three mods installed* |
  
* _Search Bar_ - A search filter that will update the list as you input characters.
* _Mod Filter_ - Opens a side panel with options to show or hide mods based on specified conditions. The image below is an example of using the filter with three scenarios (A, B, and C respectively). Clicking the checkboxes will cycle through **show** or **hide** mods (Indicated by a green checkmark or red dash respectively).
 
   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/filter%203%20example%203%20small.png)
   |:--:| 
   | *Three scenarios for using the filter* |
   
   To further elaborate on the image above:
   
   * Scenario A has the **Active Mods** filter disabled, so every mod in the list is visible.
   * Scenario B has **Active Mods** set to **Show**, so only mods that are active are visible.
   * Scenario C has **Active Mods** set to **Hide**, so mods that are active are hidden.

### Sorting the ModList

Organizing your modlist will help you keep track of your installed mods, especially if you decide to install a large quantity of mods.  

One way to sort your mods is by clicking the columns at the top of the list; your mods will be arranged based on the column selected. By default, your modlist will be sorted by Priority.  

![alt text](https://github.com/CDimang/SSE-Images/blob/main/sort%20installation.png)
|:--:| 
| *Columns to organize the modlist* |


The table below represents the available columns to sort by.

| Column |Description|   
|---|---|
|**Mod Name**   | Modlist is organized alphabetically. |   
|**Conflict**   | Modlist is organized based on which mods are conflicting with one another. This usually occurs when mods have files of the same name. |   
| **Flags**  | Modlist is organized based on the notification icons assigned to them. The icons will only display when specific conditions are met. For more information, refer to the [Flags section](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#flags). |   
| **Content**  | Modlist is organized based on the category assigned by their author. If the mod has not been assigned a category, it will be set towards the bottom of the list. See Custom Categories to learn about assigning categories to mods. |  
| **Version Number**  | Modlist is organized based on their version number and if they are up to date.| 
| **Priority**  | Modlist is organized based on their assigned priority number. This number determines the order in which mods will load when opening the managed game. For more details on Priority, see Mod Priority/Load Order. | 

You can also rearrange your modlist by clicking and dragging mods through the list. This method for organizing mods should generally be done when you want to place a mod in a specific location.


> NOTE: You cannot click and drag mods unless your modlist is sorted by Priority.

#### Flags

_Flags_ are notifications that appear when the associated mod has met a specific condition. The flags are intended to notify you if mods are interacting with one another or meets a criterion that should be addressed. The figure below is an example of mods being marked with flags. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%20Flags%20example.png)
|:--:| 
| *Mods that were flagged* |

The flags that can be displayed include:

* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20conflict%20win.png) _Conflict Win_ - Mod is overwriting at least 1 files from another mod.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20conflict%20lose.png) _Conflict Lose_ - Mod has at least 1 files being overwritten by another mod.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20conflict%20win%20and%20lose.png) _Conflict Win Lose_ - Mod is overwriting at least 1 file from another mod while also having 1 of its own file being overwritten
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20Redundant%202.png) _Redundant_: Mod has all of its files being overwritten by another mod.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20invalid%20file%20mod.png) _Invalid_ - Mod contains invalid files that cannot be read by MO2. Mods marked with this flag cannot be enabled.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20unendorsed.png) _Unendorsed_ - Mod has not been endorsed by the user. After you install a mod, this icon will appear after an undetermined amount of time.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20personal%20note.png) _Note Added_ - Indicates that a note has been added to the mod. 
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Flag%20needs%20update.png) _Outdated_ - The mod is outdated and has an update available for download. This flag only appears for mods from Nexus.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/flag%20wrong.png) _Wrong Game/Version_ - Mod is for a different game or game version (e.g., Legendary Edition Skyrim mod vs Special Edition Skyrim mod). 


#### Assigning Custom Categories to Mods

Mods can be assigned to any category (e.g., gameplay, immersion, bugfix, etc.) in MO2. 

To assign a category to a mod:

1. Right click a mod in the modlist.
2. Click **Change Categories**. A list of categories will appear. 

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%20Change%20Category.png)

3. Click the **Checkbox** of the category you wish to assign to the mod.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%20Change%20Category%202.png)

If the mod has multiple categories, you can choose the displayed category by clicking **Primary Category** (located beneath **Change Categories**) and selecting a category in the list. 

If none of the categories feel fitting for a mod, you can create a custom category with following procedures:

1. Open the **Configuration Settings**.
2. In the **General** tab, click **Configure Mod Categories**.
3. Right-click within the columns, then click **Add**. A category called **New** with be added.
4. Double click **New** to rename the category.
5. Click **OK**.


### Modlist Color Highlights

When selecting a mod in the list, mods that are interacting with the selected mod will be highlighted in a specific color. The highlights are for notifying the user of potential conflicts, overwrites, or redundancies in your modlist. 

The image below is an example of multiple mods interacting with **TK Dodge SE**, the selected mod.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/color%20plugin%202.png)
|:--:| 
| *Multiple mods that are interacting with the selected plugin* |

The colors in the image above represents the following interactions:

* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Color%20highlight%20blue.png) The mod is selected.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Color%20highlight%20purple.png) The plugin is from the selected mod.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Color%20highlight%20green.png) The mod is being overwritten by the selected mod.
* ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Color%20highlight%20red.png) The mod is overwriting the selected mod.

Pay close attention to which mods are overwriting one another as there may be unintended effects from the mods. These conflicts can generally be resolved by:

* Rearranging the mod's order
* Removing the affected mods
* Downloading a patch to resolve the conflict.


> NOTE: Overwritten mods are not always invalidated and is sometimes intended by the mod author to interact with other mods.


### Mod Priority/Load Order

The load order determines which mods will take precedent when loading the game. Mods that edit similar elements in the game will typically share the same files which will end up overwriting each other depending on the load order. In other words, mods that are loaded later will overwrite mods that are loaded earlier. 

The image below is an illustration of a load order consisting of three mods interacting with one another. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Load%20Order%20Image.png)
|:--:| 
| *Example of how a game loads with three mods* |

The figure above presents the following information:

* Skyrim will load mods based on their load order in MO2.
* **Mod A**(Toothbrush Sword) and **Mod C**(Master Sword) are both changing the model of the Iron Sword, an in-game item from Skyrim.
* **Mod B** (Flame effect) also edits the Iron Sword by adding a visual effect. The mod does not touch the model.

Based on the image and the information above, the load order performs the following steps:

1. **Mod A** loads first and changes the Iron Sword to a Toothbrush Sword.
2. **Mod B** loads second and adds the flame effect to the Iron Sword (which is now a Toothbrush Sword). It is now a Flaming Toothbrush Sword.
3. **Mod C** loads and changes the Iron Sword into the Master Sword, overwriting **Mod A**. The Flaming Toothbrush Sword is now a Flaming Master Sword. 
4. The game loads with only the Flaming Master Sword (**Mod B** and **C**) active.

The information above demonstrates how the interaction between multiple mods can create interesting combinations, but it can also create redundancies in your modlist.

When installing multiple mods that interact with the same in-game elements, be sure to always read the mod's description page on Nexus to figure out how it will interact with like-minded mods. You want to reduce the number of redundancies in your load order. This is especially important when ordering [plugins](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#plugin-panel) that are installed with the mods. 

### Overwrite Folder

The _Overwrite_ folder stores all files that would have been placed into the game's directory. **The folder will always be considered an enabled mod**. You can access this folder by clicking **Overwrite** at the bottom of the modlist. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/overwrite%20and%20folder.png)
|:--:| 
| *Overwrite folder with content inside* |

Files that are dumped into Overwrite are typically from mods or tools that generate an output file to function. Some examples include:

* Crash Logs
* Information Dumps
* Engine modification
* Mod patches
* Save data

Keeping files in Overwrite will not harm to your game, but as stated earlier, they are considered active mods and should be organized like any other mod. To manage your Overwrite folder, you can choose to create a mod comprised of the contents of the folder. 

To convert the contents of Overwrite into a mod:

1. Right-click **Overwrite**.
2. Click **Create Mod**.
3. Enter the name of the mod (preferably based on the contents of the folder).
4. Enable the mod. 

Since creating a mod will use **all** files in Overwrite, it is recommended that you follow the procedures above as soon as you have files dumped into Overwrite because you want to be able to keep track of where the generated files are from. While mixing Overwrite files from multiple sources is not harmful to your game, keeping track of the files may be very inconvenient. 

## Executable Menu

The _Executable Menu_ is for launching programs that were connected to MO2 through the [Executables Settings](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#executables). The figure below highlights the components of the menu. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Executable%20panel%20highlight.png)
|:--:| 
| *The three main components of the Executable Menu* |

The components in the image above are for the following functions:

* _Executable List_ - A drop-down menu that lists all programs that have been added to MO2.
* _Run Program_ - Execute the selected program. MO2's window will be locked whenever a program is executed this way. You will not be able to interact with the UI in any capacity.
* _Add Shortcuts_ - Create a shortcut for the selected program. The shortcuts can be added to MO2's toolbar, the desktop, and the Windows Start Menu.  


## Plugin Panel

Plugins are scripts that are used to add features into Skyrim's game engine. This is how mod authors inject brand new features into the game. Plugins are typically included with mods that are installed; however, not every mod will use a plugin. The Plugin Panel is where you will manage all plugins that are added to your game. Alongside Plugins, you can also manage other information here such as save data or downloads. The image below is an example of viewing the _Data_ tab, which displays all the files used in the Instance.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%20Data.png)
|:--:| 
| *Plugin Panel viewing the Data tab* |


The panel consists of five tabs which are for the following:

| Tab |Description|   
|---|---|
|**Plugins**   | Lists all plugins that were added from installed mods. Not every mod will contain a plugin.  |   
| **Archives**  | Lists all active BSA files from the Instance. |   
| **Data**  | Lists all files provided by installed mods. |  
| **Saves**  | Lists all save files for the Instance's game. Provides details such as game time, statistics, and mods. | 
| **Downloads**  | Lists all valid ZIP files in MO2's Download folder. | 

Given the scope of this document, the sections below will only focus on the _Plugins_ and _Downloads_ tab since the other three will not be necessary for modding. 

### Plugins Tab

The _Plugins Tab_ will list all installed plugins (ESP, ESL, or ESM files). Not every mod will use a plugin, so do not worry if the number of active plugins does not match the number of active mods. The image below is an example of the tab with over 200 plugins.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/MO2%20Plugin%20Panel.png)
|:--:| 
| *Viewing some of the active plugins* |


At first glance, the image above shares similar features to the Installation Panel such as the checkboxes, active plugin count, and ability to drag plugins through the list. Due to the nature of plugins, the load order in this tab will be independent from the Installation Panel.


#### Using the Load Order Optimization Tool

The Plugins Tab uses an addon known as the _Loot Order Optimization Tool_ (LOOT), a plugin that automatically sorts your plugin list. LOOT uses a master list developed by numerous mod authors to determine the best way to order mods based on their category, scope, and implementation. 

In addition to sorting your mods, the program also includes:

* Checking for errors such as mod incompatibility or missing requirements.
* Providing plugin specific notifications for potential issues.
* Organizing the list in a way to have as few conflicts as possible.

Sorting your plugins into a proper order is one of the best ways to create a stable mod list that will prevent crashes and mod conflicts.

To use LOOT, click the **Sort** button at the top of the window; the LOOT window will open and begin sorting your plugin list. Once it has finished sorting, the window will inform you of any potential conflicts. The image below is an example of the LOOT window displaying a potential conflict.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Loot%20Window%20Sorted.png)
|:--:| 
| *Loot displaying potential conflicts after sorting* |


> NOTE: It is recommended to use LOOT whenever you add a new plugin.


#### Good Plugin Practices

Much like mods, plugins can also be enabled or disabled by clicking the associated checkboxes in the plugin tab. While plugins can introduce unique features to Skyrim, they can create numerous issues if mismanaged. 

Some good plugin practices to consider are as follow:

* Plugins should **never** be removed from an active playthrough (existing save file). The game will attempt to call the removed plugin which will likely crash your game. The image below is the warning message that appears when you load a save file with a missing plugin.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/missing%20plugin.png)
   |:--:| 
   | *Do not try to load a file with a missing plugin* |
  
  
* It is generally okay to add plugins to an active playthrough unless stated otherwise by the mod author.
* Always make a copy of your save file before adding plugins (if adding to an active playthrough). This is so you can revert to an old save file if you find issues with an added plugin.
* The game will not load plugins until you open a save file (in-game via past the title screen through New Game or Continue Game). This prevents all existing files from being affected by new plugins.

### Downloads Tab

When downloading mods from Nexus, all files will be directed to MO2's download folder and displayed in this tab. The figure below is an example of the tab with two mods downloaded.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20tab.png)
|:--:| 
| *Two files downloaded from Nexus* |

This tab will display the following information for the files:

* The name of the files.
* The status of the files (installed, uninstalled, or recently downloaded).
* The size of the files.
* The time and date of download.

You can install mods from this tab by double-clicking a file.

# Introduction to Nexus Mods

Nexus Mods (Nexus) is a website where users can upload and download mods. The website is free to use and is easily accessible for anyone who wants to mod their games. The image below is homepage which displays the most popular games on the website.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Homepage.png)
|:--:| 
| *Homepage* |


This section will focus on teaching you how to use the website. By the end of this section, you will know:

* How to navigate the website.
* How to filter content to your liking.
* How to read information on a mod page.

## Navigating Nexus Mods

Starting out, the website can feel confusing to navigate at times, so this section will help you get a general understanding of what to look for on the website. 

For the purpose of organization, each game is separated into their own individual sections on Nexus. From the homepage you can select your favorite games to begin looking for mods. In the image below, the browser was directed to the Skyrim Special Edition section of the website.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Skyrim%20Section.png)
|:--:| 
| *The current section you are browsing (Skyrim Special Edition)* |


While inside the game's section, all navigation links and searches performed will be contained to that specific section only(e.g., if you are in the Skyrim section, only Skyrim content will appear if you use the search bar or navigational links).

### Searching the Modlist

The sections below will instruct you on how to find mods based on certain conditions. 

#### Find a Specific Mod 

Enter the name of the mod into the search bar at the top of the screen. Based on the inputted text, mods will be displayed beneath the search bar.

#### Find Mods Based on Categories 

If you are searching for a specific mod category:

1. At the top of the screen, click **Mods** > **Mod Categories**

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Mods%20to%20Mod%20Category.png)

2. Click a category of your choosing.

If you want to search for multiple mod categories:

1. At the top of the screen, click **Mods** > **Browse All** (any option in **Mods** would suffice here)
2. In the **Refine Results** box, click the **Blue Box** on the right.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Specific%20Category%201.png)

3. Inside the **Refine By Category** section, click the checkboxes of your desired categories.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Mods%20to%20Mod%20Category%202.png)

4. Click **Apply Filter**


## Blocking Content on Nexus

Given wide possibilities of content that can be created in a mod, some users may be uncomfortable with certain content (violence, sexual content, etc.) or they may dislike a certain category of mods (gameplay, immersion, etc.). You may can block certain categories from appearing when you browse the website.

To block content on the website:

1. In the top right of Nexus, click **your Profile Icon** > **Site Preferences**.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Block%20Content%201.png)

2. Click **Content Blocking**
3. In the **Search for tags to block** section, click the tags of any categories you wish to block. Blocked content will be highlighted in red

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Block%202.png)

## Understanding the Mod Page

The mod page of any mods that interest you will provide information such as features, bugs, and community feedback. The image below is the mod page for the _Unofficial Skyrim Special Edition Patch_, one of the most popular mods on the website.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Nexus%20Mod%20Page%201.png)
|:--:| 
| *General information you will see when you enter a mod page* |


The image above highlights general information that serves as a preview when you open the page. The information provides the following:

* _Statistics_ - Number of unique downloads, endorsements, views, and date for uploads.
* _Images and Videos_ - Media to demonstrate the mod.
* _Tags_ - Tags to categorize the mod when browsing the website.
* _Information Tabs_ - Information for the mod based on the associated tab.
* _Media Buttons_ - Buttons for:
   *  _Add Media_ - Upload your own images or videos to demonstrate the mod.
   *  _Track_ - Gives you a notification whenever the author makes any changes to the mod page.
   *  _Endorse_ - Give your approval to the mod. Endorsements will increase the promotion the mod gets on the website.
   *  _Vote_ - Gives the mod a vote for the Mod of the Month event. This option will be unavailable if the mod has won before.

### Mod Page Information Tabs

The tabs on the mod page will provide information on the mod. Clicking a tab will display it in the bottom half of the page. 

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Mod%20page%20tabs.png)
|:--:| 
| *Tabs that are active for this particular mod page* |

The blue boxes next to the names of the tabs represents how many items are uploaded to the tab.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Mod%20Tab%20Box%20File.png) - There is **1 file** that can be downloaded.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Mod%20Tab%20Box%20Image.png) - There are **15 images** uploaded to this page.

The tabs available on the page will vary from mod to mod. The mod author can choose to hide specific tabs if they deem it unnecessary to the mod's presentation. 

The table below represents the 9 tabs available for a mod page.

| Page Tab  | Description |
| ------------- | ------------- |
| **Description**  | Describes the mod. Will generally present information such as features, requirements, procedures for installation, conflicts with other mods, and solutions to common problems.   |
| **Images** | Screenshots to show the mod will look in-game. Users can upload their own images here, but the author can choose to delete your images if they conclude that it has no relevance to the mod.  |
| **Files**  | Files that can be downloaded through MO2 or manually through your PC. For more information, refer to [Downloading and Installing Mods](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#downloading-and-installing-mods).  |
| **Videos**  | Videos that demonstrate the mod in-game. Users may also upload their own videos here. |
| **Articles**  | Additional documentation related to the mod. Documents here will vary.  |
| **Posts**  | A discussion board where the author and users can have a discussion related to the mod.   |
| **Logs**  | Tracks all changes that were made to the mod page. |
| **Stats**  | A graph that tracks the dates for downloads, endorsements, and views. |
| **Bugs**  | A discussion board where users can report any bugs they encounter with the mod.  |


# Downloading and Installing Mods

Most of your mods will come from Nexus. Mods will typically follow the same installation procedures but there are a few exceptions that require additional setup. Be sure to **always read the mod's description page** before installing any mods; the mod page may include information such as instructions, documentations for compatibility with other mods, or frequently asked questions (FAQs). 

This section will demonstrate how to use MO2 and Nexus to download and install mods. The information below will explain the general procedures for installing a mod. Given the nature of some mods, the procedures below may vary.

1. On the mod page, click the **Files** tab.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20Mod%201.png)

2. In the **Main Files** section, click **Mod Manager Download**.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20Mod%202.png)

3. Click **Slow Download**. The website will ask for permission to access MO2.
4. Click **Open NXM Link Proxy**. MO2 will open and download the mod.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20Mod%2023.png)

5. In the **Plugin Panel**, click the **Downloads** tab.
   * If a mod is not downloaded from Nexus, you can drag the file here and proceed with step 6.
6. Double-click the mod to install it. Click **OK** when prompted.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20Mod%203.png)

7. In the **Installation Panel**, click the mod's **checkbox** to enable it.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Download%20Mod%204.png)

8. If the mod contains a plugin, click **Sort** in the **Plugin Panel** to sort it with your other plugins.

# Essential Mods for Skyrim

Regardless of how many mods you want to include in Skyrim, there are 4 mods that should **always** be included in a playthrough. Skyrim is known have numerous bugs and limitations that can negatively impact the user experience. Such issues include random crashes, unintentional effects in-games, and unoptimized gameplay. 

There are four essential mods designed to resolve the numerous issues with Skyrim. These include:

* _Skyrim Script Extenter (SKSE)_ - An addon to Skyrim's game engine that expands the limitations of scripts that can be used in-game
* _Unofficial Skyrim Special Edition Patch (USSEP)_ - A community made patch that aims to fix every bug that has not been officially resolved by Bethesda
* _Skyrim Special Edition Engine Fixes_ - A _SKSE_ plugin that resolves the numerous issues that are included with Skyrim's Creation Engine.
* _SkyUI_ - While a UI mod is not technically "essential", it fixes the cumbersome interface of Skyrim by providing a more user-friendly menu. Most of mods rely on _SkyUI_ to implement the UI elements of their mod.

This section will explain the importance of each mod and how to install them.

## Skyrim Script Extender (SKSE)

![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%20Logo.jpg)
|:--:| 
| *SKSE Logo* |

The _Skyrim Script Extender_ (SKSE) is an addon to Skyrim's scripting language that allows mod authors to develop features that are beyond the scope of what the game can handle. Skyrim's engine is very limiting and has the bare minimum functions to create dynamic features. Therefore, _SKSE_ is needed to create scripts that can introduce unique features and mechanics into the game.  

Some examples of scripted mods include:

* When dying in-game, your character can get teleported to the nearest inn.
* When swinging your weapon, a fireball could be shot from the weapon.
* When you ride a horse, your character can now fly.

Scripts are always included with any [plugin](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#plugin-panel) you install. While they can be a problem if mismanaged, they are essential for creating mods for Skyrim. SKSE is required for every mod that includes a script.

### Installing SKSE

_SKSE_ is not from Nexus and must be manually placed into your SSE directory. 

1. Navigate to the [SKSE website](https://skse.silverlock.org/).
2. Look for **Current SE Build** at the top of the page, then click **7z archive** to download the ZIP file.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%201.png)

3. Open the ZIP file
4. Extract **all** of the file's content into the SSE directory. Merge all folders when asked.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%202.png)

5. In MO2, open the **Executable Settings**.
6. Click ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Execute%20Add.png), then select **Add from file**. You will open the Windows File Explorer

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%203.png)

7. Navigate to your SSE directory, then select the **SKSE_64loader** executable file.
8. Back in the **Executables Setting**, click **Apply**, then **OK**.
9. In the **Executables Menu**, open the executable list, then select **skse64_loader**.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%204.png)

10. Click **Run**. You will be running SSE through _SKSE_.
11. On the game's title screen, press the (~) key. You will be opening the game's console.
12. Type **SKSE version** into the console. If you get a message similar to the image below, _SKSE_ is installed. If not, make sure all the files have been properly extracted to the SSE directory. 

    ![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKSE%205.png)

## Unofficial Skyrim Special Edition Patch

![alt text](https://github.com/CDimang/SSE-Images/blob/main/Unofficial%20Patch%20banner.png)
|:--:| 
| *USSEP Banner* |


The _Unofficial Skyrim Special Edition Patch_ (USSEP) is a mod that is intended to eventually fix every bug in SSE. The amount of changes is large, so please visit the [Unofficial Patch Project Team website](https://www.afkmods.com/Unofficial%20Skyrim%20Special%20Edition%20Patch%20Version%20History.html) if you want to review all the fixes made in the patch.

The patch is designed to work with every mod. Given the popularity of this patch, many authors design their mod with this patch mind, making it a requirement for a majority of mods. 

### Installing USSEP

USSEP can be installed like any other mod from their [Nexus page](https://www.nexusmods.com/skyrimspecialedition/mods/266). Refer to [Downloading and Installing Mods](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#downloading-and-installing-mods) for the procedures.

## Skyrim Special Edition Engine Fixes

The _Skyrim Special Edition Engine Fixes_ (SSE Engine Fixes) is an _SKSE_ addon that focuses on resolving the many issues that come from Skyrim's game engine such as preventing your save files from being corrupted or increasing file limit of the game. 

### Installing SSE Engine Fixes

_SSE Engine Fixes_ requires _SKSE_ and _Address Library for SKSE Plugins_. SKSE should already be installed by this point. _Address Library for SKSE Plugins_ is an addon that prevents mods from breaking when they don't match the current version of SSE. This means that whenever SSE receives an update, mods will still function regardless of if they are outdated.

[_Address Library for SKSE Plugins_](https://www.nexusmods.com/skyrimspecialedition/mods/32444) can be installed like any other mod, refer to [Downloading and Installing Mods](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#downloading-and-installing-mods) for the procedures.

To install _SSE Engine Fixes_:

1. Navigate to the [SSE Engine Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/17230?tab=description) page on Nexus
2. Click on the **Files** tab.
3. Look for **(Part 1) SSE Engine Fixes for 1.5.39 - 1.5.97**. Click **Mod Manager Download**
   * Follow the usual [installation procedures](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#downloading-and-installing-mods) to install **Part 1**.
4. Once you've installed **Part 1**, go back to the **Files** on Nexus and look for **(Part 2) Engine Fixes - skse64 Preloader and TBB Lib**. Click **Manual Download**.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Engine%20Part%201.png)

5. Open the downloaded ZIP file and extract all its content into your SSE directory. Overwrite all files if asked.

   ![alt text](https://github.com/CDimang/SSE-Images/blob/main/Engine%20Part%202.png)

## SkyUI

_SkyUI_ is an interface mod that improves the usability of Skyrim's UI by reducing the amount of empty space used and showing more information on the screen. The image below is a comparison between the original UI and _SkyUI_. As seen on the right side, some noticeable differences include:

* Showing more items on the screen.
* Providing information on the items without clicking the items.
* Including a search function to find specific items.
* Using icons to display item categories.

![alt text](https://github.com/CDimang/SSE-Images/blob/main/SKYUI.jpg)
|:--:| 
| *Default UI compared to SkyUI* |


_SkyUI_ also allows the user to access the **Mod Configuration Menu** in-game which is a menu that allows you to configure your installed mods (if included by the mod author). Due to the popularity of this interface, mod authors will design their mods with this interface mind, making it a requirement for most mods.

### Installing SkyUI

_SkyUI_ can be installed like any other mod from their [Nexus page](https://www.nexusmods.com/skyrimspecialedition/mods/12604?tab=description). Refer to [Downloading and Installing Mods](https://github.com/CDimang/SSEModdingGuide/blob/main/README.md#downloading-and-installing-mods) for the procedures.

