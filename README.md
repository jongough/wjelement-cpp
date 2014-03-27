wjelement-cpp
=============

WJElement-cpp - Lightweight C++ wrapper for WJElement with JSON Schema support

WJElement++ provides a simple, lightweight wrapper around the excellent WJElement
library. The wrapper supports JSON Schema draft-04.

While WJElement is fast and memory-efficiency, this C++ wrapper makes it
far more convenient to use and and the code is easier to understand and 
manage.

However, the wrapper is only a by-product of the real reason why this
library sprung to life. I was after a JSON Schema library for C or C++
that would allow me to deal with things such as binding validators
with elements, identifying elements as schemas, parsing the meta schema
and building schema and document stores. At the time of forking WJElement, 
its built in support for schema only supported validation and was based on 
JSON Schema draft-03.

To use this library, you will need to build and link with the wjelement++
branch of wjelement. Also note the library uses boost regex.

Peter Hug <pete@kapiti.co.nz>  - author of WJElement++

Special thanks to Micah N Gorrell for his excellent wjelement library!
