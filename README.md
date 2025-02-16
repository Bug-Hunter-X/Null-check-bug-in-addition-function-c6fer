# Null Check Bug in JavaScript Addition Function

This repository demonstrates a common, yet subtle bug in JavaScript related to null checks within a simple addition function. The function `foo` aims to add two numbers, `a` and `b`, but it handles null values incorrectly.

## Bug Description

The original code contains a bug where if either `a` or `b` is null, the function returns null, instead of handling the situation more appropriately (e.g., treating null as 0).  This can lead to unexpected results in applications where null values might unexpectedly occur.

## Solution

The solution addresses this by explicitly checking for null and treating null as 0 before performing the addition.