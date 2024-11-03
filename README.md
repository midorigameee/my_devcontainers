# my_devcontainers

このリポジトリには各種用途に合わせたdevcontaierファイルを格納する。

そのdevcontainer内でプロジェクトを作成する場合は、以下の.gitignoreファイルを作成して、このリポジトリ自体には登録しないようにする。

```
# すべてのファイルとフォルダを無視
/*

# .gitignoreで無視しないようにする
!.gitignore

# .devcontainerフォルダを無視しない
!/.devcontainer
```