# Rust TextMate Bundle

A TextMate Bundle for the Rust programming langauage.


## Installation

```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone git://github.com/elia/rust.tmbundle.git
```

### Update

```bash
cd ~/Library/Application\ Support/Avian/Bundles/avian-missing.tmbundle
git pull git://github.com/elia/rust.tmbundle.git master
```


## Current Features:

- Basic Syntax Highlighting
- Command to compile (using: rustc source.rs) (cmd+shift+c)
- Command to compile with tests (using: rustc --test source.rs) (cmd+shift+a)
- Run command. Runs compiled Rust file. If file hasn't been compiled it will compile it first. (cmd+r)
- Code Snippets
- Supports both .rs and .rc file formats (Rust and Rust Crates)

## Future Features:

- Improved Syntax Highlighting

## Installation

- Download either the zip or tar
- Unzip
- Rename SUB folder Rust_tmbundle to Rust.tmbundle
- Double click above folder (installs in TextMate)
- Enjoy




## License

This bundle is licensed under the MIT License (LICENSE).

Copyright (c) 2012 [Tom Ellis](http://www.webmuse.co.uk/)
Copyright (c) 2014 [Elia Schito](http://elia.schito.me/)
