# MusicAutomationTool
A python script that automatically generates the required .asset and .txt files for EU4 music mods

MUSIC AUTOMATION TOOL (MAT) for Europa Universalis 4

This is a script that creates the required .asset file and a basic .txt file for your Europa Universalis 4 Music Mod based on the .ogg files inside your mod's Music folder.

The script will skip over any file called "maintheme" as this only replaces the loading music and is not shown in-game by the audio engine.
The script also allows for your files to be prefixed with a number and an underscore, e.g. 1_Pokemon.ogg, 2_YuGiOh.ogg, so that you can order your music tracks. This naming system is supported up to "99_XXXXX".
You are strong encouraged to hop into the generated files and check that everything has been created properly. In particular, you may wish to add to the conditions in the .txt file that affect the chances of the music playing.

This script is open-source and was created by Runite Drill for ease in publishing music mods by community composer Utopia.
Feel free to join their music modding community and ask any questions: https://discord.gg/SdQhfBM

For more info/guide on music modding, please visit the EU4 wiki: https://eu4.paradoxwikis.com/Music_modding 

HOW TO USE
1. Drop this script in the Music folder of your EU4 mod. 
2. Add all of your .ogg music files to the folder.
3. Run the script.
4. Verify the .asset and .txt files generated.
