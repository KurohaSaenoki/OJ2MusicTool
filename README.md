# UE4-ACB-Tool
Does the Hex Editing for you so it's easier to create music packs.

## USAGE

* Use [umodel](https://www.gildor.org/en/projects/umodel) or [fmodel](https://fmodel.app/) to extract game files
* Find and extract a .uasset/uexp that contains a .acb
* Download and extract [UnrealPak](https://www.fluffyquack.com/tools/unrealpak.rar)
* Create a folder inside [UnrealPak](https://www.fluffyquack.com/tools/unrealpak.rar) called whatever you want the compiled .pak name to be
* Create the same folder structure as the extracted game files inside your UnrealPak/Mod/ folder (Example for My Hero One's Justice 2: MusicMod/HeroGame/Content/Sound/Bgm/)
* Make sure the .uasset/uexp inside the same folder structure as it was extracted
* Open this [UE4 ACB Tool](https://github.com/KurohaSaenoki/UE4-ACB-Tool/releases) and click on "Extract ACB"
* Select the .uasset/uexp to extract from, and save the .acb as the same name as the matching .awb
* Place the .acb in the same location as the .awb
* Open the .acb with [Eternity Audio Tool](https://mega.nz/file/W5NHxDYD#IM7xirUu1-K8e34lINmgC3MFqG1OWFTuscbSptK5fRw) or [ACE](https://github.com/LazyBone152/ACE)
* Replace / Add the Music tracks you want (Use [Audacity](https://www.audacityteam.org/) or other audio software to get a song setup as .wav with the same frequency the game uses.)
* Open this [UE4 ACB Tool](https://github.com/KurohaSaenoki/UE4-ACB-Tool/releases) and click on "Import ACB"
* Select the .uasset/uexp you want to import to, then your modified .acb
* Compile the mod pak with [UnrealPak](https://www.fluffyquack.com/tools/unrealpak.rar) by dragging the Mod folder into either .bat
* Install with [Unverum](https://gamebanana.com/tools/7162) if possible, or place it in your games Paks/~mods folder (if a ~mods folder doesn't exist, simply create it)
* Do any additional steps necessary for the game to load the .pak, My Hero One's Justice 2 requires the HeroGame pak to be renamed before it loads more .paks and must have a copied .sig

## VIDEO TUTORIAL

[![Click here to watch the tutorial](https://img.youtube.com/vi/bWf3RHArecI/0.jpg)](https://youtu.be/bWf3RHArecI)
[![SC2 Video](UMU/GitHubAssets/YouTube.gif)](https://www.youtube.com/watch?v=ZZrEZMi6X5o&list=PLQyrynUmnHDsB8CHILpZ_9AYXODkaNBQE)
