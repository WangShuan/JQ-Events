# JQ-Events
  
  1. val方法: 沒傳參數是獲取值 有傳參數是更改值。
  
  2. html方法與text方法: 同val的用法 沒傳參數是獲取 有傳參數是更改。
  
  3. width方法與height方法: 同val的用法 沒傳參數是獲取 有傳參數是更改 且與css方法不同的是此方法不帶任何單位。
  
  4. 獲取視窗寬高的辦法(可視區域寬高): resize方法 同JS中的onresize方法。
  
  5. 獲取各種寬度的方法: width() / innerWidth() / outerWidth() / outerWidth(true)
  
  6. offset方法與position方法: 兩者都是獲取元素的位置的方法，且都只能獲取不能設定。
  
  7. JQuery 事件機制發展歷程: 簡單click-綁定bind-委託delegate
  
  8. on 註冊事件: 結合上面三種方法所發展出來的註冊事件方式。
  
  9. 委託事件案例: 表格刪除。
  
  10. 移除事件綁定: 用bind/delegate綁定時 > unbind/undelegate方法，用on綁定時 > off方法 off方法不傳參時表示解綁所有事件。
  
  11. 觸發事件: trigger方法 參數為想觸發的事件。
  
  12. JQuery事件對象: 同JS的event對象， e.preventDefault()阻止默認事件 / e.stopPropagation()阻止冒泡事件 / return false阻止默認和冒泡事件。
  
  13. end方法: 當JQ對象發生改變時，可以使用end方法返回前一個狀態以繼續進行鏈式。
  
  14. each方法: each方法是除了for循環外 遍歷JQ對象的方法。
  
  15. JQuery 中的$ 衝突問題: 當有別的引用文件也使用$符號時，可以使用 $.noConflict() 來釋放$的控制權。
