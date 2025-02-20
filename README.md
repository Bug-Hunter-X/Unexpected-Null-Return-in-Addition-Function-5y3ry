# Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript error involving unexpected null returns from a function designed to perform addition. The function `foo` returns `null` if either input is `null`, which may not always be the desired behavior.  This example highlights the importance of handling null and undefined values explicitly to avoid unexpected results.

## Bug Description

The `foo` function unexpectedly returns `null` when one of its arguments is `null`.  A more robust solution should either treat `null` as 0, throw an error, or provide a more informative return value.

## Solution

The solution demonstrates how to modify the `foo` function to handle null values more gracefully, by replacing null values with 0 before performing the addition.