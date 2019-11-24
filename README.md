## NG-Static
An example of a responsive static html page 


##### Directory structure
```
Root
│──README.md
│──Gulpfile.js    
│   ... Build automation script
└───src
│   │   index.html
│   │
│   └───js
│   │    │   ... unminified js
│   │ 
│   └───media
│   │    │   ... unoptimized images
│   │
│   └───sass
│        │   ... unprocessed sass
└───dist
     │   index.html
     └───css
     │    │   ... compiled css
     │
     └───js
     │    │   ... minified js
     │ 
     └───media
          │   ... optimized images
```

##### Usage
###### Without the build tools
Run index.html from the dist folder
###### With the build tools
Do `npm install` (on the first time) then use `gulp` command

##### Dependencies
 [GlideJs](https://glidejs.com/)

##### Dev dependencies
[nodeJs](https://nodejs.org)

[GulpJs](https://gulpjs.com/)

[browsersync](https://www.browsersync.io/)

[sass](https://sass-lang.com/)
