# asdf-ant

[Ant](http://ant.apache.org/)
plugin for the [asdf version manager](https://github.com/asdf-vm/asdf)

## Requirements

### MacOS

* [GNU Core Utils](http://www.gnu.org/software/coreutils/coreutils.html) - `brew install coreutils`

### Linux (Debian)

* [GNU Core Utils](http://www.gnu.org/software/coreutils/coreutils.html) - `apt install coreutils`
* [curl](https://curl.haxx.se) - `apt install curl`

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add ant https://github.com/jackboespflug/asdf-ant.git
```

and install new versions like this:

```bash
asdf install ant 1.10.9
```

and switch versions like this:

```bash
asdf global ant 1.10.8
```

## Reading

Read the [asdf readme](https://github.com/asdf-vm/asdf)
for instructions on how to install and manage versions of any language.

## Development

* asdf's [creating-plugins.md](https://github.com/asdf-vm/asdf/blob/master/docs/creating-plugins.md)

## Contributing

Feel free to create an issue or pull request if you find a bug.

## Issues

* Assumes Linux, FreeBSD, or Mac

## License

MIT License
