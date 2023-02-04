# TextMate Grammar for storm (Vertex Synapse) README
TextMate Grammar that allows storm syntax highlighting in for example Visual Studio Code.

## Features
Syntax highlighting for Visual Studio Code for the storm language used by Vertex Synapse.
## Installation
On MacOS, take the directory and copy it to `<userprofile>/.vscode/extensions`. The `.vscode` directory should look similar to this:
	.
	├── argv.json
	└── extensions
	    └── storm
	        ├── LICENSE
	        ├── README.md
	        ├── language-configuration.json
	        ├── package.json
	        └── syntaxes
	            └── synapsestorm.tmLanguage.json




## Known Issues

- IP addresses in storm are not highlighted completely correctly.

## Release Notes

### 1.0.0

Initial release of synapse storm grammar

## References
https://www.apeth.com/nonblog/stories/textmatebundle.html
https://github.com/microsoft/vscode-textmate/tree/main/test-cases/themes/syntaxes
https://github.com/rakuy0/vim-storm