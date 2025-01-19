# Lua pairs Iterator Bug

This repository demonstrates an uncommon bug related to the `pairs` iterator in Lua when dealing with deeply nested tables. The issue arises when modifying the table during iteration, leading to unexpected behavior.

## Bug Description

The `pairs` iterator in Lua, when used with deeply nested tables, may skip elements or produce unexpected results if the table's structure is altered during iteration.

## Reproduction

The `bug.lua` file contains code that showcases this issue. Executing this code may not always produce the same results, depending on the Lua interpreter and its implementation of the `pairs` iterator.

## Solution

The `bugSolution.lua` file provides a solution demonstrating how to safely iterate over nested tables without causing unexpected behavior.

## Contributing

Contributions are welcome!