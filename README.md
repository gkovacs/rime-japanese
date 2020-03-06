# rime-japanese

## About

This is a layout for typing in Japanese 日本語. Supports words in all 3 scripts (Kanji, Hiragana, Katakana).


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

Finally edit `default.custom.yaml` and add `japanese` to the schema list:

```bash
patch:
  schema_list:
    - schema: japanese
```

Now reload RIME and it should appear under your layouts.
