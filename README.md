# dotnet_BlazorHybrid2

## 概要
* 試行錯誤中
* 開発環境含め一式揃えたい
* ベース: [dotnet_BlazorHybrid](https://github.com/Tobotobo/dotnet_BlazorHybrid)

## 参考サイト
感謝！
* [ねこじょーかー/Blazor HybridとBlazor Web AppのUIをRCLで共通化する手順](https://blazor-master.com/blazor-hybrid-maui-rcl/)
* [nekojoker/BlazorHybrid](https://github.com/nekojoker/BlazorHybrid)
    > .NET MAUI Blazor アプリと Blazor Web App の Razor コンポーネントや静的資産を Razor クラスライブラリで共通化したプロジェクトです。  
    > .NET 8 に対応しています。

## 環境
```
> dotnet --info   
.NET SDK:
 Version:           8.0.204   
 Commit:            c338c7548c
 Workload version:  8.0.200-manifests.c4df6daf

ランタイム環境:
 OS Name:     Windows
 OS Version:  10.0.19045
 OS Platform: Windows
 RID:         win-x64
 Base Path:   C:\Program Files\dotnet\sdk\8.0.204\
```

## 詳細

```
dotnet run --project ./BlazorHybrid.Web
dotnet watch --project ./BlazorHybrid.Web
```
