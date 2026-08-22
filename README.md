# AA時計 / A Clock For You — サポートとプライバシーポリシー

iPhone 向け時計アプリ **AA時計（A Clock For You）** の公開ページ。
GitHub Pages で配信し、App Store Connect の Support URL / Privacy Policy URL に登録している。

| ファイル | 公開 URL | App Store Connect での用途 |
| --- | --- | --- |
| `index.html` | https://get2437.github.io/aa-clock/ | Support URL |
| `privacy.html` | https://get2437.github.io/aa-clock/privacy.html | Privacy Policy URL |

## 編集するときの注意

- **CSS は各 HTML に直接埋め込んである**（外部ファイルにすると 404 で崩れる事故があるため）。
  片方だけ直すと見た目がずれるので、スタイルを変えるときは 2 ファイルとも直すこと
- 内容の正本はアプリ側リポジトリの `AppStore/privacy-policy.md` と `AppStore/support.md`。
  **文言を変えたら両方を直す**（片方だけ直すとずれる）
- 外部リソース（フォント・CDN・解析タグ）は一切読み込まない方針
