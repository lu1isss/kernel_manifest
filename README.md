## Repo Init ##
```bash
repo init -u https://github.com/cyberknight777/kernel_manifest.git -b cancunf
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
