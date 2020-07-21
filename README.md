# FBsharer

不須串接API即可快速使用的Facebook分享套件
    1. 如果分享網址非當前頁面,則圖片優先使用分享網址中設定的meta og:image,若分享網址無設定才使用當前頁面的meta og:image
    2. og:image 最小需 200 * 200px 以上才可生效
    3. og:image 不可超過 8MB
    4. og:image 必須使用絕對路徑(完整的圖片網址)
    5. og:image 的圖片檔案格式需與 og:image:type 所填寫的格式對應,建議使用jpeg
    6. 1200 * 630px 以上的圖片可以獲得最佳顯示效果, 600 * 315px 以上的圖片可以有較大的縮圖顯示
    7. 每當修改頁面後,使用 https://developers.facebook.com/tools/debug/sharing/ 此工具來偵錯,並且點擊【 再次抓取 】,一定要點才能刷新快取,才能使最新設定生效
    8.範例中的屬性皆為必填,若有缺少則可能無法生效
    9.將FB分享的<a>中的網址 ?u= 後面接上需要分享的網址即可, 例如: ?u=https://www.google.com.tw/
