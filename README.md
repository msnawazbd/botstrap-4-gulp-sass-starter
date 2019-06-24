# botstrap-4-gulp-sass-starter
Botstrap 4 Gulp SASS Starter


<h1>Process 1:</h1>


	@ npm init
	# Note: license (MIT)
	@ atom .
	@ npm install bootstrap jquery popper.js font-awesome --save
	@ npm install gulp@3.9.1 browser-sync gulp-sass --save-dev
	@ npm install autoprefixer gulp-clean-css gulp-postcss gulp-rename gulp-scss-lint gulp-sourcemaps merge-stream --save-dev
	#Create Src, Create gulpfile.js
	@ gulp


<h1>Process 2 (Existing Download):</h1>


	@ npm install
	@ npm start
	
<h1>Run Existing Project:</h1>


	change package.json line 7
	"test": "echo \"Error: no test specified\" && exit 1"
	To
	"start": "gulp"
	
	@ npm start
