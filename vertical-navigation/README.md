# PatternFly vertical navigation component

## Requirements

 * patternfly

## Install

    npm install pfdemo-vertical-navigation
    
## Import it

### CSS

    <link rel="stylesheet" href="node_modules/pfdemo-vertical-navigation/dist/css/pf-vertical-navigation.css">    

### Template

    <div class="pf-vertical-nav">
        <div class="pf-vertical-nav__logo">
            <img src="images/logo.svg" alt="">
        </div>
        <div class="pf-vertical-nav__category">
            First Category
        </div>
        <ul class="pf-vertical-nav__menu">
            <li class="pf-vertical-nav__item active">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-dashboard"></i>
                    Lorem ipsum dolor
                </a>
            </li>
            <li class="pf-vertical-nav__item">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-shield"></i>
                    Dolor
                </a>
            </li>
        </ul>
        <div class="pf-vertical-nav__category">
            Second Category
        </div>
        <ul class="pf-vertical-nav__menu">
            <li class="pf-vertical-nav__item">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-dashboard"></i>
                    Lorem ipsum dolor
                </a>
            </li>
            <li class="pf-vertical-nav__item">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-shield"></i>
                    Dolor
                </a>
            </li>
            <li class="pf-vertical-nav__item">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-graduation-cap"></i>
                    Adipscing
                </a>
            </li>
            <li class="pf-vertical-nav__item">
                <a href="#0" class="pf-vertical-nav__link">
                    <i class="fa fa-fw fa-gamepad"></i>
                    Lorem
                </a>
            </li>
        </ul>
    </div>
    <div class="pf-main-content">
    </div>


## Options

### small links

add `pf-vertical-nav-sm` class

    <div class="pf-vertical-nav pf-vertical-nav-sm">
    </div>
    
### masthead title

if you use vertical navigation component in conjunction with masthead component you can add `bg-masthead` class to the logo.   

    <div class="pf-vertical-nav__logo bg-masthead">
        <img src="images/logo.svg" alt="">
    </div>
    
## Known errors

### 100% height

Be sure `pf-vertical-nav` parent element is an element with `height: 100%`

    <body>
        <div class="pf-vertical-nav">
        </div>
        <div class="pf-main-content">
        </div>
    </body>
    
    <body>
        <div class="my-container" style="height:100%;">
            <div class="pf-vertical-nav">
            </div>
            <div class="pf-main-content">
            </div>
        </div>
    </body>

## Tests

    npm run test
    
## Watch mode

    npm run watch