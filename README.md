# regex

Regular expressions (POSIX Extended Regular Expressions, ERE). Supported: literals · anchors `^` `$` · character classes `[abc]` `[^abc]` `[a-z]` quantifiers `*` `+` `?` `{n}` `{n,m}` · grouping `(

This package is also bundled with the Quirk compiler at
`<QUIRK_HOME>/packages/regex/`, so `use regex` works out of the box on a
fresh install. This repo is the canonical home — when you want a version
newer than the one your compiler shipped with, install it explicitly:

```bash
quirk pkg install regex             # latest tag from this repo
quirk pkg install regex@1.0.0       # pinned
```

The compiler-shipped registry maps the bare name `regex` to this repo
(since v1.4.0), so no `quirk pkg registry add` is needed.

## Origin

Split from `quirk-compiler/packages/regex/` in compiler v1.5.0 as part of
the stdlib-in-independent-repos rollout. Source history before that lives
in [AlexVachon/quirk](https://github.com/AlexVachon/quirk).

## License

MIT (see [`LICENSE`](LICENSE)).
