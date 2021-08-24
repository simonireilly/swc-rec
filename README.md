# .<filename> fails directory compile

## Testing

```bash
yarn swc src -d dist/pass

tree dist

dist
└── pass
    └── utils
        └── example.js


yarn swc .src -d dist/fail

tree dist

dist
└── pass
    └── utils
        └── example.js

```
