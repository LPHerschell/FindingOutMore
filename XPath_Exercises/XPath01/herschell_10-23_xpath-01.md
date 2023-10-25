# Lyndon Herschell - XPath Exercise 1

1. "//cbml:div[@type="panelGrp"]"

2. //cbml:div[@type="panelGrp"][2]//cbml:panel

3. count(//cbml:div[@type="panelGrp"][2]//cbml:panel)

4. //@characters

5. //cbml:panel[not(@characters) or @characters="narrator"]

6. count(//cbml:panel[cbml:floatingText])
