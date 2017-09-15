Returns a map of the refer mappings for the namespace.

Note
====

The returned value is a subset of the mapping returned by `clojure.core/ns-map`, where
ns-map = ns-refers + ns-interns + ns-imports

Parameters
==========
ns: symbol or namespace (`clojure.lang.Namespace`)

Return value
============
namespace or nil

Exceptions
==========
- `java.lang.ClassCastException`: when the given parameter is not one of the expected types
- `java.lang.Exception`: when the given symbol does not refer to a known namespace
- `java.lang.NullPointerException`: when the given parameter is nil

Related functions
=================
`clojure.core/ns-map`
`clojure.core/ns-interns`
`clojure.core/ns-imports`
