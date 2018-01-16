=> create a folder and open CMD in that folder.
1. npm init // To create package.json file

2. npm install --save react react-dom  // install react package

3. npm install --save-dev html-webpack-plugin webpack webpack-dev-server babel-core babel-loader babel-preset-react babel-preset-es2015

4. craete "app" folder and get in app
	1. create html files index.html
	2. create js file index.js

5. create webpack.config.js

6. Change following in "script" section of package.json file.
	"scripts: {
		"production" : "webpack -p",
		"start" : "webpack-dev-server"
	}

7. Create babelrc file and add  - 
	{
	  "presets": [
	    "react",
	    "babel-preset-es2015"
	  ]
	}

// To run Project - 
1. npm run production // for production version
2. npm run start // for development localhost:8080
