# controllette v1.0

# Documentation
- STATUS:GO : all ex* subdirectories have no extra files
apart from ft* files and contain at least one ft* file;
- STATUS:NO-GO : one of these conditions is not met.

# Usage
Import into project directory and run "bash controllete.sh"
on bash.

# Final remarks
- The script creates, if necessary, a .gitignore and adds its original name and ".gitignore" to it;
- It also searches for unnecessary files in the root directory;
- Max depth is 1, in other words only the root and its ex* subdirectories are checked. Subdirectories of ex* subdirectories are ignored.
