### Frontend UI Development with Gulp and living Styleguide (SC5)
---

#### Getting Started

1. Open `CMD` or `Terminal`, point the path to your designed folder.
2. In the same CMD or , run `cd gulp-fe-dev`
3. Next, run `npm i` (`i` stands for `install`)
 
Now, run `gulp` from same CMD window. It will open the project server: 
- `Project` - `http://localhost:3000/`
- `Styleguide` - `http://localhost:3001/`

Continue working, as soon as you save - it will compile CSS, and Refresh HTML too.

##### Gulp Tasks
- `gulp` - Compiles the development files and generate the production ready files.
- `gulp styleguide` - Generate the styleguides with *styleguide* folder on root path.
- `gulp webstandards` - Validates whether your HTML/CSS/JS is up-to-date or not and or according to Web Standards.


##### File Structure

**Production Files:-**
```
	+-- dist
	|   +-- images
	|   +-- scripts
	|	|   +-- main.min.js
	|   +-- css
	|	|   +-- styles.min.css 
	|   +-- index.html
```

**Development Files:-**
```
	+-- dev
	|   +-- fonts
	|   +-- images
	|   +-- includes
	|	|	+-- aside.html
	|	|	+-- header.html
	|	|	+-- footer.html
	|   +-- scripts
	|	|   +-- vendors
	|	|	|   +-- Dependencies 1
	|	|	|   +-- Dependencies 2
	|	|   +-- scripts.js
	|   +-- scss
	|	|   +-- base
	|	|	|   +-- _branding.scss
	|	|	|   +-- _typo.scss
	|	|	|   +-- _units.scss
	|	|	|   +-- _vars.scss
	|	|   +-- components
	|	|	|   +-- _button.scss
	|	|	|   +-- _form.scss
	|	|   +-- layout
	|	|	|   +-- _header.scss
	|	|	|   +-- _nav.scss
	|	|	|   +-- _footer.scss
	|	|	|   +-- _page.scss
	|	|   +-- modules
	|	|	|   +-- _modules-name.scss
	|	|   +-- vendors
	|	|	|   +-- _vendors 1.scss
	|	|	|   +-- _vendors 1.scss
	|	|   +-- styles.scss
	|   +-- index.html
```

#### UI Resources/References
 - [Autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
 - [BEM](https://en.bem.info)
 - [Bootstrap V4](http://v4-alpha.getbootstrap.com)
 - [BrowserSync](https://www.browsersync.io/)
 - [Concat](https://www.npmjs.com/package/gulp-concat)
 - [File-include](https://www.npmjs.com/package/gulp-file-include)
 - [Gulp](https://www.npmjs.com/package/gulp) 
 - [Htmlmin](https://www.npmjs.com/package/gulp-htmlmin)
 - [Imagemin](https://www.npmjs.com/package/gulp-imagemin)
 - [Jshint](https://www.npmjs.com/package/gulp-jshint)
 - [Plumber](https://www.npmjs.com/package/gulp-plumber)
 - [Rename](https://www.npmjs.com/package/gulp-rename)
 - [Sass](https://www.npmjs.com/package/gulp-sass)
 - [SMACSS](https://smacss.com)
 - [Sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)
 - [Strip comments](https://www.npmjs.com/package/gulp-strip-comments)
 - [Sc5 styleguide](https://github.com/SC5/sc5-styleguide)
 - [Uglify](https://www.npmjs.com/package/gulp-uglify)
 - [Util](https://www.npmjs.com/package/gulp-util)
 - [Webstandards](https://www.npmjs.com/package/gulp-webstandards)

#### About Me
I’m Sanjay Shrestha from Kathmandu, Nepal. I’m a Certified Usability Analyst, UX/UI Expert and UI Developer. I have more than 8 years of experience in the field and got good grasp on User Centric Design Process, Software Development Cycle and AGILE Methodology. I have a vast experience designing UI backed with science and data. 

| Name     | Sanjay Shrestha                     |
|----------|-------------------------------------|
| Email    | dziner.sanjay@gmail.com             |
| Facebook | http://facebook.com/dziner.sanjay   |
| LinkedIn | http://linkedin.com/in/shresthasans |
| Twitter  | http://twitter.com/shresthasans     |
| Skype    | sanzaysan                           |
| Behance  | http://behance.net/shresthasans     |
| Dribbble | http://dribbble.com/shresthasans    |

