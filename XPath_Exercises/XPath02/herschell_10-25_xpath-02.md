# Lyndon Herschell - XPath Exercise 2

1. 
   - `//div[@class='historical-person]`

2b.  
   - `//div[@class='historical-person']/*`

2c. 
   -  `//div[@class='your-choice-div']/*`

2d. 
   - `count(//div[1]/*)`

3a. 
   - `//list[@class='animals']/* and count(//list[@class='animals']/*)`

3b. 
   - `(//list[@class='animals']/*)[last()]`

3c. 
   -  `(//list[@class='plants']/*)[5]`

3d. 
   - (//list[@class='plants']/*)[position() <= 6]`

4 . 
   - `"//person/occupation[1]"` will return the starting  `"<occupation>"` element under every `"<person>"`. 
   - `(//person/occupation)[1]` returns the first `<occupation>` element among every `<occupation>` elements that are under `<person>`. 
   
5a. 
   - XPath Expression: `count(//person)`

5b. 
   - XPath Expression: `count(//person[@sex]) = count(//person)`

5c. 
   - XPath Expression: `(count(//person[@sex]) div count(//person)) * 100`

5d. 
   - XPath Expression: `count(//person[@sex='f'])`