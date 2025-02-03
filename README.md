# Tailwind CSS @apply Directive Style Conflict

This repository demonstrates a common error encountered when using Tailwind CSS's `@apply` directive: style conflicts between `@apply` and directly written styles.

## Problem

When applying styles using `@apply` and also declaring the same styles directly, the direct styles override `@apply`. This often leads to unexpected visual behavior, where the expected styles from the `@apply` directive are not reflected.

## Solution

The solution is to remove any redundant style declarations and rely entirely on `@apply` or define a consistent style system that avoids direct style overriding within the same element.