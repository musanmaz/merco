# staging
This repository contains 
* packagelists for staging CSDs (Translist, Translist_PV, Translist_TB folders)
* the scope for packagelist generation (scope folder)
* fkhistory files to validate installation (fkhistory folder)

The Translist files reflect the expected state and include all CSDs that are in scope with their respective version to be installed. Those files will be pushed to Artifactory (triggered by commit).

The scope folder is updated manually.

The fkhistory files are pulled from Artifactory, based on an interval.
