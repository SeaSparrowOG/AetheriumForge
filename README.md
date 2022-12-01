# Aetherium Forge - A modlist for mod makers.

## Preamble

 I have been modding Skyrim Special Edition for 3 years. During that time, I took an interest in making mods, and have been having a blast doing so. I spent a considerable amount of time helping others create mods or solving issues with their load order, and thought to myself "What if I used an automated tool to make it easier to create mods for begginers?". And thus, the idea of the Aetherium Forge was born.
 

------------


 ## Installation
 Installation is relatively simple. For the sake of completeness, I will be going over all the necessary steps, including installing the prerequisites.
 

------------


 ### The Pre-Requisites
 1. **Windows 10 x64**
   Currently, this modlist only supports Windows 10 x64. If you run any other OS, you are on your own.
 
 1. **7-Zip**
   Likely already installed and running on your computer. Navigate to the 7-Zip site, linked [here](https://www.7-zip.org/ "here"), and download the latest release for your operating system (likely windows x64). Follow the installer prompts.
7-Zip is a free to use file archiving program that is incredibly usefull for a variety of tasks. In your modding journey, you will mostly use it to pack your mods to release them on the nexus.
 
 1. **C++ Redistributable**
   Likely already installed and running on your computer. Navigate to Microsoft's website, linked [here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022 "here"), and download the "x64" version.
 
 1. **Nexus Account**
   Nexus is THE hosting site for Skyrim Special Edition mods, bar none. In order to install this modlist, you will need a nexus account to download mods, and for uploading your future mods. Thankfully, it's free and easy to do. Go [here](https://users.nexusmods.com/register "here") and follow the instructions. Do not create multiple accounts.

### Prepping your Skyrim Special Edition installation
1. **Clean Installation**
  In order for Wabbajack to finish the installation, it needs you to have the latest Skyrim Special Edition installed. This means that you need to have all UNEDITED files for Skyrim version 1.6.640 somewhere on your hard drive. This is relatively simple.
  1. Open Steam.
  1. Under "Library", locate "Skyrim Special Edition" and right click it.
  1. Click on "Properties".
  1. Click on "Local Files" in the window that pops up.
  1. Click on "Verify integrity of game files..."
    Notice that if you have modified any of the base game files (Downgrading or "cleaning" them through QuickAutoClean"), this will undo your modifications.
1. **Clean Creation Kit Installation.**
  1. Open Steam.
  1. Under "Library", locate the search bar.
  1. Search for "Skyrim Special Edition: Creation Kit".
  1. Click on "Install", and install like you would any Steam game.
1. **Extracting the "Source" pack.**
  1. Open Steam.
  1. Under "Library", locate "Skyrim Special Edition" and right click it.
  1. Click on "Properties".
  1. In the window that pops up, click on "Local Files".
  1. Click on "Browse" on the top ribbon.
    This is your "Base Directory". It's where Skyrim is installed. It's good practice to pin it to your Quick Access bar, because you'll be going there frequently.
  1. Locate the "Data" folder and go inside.
  1. In there, there is a "Scripts" compressed file. Right click it, and under the 7-zip category, there is an option to "Extract Here". Click it. If you do not have the "7-Zip" menu, that means that 7-Zip was not installed correctly.
1. **Running the Creation Kit once.**
  1. Open your "Base Directory". If you do not know what that is, refer to step **17** under "Extracting the Scripts pack".
  1. Double-click on "CreationKit".
  At this point, you may notice that the creation kit\'s "render window" is **RAPIDLY FLASHING.** If you are susceptible to epileptic attacks, **DO NOT PROCEED**. This is an issue with the latest NVIDIA drivers, not the creation kit itself.
  1. If you are given a prompt to extract the "Scripts.zip" pack, ignore it - you've already completed this step.
  1. Close the Creation Kit.
  

------------

### Running Wabbajack

Congratulations! You are now at the point where you can run wabbajack. First, you\'ll need to download it, then choose the Aetherium Forge list, and then install it.

1. Download the latest release of the Aetherium Forge from this repository. After you finish the installation, you can delete it.
1. Downloading Wabbajack
  1. Navigate to [Wabbajack.org](https://www.wabbajack.org/ "Wabbajack.org"). Ths is the official website from where you will download and install Wabbajack itself.
  1. Click on "Download".
    This will download an **EXECUTABLE**, not an archive. I recommend putting it in a folder somewhere (example: C:\Wabbajack Executable), making a shortcut of it and moving the shortcut to the desktop.
1. Run Wabbajack
1. Choose "Install From Disk".
1. Under "Target Modlist", press the elipses to the right of the field (the three dots) and navigate to where you placed the "Aetherium Forge" file.
1. Under "Modlist Installation Location", you\'ll want to choose **SPECIFICALLY** "C:\Wabbajack\Aetherium Forge". If the folder does not exist, create it. Don\'t rename it, make sure you don\'t make a typo. The location is important so some of the tools can run.
1. Under "Resource Download Location", choose any location on your PC. You can delete these files after you successfully run Wabbajack.
1. Congratulations! You're now ready to start using the Aetherium Forge.
