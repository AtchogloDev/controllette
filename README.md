# controllette v1.0
Scans current directory for unnecessary files and at least one ft* file in each ex* subdirectory and outputs the findings and a final result.

# Documentation
STATUS:GO : all ex* subdirectories have no extra files
apart from ft* files and contain at least one ft* file.
STATUS:NO-GO : one of these conditions is not met.

# Usage
Import into project directory and run "bash controllete.sh"
on bash.

# Remarks
Creates if necessary a .gitignore and adds its original name and ".gitignore" to it.
