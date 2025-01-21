# Tailwind CSS `@apply` Directive Conflicts

This repository demonstrates a potential issue when using Tailwind CSS's `@apply` directive.  Specifically, it highlights the problem of conflicting styles when applying the same utility class with different values.

## Problem

The `@apply` directive, while convenient, can lead to unexpected results if you try to apply multiple utilities with overlapping properties.  This can make debugging difficult as the final style may not be easily traced back to its source.

## Solution

To avoid this issue, it's best to avoid applying conflicting utilities with `@apply`.  Instead, you should create more specific classes that combine the desired styles. This provides a more organized and maintainable stylesheet that makes it easier to pinpoint unexpected styles or conflicts.
