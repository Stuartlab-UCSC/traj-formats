# traj-formats
Format specifications for communicating trajectory information.

There are two modalities for common formats: tab delimited matrix files, and json formats.

## tab delimited matrix files
1.) cell x branch: Columns are branch ids and rows are cell ids. Values of the matrix are pseudotime assignment.

## json formats
Currently using json-schema for specification. Pull the repo and use the *-schema.json files
and your favorite utility for validation ect.

Can use jsvalidate-cli for command line validation:
`jsvalidate -s v1.graph-schema.json v1.graph-example.json`

Check the wiki for details/discussion.
