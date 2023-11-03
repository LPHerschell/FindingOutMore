# Lyndon Herschell - XPath Exercise 3


1. 
   - //div/count(*) counts the number of child elements of <div> elements throughout the document.
   - //div/*/count(*) is an expression that counts the number of child elements for <div> elements. 

2 .  max(//div/*/count(*))
   - 1071
   
3 . //div[count(*) = max(//div/*/count(*))]

4 . //div[count(*) = //div/*/count(*) and not(count(*) < //div/*/count())]

5a. distinct-values(//occupation/@type)

5b. //occupation[@type="artist"]

5c.//person[occupation/@type="artist" and @sex="f"]

5d. //person[occupation/@subtype="engraver"]

6a. distinct-values(//*/name())

6b. count(distinct-values(//*/name()))
