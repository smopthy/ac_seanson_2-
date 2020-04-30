# topic : DOM 操作與事件處理 
  
## u44-u49   
## #u44:  
   u45:瀏覽器渲染流程與DOM  
       瀏覽器先讀取hmtl,css 之後才會讀取javascript ,    
       因此，javascript 會改變html 的結構 之後開始渲染       
       html 解析後會成為 dom       
       css 解析後會成為 cssom      
       dom 與 cssom 如同 瀏覽氣開放給javascript 的api    
  
u46 : 樹狀結構與dom節點    
&emsp;&emsp;dom 全面叫做 文件物件模型 (document object model)   
&emsp;&emsp;也就是html 會被解析成為 object 物件，  
&emsp;&emsp;因此我們後續找尋節點的方式也是物件方法    
  
&emsp;dom 的數據結構是樹狀結構dom tree  
&emsp;dom 的元數節點之間會成為父子、兄弟關係  
&emsp;瀏覽器為最高級別 window window 裡面其中一個物件為 document   
&emsp;document 為 html 物件中最高級別    
    
&emsp;u47 : 選出特定dom 節點    
&emsp;&emsp;幾種常見的方式：    
`document.querySelector('')  

&emsp;備註：.node => class  #id  name=> 所有節點  


u50-u51 :  
u53-u54 :   
  
&emsp;u53設置事件：
  
&emsp;&emsp;我們如何知道hmtl上面的哪一個元素被點擊。  
&emsp;&emsp;方式是透過是對元素的監聽，專有名詞為“事件監聽“  
&emsp;&emsp;事件：包含：click , hover , input , sumbmit   
        
`element.EventListener('click' , greet())
 funciton greet () {}
  
`element.EventListener('click' , function()=>{})

&emsp;&emsp;此外，我們可以直接寫在html裡面 // 比較舊的寫法，且很多游覽器不支持，所以不推薦  
        
`<input value="Click me" onclick="greeting()" type="button">  
        
&emsp;u54事件操作：todolist 
