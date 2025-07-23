# optional-packages

A collection of [NPM](https://npmjs.com/) packages that are all empty or otherwise optional. There are two types of packages in this collection:

  1. **Empty packages**: Like `empty-pkg`, `minimal-pkg`, as well as `optional-pkg`, they are indeed completely empty / minimal and
  2. **Failing packages**: So packages that are not only empty, but also fail to install, like `failing-pkg`.

*Why the frick*, you ask? Well *great question*! Let me loop you into the science behind empty packages: **They should be minimal.** I needed a minimal empty / dummy package to cheat Yarn (see [`yarn-plugin-optional-resolution`](https://github.com/kristian/yarn-plugin-optional-resolution)) and I didn't want to risk referring to a package that could be potentially malicious, or contains more than it should. This is why I created the `optional-packages` package collection. Neat, isn't it?

## Author

Written by [Kristian Kraljić](https://kra.lc/).

## Found a Bug?

I am just asking you this: ***How?!*** These packages are literally empty! If you think you found a bug, please file an issue [on Github](https://github.com/kristian/optional-packages). *I am curious!*

PS: Please do not report that the `failing-pkg` fails to install, that is the whole point... dummy. ;)
PPS: Why is there no [`README.md`](README.md) on NPM? Well, the packages had to stay *minimal* that was the whole premise. ;) If I had included a `README.md` into the tarball, would you still consider it minimal?

## License

All packages are licensed under the [MIT](LICENSE) license.
