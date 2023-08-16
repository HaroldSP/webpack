# About
General start-up repo for web projects

`npm init -y` or `npm init` to set up the environment manually

`npm install webpack webpack-cli --save-dev`

`npm i` if you deleted node_modules folder and package-lock and want them back

`npm i webpack-dev-server --D` if you want to install webpack inner liveserver. --D stands for development mode.

After that, you can build a project:

`npm run build` or `npm start` to use webpack web server and have a live update

That lines were added to package.json for better usability:

    "scripts": {
  
      "build": "webpack --mode=production",
    
      "watch": "webpack --watch --mode=development",
    
      "start": "webpack serve --mode=development --open"
    
    }
