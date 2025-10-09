# $${\color{red}THIS\ REPO\ IS\ OBSOLETE\ (ARCHIVED\ ON\ 10/9/25)}$$

---

# Special Collections Finding Aids ***FABified*** EAD Repository

This repository contains the `FABified` versions of the ArchivesSpace-exported EADs.  

A `FABified` EAD is an ArchivesSpace-generated EAD that has been modified using the [`fasb fabify`](https://github.com/nyudlts/dlts-finding-aids-fasb) command to match the [`FAB`](https://github.com/nyulibraries/specialcollections) indexing expectations.  

For example, ArchivesSpace changed the "creator" XML element name from `creator` to `Creator`.  The `FAB` was written before the change and so the `Creator` elements were not being indexed. The `fasb fabify` step converts all `Creator` elements in an EAD to `creator` elements.  

The `non-FABified` versions of the EADs can be found in the production EAD repository [here](https://github.com/nyulibraries/findingaids_eads_v2).  
