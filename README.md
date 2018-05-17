# &lt;expanded-card&gt;

#### _This functionality is now available using a combination of [iron-collpase](https://www.webcomponents.org/element/PolymerElements/iron-collapse/) and [paper-icon-button](https://www.webcomponents.org/element/PolymerElements/paper-icon-button) without the need for a custom element - see [paper-card demos](https://www.webcomponents.org/element/PolymerElements/paper-card/demo/demo/index.html)._

This Polymer element  is designed to be used inside of paper-material as a card and displays a [paper-icon-button](https://elements.polymer-project.org/elements/paper-icon-button) with an expand icon. The element also wraps the content that appears when expanded using [iron-collapse](https://elements.polymer-project.org/elements/iron-collapse). A rotation animation is also displayed when the expansion icon is pressed using [neon-animation](https://elements.polymer-project.org/elements/neon-animation)

## Demo

[Check it live!](http://JoeWells.github.io/expanded-card/demo)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install expanded-card --save
```

Or [download as ZIP](https://github.com/JoeWells/expanded-card/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/expanded-card/expanded-card.html">
    ```

3. Start using it!  
    ```html
    <paper-material>
        <h1>Card Title</h1>
        <p>Contents...</p>
        <expanded-card>
            <p>Further contents</p>
        </expanded-card>
    </paper-material>
    ```

## Options

Attribute         | Options     | Default      | Description
---               | ---         | ---          | ---

## Methods

Method           | Parameters                              | Returns     | Description
---              | ---                                     | ---         | ---


## Events

Event         | Description
---           | ---

## History

For detailed changelog, check [Releases](https://github.com/JoeWells/expanded-card/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
