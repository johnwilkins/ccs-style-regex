# ccs-style-regex

The `ccs-style-regex` repository contains regular expressions for converting asciidoc style and errors in common spellings or usage in CCS docs. The intent is to automate some of the substitution changes and reduce work for peer reviewers and editors, and streamline the process for writers. 



## The Red Hat Supplementary Style Guide

The scripts are based on the general conventions described in https://redhat-documentation.github.io/supplementary-style-guide/#general-conventions. The asciidoc source for these conventions can be found here: https://github.com/redhat-documentation/supplementary-style-guide/tree/master/supplementary_style_guide/glossary_terms_conventions/general_conventions.

## Scripts

The scripts follow the general conventions source of breaking the scripts down alphabetically. Once tested, these may be consolidated into a single script. 

## Testing the scripts

To see the changes without modifying the test file, execute: 

$ sed -rf script test.adoc

You can also make a copy of test.adoc and run it interactively so that it actually modifies the file.

$ sed -rf script -i test1.adoc
