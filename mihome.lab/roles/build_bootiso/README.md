Readme.md file for build_bootiso_v2
-----------------------------------
Version 2 should include the following optimized features.

- Download boot images from url once, per os major version (e.g. 6 or 7) in order to save bandwith.

- More work needs to be done, upon adding the task/main.yml on get_url.
  The idea is download bootiso files, then copy to individual host tmp directory, and build an ISO 
  from it.
