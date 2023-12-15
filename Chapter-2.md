## My Understanding:

- Use `head` to display the first 10 lines from a file and `tail` for the last 10 lines.
- `nl` numbers the lines in a file.
- `grep` filters file content based on specified patterns.
- With `sed`, replace specific strings in a file and save changes to a new file.
- `more` and `less` allow viewing file contents page by page, with `less` offering additional functionalities.

## Exercise Solution:

```bash

# 1. 
cd /opt/metasploit-framework/embedded/framework/data/wordlists

# 2. 
cat password.lst

# 3.
more password.lst

# 4
less password.lst

# 5.
nl password.lst

# 6.
tail -20 password.lst

# 7.
cat password.lst | grep 123

