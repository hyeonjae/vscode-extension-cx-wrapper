# cx wrapper README

Wrap selected word with `cx()`.

```
'hello'
=>
cx('hello')
```

## Features

Multiple selections of words are all wrapped with `cx()`.

```
'hello', 'world'
=>
cx('hello'), cx('world')
```

In case the word is wrapped with `cx()` already, cx wrapper removes it.

```
'hello', cx('world')
=>
cx('hello'), 'world'
```

## Release Notes

### 0.0.1 (2018/07/25)

Initial release

-----------------------------------------------------------------------------------------------------------

## For more information

* [hyeonjae/vscode-extension-cx-wrapper](https://github.com/hyeonjae/vscode-extension-cx-wrapper)

**Enjoy!**
