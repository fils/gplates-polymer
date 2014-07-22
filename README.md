# &lt;gplates-latlong&gt;

> A Web Component example using [Polymer](http://www.polymer-project.org/).
>
> Looking for a boilerplate? Check [polymer-boilerplate](https://github.com/webcomponents/polymer-boilerplate).

## Background
This component makes a call to the [gplates service](http://gplates.gps.caltech.edu:8080/doc/).  [Gplates](http://www.gplates.org) is a tool for making 
visualizations of plate tectonic movement.  One can view a model of what the earth looked like millions of years ago.  For modern researchers it provides an 
method to see where a sample (like a fossil) found today would have been located when it existed.   

This web component allows a person to provide a set of latitude and longitude points, an age in millions of years and see where they would have been located and what
the plates would have looked like.  

## Demo

Coming...

## Install

Coming...

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/gplates-latlong.html">
    ```

3. Start using it!

    ```html
     <gplates-latlong lat="-51.0,-45.0" lng="38.0,30.0" age="75.0"></gplates-latlong>
    ```

## Options

```
Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---    
`lat`      | *string*                  | ``                  | String of latitudes seperated by commas    

`lng`      | *string*                  | ``                  | String of longitudes seperated by commas   

`age`      | *string*                  | ``                  | Age to reproject to        
```


## History

For detailed changelog, check [Releases](https://github.com/webcomponents/hello-world-polymer/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
