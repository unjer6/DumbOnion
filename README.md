# DumbOnion
A TTS mod for the game Dominion for the purposes of creating and playtesting custom variant cards in an easy automated environment. Please support the official release.

# How do I contribute?
1. Fork this repository.
2. Make your changes. DO NOT edit code and the game save at the same time. Always make changes in TTS, save, and then go into code.
3. Submit a pull request and allow edits from maintainers.
4. If your changes pass code review, a maintainer will merge your code into this repo.

# Setting up your project
1. Install Atom and the TTS plugin: http://berserk-games.com/knowledgebase/atom-editor-plugin/
2. In Atom, go to File->Settings->Packages->Click on settings for tabletopsimulator-lua
3. Check "#include other files"
4. Under "Base path for files you wish to #include", paste the path to your git folder
5. Now load your save of DumbOnion and optionally make a new save file if you wish to keep a clean copy.
6. Now right-click your Project explorer on the left side and choose "Add project folder" and choose your git folder.
7. You should now be able to edit the code as separate files, rather than one big global file. Select Packages->Tabletop Simulator->Save and Play to update and load your save file with script changes.

# Making changes to the save file
1. Copy the current save file from your git folder into your Tabletop Simulator saves folder.
2. Open TTS and makes changes to the file, add new cards, etc.
3. Save the game. Copy the save file from your TTS saves folder into your git folder, overwriting the previous git save.
4. Commit and push your changes. Notify the discord that you've made changes, so everyone knows to copy/paste the git save again.
