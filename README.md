# sass-course
link Tutorial : https://www.youtube.com/watch?v=nu5mdN2JIwM&t=1870s

# how to set up
1.check for Node.js \
2.sudo 'npm i -g sass' to install globally;\
3.'sass --watch scss/style.scss css/style.css' to watch and specify the path of sass file\
4.add vscode extension Live Sass Compiler then go settings search live sass and edit settings.json with this\

{
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "liveSassCompile.settings.generateMap": false,
    "liveSassCompile.settings.formats": [
        {
            "format": "compressed",
            // "extensionName": ".css",
            "savePath": "/css"
        }
    ],
    "liveServer.settings.donotVerifyTags": true
}