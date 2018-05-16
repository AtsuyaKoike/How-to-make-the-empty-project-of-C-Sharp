# How to make the empty project of C-Sharp
今のVisualStudioは機能が多く、根本からC#を学習しようとすると環境構築から躓くので、まとめました

## 「Visual Studio Community 2017」をダウンロード
https://www.visualstudio.com/ja/downloads/

## Vsiual Stduio Community 2017を立ち上げる
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup1.png)
インストール後、起動するとこのような画面がでてきます。<br>
左上のファイルをクリックします。<br>
ファイル＞新規作成＞プロジェクトをクリックする次の画面が出てきます。<br>
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup2.png)
そして左のメニューの<br>
インストール済み＞Visual C#＞Windows クラシック デスクトップ<br>
を選択。<br>
そして「空のプロジェクト(.NET Framework) Visual C#<br>
を選択します。<br>
<br>
今回は名前をnyumonにしてみました。<br>
<br>
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup3.png)
このような画面になっているはずです。<br>
そして右側のメニューのnyumonを右クリして<br>
nyumon＞追加＞新しい項目<br>
を選択します。<br>
<br>
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup4.png)
左のメニューはデフォルトで「Visual C# アイテム」になっているはずです。そのまま中央のメニューから「クラス Visual Studio アイテム」を選択します。<br>
<br>
これで設定は完了です。<br>
public Class1()のコードブロックにプログラムを書いていくことができます。<br>
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup5.png)
<br>
以上で完了です。<br>
<br>
# Hello, World 
せっかくなので、Hello, Worldのプログラムを載せておきます。
```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace nyumon
{
    class Class1
    {
        static void Main()
        {
            Console.WriteLine("Hello, world!"); 
        }
    }
}
```
Ctrl+F5で実行することができます。<br>
![](https://github.com/AtsuyaKoike/How-to-make-the-empty-project-of-C-Sharp/blob/master/cshapsetup6.png)
