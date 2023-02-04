# TextMate Grammar for storm (Vertex Synapse) README
TextMate Grammar that allows storm syntax highlighting in for example Visual Studio Code.

## Features
Syntax highlighting for Visual Studio Code for the storm language used by Vertex Synapse.

## Installation
On MacOS, take the directory and copy it to `<userprofile>/.vscode/extensions`. The `.vscode` directory should look similar to this:
```
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

```
<img width="1081" alt="textmate_storm" src="https://user-images.githubusercontent.com/43104903/216791209-f918e07d-ac2c-4d3b-9a2e-f914c182ce17.png">

## Known Issues

- IP addresses in storm are not highlighted completely correctly.

## Release Notes

### 0.0.1

Initial release of synapse storm grammar.

## References
- https://www.apeth.com/nonblog/stories/textmatebundle.html
- https://github.com/microsoft/vscode-textmate/tree/main/test-cases/themes/syntaxes
- https://github.com/rakuy0/vim-storm
