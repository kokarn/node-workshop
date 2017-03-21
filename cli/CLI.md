# Build a CLI tool

To build a tool that packages a directory specified by an argument you need to do two parts.
Both parse the arguments and the build a zip file.

To parse arguments I'd recommend the [minimist](https://www.npmjs.com/package/minimist) package.

To build zipfiles there are a bunch of good options. Either [archiver](https://www.npmjs.com/package/archiver) or [yazl](https://www.npmjs.com/package/yazl) is what I'd use.

If you want to build more automated [commander](https://www.npmjs.com/package/commander) might be for you.
