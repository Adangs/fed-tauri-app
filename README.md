# Tauri + Vanilla

初始化一个使用`Tauri`打包的桌面端应用，也可以配合Vue等一起使用.

## 开发
```shell
yarn run tauri dev
```

## 发布
```shell
yarn run tauri build
```

### window 下的坑
1、`yarn run tauri dev` 或者 `yarn run tauri build` 的时候可能有很多包下载不成功，多执行几次就好了.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
