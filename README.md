#Enjoy Yoga 

![home page upper part](https://github.com/user-attachments/assets/42b7cabd-1eea-4d0f-af19-e013c5ad015c)

![home page lower part](https://github.com/user-attachments/assets/75389502-4332-48f9-9f33-246c652d4a24)

##Description
This project is for people who would like to either try a new activity to get involved in and partake either indoors or outdoors, or simply to enjoy yoga with new acquaintances or old acquaintances. It informs people about the usefullness of being active in yoga and what you might gain out of it.

##Author:
@matthew mears
GitHub Page:
https://github.com/MJM125

##Testing On Opera
Contact
documentation/lighthouse_contact_desktop.png
documentation/lighthouse_contact_mobile.png
documentation/lighthouse_index_desktop.png
documentation/lighthouse_index_mobile.png
documentation/lighthouse_schedule_desktop.png
documentation/lighthouse_schedule_mobile.png

##Which Browser can it be opened on?
The deployment link - https://mjm125.github.io/Enjoy-Yoga/ - is tested on firefox, opera, chrome, bing, microsoft edge.

##BEM Methodology

BEM (Block, Element, Modifier) is a popular naming convention for classes in HTML and CSS, originally developed by Yandex. It is designed to create reusable, modular, and maintainable code.

BEM Structure
BEM divides the user interface into independent blocks, which can be reused across different parts of the application. The naming convention follows a specific structure:

Block: The top-level component or a standalone entity that is meaningful on its own.
Example: header, container, menu
Element: A part of a block that performs a certain function and has no standalone meaning.
Example: header__title, menu__item
Modifier: A flag on a block or an element that changes its appearance or behavior.
Example: menu__item--active, header--large
Naming Convention
The BEM naming convention uses a double underscore (__) to separate elements from their block and a double hyphen (--) to separate modifiers from blocks or elements.

Block: block-name
Element: block-name__element-name
Modifier: block-name--modifier-name or block-name__element-name--modifier-name
Example
<div class="menu">
  <ul class="menu__list">
    <li class="menu__item menu__item--active">Home</li>
    <li class="menu__item">About</li>
    <li class="menu__item">Contact</li>
  </ul>
</div>
In this example:

menu is the block.
menu__list and menu__item are elements of the menu block.
menu__item--active is a modifier that changes the appearance of the menu__item element.
Benefits of BEM
Clarity and Readability: BEM makes it clear what each class refers to by looking at its name. It is easy to identify whether a class represents a block, an element, or a modifier.

Modularity: BEM promotes the creation of independent components. Each block is standalone, making it easier to reuse and maintain.

Avoids Naming Conflicts: The structured naming convention helps avoid class name conflicts, which are common in larger projects with many contributors.

Improved Maintainability: With BEM, the CSS and HTML structure is more organized, making it easier to understand, debug, and modify the code.

Enhanced Scalability: BEM's approach is particularly useful for large projects as it provides a consistent methodology for naming and structuring classes.

Better Collaboration: The clarity and structure provided by BEM make it easier for multiple developers to work on the same project without confusion.

Sass

CSS Validation
The CSS code has been run through the W3C - CSS validator. Results can be found below.
documentation/html_checker.png
