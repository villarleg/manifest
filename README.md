# Patches needed for bringup

Recommended to use repopick.

-----

### build

- 186687

### core

- 189546
- 189547
- 189548
- 189549
- 189550

### device/oppo/common

- 193331
- 193341
- 194268

### qcom display

- 188677

### system/bt

- 192528
- 192529

### Copy - Paste
    repopick 186687

    repopick 189546
    repopick 189547
    repopick 189548
    repopick 189549
    repopick 189550

    repopick 193331
    repopick 193341
    repopick 194268

    repopick 188677

    repopick 192528
    repopick 192529

-----

# Extras

Not needed but nice to have

-----

### system core (DASH)

- 185657

### vendor/lineage

- 191330

### Copy - Paste
    repopick 185657 -f
    repopick 191330

-----

# KRYO

- kryo-libc

# ARMV8 32-BIT

- armv8-32bit
- https://android.googlesource.com/platform/external/skia/+/667a567f52cd00e809ade6e0f174772a768bb9a4

### Copy - Paste
    repopick -t kryo-libc
    repopick -f -t armv8-32bit

Need to pick external/skia manually

-----
