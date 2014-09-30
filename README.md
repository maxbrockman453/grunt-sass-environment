In order to get this up and running you're gonna need to run a few things in terminal.

I've already created your GruntFile.js and your Package.json, but you'll need to "$ npm init" and rebuild it.

Then you're gonna need to have grunt and node installed.

If you don't know if you do type "$ npm -version"

Also run "$ npm install grunt -g" in order to install grunt globally.

You'll also need to run "$ npm install grunt --save" in order to create some dependencies! in your package.json

Now that you have grunt and node installed lets "$ npm install node-sass --save" & "$ npm install grunt-sass --save"

*** Dont forget to --save in order to create those dependencies ***

It should be up and running! Now all you have to do is go to the root directory of your project and run "$ grunt watch"
