# cljsjs/slip

[](dependency)
```clojure
[cljsjs/slip "2.0.0-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.slip))
```

Uses externs provided by `https://github.com/jmmk/javascript-externs-generator`, many thanks!

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
