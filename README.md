# 古馬路口1號 Old Maruko 1 

古馬路口1號基於[思源黑體](https://github.com/adobe-fonts/source-han-sans)增加破碎與暈染效果。支援简体中文、繁體中文與日文；可以免費商用，歡迎大家自由應用、自由優化、自由改作！

古馬路口1號的特色是破碎與暈染效果。

![字體預覽](https://github.com/max32002/oldmaruko1/raw/main/preview/welcome.jpg)

### 字體後面的 SC,JP,TC是什意思？
* SC是 Simplified Chinese 简体中文，代表大陸習慣字形。
* TC是 Traditional Chinese 繁体中文，代表港台習慣的字形。
* JP是 Japanese 日文，代表日本習慣字形。
* 相同一個字，在不地區的書寫方式可能會略有不同。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

可以服用下面的css:
```
@font-face {
  font-family: OldMaruko1CJKjp-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/oldmaruko1@2.005/WebFont/CJKJP/OldMaruko1CJKjp-Regular.woff2) format("woff2");
}
```

## 已知問題

* 這不是一個專業的字型檔案。
* 很多字還是可以看到思源黑體的的直角。
* 希望有贊助者，或其他勇者繼續改良和調整很多怪怪的小細節。
* 由於小編對字體編碼方式完全不清楚，相較於原版的思源黑體，可能有掉一些符號或不常用的字。

## 附註

* 演算黑科技將思源黑體的Thin字重與ZenMaruGothic字體Light字重先做對映後, 使用 zi2zi 訓練 2 個 epoch, 在 google colab 上大約5分鐘可以取得, 然後再使用思源黑體的Reqular字重對這個checkpoint 產出的模型做推論(infer) 就可以取得古馬路口1號的Regular字重。
* 由於 jsdelivr 的 webfont 檔案大小的上限是 20MB, 為了要可以使用 webfont, 所以只留下一些常用字在-Lite 的檔名裡, webfont 是用 -Lite 的來產生 。


## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造Adobe和Google所開發、發表的「[思源黑體](https://github.com/adobe-fonts/source-han-sans)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

字體授權小提示：本字型採用 SIL Open Font License 1.1 授權發表，可以免費商用。在 github 上有附上 SIL Open Font License 1.1 的授權文件，如甲方或公司需要出示授權文件，直接使用此文件即可。
    
## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

簡體/繁體轉換家族：
* 獅尾簡腿黑體 Swei Jay Leg
https://max-everyday.com/2020/11/swei-jay-leg/
* 獅尾簡中黑體 Swei Jay Sans
https://max-everyday.com/2020/11/swei-jay-sans/
* 獅尾簡中宋體 Swei Jay Serif
https://max-everyday.com/2020/11/swei-jay-serif/
* 獅尾繁腿黑體 Swei Fan Leg
https://max-everyday.com/2020/11/swei-fan-leg/
* 獅尾繁中黑體 Swei Fan Sans
https://max-everyday.com/2020/11/swei-fan-sans/
* 獅尾繁中宋體 Swei Fan Serif
https://max-everyday.com/2020/11/swei-fan-serif/

獅尾黑體家族：
* 獅尾右下腿黑體 Swei Right Bottom Leg
https://max-everyday.com/2021/08/swei-right-bottom-leg/
* 獅尾右下圓黑體 Swei Right Bottom Sans
https://max-everyday.com/2021/08/swei-right-bottom-sans/
* 獅尾飛腿黑體 Swei Dart Leg
https://max-everyday.com/2020/11/swei-dart-leg/
* 獅尾飛鏢黑體 Swei Dart Sans
https://max-everyday.com/2020/11/swei-dart-sans/
* 獅尾火腿黑體 Swei Match Leg
https://max-everyday.com/2020/11/swei-match-leg/
* 獅尾火柴黑體 Swei Match Sans
https://max-everyday.com/2020/11/swei-match-sans/
* 獅尾骨腿黑體 Swei Bone Leg
https://max-everyday.com/2020/11/swei-bone-leg/
* 獅尾骨頭黑體 Swei Bone Sans
https://max-everyday.com/2020/11/swei-bone-sans/
* 獅尾斧腿黑體 Swei Ax Leg
https://max-everyday.com/2020/11/swei-ax-leg/
* 獅尾斧頭黑體 Swei Ax Sans
https://max-everyday.com/2020/11/swei-ax-sans/
* 獅尾喇腿黑體 Swei Bell Leg
https://max-everyday.com/2020/11/swei-bell-leg/
* 獅尾喇叭黑體 Swei Bell Sans
https://max-everyday.com/2020/11/swei-bell-sans/
* 獅尾惡腿黑體 Swei Devil Leg
https://max-everyday.com/2020/11/swei-devil-leg/
* 獅尾惡魔黑體 Swei Devil Sans
https://max-everyday.com/2020/11/swei-devil-sans/
* 獅尾麥腿黑體 Swei Marker Leg
https://max-everyday.com/2020/10/swei-marker-leg/
* 獅尾麥克黑體 Swei Marker Sans
https://max-everyday.com/2020/10/swei-marker-sans/
* 獅尾詠腿黑體 Swei Fist Leg
https://max-everyday.com/2020/10/swei-fist-leg/
* 獅尾詠春黑體 Swei Fist Sans
https://max-everyday.com/2020/10/swei-fist-sans/
* 獅尾鋸腿黑體 Swei Alias Leg
https://max-everyday.com/2020/10/swei-alias-leg/
* 獅尾鋸齒黑體 Swei Alias Sans
https://max-everyday.com/2020/10/swei-alias-sans/
* 獅尾尖腿黑體 Swei Spike Leg
https://max-everyday.com/2020/10/swei-spike-leg/
* 古馬路口1號 Swei Spike Sans
https://max-everyday.com/2020/10/swei-spike-sans/
* 獅尾快腿黑體 Swei Shear Leg
https://max-everyday.com/2020/09/swei-shear-leg/
* 獅尾快剪黑體 Swei Shear Sans
https://max-everyday.com/2020/09/swei-shear-sans/
* 獅尾福腿黑體 Swei Gospel Leg
https://max-everyday.com/2020/09/swei-gospel-leg/
* 獅尾福音黑體 Swei Gospel Sans
https://max-everyday.com/2020/09/swei-gospel-sans/
* 獅尾D滷腿黑體 Swei Del Luna Leg
https://max-everyday.com/2020/09/swei-del-luna-leg/
* 獅尾德魯納黑體 Swei Del Luna Sans
https://max-everyday.com/2020/09/swei-del-luna-sans/
* 獅尾彎腿黑體 Swei Curve Leg
https://max-everyday.com/2020/09/swei-curve-leg/
* 獅尾彎黑體 Swei Curve Sans
https://max-everyday.com/2020/09/swei-curve-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三腿黑體 Swei 3T Leg
https://max-everyday.com/2020/09/swei-3t-leg/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2加糖宋體 Swei B2 Sugar
https://max-everyday.com/2020/11/swei-b2-sugar/
* 獅尾加糖宋體 Swei Sugar
https://max-everyday.com/2020/11/swei-sugar/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 馬路口圓體 Maruko Gothic
https://max-everyday.com/2021/07/maruko-gothic/
* 苦累蛙圓體 Kurewa Gothic
https://max-everyday.com/2021/06/kurewa-gothic/
* 何某手寫體 Nani Font
https://max-everyday.com/2020/09/nanifont/
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇。

如果你想支持或打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
