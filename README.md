# Laravel 10 提供依據時區 Laracon 線上研討會時程的命令列工具

引入 nunomaduro 的 laracon-schedule 套件來擴增提供依據時區 Laracon 線上研討會時程的命令列工具，該年度研討會聚集了許多充滿幹勁與熱情的各路英雄好漢使用 Laravel 網站框架建構功能強大的應用程式分享實戰經驗，提供第一手的 Laravel 資訊並分享極致效能的議題，千萬別錯過這些高手們交流的機會。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __laracon-schedule__ 指令來取得依據時區 Laracon 線上研討會時程。
```sh
$ laracon-schedule
```

----

## 畫面截圖
![](https://i.imgur.com/oZQFrK0.png)
> 透過高手們的經驗分享，讓我們更能掌握未來的脈絡
