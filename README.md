Clojure language definition for [Prism](http://prismjs.com/).

## Usage

First setup prism js and css plus clojure language definition.

```html
<html>
  <head>
    <link href="prism.css" rel="stylesheet" />
  </head>
  <body>
    ...
    <script src="prism.js"></script>
    <script src="prism.clojure.js"></script>
  </body>
</html>
```

You can then define your code snippet with the appropriate `language-clojure` 

```html
<pre><code class="language-clojure">
(defn hello []
  (println "Hello world"))

(defn -main []
  (hello))
</code></pre>
```

Check prism [documentation](http://prismjs.com/#basic-usage) for mode details.

## License

MIT [license](http://www.opensource.org/licenses/mit-license.php/). Same as prism.
