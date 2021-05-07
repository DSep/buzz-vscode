# Buzz VSCode Extension

This is a VSCode extension to provide language support for the swarm programming language [Buzz](https://the.swarming.buzz/). Buzz is a swarm oriented programming language created by [MISTLab](https://mistlab.ca) and published on Github [here](https://github.com/MISTLab/Buzz/).

The extension is in the process of being added to the VSCode extension marketplace!

## Features

This extension is a work in progress. At this time, this extension provides syntax highlighting.

The actual _grammar_ (what tells VSCode how to highlight) is located in ./syntaxes/asm.tmLanguage.json. This TextMate-formatted .json uses a tree-like structure to highlight in order, top to bottom. It matches using Regex, but looks a little bit different than standard Perl or JS (eg needing to double escape with `\\` instead of the usual `\` due to it being formatted within JSON).

Coming soon: Demo images, GIFS!

## Extension Settings

Once available, you can just install the extension and it should work!

## Known Issues

Currently, there are a few kinks still being worked out:
- Hightlighting brackets needs to be done properly.
- Bug in identifying variable names following assignment statements.

## Contributing

Feel free to make improvements and submit a PR! And if you would like to chat or discuss anything, feel free to go to discussions, or if there's an issue you'd like to report, open an issue.

## Release Notes

### 0.1

Initial release of code to the world!


## Creation and Reference
This extension was built using the CLI tools [Yeoman](https://yeoman.io/) and [VS Code Extension Generator](https://www.npmjs.com/package/generator-code). 

Important documentation that was used in learning how to build extensions and language support for VSCode:
- [Building an extension](https://code.visualstudio.com/api/get-started/your-first-extension)
- [Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [TextMate Bundle Background](https://www.apeth.com/nonblog/stories/textmatebundle.html)
- [TextMate Language Grammar](https://macromates.com/manual/en/language_grammars)


**Enjoy!**
