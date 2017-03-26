#### Private Data Layer

Cepheus uses Layering techniques that allows items to be built in the open on the primary repo of Cepheus but allow you to maintain purpose built features that are unique to your organization and data that is private.

This layer will be overlaid on the public `data/private` found in Cepheus. Any files that are in the public that match the same names found here will be overridden and any files that are unique to each repo will remain. 
