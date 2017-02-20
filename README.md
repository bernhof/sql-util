# SQL utilities and common functions
A collection of scripts that I've written or adapted for use in projects over time. Functionality, behaviour and attribution (where applicable) is described within each script.

## Add Business Days
Adds a number of business days to a date. Assumes business days Mon-Fri.
I found many examples of similar functionality when I needed it, but many didn't handle edge cases or odd input values properly. This scripts represents the best parts and some modifications to ensure simple, predictable behaviour.

## Find
Helper function to search for procedures, functions or other objects within SQL Server. Supports wildcards and can search multiple databases if user has sufficient permissions. The script came as a result of working with large, messy databases with tons of tables, functions, SPs etc., where I needed to locate *all* references to certain objects (even in strings within a function) across many databases.
