# The Tower II English patches
The Tower II patches for english-y text

The patches are applied in the install directory of The Tower II using: 
```
git apply patchname.patch
```

They have been created using the following command currently:
```
git diff --no-index --binary $OLDITEM $NEWITEM > $PATCHITEM.patch
```
