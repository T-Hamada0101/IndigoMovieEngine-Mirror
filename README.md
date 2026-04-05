# IndigoMovieEngine-Mirror
このリポジトリは、IndigoMovieEngine の公開ミラー用 elease asset 置き場です。
## 重要
- このリポジトリは sset-only mirror として運用します。
- 実ソースコードはこのリポジトリで公開しません。
- GitHub の Source code (zip/tar.gz) は GitHub が自動生成する仕組みであり、README.md のような説明ファイルだけを含む場合があります。
- ただし、IndigoMovieEngine の実ソースコードは含みません。
## 目的
- Public 側 workflow が参照する公開 elease asset を置く
- INDIGO_ENGINE_REPO_TOKEN なしで github-release-package を実行できるようにする
## 想定する配置物
- IndigoMovieManager.Thumbnail.RescueWorker-<tag>-win-x64-compat-*.zip
- IndigoMovieEngine.Thumbnail.Contracts.<version>.nupkg
- IndigoMovieEngine.Thumbnail.Engine.<version>.nupkg
- IndigoMovieEngine.Thumbnail.FailureDb.<version>.nupkg
- private-engine-packages-manifest.json（任意）
## FFmpeg について
- 本ミラーで公開する配布物には、LGPL ライセンスの FFmpeg 共有ライブラリを動的リンク構成で含む場合があります。
- FFmpeg 公式サイト: https://ffmpeg.org/