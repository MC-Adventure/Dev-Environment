Dev-Environment
===============
Custom made Eclipse environment to help others modify our mods (no idea if this actually works).

### Usage
1. Clone this repo into the folder of your choice.
2. Go grab the source for Minecraftforge (look at the readme for the Core repository).
3. Extract the zip file into the 'forge' folder.
4. Open the 'forge' folder and run 'install.cmd' (Windows) or 'install.sh' (Unix/Mac OS(?)).
5. Follow any prompts and wait for the program to finish running.
6. Open eclipse and set workspace location to the 'workspace' folder.
7. Open the Git Repository Exploring perspective in eclipse and click 'Add an existing Git repository', navigate to the 'source' folder and select the 'Core' folder.
8. Repeat step 7 (multiple times if necessary), selecting each folder inside 'source' (e.g. 'Torch-Burnout').
9. Switch back to the Java perspective.
10. If we got everything set up properly, you should now have no errors. Sweet!

### Something not working right?
This environment has not been excessively tested, so something may not work out properly.  Just post an issue, or send us a PR if you can figure out a solution.  Thanks!

