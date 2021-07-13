# Insurance-page-20210712

- index: 個人資料使用同意書
- madal: 若傳送成功/偵測到未簽署同意書

## 使用套件
- bootstrap 5

## bootstrap 5 Modal 使用
[官網範例](https://getbootstrap.com/docs/5.0/components/modal/)
- 含有 操控按鈕 與  Modal 本身
- 按鈕需裝上 data-bs-toggle="modal" data-bs-target=“#被操控元素的id“
- Modal 本身的最外層父元素除了class="modal fade"，還需裝上屬性  id="被操控元素的id" tabindex="-1"  aria-hidden="true"
- 父元素內層（也就是裝載樣式的那一層）需要加 class=“modal-dialog”
- 將範例程式碼的內的按鈕全部刪除不會影響元件運作，刪除aria-labelledby="exampleModalLabel" 也不影響運作
- 內層需要class="modal-content"，因為樣式會被蓋過，自己寫了 my-modal-content 取代。
- 檢查點 
  1. 是否有重複的id
  2. data-bs-target 的 # 是否有打
  3. 記得添加 class=“modal-dialog” 在正確位置

## 專案開發人員

> [AOI](https://github.com/aoigj100a)
