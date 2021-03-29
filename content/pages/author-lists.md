---
title: Export authors from SLS
---

# SLS report

use slsreport bib -> author exist -> save select (author) as text 

The export file have title need delete, the encoding is big-5.

use vscode :

   convert encoding to utf-8
   find html entities search &# use the encode decode extension. select the entity &#xXXXX; then ctrl-shift-P select from html entities to string
   each line may have multiple authors separated by ;; find ;; and replace "\n" (need to check use regular expression)
   search for << >> and replace with 《》 
Convert    
   Use https://tableconvert.com/?output=excel import data by copy all text from vscode then paste (choose import data from site) then select import data
   choose from the bottom of page excel then copy
Excel 
   paste the data into excel 
   sort table
   DATA -> remove duplicate
edit
   add tid and type to the table. Then add type
Convert 
   Use https://tableconvert.com/?output=excel import data by copy all text from vscode then paste (choose import data from site) then select import data
   choose from the bottom of page YAML then copy
   
