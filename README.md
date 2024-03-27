# analysis-results-cluster-01-data

To become: a first of similar places to contain the results of the different metagoflow runs.

Each of these runs should: 
- be identified by some unique ref - this is the "EMO BON ref code"
- have its results be put into its own subfolder here - format = "emobon<EMO BON ref code>-products" at Katrina suggestion, but not sure if we need the "emobon" or "-products" in those names
- each of those subfolders should build up its own ro-crate metadata
  - meaning each should have a rocrate-metadata.json folder, - why a folder? - it can just contain the ro-crate-metadata.json file plus any content not linked therein.
  - those metadata files should list all its relevant content
  - the actual content will be in there:
    - either by remote reference (ref to ENA if any)
    - either by local relative storage (smaller files)
    - either by dvc.org pointer file (retrievable large objects on a ssh server to be set-up)
