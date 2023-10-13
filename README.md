# TextMate Grammar for storm (Vertex Synapse)
TextMate Grammar that allows storm syntax highlighting in for example Visual Studio Code or PyCharm.

## Features
Syntax highlighting for Visual Studio Code/PyCharm for the storm language used by Vertex Synapse.

## Screenshots
<img width="1034" alt="storm_grammar_vsc" src="https://user-images.githubusercontent.com/43104903/216810883-6b4fb9af-373f-4381-86aa-5ea0cb7d1b1e.png">

## Installation
### Visual Studio Code
#### Marketplace
The extension should now be available via the VSCode Marketplace (look for `Synapse storm`).

#### Manual install
##### MacOS
Clone the repo into `<userprofile>/.vscode/extensions`. The `.vscode` directory should look similar to this:
```
	.
	├── argv.json
	└── extensions
	    └── storm-textmate-grammar
	        ├── LICENSE
	        ├── README.md
	        ├── language-configuration.json
	        ├── package.json
	        └── syntaxes
	            └── synapsestorm.tmLanguage.json
```

##### Linux (Debian based)
A bit dirty, but it works:

First install node.js and a few packages:
```
sudo apt-get install npm
sudo npm install -g yo generator-code
```
Make sure that your distro installs the minimum version that yo requires (>14.x). Pop!_OS installs an older version with the command above. As an alternative install it manually:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v20.6.0
```
Run in a terminal:
```
yo code
```
And select `New Language Support`

Complete the interactive process:
```
     _-----_     ╭──────────────────────────╮
    |       |    │   Welcome to the Visual  │
    |--(o)--|    │   Studio Code Extension  │
   `---------´   │        generator!        │
    ( _´U`_ )    ╰──────────────────────────╯
    /___A___\   /
     |  ~  |     
   __'.___.'__   
 ´   `  |° ´ Y ` 

? What type of extension do you want to create? New Language Support
Enter the URL (http, https) or the file path of the tmLanguage grammar or press ENTER to start with a new grammar.
? URL or file to import, or none for new: 
? What's the name of your extension? storm
? What's the identifier of your extension? storm
? What's the description of your extension? storm
Enter the id of the language. The id is an identifier and is single, lower-case name such as 'php', 'javascript'
? Language id: storm
Enter the name of the language. The name will be shown in the VS Code editor mode selector.
? Language name: storm
Enter the file extensions of the language. Use commas to separate multiple entries (e.g. .ruby, .rb)
? File extensions: .storm
Enter the root scope name of the grammar (e.g. source.ruby)
? Scope names: source.storm
? Initialize a git repository? No

Writing in /home/user/.vscode/extensions/storm...
   create storm/syntaxes/storm.tmLanguage.json
   create storm/.vscode/launch.json
   create storm/package.json
   create storm/README.md
   create storm/CHANGELOG.md
   create storm/vsc-extension-quickstart.md
   create storm/language-configuration.json
   create storm/.vscodeignore

Changes to package.json were detected.
Skipping package manager install.


Your extension storm has been created!

To start editing with Visual Studio Code, use the following commands:

     code storm

Open vsc-extension-quickstart.md inside the new extension for further instructions
on how to modify, test and publish your extension.

For more information, also visit http://code.visualstudio.com and follow us @code.


? Do you want to open the new folder with Visual Studio Code? Open with `code`
```
A new VSCode instance will open. Next, copy the contents of https://raw.githubusercontent.com/jeroenvda/storm-textmate-grammar/main/syntaxes/synapsestorm.tmLanguage.json in the new file that opened (storm.tmLanguage.json). Save it, re-open VSCode and it should work.

### PyCharm
For PyCharm, you can follow the guide on their website:
https://www.jetbrains.com/help/pycharm/textmate-bundles.html

## Known Issues

- IP addresses in storm are not highlighted completely correctly.

## Release Notes

### 0.0.1

Initial release of synapse storm grammar.

## References
- https://www.apeth.com/nonblog/stories/textmatebundle.html
- https://github.com/microsoft/vscode-textmate/tree/main/test-cases/themes/syntaxes
- https://github.com/rakuy0/vim-storm
