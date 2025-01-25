# Unexpected NaN Result for Undefined Input

This repository contains a JavaScript example demonstrating a common error: unexpected NaN results when a function receives undefined instead of null.  The code demonstrates the problem and provides a solution to handle undefined inputs gracefully.

## Problem

The provided `foo` function intends to return 0 if the input `x` is null. However, if `x` is undefined, it produces NaN. This inconsistency is a potential source of unexpected behavior.

## Solution

The solution file provides an improved version of the function.  It explicitly checks for both null and undefined inputs and returns 0 in both cases.  This ensures consistent handling of these edge cases.