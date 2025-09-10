# TD_CollectFiles
This tox automatically collects external assets that are referenced with absolute paths in a TouchDesigner project, copies them into the project directory, and updates their paths in the .toe to point to the new local copies using relative paths. 
This ensures that projects are fully self-contained, portable, and easy to share or version-control without broken links.
