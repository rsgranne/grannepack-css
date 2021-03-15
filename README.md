# GrannePack CSS

This extension pack of CSS-related extensions is aimed at students in [Scott Granneman’s](https://www.granneman.com) beginning & advanced Web Development courses. Other extension packs focus on [HTML](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-html), [Git](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-git), & [Markdown](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-markdown).

## Extensions

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2): colorize matching brackets up to 4 levels deep
* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion): class attribute completion, even for remote files
* [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass): automatically compile Sass to CSS
* [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script): NPM support used in advanced CSS courses
* [Style formatter](https://marketplace.visualstudio.com/items?itemName=dweber019.vscode-style-formatter): formatter for CSS, Less, & Sass

## Optional Settings

I have created a GitHub Gist titled “[VSCode settings for the extensions installed via GrannePack CSS](https://gist.github.com/rsgranne/98c3040953a83d8d3cec41b8c058a0ae)”. If you wish to use these settings:

1. Click on the Raw button & copy the contents of the Gist.
2. Invoke the Command Palette (`Shift-Command-P` for macOS or `Ctrl-Shift-P` for Windows & Linux), search for `Open Settings (JSON)`, & press Return/Enter.
3. Paste the contents of my Gist into your User Settings. If you already have settings you wish to keep, you will need to carefully remove the curly braces (`{` & `}`) from my Gist after you paste it in, & pay attention to the rules of formatting JSON files.

If Visual Studio Code reports errors with `settings.json`:

* Visual Studio Code should indicate the problems that need fixing. Look at the [Common Questions section](https://code.visualstudio.com/docs/getstarted/settings#_common-questions) on the [User and Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings) page in [Documentation](https://code.visualstudio.com/docs) for more information.
* Paste the contents of your `settings.json` file into the [JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/) web tool. It will provide clear solutions to help you mitigate errors.
