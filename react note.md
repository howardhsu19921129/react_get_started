參考資料:

https://j6qup3.github.io/2016/08/06/%E7%8C%B4%E5%AD%90%E4%B9%9F%E8%83%BD%E7%9C%8B%E6%87%82%E7%9A%84-React-%E6%95%99%E5%AD%B8-1/

https://www.w3schools.com/react/react_getstarted.asp

https://zh-hant.reactjs.org/

https://zh-hant.reactjs.org/docs/introducing-jsx.html

*react 與以往html css js的架構不太相同，他將幾個這三者(html css js)以JSX的方式包裝成一個一個不同的物件。
每個物件以一個.js檔案呈現。

*(觀念待確認)src/index.js內記錄了全部物件的名稱與物件資料夾的路徑。亦定義了這些物件在被index.html(網頁主框架)呼叫時的名稱。

*以範例的App.js來說，App.js內是物件本體。期內亦import了.css來做渲染。// **但不知道是如何插入圖片**

*(觀念待確認)上層透過index.js去定義App.js = root。所以在poblic/index.html裡看到的是root

目前試著也製作一個物件，Meme.js。以可以成功加入顯示在index.html。但遇到兩個問題

        1.圖片無法導入至物件中
        2.若index.html中沒有使用到Meme.js，則必須將src/index.js(物件的清單?)中關於meme.js的import與getElementById註解掉，否則網頁會crash