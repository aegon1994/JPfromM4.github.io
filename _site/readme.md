# 城中新生手冊

## Intro

這是個為了城中校區宿舍的學弟妹們所寫的介紹網站，主要是以 [Jekyll](https://jekyllrb.com/) 及 [markdown](markdown.tw) 編寫。

## Update

如果想要更新資訊，請直接更新`.pages/*.md`裡的分頁檔案，並將所更動的地方同步在`./pages/00_all.md`更動，以保持分頁版本與全頁版本一致。請**不要直接更動全頁版本**，以方便除錯。  

如果更動了頁面（如新增、合併等），請一併更動`./_data/navigation.yml`的相應項目。    

未來將考慮移除全頁版本，或至少藉由Jekyll語法使分頁上的文字直接顯示於全頁版本的頁面上。

## Commit

如果需要自行更動資訊，請執行以下指令：  

```
$ git clone https://github.com/JPfromM4/JPfromM4.github.io.git
$ git branch <a New Branch>
$ git checkout <Your Branch>

# after update

$ git add .
$ git commit -m "<some message>"
$ git push <Your Fork>

```

更新完成之後，請[聯絡原作者](mailto:p2295930@gmail.com?subject=您好，我更新了城中新生手冊)。

## Layout
所有的css都在`./styles.css`統一管理，而版面設定則在`./_layout/default.html`，左方選單內容請見`./_data/navigation.yml`。