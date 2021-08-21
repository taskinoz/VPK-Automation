# VPK Automation

Automate the building of VPK files for Titanfall 2 with Github Actions

## About

The Github workflow will currently run whenever a change to `changelog.md` has been made.

The Workflow will:

- Download the RSPNVPK tool
- Download the `englishclient` vpk file you will be packing
- Run the `build.sh` script which could be moved to the workflow (but I use it locally to build vpks)
- Zip the files and create a draft release

**The location secret used in the workflow is the URL where I host my vpks and the tool**
