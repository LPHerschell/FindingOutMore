# Lyndon Herschell - XPath Exercise 4


1. //cbml:panel/@characters

2. tokenize(//cbml:panel/@characters, ' ')
   
3. 
    1. //cbml:panel[contains(@characters, 'drkelly')]  (5 Items were found)
    2. //cbml:panel[cbml:balloon[string-length(.) = max(//cbml:balloon/string-length(.))]]/@characters

4. //cbml:panel[cbml:balloon[string-length(.) = max(//cbml:panel/cbml:balloon/string-length(.))]]/@characters

5. 
   1. //cbml:panel[.//cbml:note[contains(., 'skull')]] 
   2. 
        1. //div[//cbml:balloon[contains(., 'NO')]] (20 items)
        2. //div[.//cbml:balloon[contains(., 'NO')]] (10 items)