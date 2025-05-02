# Datalog Syntax

A simple Extension to support syntax coloring for datalog in VSCode.

Support the following format:
```
Head(X, Z) :- pred1(X, "hello"), Z = sum[W] pred2(W).
?- Head(X, Y).
```