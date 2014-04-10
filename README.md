## PSD-to-HTML: Engine Labs About page
Technologies/skills used: HTML, CSS  

### Task
> Download assets from here: [http://bit.ly/1k4yKZI](http://bit.ly/1k4yKZI)

+ Turn the **blank** index.html file into the Engine Labs homepage based on a mock image
+ If you have the site's homepage complete, you can use it as a template for this page. 

### Steps
**Mockup to recreate**
Look at the mockup PNG in the root directory: `General_Assembly_01_960_grid_12_col_blue_about.png` 
* **Sections**   
  * spans the width of the page (100%)
  * have a more narrow (960px), centered subsection where the content goes
* **Images** This time, all the design assets you will need have been added to the sprite.png file.
* **Font** is Google's [Source Sans Pro](http://www.google.com/fonts/specimen/Source+Sans+Pro). It should already be listed in the header of your document. Take a look at all the weight and style options.
* **Colors**:  
  * dark blue `#003047`
  * light gray `#EDEDED`
  * medium blue `#01527D`
  * white `#FFFFFF`
  * black `#000000`

### Tips
* Start off by copying the entire homepage's index.html file from your last project into both the index.html file in this project, as well as the about.html file. 
* Go through and remove sections from the about.html file that aren't relevant to the about page (this will be most of them). See if there are any sections in the new page design that use a similar structure to existing pieces of the old page, and leave those sections of the old HTML in place.
* Don't forget to declare your site's CSS and any additional required resources in the header of the document
* For the circle Team photos, you will need to add an `<a>` tag that covers an individual person's photo and links to a social profile of your choosing. Each `<a>` will have its own background image.

#### Keep it simple
* Try this without using a grid framework like Skeleton or Bootstrap.
* Once you feel confident hand-coding, investigate a grid framework and see how much time it saves you.

#### Create structure systematically
* Work top to bottom
* Break the page into vertically-stacking sections  
_for example, create header, hero image, quote, features, etc_

#### Use classes effectively
* Name classes by function of a particular element rather than content inside it
* Lets you style elements quickly when they need to serve a common purpose.  
_For instance, for a div that needs to be noticable, naming it `.callout` rather than `.side-of-story-color-background-designer-quote` means you don't have to restrict the content inside to quotations from designers--and you can easily use the class name elsewhere in the site._
* Want to use SCSS rather than CSS? Using [SASS](http://sass-lang.com/documentation/index.html) with this assignment is pretty easy. With a single file, go to the folder where you're saving your style files. Create a scss and css files with the same name (ie, `style.css` and `style.scss`. In the terminal `sass --watch style.scss:style.css`. More help `sass --help`

### Resources
* [A grid system with nice demos](http://960.gs/)
* Great resource for how to work with [sprite styles](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/CSS_Image_Sprites): [Sprite Cow](http://www.spritecow.com/)
* Great resource for CSS tutorials and guidelines: `http://css-tricks.com/`
* Great resource for web stuff in general, including CSS and HTML: `http://www.html5rocks.com/en/`
* [Absolute positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position) and [floats](http://css-tricks.com/all-about-floats/).
* Reseting styles: Use a `reset.css` for cross-browser harmony. [Skeleton](http://www.getskeleton.com/), [Bootstrap](http://getbootstrap.com/css/), [HTML5Boilerplate](https://github.com/h5bp/html5-boilerplate/blob/master/doc/TOC.md) and [YUI](http://yui.yahooapis.com/3.10.1/build/cssreset/cssreset-min.css) have reset files/components.

### Tutorails
* More tutorials: [GA Dash](https://dash.generalassemb.ly/)
