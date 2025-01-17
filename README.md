# WPFBlazorAppTemplate
WPF Blazor アプリ を作成するためのテンプレート

## 使用法

### テンプレートの取得
[WPFBlazorApp.nupkg](https://github.com/kznagamori/WPFBlazorAppTemplate/releases/download/v1.0.0/kznagamori.WPFBlazorApp.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.WPFBlazorApp.1.0.0.nupkg
```

### WPF Blazor アプリプロジェクトの作成
```
dotnet new wpf-blazor.app -n <プロジェクト名>
```
**例:** `dotnet new wpf-blazor -n MyWpfBlazor`

### テンプレートのアンインストール
```
dotnet new uninstall kznagamori.WPFBlazorApp
```

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

### 実行

`dotnet run` で実行すると以下の画面が表示されます。

![image-20240826174100185](assets/image-20240826174100185.png)



### kznagamori.WPFBlazorApp.X.X.X.nupkgの作成

```
nuget pack .\WPFBlazorAppTemplate.nuspec
```

