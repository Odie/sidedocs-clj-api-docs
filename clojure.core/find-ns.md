Returns the namespace named by `sym`

Parameters
==========
sym: symbol of the namespace to retrieve

Return value
============
namespace or nil

Exceptions
==========
- `java.lang.ClassCastException`: when the given parameter is not one of the expected types
- `java.lang.NullPointerException`: when the given parameter is nil

Related functions
=================
`clojure.core/the-ns`
