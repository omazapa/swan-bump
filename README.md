# swan-bump
SWAN Bump Tool

Allows to set the version for a given package in  setup.py and packaje.json files. 
Also allows to create a commit and tag with the changes.

# Examples
Inside the repository
`
swan_bump -n=HdfsBrowser -v=1.1.1
`
with optional message
`
swan_bump -n=HdfsBrowser -v=1.1.1 -m='tag notes here'
`