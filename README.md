# PatternFly components demo

POC patternfly css components "à la carte"

## Requirements

 * patternfly

## Install

    npm install pfdemo
    
## Import components

directly in html, import the component you need

    <link rel="stylesheet" href="node_modules/pfdemo/dist/css/pf-vertical-navigation.css">
    
or in your javascript code

    import 'pfdemo/dist/css/pf-vertical-navigation.css'
    
then create associated template to the related component

    <div class="pf-vertical-nav">
        ...
    </div> 

## Available components

 * [holy-grail-layout](/holy-grail-layout)
 * [masthead](/masthead)
 * [vertical-navigation](/vertical-navigation)

## Tests

    npm run test
    
## Watch mode

    npm run watch

then open `index.html` in your browser
 
## License

Apache 2.0