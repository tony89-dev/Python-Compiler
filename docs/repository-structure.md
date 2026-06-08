# Repository Structure

This document explains the general structure of the Latte Compiler repository.

## Overview

The repository contains source code, tests, and project files related to the compiler implementation.
Keeping the structure clear helps future contributors understand the project faster.

## Common Areas

The main areas of a compiler project usually include:

- source code for compiler logic
- parser or syntax-related code
- validation or semantic analysis logic
- test files
- documentation files
- project configuration files

## Maintenance Guidelines

When adding new files, keep them in a clear location.
Avoid mixing source code, test files, and documentation in the same place unless the project already follows that pattern.

## Review Notes

Before merging structural changes, check that:

- file names are clear
- folder usage is consistent
- documentation matches the current project
- unnecessary files are not included

## Goal

A clean repository structure makes the project easier to maintain, review, and extend.
