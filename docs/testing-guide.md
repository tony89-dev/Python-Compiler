# Testing Guide

This document describes a simple testing approach for the Latte Compiler project.

## Purpose

Compiler projects need careful testing because small changes can affect parsing, validation, or output generation.
The goal of testing is to confirm that existing behavior remains stable after each update.

## Suggested Testing Steps

1. Build or run the project using the available project commands.
2. Run existing tests if the repository includes a test suite.
3. Check sample input files if examples are available.
4. Confirm that valid source code is processed correctly.
5. Confirm that invalid source code produces clear errors.

## What to Review

When reviewing a compiler change, pay attention to:

- parser behavior
- validation rules
- error handling
- output consistency
- test coverage

## Notes

Testing should stay simple and repeatable.
Each pull request should be small enough to review safely.
