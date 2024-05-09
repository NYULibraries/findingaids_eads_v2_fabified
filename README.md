# Special Collections Finding Aids ***FABified*** EAD Repository

This repository contains the `FABified` versions of the ArchivesSpace-exported EADs.  

A `FABified` EAD is one in which has been modified using the `fasb fabify` operation.  `FABification` modifies the ArchivesSpace-generated EAD so that it matches the `FAB` indexer expectations.  

For example, in 2019, ArchivesSpace changed the "creator" XML element name from `creator` to `Creator`.  The `FAB` was written before 2019 and so the `Creator` elements were not being indexed. The `fasb fabify` step converts all elements in an EAD named `Creator`  to `creator`.  

The `non-FABified` versions of the EADs can be found [here](https://github.com/nyulibraries/findingaids_eads_v2).  
