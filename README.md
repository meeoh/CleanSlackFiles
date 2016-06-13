# CleanSlackFiles
Deletes specific filetypes from a slack channel to create space

# Usage
First set access token and _domain variables *THIS MUST BE DONE OR IT WONT WORK*
You're access token also must have the correct permissions or else the deletion will fail.
Then add or cases to line 49 for all the file types you wanted deleted.
Finally, run `python RemoveSlackHistory.py`

# Debugging
If the deletions aren't working, uncomment line 63 to see the result of the post call, this will show you if you have sufficient permissions on your channel
