# Sparse checkouts

- Clone repo with `--spare` flag

```bash
git clone --filter=blob:none --sparse https://github.com/GoGoPenguin/sparse-checkout
cd sparse-checkout
```

- Init cone mode

```bash
git sparse-checkout init --cone
```

- Spare checkout

```bash
git sparse-checkout set $DIRECTORY
```
