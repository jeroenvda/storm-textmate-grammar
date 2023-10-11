# TextMate Grammar for storm (Vertex Synapse)
TextMate Grammar that allows storm syntax highlighting in for example Visual Studio Code or PyCharm.

## Features
Syntax highlighting for Visual Studio Code/PyCharm for the storm language used by Vertex Synapse.

## Installation
### Visual Studio Code
Should now be available via the VSCode Marketplace (look for `Synapse storm`).

If you prefer a manual install:
On MacOS, take the directory and copy it to `<userprofile>/.vscode/extensions`. The `.vscode` directory should look similar to this:
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
<img width="1034" alt="storm_grammar_vsc" src="https://user-images.githubusercontent.com/43104903/216810883-6b4fb9af-373f-4381-86aa-5ea0cb7d1b1e.png">

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
