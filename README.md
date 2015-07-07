WorkFlow
=======

Design is used as a identity for a product, thus indivudality is very important. This documnet explains how to follow a component based modular approach for your project. It also helps define a vocabulary for the team.

### Architecture
    Base | Theme
         |
         --- Fragments
                |
                --- Components
                        |
                        --- Layouts

#### Base
This is the core foundation of your application.

* Normalize
* Typography
* Grid System

#### Theme
Theme contains the top most coat of design for your application.

* Colors

#### Fragments
These are re-usable elements at there most basic atomic unit but sufficiently complete to be used independently or with components.

* Buttons
* Input Elements
* Icons
* Image

#### Components
Componets are modular re-usable parts of our design. Componets can often extend themselves and use one or more fragments.

    Component X
        |
        --- X.1
        --- x.2
        --- x.3
        
    Nav
     |
     --- Menu
     --- Pagination
     
    Popup
     |
     --- tooltip
     --- popover
     --- growl-notifications


#### Layouts
Layouts are sections of your page which hold components together.

* Header
* Filters
* Masthead

### States
It is import to follow common semantics for states as this would be a interface for your javascript to interact with the code.

* Hidden
* Expanded
* Active

### Typography

- Use a modular scale for your typography.

### Ecosystem
The system works like a pyramid structure, top of the pyramid being base and bottom being views. Base is unlikely to change a lot and requires thorough impact assement while views are created most often with least impact to project.

### Testing

- Unit testing for each Module as specified in sample Application

### Preprocessor

- [Examples](https://github.com/ornament-design) are written in sass and compilled using libsass for its speed and ease of integration.

### Tools
Extend works well with [MDL](http://www.getmdl.io/)

### Author

**Adi Chikara**
- http://twitter.com/adi_ads

### References and good reads
* [Meaningful Typography](http://alistapart.com/article/more-meaningful-typography)
* [Atomic Design System](http://pattern-lab.info/)
* [Responsive Deliverables](http://daverupert.com/2013/04/responsive-deliverables/)
* [Responsive Resources](http://bradfrost.github.io/this-is-responsive/resources.html)
* [BEM Methodology](http://bem.info/method/)
* [Smacss](http://smacss.com/)
