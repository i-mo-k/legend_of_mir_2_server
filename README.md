# The Legend of Mir 2

The real project is an open source game broadcast in 2011. The current work is a practice work to add some looping functionalities for farmig purposes.

### Getting the files (from the original workpiece)
Note - Make sure you have the data files obviously, as getting the source code without the files won't really do anything as it just builds the server.exe and client.exe to work WITH the data files.

1) Visithttps://github.com/Suprcode/mir2 and then on the right hand column select 'Download ZIP'
2) That will start the download of the zipped up files.
3) Unzip the files to a location on your computer as you normally would with any download/unzip

### Using the files
Note - You need a compling software. I use VS 2022

1) In your mir2-master (source files) find a file called Legend of Mir, and run it. You may need to set it to use VSE 2103 as noted above, but it will eventually open up in there
2) When it opens you'll see the page opened in to separate 'windows'.
----- Top -left is where the actual code will load
----- Top -right is the 'folder' view if you think of windows. It's where the files can be selected to be viewed in the left side window.
----- Bottom-right : Ignore
----- Bottom-left is the 'status' sorta thing. It'll tell you when an error occurs, and etc
3) On the 'Solution Explorer' (top right), you'll see the main 'projects' are collapsible. Client and Server are the two you'll find most important. The .cs files are all stored in those solutions.
4) You can collapse/expand, find files you want to edit and then edit them from the left hand code screen.

### Building/Compiling
Note - Make sure you know where your data file are, downloaded from the guide sticky. C:\CrystalServer for example. Make sure you note where the client.exe is stored, and the server.exe

1) The project is set to build the solutions in a default location (usually 1 folder up, then create a folder called Mir2. Obviously this isn't where your data is, so building there is going to be pointless. You can just build there and copy paste to the real location etc, but meh.
2) On the 'Solution Explorer' select each solution. We'll start with Client. Select client so it goes blue.
3) On the navigation options (up top) select 'Project' -> 'Client Properties' . A new screen will open in the code bit (top-left)
4) On the left hand menu, several options will be present. Select 'Build'
5) On this screen you'll see an output section, with subheading output path. Change this to your client.exe folder location (in our example the exe is in C:\CrystalServer\Client, so we browse to that and 'Select Folder' it)
6) Ctrl S (save)
7) Repeat steps 2-6 for the server solution. Obviously choosing the server.exe folder location this time.
8) You can now build to the right locations, making your changes. Build by pressing F7. Doing so will make any changes necessary to the client.exe and the server.exe files.

## The Legend of Mir 2
The Legend of Mir 2 is a sprite-based isometric three dimensional massively multiplayer online role-playing game. Players have the option of playing different professions. Taoist, healers who use magical abilities to summon pets to assist in battle, poison targets and heal allies. Warriors, who have the highest defense and attack attributes of all classes. Wizards depend on magic and can kill multiple monsters with ease using spells. Assassins have taken over as the primary melee damage dealing class but have much weaker defense attributes than warriors. Archers are a class of great accuracy and strength, using their powerful skills with bows to deal extraordinary damage from range.

## Crystal Source
The Legend of Mir 2 Crystal Source is a public repository hosted on GitHub that aims to develop a server and game client written in the programming language of C Sharp (C#).

## Installation
1. Install Microsoft Visual Studio with .NET Packages.
2. Download the latest source (https://github.com/Suprcode/mir2/releases).
3. Open the project and configure NuGet packages.

## Contributing
1. Fork the project hosted on GitHub (https://github.com/Suprcode/mir2).
2. Fix a bug or implement a new feature within your forked source.
3. Submit a pull request comparing to your forked source (https://github.com/Suprcode/mir2/compare).

## Guidance
For further information about server and game files visit the Legend of Mir Wikipedia (http://mironline.co.uk).

## Community
Legend of Mir Community Network (https://www.lomcn.org/forum/forumdisplay.php?633) is a forums website dedicated to everything related to The Legend of Mir. If you have a question related to running or developing a Legend of Mir server this is the best place to ask.

## Credits
- Far (Developer)
- Jamie (Developer)
- Public Contributions (https://github.com/Suprcode/mir2/graphs/contributors)

## License
Currently, there's no license for this project.
