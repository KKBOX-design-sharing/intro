## 進入主題
目前已經有軟體可以編譯`Sass`與`Susy2`，  
例如[Fire.app](http://fireapp.kkbox.com/)、[codekit](http://incident57.com/codekit/index.html)等等，  
你不用安裝繁瑣的環境，透過軟體就可以直接編譯Sass，  
我目前用的軟體是Fire.app，而目前他也已釋出了Sass3.4、Compass 1.0的版本，  
更重要的是它內建就安裝好了Susy 2和Breakpoint的功能，開發上也變得相當方便，  
在去年我也曾經為了Fire.app寫了一篇[圖影教學](https://www.youtube.com/watch?v=Z_CmIMAiSiI)，  


	@import "compass";
      @import "mixin";  // 所有全域變數與Mixin  
      @import "reset";  // reset.css  
      @import "extend"; // 都放@extend用的檔案  
      @import "layout"; // 共同框架,第一層
      @import "module"; //button,form,table   
      @import "pages/index、pages1、pages2 ";     
