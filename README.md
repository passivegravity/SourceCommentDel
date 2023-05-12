# SourceCommentDel
(´･ω･`) Skid freely.


Edit file location: 
```py

# Read the Cheat Engine table file
with open(r'C:path.to\file_with_comments.txt', 'r') as file:
    table_contents = file.read()

# Remove comments from the table contents
cleaned_table = remove_comments(table_contents)

# Save the cleaned table to a new file
with open(r'C:path.to\cleaned_comments.txt', 'w') as file:
    file.write(cleaned_table)

```
