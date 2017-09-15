Returns the namespace named by `x`

Parameters
==========
x: symbol or namespace (`clojure.lang.Namespace`)

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
`clojure.core/find-ns`
