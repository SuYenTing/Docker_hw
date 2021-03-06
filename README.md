# Docker作業

此專案是放置我在Tibame學習Docker課程所做的作業，指導老師為 周廷諺老師。

## 作業環境

* 採用VMware Workstation 16 Pro建立虛擬機器
* 主體作業系統：Windows 10
* 客體作業系統：CentOS7

Docker部署在虛擬機CentOS7作業系統上。

## HW1

作業一是以docker-compose部署MongoDB與Jupyter Notebook(Python)，並在Jupyter內以Python程式碼對MongoDB進行「增刪改查」。

可直接下載HW1資料夾，在該資料夾目錄底下輸入`docker-compose up -d`，即可部署MongoDB與Jupyter Notebook(Python)。

作業內容詳細說明可參考[Docker作業一筆記](https://hackmd.io/@suyenting/ryN6GoJxO)。

## HW4

作業四是製作一個Line機器人，用戶上傳照片，會將照片搜集回本地的專案資料夾內。

可直接下載HW4資料夾，在該資料夾目錄底下輸入`docker-compose up -d`，即會部署Line機器人所需要的MySQL、Python及Ngrok三個容器，但還需要手動執行相關設定。

詳細說明可參考[Docker作業四筆記](https://hackmd.io/@suyenting/SyXDmqml_)。

## 上課補充筆記

這是我自行整理的上課補充筆記，主要是將老師上課提到的專有名詞或業界新知記錄下來，並Google搜尋資料補充進去。

[Docker課程補充筆記](https://suyenting.github.io/post/docker-notes/)

[Docker課程補充筆記2](https://suyenting.github.io/post/docker-notes2/)
