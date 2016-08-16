# Minecraft Modding
Minecraft is made in Java, and as such is very easy to mod for. There 
are several commonly-used APIs for this, but the most popular is 
[Minecraft Forge](http://files.minecraftforge.net). We will be using 
Minecraft Forge for Minecraft 1.7.10, as this is still the version most 
commonly used for modding.

So, lettuce begin!
## Part 1 - Setting up a workspace
*[MDK]: Minecraft Development Kit

Firstly you want to navigate to [http://files.minecraftforge.net](http://files.minecraftforge.net) and download the src package (also known as the MDK) for the version of Minecraft you want to mod for. Most mainstream mods are currently on Minecraft 1.7.10, as 1.8 made some _VERY_ big changes to how block data and models are created and stored, and so we will use 1.7.10.

### Windows:
Once the MDK has downloaded, extract the zip archive and open a Command Prompt (I repeat, this is for Windows) in the extracted directory and run the command `gradlew setupDecompWorkspace`, which tends to take between 10 and 15 minutes to complete (it varies though). Once that is done, run `gradlew eclipse`, which generally takes 5 to 10 minutes. Next, you want to download and install the Eclipse IDE from [http://www.eclipse.org/downloads/eclipse-packages/](http://www.eclipse.org/downloads/eclipse-packages/)

### OSX:
TODO

### LINUX:
TODO


Once you are done, close your cmd or Terminal window and open the Eclipse IDE, which will ask for a workspace folder. Set this to the 'eclipse' folder inside the extracted MDK directory, and press OK. Give it a minute to load, and Eclipse should open. Inside the src/java/main folder there should be a package named com.examplemod or similar - this can be deleted as we do not need it.
So there we have it! In the next tutorial we will start work on our main mod class and our CommonProxy, ClientProxy and ServerProxy classes, and have a functional mod, one which appears in the mod list inside Minecraft.


#### More coming soon!
