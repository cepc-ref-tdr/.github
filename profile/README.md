# CEPC Ref TDR source code

The source code of chapters are linked between overleaf and GitHub. 

Please send your GitHub account to Tao Lin to get the read permission.

## How to build the project?

Get the main project:
```bash
git clone --recurse-submodules git@github.com:cepc-ref-tdr/TDR_main.git
```

Run build.sh:
```bash
cd TDR_main
bash ./build.sh
```

## How to register your chapter?
Edit build.sh and find following:
```bash
function cepc-ref-tdr-repos-dirs() {
    echo TDR_03_MDI:chap03_MDI
}
```

The first part is the repo name. The second part is the folder to be linked under build directory. Ask Tao to upload your chapter. 


