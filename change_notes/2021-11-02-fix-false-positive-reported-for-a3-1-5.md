 - `A3-1-5` - `NonTrivialNonTemplateFunctionDefinedInsideClassDefinition.ql`          `TrivialOrTemplateFunctionDefinedOutsideClassDefinition.ql`
     - Fix #378 - Inlined pure virtual operators are no longer flagged as non-compliant so the rule will produce fewer false positives.
     - Adjust the definition of a trivial accessor and trivial mutator to follow the examples from the standard.