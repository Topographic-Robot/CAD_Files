# CAD_Files
CAD files for the topographical map robot

## Environment Setup

Install git-lfs
```sh
apt-get update
apt-get install git-lfs
```

Clone the repo
```sh
git clone git@github.com:Topographic-Robot/CAD_Files.git
cd CAD_Files
```

Install LFS for the repo
```sh
git lfs install
```	

Track large files
```sh
git lfs track "*.STL"
git lfs track "*.stl"
# continue for all other files
```
