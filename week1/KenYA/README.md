# First Week #
----------
## 自我介紹 ##
名字   ： 吳克彥 , KenYA  
來自   ： 台中  
畢業於 ： 雲林科技大學資管系  
### 參加原因
心裡一直有個目標轉職成為「程式設計師」  
所以加入「實習計畫」成為實習生，並且很開心獲得了上課的機會  
藉由這個機會與大家互相交流  
大家一起學習成長，往自己的目標前進 (↗＝ ω＝)↗

### 工作經歷  
  - 網路工程師，安裝設定 Cisco Switch , Firewall , Wan load balance
  - HelpDesk，協助排除 User 端所遭遇的所有問題，監控系統、網路設備  

### 興趣休閒 ：
  - *慢跑*，登山步道，電玩 (_PS4_ , XONE)  

----------
## 上課心得 ##
大家在自我介紹的時候，好多雲科的同學阿，超想認親的QQ，而且人真的超級多的  
教室大爆滿，雖然是坐在教室另一邊(笑)，但還是能夠藉由 zoom 軟體得到同步的上課畫面
### Markdown
[MarkDown](http://markdown.tw/)語法線上說明  
線上編輯器 [Dillinger](http://dillinger.io/)

### Git
這次上課主要為GIT的使用，GIT 真的工程師必點技能，藉由這次上課重新複習GIT  

*養成好習慣，多多 commit 有益身體健康*，每次寫一個新功能或修正Bug後就Commit一次  


很重要的觀念 [Git Flow](https://github.com/trunk-studio/hellojs-gitbook/blob/master/vcs/git/flow/README.md)  
搭配圖形化軟體，可以更清楚各個分支的狀況  
-  [sourceTree](https://www.sourcetreeapp.com/) ： MacOS , Windows (沒Linux版本 哭哭...)
-  [Smartgit](http://www.syntevo.com/smartgit/download) ： MacOS, Windows , Linux(下載 deb檔案 ，Ubuntu 16.04 使用 GDebi 安裝)

Git衝突，當一個檔案有多人修改後，merge時該如何解決，但團隊還是要多**溝通**來避免衝突狀況  

免費的 [GitPage](https://pages.github.com/)，可成為放置放置靜態網頁主機，
搭配[Hexo](https://hexo.io/zh-tw/) 就可以建立自己的Blog  

----------

#### 指令筆記
```
//資料夾git初始化
git init
//如果是在GitHub上面，可以直接Clone回Local端
git clone https://remote_GitHub_url
//查看目前是否有已修改檔案、未加入檔案
git status
//將檔案加入 追蹤索引
git add file1
//將此次修改的內容加入索引，並加上註解
git commit -m "somethig about this commit"
//建立名稱為 origin 的遠端git庫
git remote add origin https://github.com/tikka0910/git_test.git
git push -u origin master
// 新增分支 myfun
git branch myfun
// 切換分支
git checkout myfun

//切換到master分支，並且合併myfun分支
git checkout master
git merge myfun
```
