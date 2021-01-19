# M'Orange Lottery 2021

M'Orange 於 2021/01/22 的尾牙抽獎裝置，使用 Arduino UNO + Webduino Fly 搭配 RFID-RC522 模組，於扭蛋球中放入 RFID 感應扣，參加抽獎者從扭蛋機中轉出扭蛋後，將球放置於感應器上方進行感應，即可於投影畫面上得知抽中的獎項。

---
## 變數說明

awards (陣列，獎項清單)
```
var awards = [
    {
        id: 'F98BAEB9',                      // RFID 感應扣 ID
        name: 'Dyson 二合一智慧涼風空氣清淨機',  // 獎項名稱
        type: '特獎'                          // 獎項等級
    }
    // ... (以下省略)
]
```
deviceID (字串，裝置 ID)

---
## 其他備註
(暫無)