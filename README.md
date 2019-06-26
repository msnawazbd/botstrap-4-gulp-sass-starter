# Botstrap 4 Gulp SASS Starter


## Process 1:


	@ npm init
	# Note: license (MIT)
	@ atom .
	@ npm install bootstrap jquery popper.js font-awesome --save
	@ npm install gulp@3.9.1 browser-sync gulp-sass --save-dev
	@ npm install autoprefixer gulp-clean-css gulp-postcss gulp-rename gulp-scss-lint gulp-sourcemaps merge-stream --save-dev
	#Create Src, Create gulpfile.js
	@ gulp


## Process 2 (Existing Download):


	@ npm install
	@ npm start
	
## Run Existing Project:


	change package.json line 7
	"test": "echo \"Error: no test specified\" && exit 1"
	To
	"start": "gulp"
	
	@ npm start
