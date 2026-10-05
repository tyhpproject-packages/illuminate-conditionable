<!-- tyhp-readme:start -->
# tyhpdef/illuminate-conditionable

Tyhp type definitions for `illuminate/conditionable` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-conditionable:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-conditionable-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-conditionable-impl`.

See https://tyhplang.com.

## Maintain `illuminate/conditionable`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/conditionable`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-conditionable-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/conditionable` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-conditionable": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/conditionable` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/conditionable` with a real constraint,
   `"replace": { "tyhpdef/illuminate-conditionable": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/conditionable` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-conditionable` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
