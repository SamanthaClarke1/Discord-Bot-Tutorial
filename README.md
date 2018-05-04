# Discord-Bot-Tutorial
How to make a discord bot in NodeJS.
## Prerequisites
1. Free Code Camp (finish object orientated javscript)
2. glitch.com (finish nodejs)
3. [npm explaination](https://docs.npmjs.com/getting-started/what-is-npm) (read through and watch vid)
4. Install Nodejs (If you havn't already)
## Creating the Project
1. Start by creating a project folder.
2. Open the folder in atom.
3. Open a command line and cd into the current folder. E.g: `cd PATH/TO/FOLDER`
4. Once you have cd'd into the correct folder type in `npm init`
5. Go through the setup (mainly just press enter)
6. Look at the package.json in atom.
7. After a `},` add: 
```JSON
"dependencies": {
  "discord.js": "latest"
},
```
> Heres an example file:
```JSON
{
  "name": "ecio-discord-bot",
  "version": "1.0.0",
  "description": "Economy based discord bot.",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "torinberger",
  "dependencies": {
    "discord.js": "latest"
  }
}
```
8. Make sure to save. Type into your command line: `npm install`, then wait for it to finish installing. If there are any errors ask someone else to help.
9. Create a index.js file from atom. You can do this by right clicking the folder tree view (on the right of atom) and selecting create file.
10. Open index.js in atom and type:
