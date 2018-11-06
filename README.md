# TabNine

This is the repository for the backend of [TabNine](https://tabnine.com), the all-language autocompleter.
There are no source files here because the backend is closed source.

You can make feature requests by filing an issue. You are also welcome to make pull requests for changes to the configuration files.

`languages.yml` determines which file extensions are considered part of the same language. (For example, identifiers from `.c` files will be suggested in `.h` files.)

`language_tokenization.json` determines how languages are tokenized. For example, identifiers can contain dashes in Lisp, but not in Java.

If your feature request is specific to a particular editor's TabNine client, please file an issue in one of these repositories:

- [VS Code](https://github.com/zxqfl/tabnine-vscode)
- [Sublime Text](https://github.com/zxqfl/tabnine-sublime)
- [Vim](https://github.com/zxqfl/tabnine-vim)
- [Atom](https://github.com/zxqfl/tabnine-atom)
