# buckaroo-github-example

This is an example of a [Buckaroo](https://buckaroo.pm) package hosted directly on GitHub. More information can be found in [the docs](http://buckaroo.readthedocs.io/en/latest/github-package-guide.html). 

This package is a library containing a single function: 

```
int sum(int x, int y) {
  return x + y;
}
```

Here are the important files: 

 * `.buckconfig` - Marks this project as a [Buck](https://www.buckbuild.com) project
 * `BUCK` - The build script for the library
 * `buckaroo.json` - Metadata used by Buckaroo

To install this package in another project using Buckaroo: 

```
buckaroo install github+njlr/buckaroo-github-example
```

Buckaroo will read the release tags of the repository. 

To create a new release, just use the [GitHub web UI](https://github.com/njlr/buckaroo-github-example/releases). 
