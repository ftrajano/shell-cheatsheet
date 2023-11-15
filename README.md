# shell-cheatsheet
## List of Commands

1. <a href='#pwd'>pwd</a>
2. ls
3. cut
4. paste
5. grep
6. head
7. tail
8. sort
   
## Wildcards
What other wildcards can I use?
The shell has other wildcards as well, though they are less commonly used:

? matches a single character, so 201?.txt will match 2017.txt or 2018.txt, but not 2017-01.txt.
[...] matches any one of the characters inside the square brackets, so 201[78].txt matches 2017.txt or 2018.txt, but not 2016.txt.
{...} matches any of the comma-separated patterns inside the curly brackets, so {*.txt, *.csv} matches any file whose name ends with .txt or .csv, but not files whose names end with .pdf.

<h2 id='pwd'>pwd</h2>
<h2 id='ls'>ls</h2>
<h2 id='cut'>cut</h2>
<h2 id='paste'>paste</h2>
<h2 id='grep'>grep</h2>
<h2 id='head'>head</h2>
<h2 id='tail'>tail</h2>
<h2 id='sort'>sort</h2>
1. **Function of Sort**: Puts data in order.
2. **Default Behavior**: Sorts in ascending alphabetical order.
3. **Flag -n**: Sorts data numerically.
4. **Flag -r**: Reverses the order of the output.
5. **Flag -b**: Ignores leading blanks in data.
6. **Flag -f**: Folds case, making the sorting case-insensitive.
7. **Common Usage in Pipelines**:
   - Initially use `grep` to eliminate unwanted records.
   - Then apply `sort` to organize the remaining records.
