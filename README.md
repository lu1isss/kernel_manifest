## Repo Init ##
```bash
repo init -u https://github.com/Witcher-Projekt/kernel_manifest.git -b pickle
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
