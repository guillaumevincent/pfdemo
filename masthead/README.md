# PatternFly masthead component

## Requirements

 * patternfly

## Install

    npm install pfdemo-masthead
    
## Import it

### CSS

    <link rel="stylesheet" href="node_modules/pfdemo-vertical-navigation/dist/css/pf-vertical-navigation.css">    

### Template

    <div class="pf-masthead">
        <ul class="pf-masthead__menu">
            <li class="pf-masthead__item">
                <a href="#0" class="pf-masthead__link">
                    <i class="fa fa-fw fa-dashboard pf-masthead__icon"></i>
                    <span class="pf-masthead__link-text">Lorem</span>
                </a>
            </li>
            <li class="pf-masthead__item">
                <a href="#0" class="pf-masthead__link">
                    <i class="fa fa-fw fa-shield pf-masthead__icon"></i>
                    <span class="pf-masthead__link-text">Dolor</span>
                </a>
            </li>
            <li class="pf-masthead__item">
                <a href="#0" class="pf-masthead__link">
                    <i class="fa fa-fw fa-graduation-cap pf-masthead__icon"></i>
                    <span class="pf-masthead__link-text">Adipscing</span>
                </a>
            </li>
            <li class="pf-masthead__item">
                <a href="#0" class="pf-masthead__link">
                    <i class="fa fa-fw fa-gamepad pf-masthead__icon"></i>
                    <span class="pf-masthead__link-text">Lorem</span>
                </a>
            </li>
        </ul>
    </div>


## Options

### vertical navigation

add `vertical-navigation` class if you use it with vertical navigation

    <div class="pf-masthead vertical-navigation">
    ...
    </div>


## Tests

    npm run test
    
## Watch mode

    npm run watch