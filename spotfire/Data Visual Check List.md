# Items to Check For Prior to Placing a DXP Into Live

These are some questions to ask prior to placing a visual into production.

##Basic Questions
1. Is the header correct?
2. Is the data limiting correct? (Limit data using expression, markings)
3. Do the colors match existing visuals?
4. Are the axises formatted correctly? (Date, string, scrollbars)
5. Is the marking set linked?

##Validation Questions
1. Are the numbers calculated elsewhere? If so, do those numbers match what you see?
2. Are you doing any calculation on aggregates? _Avg() - Avg() (This is bad!)_
