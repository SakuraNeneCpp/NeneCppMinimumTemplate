# NeneCppMinimumTemplate
C++ Minimum Cookiecutter Template

## フォルダ構成
```txt
{{cookiecutter.project_slug}}/
    main.cpp
    .gitignore
    CMakeLists.txt
    README.md
```

## cookiecutter.json
```json
{
    "project_name": "NeneCppMinimumApp",
    "project_slug": "{{ cookiecutter.project_name | lower | replace(' ', '_') | replace('-', '_') }}"
}
```