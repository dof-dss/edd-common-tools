# edd-common-tools
Toolkit of common uses cases for re-use.

This is a handy package to add common code that needs re-used time and again.
There is a requiredif that can be used in a Viewmodel to indicate whether a field should be required based on another value.

There is also some attributes to strip out any dangerous values such as angle brackets from inputs from the user.
Just add these attributes in your Viewmodel above the fields you want to protect. This was required by a recent pen test.

# To install

## Nuget package manager:

Install-Package edd-common-tools -Version 1.0.0

## .Net cli:

dotnet add package edd-common-tools --version 1.0.0
