# Go Map Access Panic

This repository demonstrates a common error in Go: panics caused by accessing a nil map.  Attempting to access a key in an uninitialized map will cause a runtime panic, abruptly terminating the program. This is unexpected behavior for many developers unfamiliar with Go's map behavior.

## Reproduction

The `bug.go` file contains code that reproduces the error. Running this code will result in a panic.

## Solution

The `bugSolution.go` file shows how to prevent this panic by using a check before access.
