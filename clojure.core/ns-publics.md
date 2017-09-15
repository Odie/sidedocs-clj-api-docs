Returns a map of the public [intern mappings](EXPLAINME) for the namespace.

Parameters
==========
ns: symbol or namespace (clojure.lang.Namespace)

Return value
============
{symbol -> var} or nil

Exceptions
==========
- `java.lang.ClassCastException`: when the given parameter is one of the expected types
- `java.lang.Exception`: when the given symbol does not refer to a known namespace
- `java.lang.NullPointerException`: when the given parameter is nil

Related functions
=================
`clojure.core/ns-interns`
