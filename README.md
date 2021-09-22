When creating a new YSQL cluster, initial state of system catalog (`pg_catalog` schema) is taken from pre-generated system catalog snapshot.
This repository will be used to store such (older) snapshots so that we can test our changes against clusters using outdated state of system catalog.
