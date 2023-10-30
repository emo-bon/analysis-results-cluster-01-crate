# analysis-results-cluster-01-data

To become: a first of similar places to contain the results of the different metagoflow runs.

Each of these runs should: 
- be identified by some unique ref
- have its results be put into its own subfolder here
- each of those subfolders should build up its own ro-crate metadata
  - meaning each should have a rocrate-metadata.json folder,
  - those metadata files should list all its relevant content
  - the actual content will be in there:
    - either by remote reference (ref to ENA if any)
    - either by local relative storage (smaller files)
    - either by dvc.org pointer file (retrievable large objects on a ssh server to be set-up)
