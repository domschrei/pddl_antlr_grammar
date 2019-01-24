# ANTLR Grammar for PDDL

This is a patched and revised version of the [PDDL ANTLR grammar](https://github.com/antlr/grammars-v4/blob/master/pddl/Pddl.g4) from the ANTLR repository. 

Noteable changes include the support of equality predicates, general case-insensitivity, and a couple of minor bug fixes.

This grammar is used for parsing PDDL files within the [Aquaplanning](https://github.com/domschrei/aquaplanning) framework.

## Parser Generation

In order to generate a parser in Java, fetch [some ANTLR executable antlr.jar](https://www.antlr.org/download/antlr-4.7.2-complete.jar) and then execute `java -jar antlr.jar Pddl.g4`.
