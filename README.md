# rime-nihongo-hybrid

## About

This is a layout for typing in a Japanese.


## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-nihongo-hybrid` using plum:

```bash
bash rime-install gkovacs/rime-nihongo-hybrid
```

Finally edit `default.custom.yaml` and add `rime_nihongo_hybrid` to the schema list:

```bash
patch:
  schema_list:
    - schema: rime_nihongo_hybrid
```

Now reload RIME and it should appear under your layouts.
