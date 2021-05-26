# OnePlus 5 (cheeseburger) Manifest
Manifest for building LineageOS for the OnePlus 5 (cheeseburger)

Clone this repository in the .repo folder of your project

My device, kernel and vendor trees are based on the latest LineageOS trees

To build, execute the following commands in following order:

```bash
source build/envsetup.sh
```
```bash
lunch lineage_cheeseburger-user # (or lineage_cheeseburger-userdebug)
```
```bash
mka bacon # (or mka or m (m gives build error for some reason))
```

To clean in between, builds execute the following command:

```bash
mka clobber
```

