# Naming convention for issue files

```
<class>[.sub-class][.<variant>].md
```
  
e.g:
* xss.md
* xss.reflected.md
* xss.dom-based.custom-js-code.md

# Sections

To cover all flavours we stick to the FILR format.
Each issue file must contain the following sections:
* Finding
* Impact
* Likelihood
* Recommendation

# Flavours?
yep, flavours.
Cooking the same ingredients in a different way: Different reporting formats - different flavours.
Most of the clients prefer reports in the FILR format described above.

You can still copypaste/generate/whatever to create your report by joining these sections to provide the required format.
for example:

Some prefer the FRR flavour
* Finding <= Finding
* Risk <= Impact + Likelihood
* Recommendation <= Recommendation

Rare dummy FdR flavour:
* Full description <= Finding + Impact + Likelihood
* Recommendation <= Recommendation

Some of them prefer their report in a single-section overview...
