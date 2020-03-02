# rime-hapanese

## About

This is a layout for typing in a Japanese.


## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-japanese` using plum:

```bash
bash rime-install gkovacs/rime-japanese
```

Finally edit `default.custom.yaml` and add `rime_japanese` to the schema list:

```bash
patch:
  schema_list:
    - schema: rime_japanese
```

Now reload RIME and it should appear under your layouts.
