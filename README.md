Programs in use: HTML with JS, CSS y SCSS

///////////////////////////////////////////////

INDEX:
CSS / CSS file: style.css
HTML / HTML file: index.html
recursos / images in use
SCSS / folders containing SCSS files divided by theme
prepros.config / preprocessing configuration file
README.md / this readme

SCSS FOLDER INDEX:
atmosphere / web aesthetic
    _img.scss / images
    _mouse.scss / mouse efects like :hover, :checked, etc.
    _placing.scss / position propoerties
    _text-style / text style properties
operation / web operation thorugh checkboxes 
    _checkbox-operation.scss
variable / declared variables
    _variables.scss
style.scss / to import scss file into css file

///////////////////////////////////////////////

OPERATION CLASSES:
The web operation is made throught checkboxes this require inputs, labels and sections with classes in common as: "radio", "radioX" (as in "r"adio1", "radio2", etc.), "nav", "input-sectionX", "sectionX" and "scroll-section".

SECTIONS CLASSES:
Web contains 6 main sections: intro, web, graphic, music, skills and contact.
Each one of them is a class for its own purposes (as in class=intro) so that you can refer to an element in a section by adding the class to the element. This workflow is usefull for placing, since the web has no extric composition, elements flow and overlap one into another and every section is different.

OTHER CLASSES:
There also a class in refenre to the menu called "top-bar".
Skills is a section within a grid for whats is used "studies-row" class.
For mouse effects there especific classes such as "mail", made to change the hover color of only one link.

///////////////////////////////////////////////

@MEDIA

*Text styles and placing are to be changed by @media for responsive purposes. Since we have text style and placing in two different SCSS files we have to include the same @media in both files.

no @media: MOBILE
@media all and (min-width: 750px): MID
@media all and (min-width: 1000px): DESKTOP