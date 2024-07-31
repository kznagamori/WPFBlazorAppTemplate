# WpfBlazorAppTemplate
WPF Blazorアプリを作成するためのテンプレート

## 使用法

### テンプレートの取得

`https://github.com/kznagamori/WpfBlazorAppTemplate.git`をダウンロードして、任意のディレクトリに展開します。

### テンプレートのインストール

`dotnet new install .\WpfBlazorAppTemplate`

### WPF Blazorアプリプロジェクトの作成

`dotnet new wpf-blazor -n <プロジェクト名>`

**例:** `dotnet new wpf-blazor -n MyWpfBlazor`

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### リリースビルド

```
dotnet publish -c Release
```

