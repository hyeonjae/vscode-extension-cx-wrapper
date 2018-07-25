# cx wrapper README

선택한 단어에 cx()로 감쌉니다.

```
'hello'
=>
cx('hello')
```

## Features

여러 단어가 선택된 경우 모두 cx()로 감쌉니다.

```
'hello', 'world'
=>
cx('hello'), cx('world')
```

이미 cx()로 감싸여진 단어는 cx()를 제거합니다.

```
'hello', cx('world')
=>
cx('hello'), 'world'
```

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

Initial release

-----------------------------------------------------------------------------------------------------------

### For more information

* [hyeonjae/vscode-extension-cx-wrapper](https://github.com/hyeonjae/vscode-extension-cx-wrapper)

**Enjoy!**
