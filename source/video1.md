## 電腦、IC 與 PCB 的製造過程

從上文「電腦工業的結構」當中，我們知道電腦主要是由 IC (晶片) 與 PCB (印刷電路板) 所組成的，如下圖所示：

![](../img/computer_prduce_flowmap.jpg)

但是、IC 與 PCB 到底是怎麼製造出來的呢？

本文將透過影片導引的方式，動態的展示 「IC、PCB 與電腦」的製造過程。

### IC 的製造過程

IC 的製造過程是非常複雜、而且耗費資本的工作。一間 12 吋的晶圓廠要耗費將近一千億才能夠建造出來，因此要拍攝到這些製造過程也通常要取得晶圓廠的同意才行。

大致來說 IC 的製造可以用「晶柱生產 => 切割成晶圓 => 晶圓代工 => 封裝 => IC」來描述，但其中的晶圓代工步驟則是相當的複雜，通常包含下列流程：

> 晶圓 => (成膜 => 微影成像 => 蝕刻 => 雜質參雜 => CMP 平坦化)* => 研磨 => 切割 => 黏晶 => 引線接合 

而封裝步驟則包含下列流程：

> 塑膜封裝 (壓模) => 導線金屬鍍膜 => 導線加工 => 標印 => 電路檢查 => 預燒 => 電路檢查

(註解：以上製程用語為大陸版，台灣的用語對照為：成膜 <=薄膜製程，微影成像<==黃光製程，雜質參雜<==擴散製程)

以下影片很清楚的介紹了 CPU 這顆電腦核心 IC 的製造過程，筆者強烈建議讀者花個十分鐘的時間看完它，您將會對整個 IC 工業有一個大致的理解。

* [YouTube : How a CPU is made](https://www.youtube.com/watch?v=qm67wbB5GmI)

如果您想進一步瞭解 IC 製造的流程與原理，可以參考下列文件。

* [第二十三章 半導體製造概論 (PDF)](http://www.taiwan921.lib.ntu.edu.tw/mypdf/mf23.pdf)

### 電路板的製造過程

接著、讓我們說明一下電路板的設計製造流程，以下是簡化的流程。

> 電路設計 => 電路板印製 => 插件 => 檢查電路正確性 

以下影片清楚的介紹了電路板的工業設計製造流程，只要花 5 分鐘就可以看完了。

* [YouTue : How it's Made:Computer Circuit Boards](https://www.youtube.com/watch?v=YJS_Jqw3Sy0)

當然、如果您想要自己動手設計電路板也是可以的，設計好之後可以用「手洗」的方式將電路板洗出來，以下影片介紹了「手洗」電路板的方法。

* [YouTube : 感光板製作流程](https://www.youtube.com/watch?v=LuOk2cMcXaA)

當然、洗完之後，元件也必須自己動手插上去並焊接，當然這比機器插件焊接會慢很多。

影片中的流程，大製就是如以下文件中所描述的一樣，這個文件詳述了整個電路板的「手洗製作流程」。

* [如何製作電路板 (PDF)](http://designer.mech.yzu.edu.tw/article/articles/technical/file/(2001-04-27)%20%E5%A6%82%E4%BD%95%E8%A3%BD%E4%BD%9C%E9%9B%BB%E8%B7%AF%E6%9D%BF.pdf), 作者：林浩瑋、蔡宗成、陳明周，元智大學最佳化實驗室。

如果您有雕刻機的話，那麼也可以不需要用「洗的」，用雕的也行，下述影片展示了雕刻機的操作過程。

* [YouTube : 民智科技 PCB 印刷電路板雕刻機 ELEVEN-LAB 實機操作](https://www.youtube.com/watch?v=2WBsfOqCIwY)

## 電腦的組裝製造過程

有了「電路板與 IC」 之後，只要在準備好週邊裝置與機殼等材料，就可以做出整台電腦了，以下影片介紹了「電腦與處理器的組裝製造過程」，影片長度是 11 分 47 秒。

* [YouTube : How It's Made: Computer And Microchips](https://www.youtube.com/watch?v=DVgOMRUNXsg)

當您看完上述影片之後，相信會對電腦的製造原理有一定的認識了。這些製程通常是在工廠裏進行的，因此即使是在學校也很難完整的學到的，這是一個很大很複雜的工業體系，很少人能從頭做到尾。

### 設計一台電腦

不過、如果是要「設計一台電腦」，就不需要耗費這麼大的資本了。相反的、設計電腦主要依靠的是「知識、腦力、電腦語言和軟體工具」。舉例而言、我們可以用 Verilog 語言設計 CPU 處理器與 IC 的數位電路，然後用 Altium Designer 或 Eagle 等工具設計 PCB 的電路，接著用 C 語言設計「編譯器、組譯器與作業系統」等軟體。而這些設計，也幾乎都是在「電腦上完成的」。

在這裡、讀者可能會產生一個問題。

電腦的設計都是用電腦來完成的，那麼第一台電腦的設計又是怎麼完成的呢？

關於這點的答案，那當然是人腦囉！ 不過整個電腦的演進史是很漫長的，所以當時人腦可以做出最簡單的電腦，然後再用這些最簡單的電腦一代一代發展，設計出更好的電腦。

不過、現在要「只靠人腦設計出電腦」，幾乎是不可能的了。因為只靠人腦所能設計出的那種電腦，都太陽春而難以稱為一台完整堪用的電腦了。


