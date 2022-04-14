# boomerang-sbom
Repository containing software bill of materials of boomerang releases.

## Create SBOM for a version of boomerang

To create an Software Bill of Materials (SBOM) for a version of boomerang, go into the GitHub Actions Tab and choose the "Create new Release" workflow. 
There choose to start it manually and set as the input the Tag associated with the version of boomerang you want the SBOM for.  
The action will then generate the SBOM and release it in a GitHub Release with the same name as the given version in this repository.