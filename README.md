# EKPlates

* 數字模式與條形模式
* 自定義光環顯示白名單
* 自定義能量監控白名單
* 自定義名字染色白名單
* 目標、指向、焦點高亮
* **無遊戲內設定介面**
* **只顯示血量百分比**
* **無法在地城內顯示友方名條**
* **所有的改動都要編輯Config.lua，推薦使用Notepad++**
* 數字模式
    * 可選條形或圖示施法條
    * 圖示施法條：可打斷灰色邊框，不可打斷紫色邊框
    * 滿血時只顯示名字
    * 名字左方團隊標記，右方能量監控，下方施法條，上方光環
* 條型模式：普通的名條

## 簡單寫一下FAQ：

1.設定指令是什麼？

這個插件沒有遊戲內設定指令，沒有遊戲內選項，沒有遊戲內的圖形化介面(GUI)控制台，將來也不會有。所有的改動都要編輯Config.lua，如果要求高度自定義，那就自己改ekplates.lua吧。如果不願意，那這個插件不適合你，去用knp或tptp吧。

2.怎麼顯示血量啊

因為一堆人要豐富的設定卻又跑來ekplates，所以我把話放這裡了：**ekp是以簡潔美觀為主旨的名條插件，顯示等級的PR都是別人加的，而且主打數字模式；條型模式也不打算顯示血量百分比以外的數值。要不自己魔改，要不摸摸鼻子認命改變自己的思維和習慣，什麼東西都附上一堆資訊是很沒有意義的事情。**

喔對了，用了魔改版如果出了什麼問題別來找我～關老子屁事。

## 關於EKPlates

Dawn是個神人，也曾經很高產，但軍團入侵時我真的以為他不更新了，於是有了這個。現在Infinity Plates仍在，而且代碼一如既往地精簡強大。

數字模式用了超過五年，以後大概也會一直用下去；本插件不提供售後，條形模式的bug修復也永遠不是最優先。

## license: All Rights Reserved

目前沒有寫License，計劃跟ekminimap release一起完成，所以先使用All Rights Reserved，我去（消音）的多玩魔盒

## 更新紀錄

* R2.1a
    * 修正條形模式的玩家名條錯誤顯示不該顯示的名字的問題
    * 調整條形模式的高亮層級至陰影之後
    * 調整條形模式的名字與光環布局
* R2.1
    * 更正不規範的寫法
    * 滿等後，隱藏同等級(120)的等級數字
    * 修正條形模式的高亮錯誤
* R2.0
    * 刪除legion白名單
    * 重做高亮功能，現在可以高亮目標、焦點和滑鼠游標指向的目標
    * 名條的預設大小現在和暴雪預設的數值一樣了
    * 名條的貼邊距離微調
    * 將美化陰影正確套用在數字模式的條形施法條上
    * to do: 激勵改為層數疊加
    * 火爆詞綴的小球染色改為亮青色
* R1.9a
    * fix toc. emmm....
* R1.9
    * bump toc
    * 刪除legion相容性
    * 將新的感染詞綴加入法術白名單
    * 將的感染詞綴小怪加入怪物染色白名單：黃色
    * 將神廟一王加入能量白名單
* B1.8
    * for bfa test: 相容live735和beta801
* R1.7a  
    * 將泰夏拉克燼火加入能量白名單  
* R1.7  
    * bump toc  
    * T21 Spell  
* R1.6  
    * 更新cvar和inset選項  
    * 數字模式的個人資源現在總是在非隱藏狀態時顯示血量，不論是否滿血  
    * 整理排版  
    * 修正條形模式光環圖示的錨點  
    * 補充幾個控場法術  
* R1.5  
    * 增加四個CVAR  
    * 數字模式的法力值改成百分比而非數值  
* R1.4  
    * 針對7.2.5 PTR的更新。暴雪超無聊，更名爆破副資源  
* R1.3a  
    * 快速修復：條形樣式的名字錯位。是的，我又不小心搞爆它了  
* R1.3  
    * 試著修復載具問題  
    * 幹掉boss mod，保留友方只顯示名字的功能，但只在副本外生效  
    * 因為某些連遊戲介面選項都不看的（逼）太煩了，強制開啟敵方守護者和僕從名條  
    * 加入m+易爆小球特殊染色：黃色
    * 修復數字模式的個人資源會以百分比顯示的問題  
    * 現在可以單獨設定名條的最大顯示距離，預設45  
    * 數字模式現在有施法「條」的選項了  
    * 整理config註解  
* R1.2  
    * 加入點擊穿透選項  
    * 幹掉友方非玩家名條，但是除了NPC以外，這些CVAR本來應該由用戶自己去開關，所以敵方的你們自己處理吧  
    * 光環可以調整字體了  
    * 試著幹掉dbm nameplate  
    * 待修復: 載具bug  
* R1.1  
    * 修復增加隱藏姓名選項時捅的漏子會導致記憶體爆炸的問題  
    * 強制套用修復掉幀的CVAR  
    * 整理Config註解  
* R1  
    * 噱頭：第一個release  
