# Cobbler 中文文件
> Important: This document is a translated document, not offical document. If you need offical document, you can click [here](http://cobbler.github.io/).  
> 注意：這個文件是一個隨手翻譯的中文文件，並非官方文件。如果你想看官方文件，你可以點[這裡](http://cobbler.github.io/)！

## 什麼是 Cobbler
Cobbler 是一個 Linux 安裝伺服器，Cobbler 讓您可以快速建立一個網路安裝環境。Cobbler 結合並自動化許多相關的 Linux 任務，因此您不需要在部署新系統或調整現有系統時，在各種指令和應用程式中來回操作。Cobbler 也可以協助您管理 DNS 和 DHCP、套件管理、電源管理、設定管理編排等等。

## Cobbler 如何幫助您
自動化是速度、一致性和重複性的關鍵，無論是少數幾個伺服器或上千個伺服器組成的架構，這些屬性對於管理這些架構是相當重要的。Cobbler 可以協助透過自動化從裸機配置伺服器的流程或從虛擬機器部署到各式管理程序上。

## 重複利用...
正如設定管理系統依賴模板來簡化更新一樣，Cobbler 也是如此。 模板廣泛用於管理DNS和DHCP等服務，各個分支（例如：kickstart、preseed等等）的響應文件都模板化的，以達到最大的程式碼重複使用。
除了模板，Cobbler 依賴於一個模板本身一小部分的程式碼，讓它可以嵌入到其他模板中。這允許了管理員只要寫一次，就可以在任何想要使用的地方透過一個簡單的include來引入，只需要在一個地方進行管理。

## 誰在使用 Cobbler？
這些只是數百家公司、大學和政府機構的一小部分，他們每天都依賴 Cobbler 來建置自己的基礎設備。  
[看看名單](http://cobbler.github.io/users.html)

## 讓我們開始吧！
- [快速開始手冊](quickstart.md)
- [完整操作手冊](manual/index.md)
- [開發人員手冊](developer.md)
