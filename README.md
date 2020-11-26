# leveldown-nodejs-mobile

Fork of [leveldown](https://github.com/Level/leveldown) that is committed to support [nodejs-mobile](https://github.com/janeasystems/nodejs-mobile) because leveldown [not necessarily supports](https://github.com/Level/leveldown/issues/575) it.

## Supports

- Version 5.4.1, 5.1.1
- Android
- iOS

## Diff

The changes made from leveldown to leveldown-nodejs-mobile are:

- Using `bindings` instead of `node-gyp-build` to load the native bindings

## Versioning

We will follow the convention of having the same SemVer code as the official leveldown, but with a suffix `-X` (where `X` is a number). For instance, `leveldown-nodejs-mobile@5.1.1-3` is the `3`rd version of this library that is equivalent to `leveldown@5.1.1`.

## License

[MIT](LICENSE.md) © 2012-present Rod Vagg and [Contributors](CONTRIBUTORS.md).

_`leveldown` builds on the excellent work of the LevelDB and Snappy teams from Google and additional contributors. LevelDB and Snappy are both issued under the [New BSD License](http://opensource.org/licenses/BSD-3-Clause). A large portion of `leveldown` Windows support comes from the [Windows LevelDB port](http://code.google.com/r/kkowalczyk-leveldb/) (archived) by [Krzysztof Kowalczyk](http://blog.kowalczyk.info/) ([`@kjk`](https://twitter.com/kjk)). If you're using `leveldown` on Windows, you should give him your thanks!_
