# Allegro_game1945
課程:計算機程式

成員:劉晏誠 陳秀峰 陸芃翰 歐旻修

遊戲專題: 終極彈幕

設計動機: 當初我們覺得空戰1945挺好玩的，古早味遊戲的感覺，所以設計以前遊戲機台的遊戲，決定做一個類似的。

![level_1](https://github.com/yencheng1028/Allegro_game1945/blob/main/Level_1.jpg)

遊戲介紹:
我方飛機有5點血​
使用左右方向鍵進行移動​​
遊戲中可按下esc結束​
按下tab可暫停遊戲​
打到敵人一下為20分​
左右方向鍵按越快，敵機飛越快

關卡介紹:
第一關敵方飛機有5台各兩點血，一次發射一發子彈​
第二關敵機有6台一點血，一次發射一堆子彈​
第三關敵機有6台二點血，一次發射一堆子彈​
第四關敵機有8台十點血，一次發射一堆子彈，但己方飛機一次攻擊打兩點血且攻擊範圍增加

 ![level_2](https://github.com/yencheng1028/Allegro_game1945/blob/main/level_2.jpg)

 ![level4](https://github.com/yencheng1028/Allegro_game1945/blob/main/level4.jpg)
     ​
分工:

劉晏誠:​
編寫切換武器function，使用分數判別切換​
第二份飛機子彈資料結構​
第二份子彈切換判別​
處理玩家結構並顯示分數字型設定​
終端機偵測碰撞顯示位置​

歐旻修:
1.己方飛機的移動、發射子彈
2.敵方飛機打到消失
3.不同關卡(增加敵機、增加血量)

陳秀峰:
menu
暫停功能
敵方飛機子彈
畫圖

陸芃翰:  ​
基本程式架構​
背景​
敵人移動+射擊​
己方飛機射子彈​
合併程式​
暫停​
debug​
碰撞偵測子彈消失​



心得分享:  

劉晏誠: 
對於大型程式任務我遇到的一些困難點，程式有很多，所以從頭到尾讀程式要很費力，而且函式會呼叫函式會一直呼叫到別的地方，再來有怎麼使用Allegro的library去呼叫來使用我覺得很難，因為要知道如何丟參數並傳回值，功能開發時會遇到很多bug，明明覺得邏輯沒錯程式卻跑不動，還有從沒東西時去寫出程式要思考很久，也讓我學到時間管理的重要性，因為這堂課程需要花很多時間去完成，但在學校並不只修這堂課程，如何安排課業並完成期末專題讓我更有經驗，但也很有壓力，因為有時間壓力，所以跟隊友熬夜趕工，也非常感謝跟隊友合力做出一份遊戲，需要團隊合作分工像外面工作一樣，沒有隊友就無法完成，感謝遇到一群好隊友，也讓我程式能力進步，沒想到自己有一天也可以跟同學做出遊戲，小時候根本沒想過。 

陳秀峰:  
我認為這次是個很有挑戰性的一項作業，很多功能都要自己慢慢摸索，並且又面臨著期末考好幾個主科壓力，時間有點喘不過氣來，所以我們算是能做的那幾天都過得很艱難，並且有很多bug，又加上要想如何能夠將自己在腦海想的邏輯，驗證在程式上是一大難題，我們花費了很長時間，我有時候可能程式能力不夠，所以需要花更大的心力完成，雖然很辛苦，但看到東西有做出來了心裡很是開心，雖然之後可能沒有要走這條路，但我認為這是一次很有意義的課程，也大幅度的增加了我的程式能力，並且也有做出來的成就感，我很開心能夠上這堂課。  

陸芃翰:  
這次的課程東西有點多，所以我們做了很久，而剛好這幾周是段考週， 所以有點來不急做完的感覺，但還是做完了，因為我們不分晝夜，花了好幾天的時間，甚至好久都沒睡覺了的感覺，身心十分的疲累，我雖然對程式有點概念，但這整個遊戲說起來，真的是非常的多，要摸索的地方也很多，bug也很多，一再的出現讓我有點招架不住，但用時間慢慢磨終究是都解決了，雖然感覺壽命縮減了，但我又更加精進了我的程式能力，感覺非常的有成就感也非常地有意義。  

歐旻修: 
這次的作業對我而言有點困難，第一次做遊戲讓我一開始有些不知所措。遊戲的許多功能需要自己思考該怎麼做，做出來時又有很多bug需要修，常常花了好幾個小時也做不出來。最痛苦的地方莫過於是從0開始想一個功能怎麼做，所幸有chatgpt這項神器讓我可以有個大概的雛形。修bug也可以用到chatgpt，但它也不是萬能的，出來的東西有許多問題，這就需要我慢慢解決。除了程式難寫外，期末考也是很大的時間壓力。這導致我們需要在有限的時間內做出成果，是一大挑戰。不過做出來很有成就感，也讓我對C語言更加了解，很高興能上這門課。 

