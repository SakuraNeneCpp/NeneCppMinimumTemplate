# {{cookiecutter.project_name}}

## コマンド一覧

### CMake初期化
```sh
cmake -S . -B build
```

### ビルド
```sh
cmake --build build
```

### 実行
```sh
./build/Debug/{{cookiecutter.project_slug}}
```

### クリーン
```sh
rm -rf build
```