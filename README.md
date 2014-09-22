# VerbalXPath Specification

VerbalXPath, like VerbalExpressions, aims to be a saner way to write XPath
expressions.

## Motivation

XPath is often not a pleasant thing to write. VerbalXPath's objective is
to create a library (or set of) to provide a friendlier mechanism for writing
and reading XPath. By exposing a well defined interface and hiding the 
underlying XPath code, it is also easier to handle backward incompatible 
changes if they happen to occur.
