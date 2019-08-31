To Continues Compile of Sass to Css :
    - $npm run compile:sass
To Continues Run of index.html in default browser
    - $live-server

---------------------------------------------------------

- Create the folder "Html Sample"
- Create an empty project in web storm
- In the terminal window
    - npm init
- Copy index.html file
- $npm install node-sass --save-dev
- Add to package.json
      "scripts": {
        "compile:sass": "node-sass sass/main.scss css/style.css -w"
      },
- $sudo npm install live-server -g
- Create directories for the SASS files, and insert files as in the project
- Sometimes -w parameter in "node-sass sass/main.scss css/style.css -w" which stands for watch, doesn't work in the first run.
  If so, delete the -w parameter in package.json, run once, then add -w parameter and rerun it in the terminal.
- Run live-server

