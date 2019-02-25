# FED-master

Step to run:

1. Install npm    	::    npm install
This will download all dependency that we have defined in package.json. All dependency are required at development time.

2. Install gulp-cli     	::    npm install -g gulp-cli
To run UI automation, we need gulp cli. gulp cli will read gulpfile.js and execute UI automation.

3. Run gulp    	::    gulp + Enter
This command will run gulpfile.js and run all task that we have defined in this js file like minified css, convert sass to css, optimize images, recreate "dist" folder and many more.

4. Run gulp watch	::    gulp watch + Enter
This command will watch changes in scss and html file and it will run the gulp task.
