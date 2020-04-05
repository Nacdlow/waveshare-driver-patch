# Waveshare Driver Patch

This is a patch for the Python Waveshare `epd2in13_V2.py` driver, which flips
the output upside-down.

This should easily be portable to other Python Waveshare drivers.

## How to patch

Use the `patch` utility.

```sh
$ patch epd2in13_V2.py < epd2in13_v2_upside_down.patch
```

Ta-da!
