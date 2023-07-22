# Design Patterns

In software engineering, a design pattern is a general, reusable solution to a commonly occurring problem. They are formalised best practices, templates that a programmer can use to solve common problems.

## Repository structure

This repository is a collection of most common design patterns in various languages. Each pattern is given a directory with:

  - a simple README that describes the pattern in greater details;
  - one self-contained implementation per language in the following format: <br>
    `[language-name].[language-extension]`

## Patterns overview

A list of languages implementations and patterns included in this repository is by no means set. It merely reflects my interests and requirements.

The following patterns are included:

- [**Strategy**](./strategy) – process Class A using a set of rules defined by Class B.
- [**Observer**](./observer) – for when Class A needs to react to changes in Class B.
- [**Composites**](./composites) – helps to build a tree of leaf / trunk nodes.
- [**Iterator**](./iterator) – for when each object in Class A needs to be fetched in turn.
- [**Command**](./command) – separate the description of a thing from its actions.
- [**Adapter**/**Decorator**/**Proxy**](./adapter) – separation of concerns, Class B extends functionality of Class A.
- [**Singleton**](./singleton) – There can only be one!
- [**Builder**/**Factory**](./builder) – assemble a whole out of multiple components.
