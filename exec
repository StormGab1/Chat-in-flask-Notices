import re

while True:
 palavras_proibidas = ["carlos", "templeuser"]
 
 for group_name in list(groups.keys()):
     for palavra in palavras_proibidas:
         if re.search(palavra, group_name, re.IGNORECASE):
             del groups[group_name]
             break
 time.sleep(50)
