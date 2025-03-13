<p align="center">
    <img src="./assets/logo.png" />
</p>

# 🦉 [beta.blog.momee.mt](https://beta.blog.momee.mt/)

- [blog.momee.mt](https://blog.momee.mt)のテスト環境
- [Ravenlog](https://github.com/brack-lang/ravenlog)の動作や変更を確かめるのにも使います

## 執筆環境

### Nix
nix-direnvを利用している場合には、以下のコマンドを実行すればプロジェクトルートに移動すれば執筆環境の準備は終了です。

```
echo "use flake" > .envrc
direnv allow
```

そうでない場合は、以下のコマンドを実行してください。ただし、Nix Flakesを利用できる必要があります。

```
nix develop .
```

### 手動インストール
以下の2つのソフトウェアに依存しています。

- [Brack](https://github.com/brack-lang/brack)
- [Ravenlog](https://github.com/brack-lang/ravenlog)

## LICENSE
このリポジトリは、以下のようにライセンスされています。

- `docs/**`
    - CC-BY-4.0でライセンスされています
- `assets/**`
    - **All rights reserved**
    - 画像ファイルの再利用は認められません
- `assets/**`を除いたファイル
    - Apache-2.0でライセンスされています
