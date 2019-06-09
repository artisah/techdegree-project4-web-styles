# techdegree-project4-web-styles
Organize your Sass files.
Inside the existing scss folder, create the following subfolders to organize your CSS code into SCSS partial files:
utilities (a folder to contain partials for global variables, extends, mixins, and functions)
base (for the normalize.css file and base styles that are used in the project)
The components folder, as well as the index and grid partials is created for you. In addition to these, you will add partials for things like: typography, navigation, images, buttons, forms
Each subfolder you create should contain an _index.scss file. You’ll use that file to import each sass partial file in the folder.
Create a css folder for your compiled CSS. As you work on the project, you’ll be able to run sass --watch scss:css from the command line to compile the sass that you write.

Adding to the styles.scss file in the root of your Sass project (in your ‘scss’ folder).
Import all of your _index.scss partials into this main styles.scss file.
Make sure your imports are listed in the correct order for styling.
Create a partial for variables in your utilities folder
Use this partial to create variables for your repeated values.
At minimum, create variables for fonts, breakpoints, and colors.
Import this partial into your utilities/index.scss file
Create a partial for your mixins in your utilities folder
Inside your mixins partial, you’ll want to create mixins for:

Media Queries
Flexbox settings

Create a partial for your placeholders in your utilities folder
In your placeholder partial, create placeholders for at least the following:

Links
Images
Nav items
Components
All your styles for this project will be applied using the classes listed in the comment at the top of index.html. You’ll style these classes in the 'components' folder. Try not to combine selectors from two different categories. For example, avoid using .grid__col--8 .link to style the link in the typography section, as it makes the style of links dependent on what grid column they’re in. The best way to organize this is to make a file in the components folder for each of the following:

Grid (already in the project files)
Typography
Navigation
Images
Buttons
Forms

Base folder
In your base folder, include a normalize.css file and create a base.scss file. In the base.scss file, you can only apply styles to four different elements directly:

the universal selector (*)
ul elements
p elements
a elements
Check your work
Open the no_classes.html file. If you’ve only used the proper classes to style your page, this page should match the no_classes_mockup.png mockup, and should be almost completely unstyled. If you’ve used element or id level selectors somehow, you’ll see the difference between these two files. Be sure to check that your classes do only what they’re meant to and that each component category doesn’t depend on styles from another category (E.g. - avoid selecting .grid__col--8 .link to style a link in a grid column.) Making these classes as independent as possible will increase the usefulness of using this style guide on other projects.
