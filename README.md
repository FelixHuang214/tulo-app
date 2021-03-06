## 網站名稱： Tulo 圖樂
網站連結：https://tulo.secomet.tw

未登入的使用者可以瀏覽網站內的作品，點進作品可以看到作品資訊、作者資訊及作品圖片。
<p>
  <img src="https://github.com/FelixHuang214/final-project/blob/master/images/pic0.png" height="300px" />
</p>
<p>
  <img src="https://github.com/FelixHuang214/final-project/blob/master/images/pic1.png" height="300px" />
</p
<p>
  <img src="https://github.com/FelixHuang214/final-project/blob/master/images/pic2.png" height="300px" />
</p>
登入後可以看到自己上傳的作品，並按下＋後新增作品。
<p>
  <img src="https://github.com/FelixHuang214/final-project/blob/master/images/pic3.png" height="300px" />
</p>
上傳的圖片可以依照自己的喜好調整順序，並點擊圖片右上角的 x 進行取消，最後按送出即可新增作品。
<p>
  <img src="https://github.com/FelixHuang214/final-project/blob/master/images/pic4.png" height="300px" />
</p>


### 目錄：
  * [專案簡介](#專案簡介)
  * [如何執行](#如何執行)
  * [使用技術](#使用技術)
  * [資料夾結構](#資料夾結構)
  * [後端 repository](https://github.com/FelixHuang214/final-project-server)
  

## 專案簡介
 * 提供創作者分享作品的空間，建立一個可以讓觀賞者及創作者互動的空間，希望可以讓創作者有持續創作的動力。
 * 創作者可將繪畫、漫畫或歌曲等作品上傳供其它人觀賞，觀賞者可對喜歡的作品留言及贊助。
## 如何執行

### 安裝專案所需套件

`npm install`

### 在 http://localhost:3000 開啟專案網頁

`npm run start`

> 可自行修改 src/images 內的檔案，讓網站的 logo、banner 呈現不同的樣貌

### 建立此專案的 production 版本

`npm run build`

### 於 GitHub Page 上部屬專案網站

`npm run deploy`

## 使用技術
 * React Hooks
 * React Router
 * React Sortable Hoc
 * Styled Components

## 資料夾結構
```
├── public
│   ├──index.html
│   └── robots.txt
├── src
│   ├── components
│   │   ├── AuthorDetail
│   │   │   ├── index.js
│   │   │   └── AuthorDetail.js
│   │   ├── Input
│   │   │   ├── index.js
│   │   │   ├── Icon.js
│   │   │   └── Input.js
│   │   ├── PhotoCrop
│   │   │   ├── index.js
│   │   │   ├── CropBox.js
│   │   │   └── PhotoCrop.js
│   │   ├── PictureEditor
│   │   │   ├── index.js
│   │   │   ├── Upload.js
│   │   │   ├── Picture.js
│   │   │   └── PictureEditor.js
│   │   ├── PictureReader
│   │   │   ├── index.js
│   │   │   └── PictureReader.js
│   │   ├── SideBar
│   │   │   ├── index.js
│   │   │   ├── Icons.js
│   │   │   ├── Header.js
│   │   │   ├── Profile.js
│   │   │   ├── Search.js
│   │   │   ├── SideBar.js
│   │   │   └── SideLink.js
│   │   ├── SignIn
│   │   │   ├── index.js
│   │   │   ├── Icons.js
│   │   │   └── SignIn.js
│   │   ├── SignUp
│   │   │   ├── index.js
│   │   │   ├── Icons.js
│   │   │   └── SignUp.js
│   │   ├── SiteBanner
│   │   │   ├── index.js
│   │   │   └── SiteBanner.js
│   │   ├── SiteHeader
│   │   │   ├── index.js
│   │   │   └── SiteHeader.js
│   │   ├── UserDetail
│   │   │   ├── index.js
│   │   │   └── UserDetail.js
│   │   ├── WorkDetail
│   │   │   ├── index.js
│   │   │   ├── InputWorkDetail.js
│   │   │   ├── ViewWorkDetail.js
│   │   │   └── WorkDetail.js
│   │   ├── WorksBlock
│   │   │   ├── index.js
│   │   │   ├── Work.js
│   │   │   └── WorksBlock.js
│   │   └── App.js
│   ├── constants
│   │   └── globalStyle.js
│   ├── global
│   │   ├── animations.js
│   │   ├── compressImage.js
│   │   ├── contexts.js
│   │   ├── device.js
│   │   ├── setNewFiles.js
│   │   ├── webAPI.js
│   │   └── staticData.js
│   ├── hooks
│   │   ├── useCropBox.js
│   │   ├── useParams.js
│   │   ├── usePictures.js
│   │   ├── useUser.js
│   │   ├── useUserDetail.js
│   │   └── useWorkDetail.js
│   ├── pages
│   │   ├── SettingPage.js(未完成)
│   │   ├── WorkEditPage.js(未完成)
│   │   ├── HomePage.js
│   │   ├── SignInPage.js
│   │   ├── SignUpPage.js
│   │   ├── UserPage.js
│   │   └── WorkPage.js
│   ├── images
│   │   ├── banner1.jpg
│   │   ├── banner2.jpg
│   │   ├── banner3.jpg
│   │   ├── banner4.jpg
│   │   ├── logo.png
│   │   └── userAvatar.jpg
│   ├── App.test.js
│   └── index.js
├── .gitignore
├── node_modules
├── package.json
├── package-lock.json
└── README.md


```
