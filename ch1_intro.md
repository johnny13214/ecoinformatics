# R 的介紹

## 為什麼要使用 R?

現在市面上有許多商業的專業統計軟體，例如 SAS、SPSS、Statistica 等，為什麼我要介紹各位使用 R?你可能會問,我這些資料很簡單,用 Microsoft Excel 做統計分析或 SPSS 按一按就好了，報表也都能漂亮地印出來,為什麼還要再多花心思去學一 套新的軟體?因為 R 是:

1. 百分之百自由軟體 (free software)，這意味著你可以自由取得、複製及散佈
2. 開放原始碼，R 的原始碼是公開的，你可以閱讀甚至修改
3. 龐大的使用者社群,因為自由軟體的特性,所以全世界有許多人貢獻他們的心力與 程式碼,所以許多新的統計方法可以很快就有 R 套件的支援
4. 跨平台 (cross-platform),不管你是使用 Windows, GNU/Linux, Mac OS 甚至是 FreeBSD,都可以執行 R 程式
5. 易於開發套件，你可以使用 C 或是 FORTRAN 語言開發延伸套件
6. 整合性高，可使用諸如 bash, python (rpy2) 或是 perl (RSPerl) 等語言呼叫 R 物件寫作
7. 高品質的圖形與表格排版輸出

## 安裝R
在這個章節中,我不打算花太多的篇幅講 R 的安裝,都是重點提示，詳細的安裝說明請至 R 的網站上閱讀。R 的下載網址為 http://www.r-project.org 現在的 GNU/Linux 作業系統通常都會有套件管理程式,你可以直接從該套件管理 程式安裝 R 程式，下面以 Debian/Ubuntu 的 apt 套件管理程式為例，示範如何安裝:
終端機底下安裝 R 主程式(或是你可以從圖形化的套件管理程式來安裝)

```shell
# apt-get install r-base
```

在 Windows 作業系統中安裝 R 程式只需要下載執行檔 R-版本號碼.exe,並按照步驟安裝即可。
￼￼