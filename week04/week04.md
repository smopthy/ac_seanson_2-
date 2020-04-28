topic : DOM 操作與事件處理 
  
  u44-u49   
  u44:  
  u45:  

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
