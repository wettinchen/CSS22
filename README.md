## Chapter 22: Animations
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 資源
https://github.com/gitdagray/css_course

### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept outline
###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Menu Preview
        預習 / 預覽

###  4. Starter Code
        初始設定說明

###  5. Using Pseudo-Class Selectors
        修改 第一個 div 背景為 dodgerblue，
        第二個 div 背景為黃色，
        最後一個 div 背景為萊姆綠

###  6. transform: translate
        (1)設定第一個 div 朝 X 軸移動右移 50%
        (2)設定第一個 div 朝 X 軸移動左移 50%
        (3)設定第二個 div 朝 Y 軸移動下移 2rem
        (4)設定第二個 div 朝 Y 軸移動上移 2rem
        (5)設定最後一個 div 朝 X 軸移動右移 100%，
        朝 Y 軸移動上移 2rem
        (6)設定最後一個 div 朝 X 軸移動右移 100%
        (7)設定最後一個 div 朝 X 軸移動右移 100%，
        朝 Y 軸移動上移 5rem

###  7. transform: rotate
        (1)設定第一個 div 沿著 X 軸旋轉 180 度，圖片會由上面翻至下面
        (2)設定第一個 div 沿著 X 軸旋轉 45 度
        (3)設定第二個 div 沿著 Y 軸旋轉 45 度
        (4)設定第二個 div 沿著 Y 軸旋轉 180 度，圖片會由左面翻至右面
        (5)設定最後一個 div 沿著 Z 軸旋轉 90 度，圖片會順時針旋轉 90 度
        (6)設定最後一個 div 沿著 Z 軸旋轉 180 度，圖片會順時針旋轉 180 度
        (7)設定最後一個 div 沿著 Z 軸旋轉 45 度，圖片會順時針旋轉 45 度
        (8)設定最後一個 div 圖片順時針旋轉 45 度
        (9)設定最後一個 div 圖片順時針旋轉 135 度
        (10)設定最後一個 div 圖片順時針旋轉 78 度

###  8. transform: scale
        (1)設定第一個 div 的 X 軸長變為 120%，左右增加 20%
        (2)設定第二個 div 的 Y 軸長變為 120%，上下增加 20%
        (3)設定第三個 div 的 X 軸和 Y 軸長變為 50%，上下和左右各減少 50%

###  9. transform: skew
        (1)設定第一個 div 沿著 X 軸向右歪斜 10 度
        (2)設定第二個 div 沿著 Y 軸向下歪斜 10 度
        (3)設定第三個 div 沿著 X 軸向右歪斜 10 度，沿著 Y 軸向上歪斜 10 度

### 10. Find more values
        transform - CSS: Cascading Style Sheets | MDN
        https://developer.mozilla.org/en-US/docs/Web/CSS/transform

### 11. CSS Transitions
        (1)設定懸停在 div 時，轉換屬性為午夜藍背景色，持續時間為 2 秒，延遲時間為 0.5 秒
        (2)懸停在 div 時，修改持續時間為 2 至 3 秒；並且懸停在第三個 div 會旋轉 180 度。
        (3)使用 transition 縮寫取代transition-property, transition-duration, transition-delay
        (4)設定 transition-timing-function 為 ease
        (5)移除 transition-timing-function，修改 transition 為 all 2s ease 0.5s
        (6)設定 transition-timing-function 為 linear
        (7)移除 transition-timing-function，修改 transition 為 all 2s linear 0.5s
        (8)修改 transition 為 all 2s ease-in-out 0.5s
        (9)修改 transition 為 all 2s 0.5s
        
### 12. CSS Animations
        (1)在 .animate 動畫名稱為 slide，持續時間為 5 秒，
        animation-timing-function 為 ease-in-out，延遲時間為 1 秒，播放次數 5 次
        (2)在 @keyframes slide 的 0% 選擇器中，將 transform 設置爲 translateX(0)；
        在 33% 選擇器中，將 transform 設置爲 translateX(600px) rotate(180deg)；
        在 66% 選擇器中，將 transform 設置爲 translateX(-600px) rotate(-180deg)；
        在 100% 選擇器中，將 transform 設置爲 translateX(0)，背景色最後改為 rebeccapurple；
        (3)在 @keyframes slide 的 33% 選擇器中，
        修改 transform 設置爲 translateX(300px) rotate(180deg)；
        在 66% 選擇器中，transform 設置爲 translateX(-300px) rotate(-180deg)；
        (4)設定 .animate 的 animation-direction 為 normal
        (5)修改 animation-direction 為 alternate
        (6)修改 animation-direction 為 alternate-reverse
        (7)修改 animation-direction 為 reverse
        (8)設定 .animate 的 animation-fill-mode 為 forwards
        (9)設定 .animate 的 animation-fill-mode 為 backwards
        (10)設定 .animate 的 animation-fill-mode 為 both
        (11)修改 animation-direction 為 alternate，animation-fill-mode 為 forwards
        (12)修改 animation-iteration-count 為 2
        (13)修改 animation-direction 為 normal
        (14)使用 animate 縮寫取代 animation-direction, animation-timing-function, animation delay, animation-iteration-count, animation-direction, animation-fill-mode, animation-name

### 13. Navbar Starter Code
        說明 menu.html 和 menu.css

### 14. Build the Hamburger Menu Icon
        (1)設定 .header-title-line 的 padding 為 0.25rem 0.5rem，display 為 flex，flex-flow 為 row nowrap，justify-content 為 space-between
        (2)設定 .menu-button 為 background-color 為 transparent，border 為 none，寬度和高度為 48px
        (3)設定 display 為 flex，justify-content 為 center，align-items 為 center，position 為 relative
        (4)設定 .menu-icon, .menu-icon::before, .menu-icon::after 的 background-color 為 var(--HEADER-COLOR)，寬度為 40px，高度為 5px。
        (5)設定 border-radius 為 5px，position 為 absolute，transition 為 all 0.5s
        (6).menu-icon::before, .menu-icon::after 為 content 為 ""，使內容可被看見
        (7).menu-icon::before，transform 為 translate(-20px, -12px)
        (8).menu-icon::after，transform 為 translate(-20px, 12px)

### 15. Create the Dropdown Menu
        (1)設定 nav 的 display 為 block，transform-origin 為 top center
        (2)在 @keyframes showMenu 的 0% 選擇器中，
        修改 transform 設置爲 scaleY(0)； 80% 選擇器中，
        修改 transform 設置爲 scaleY(1.2)；
        100% 選擇器中，
        修改 transform 設置爲 scaleY(1)；
        (3)設定 nav ul 的 list-style-type 為 none，display 為 flex，flex-flow 為 column nowrap
        (4)設定 nav li 的 padding 為 0.5rem，border-top 為 1px solid var(--HEADER-COLOR)

### 16. Style and Transform Menu Links
        (1)設定 nav a 的 display 為 block，text-align 為 center，width 為 80%，margin 為 auto
        (2)設定 nav a:any-link 的 color 為 var(--HEADER-COLOR)，字體粗細為 bold，text-decoration 為 none
        (3)設定 nav a:hover, nav a:focus 的 transform 為 scale(1.2)，transition 為 all 0.3s

### 17. Animate the Hamburger Icon and Dropdown Menu
        (1)修改 nav 的 display 為 none。新增transform-origin 為 top center， animation 為 showMenu 0.5s ease-in-out forwards
        (2)新增 :is(header:hover, header:focus-within) .menu-icon 的背景為 transparent
        (3)新增 :is(header:hover, header:focus-within) .menu-icon::before 的 transform 為 translateX(-20px) rotate(45deg)
        (4)新增 :is(header:hover, header:focus-within) .menu-icon::after 的 transform 為 translateX(-20px) rotate(-45deg)
        (5)新增 :is(header:hover, header:focus-within) nav 的 display 為 block
        (6)在 nav 的 background-color 為 var(--HEADER-BGCOLOR)
        (7)在 :is(header:hover, header:focus-within) .menu-icon 新增 transform 為 rotate(720deg)
