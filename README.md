# Homebrew tap for maclean

maclean CLI 的 Homebrew 安装入口。

## 安装

```sh
brew tap jamesfeng2009/maclean
brew install maclean
```

或一步到位：

```sh
brew install jamesfeng2009/maclean/maclean
```

## 升级

```sh
brew upgrade maclean
```

## 说明

- formula 从 GitHub 源码 tarball 构建（`cargo install --locked --path apps/maclean-cli`），不依赖预编译二进制。
- `version` / `sha256` 由 maclean 仓库的
  [`.github/workflows/update-homebrew-tap.yml`](https://github.com/jamesfeng2009/maclean/blob/main/.github/workflows/update-homebrew-tap.yml)
  在 Release 发布后自动回填（需配置 `MACLEAN_HOMEBREW_TOKEN`）。
- maclean CLI 永久免费（Apache-2.0）；GUI App（14 天试用 / 付费）在私有 maclean-pro 仓库分发，不在本 tap 内。
