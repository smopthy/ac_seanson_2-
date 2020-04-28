topic : DOM 操作與事件處理 
  
  u44-u49   
  u44:  
  u45:瀏覽器渲染流程與DOM  
    &emsp;瀏覽器先讀取hmtl,css 之後才會讀取javascript ,  
    &emsp;因此，javascript 會改變html 的結構 之後開始渲染 
    &emsp;html 解析後會成為 dom   
    &emsp;css  解析後會成為 cssom  
    &emsp;dom 與 cssom 如同 瀏覽氣開放給javascript 的api 
  u46 : 樹狀結構與dom節點  
    dom 全面叫做 文件物件模型 (document object model)
    也就是html 會被解析成為 object 物件，  
    因此我們後續找尋節點的方式也是物件方法  
    
    dom 的數據結構是樹狀結構dom tree 
    dom 的元數節點之間會成為父子、兄弟關係
    瀏覽器為最高級別 window window 裡面其中一個物件為 document  
    document 為 html 物件中最高級別  
    
  u47 : 選出特定dom 節點  
    幾種常見的方式：  
    document.querySelector('')  

    備註：.node => class 


u50-u51 :  
  u53-u54 :   
  
  u53設置事件：
  
        我們如何知道hmtl上面的哪一個元素被點擊。  
        方式是透過是對元素的監聽，專有名詞為“事件監聽“  
        事件：包含：click , hover , input , sumbmit   
        
        element.EventListener('click' , greet())
        funciton greet () {}``

        element.EventListener('click' , function()=>{})

        此外，我們可以直接寫在html裡面 // 比較舊的寫法，且很多游覽器不支持，所以不推薦  
        <input value="Click me" onclick="greeting()" type="button">  
        
   u54事件操作：todolist 
