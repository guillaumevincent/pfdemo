# PatternFly components demo

POC patternfly css components "à la carte"

## Demo

 * [holy-grail-layout](https://rawgit.com/guillaumevincent/pfdemo/master/holy-grail-layout/index.html) ([documentation](/holy-grail-layout))
 * [masthead](https://rawgit.com/guillaumevincent/pfdemo/master/masthead/index.html) ([documentation](/masthead))
 * [vertical-navigation](https://rawgit.com/guillaumevincent/pfdemo/master/vertical-navigation/index.html) ([documentation](/vertical-navigation))

See components all together:

 * [pfdemo](https://rawgit.com/guillaumevincent/pfdemo/master/index.html)

## Requirements

 * patternfly

## Install

    npm install pfdemo
    
## Import components

directly in html, import the component you need

```css
    <link rel="stylesheet" href="node_modules/pfdemo/dist/css/pf-vertical-navigation.css">
```

or in your javascript code

```javascript
    import 'pfdemo/dist/css/pf-vertical-navigation.css'
```

then create associated template to the related component

```html
    <div class="pf-vertical-nav">
        ...
    </div> 
```

## Tests

    npm run test
    
## Watch mode

    npm run watch

then open `index.html` in your browser
 
## License

Apache 2.0