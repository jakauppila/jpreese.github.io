---
layout: post
title: smelly code
---
- Large class: a class that has grown too large. See God object.
- Feature envy: a class that uses methods of another class excessively.
- Inappropriate intimacy: a class that has dependencies on implementation details of another class.
- Refused bequest: a class that overrides a method of a base class in such a way that the contract of the base class is not honored by the derived class. See Liskov substitution principle.
- Lazy class / freeloader: a class that does too little.
- Excessive use of literals: these should be coded as named constants, to improve readability and to avoid programming errors. Additionally, literals can and should be externalized into resource files/scripts where possible, to facilitate localization of software if it is intended to be deployed in different regions.
- Cyclomatic complexity: too many branches or loops; this may indicate a function needs to be broken up into smaller functions, or that it has potential for simplification.
- Downcasting: a type cast which breaks the abstraction model; the abstraction may have to be refactored or eliminated.[7]
- Orphan variable or constant class: a class that typically has a collection of constants which belong elsewhere where those constants should be owned by one of the other member classes.
Method-level smells:
- Too many parameters: a long list of parameters is hard to read, and makes calling and testing the function complicated. It may indicate that the purpose of the function is ill-conceived and that the code should be refactored so responsibility is assigned in a more clean-cut way.
- Long method: a method, function, or procedure that has grown too large.
- Excessively long identifiers: in particular, the use of naming conventions to provide disambiguation that should be implicit in the software architecture.
- Excessively short identifiers: the name of a variable should reflect its function unless the function is obvious.
- Excessive return of data: a function or method that returns more than what each of its callers needs.
