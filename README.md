To build the firmware for the Corneish Zen v2 left half, run the following command:

```console
west build -p  -b corneish_zen_v2_left -- -DZMK_CONFIG=/workspaces/zmk-config/config
```

To build the firmware for the Corneish Zen v2 right half, run the following command:

```console
west build -p  -b corneish_zen_v2_right -- -DZMK_CONFIG=/workspaces/zmk-config/config
```

The pristine is for cleaning the build directory before building. Used when changing half or board