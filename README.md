# NUS Dev Tools

This repo serves as a list of tools, extensions, and resources for the NUS Marketing Development team.
The purpose of this is to keep the team and the codebase organized, consistent, and simpler as to leave us more time to focus on tasks at hand instead of small pesky errors one could make.

## Table of Contents
- [Code Editor Extensions](#code-editor-extensions)
- [Placeholders](#placeholders)
- [Image Compression](#image-compression)
- [Pagespeed](#pagespeed)

## Code Editor Extensions
This section lists extensions which are available for most code editors, primarily Visual Studio Code editor.

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - As it states, auto closes your tags. Valid markup yo!
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - Keep your spelling on check so that your naming conventions and comments make sense to _future_ devs, or yourself when debugging.
    - Add the provided dictionaries in the `/code-spell-dictionaries/` directory so that you do not get distracted or start your own from scratch.
    - Refer to the `settings.json` file for how to set up the custom dictionaries as part of your VS Code setup.
    - Feel free to do a pull request to add more words or more dictionaries.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code to lint JS code in your project. [Atom Ext.](https://atom.io/packages/linter-eslint)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - Displays inline the cost (size) of the package you are using in your ES6 JS. [Atom Ext.](https://atom.io/packages/import-cost-atom)
- [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker) - Keep your code documented. No need to add a comment for every line. Use naming conventions, breathing room (space), and other methods to make your code understandable as it's read line by line. This extension is more to help do block docs for files, functions, classes, and methods and give an understanding of these, their parameters, etc. [_Similar_ Atom Ext.](https://atom.io/packages/docblockr)
- [phpcs](https://marketplace.visualstudio.com/items?itemName=ikappas.phpcs) - Keep your code clean and up to WP/WPVIP/NUS team standards. This makes someone viewing your code not have to learn new (or unique) methodologies. Consistency, cleanliness! Remember, the codebase should look like one person wrote the whole thing. [Atom Ext.](https://atom.io/packages/linter-phpcs)
- [SASS](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented) - Supported for indented SASS.
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) - Real time code collaboration, so like Google docs but for code. Ever need help from a team member outside the office? Forget screenshots, use this.
- [WordPress Snippet](https://marketplace.visualstudio.com/items?itemName=tungvn.wordpress-snippet) - Gives you suggestions for WP Snippets as you type, in case you forget any of them but remember partial function names.

## Placeholders
- [placeholder.com](https://placeholder.com/) - Most basic of placeholder images. For such uses as wireframing or quickly mocking up a dev site.
- [Lorem Picsum](https://picsum.photos/) - As their site says, Lorem Ipsum... but for photos.
- [Unsplash Source](https://source.unsplash.com/) - Like the above but official to Unsplash.com.

## Image Compression
- [Compressor.io](https://compressor.io/) - Always swore by this site. Really wish it had an API or that I could purchase it.
- [Squoosh](https://squoosh.app/) - Google's public image compressor. Has more options than compressor.io.

## Pagespeed
- [GTmetrix](https://gtmetrix.com/) - A lot of detail in the resulting report for the testing sites. Lots of options to run the tests including ad blocker, white/blacklisting resources URls, location test, waterfall. An account is required for some features but accounts are free.
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Google's tool to help you clean up your act but will ding your score for Google Analytics and other resources they provide. Definitely use this tool to get a higher score because this is one of the most popular tools that non-dev people will test against.
- [Pingdom Website Speed Test](https://tools.pingdom.com/) - Pingdom's reporting tool.
