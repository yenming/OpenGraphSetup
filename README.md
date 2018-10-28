# 常用 Open Graph 設定筆記

Facebook 開發者資料：https://developers.facebook.com/docs/sharing/webmasters
<br>

### 常用的 Open Graph

<ul>
  <li>og:url：您網頁的標準網址。此網址應該沒有任何修飾，沒有工作階段變數、用戶識別參數或計數器。</li>
  <li>og:title：您的文章的標題，不包含網站名稱等。</li>
  <li>og:description：內容的簡短說明，通常為 2 到 4 個句子之間。此簡短說明在 Facebook 上顯示於貼文標題之下。</li>
  <li>og:image：用戶將內容分享至 Facebook 時顯示的圖像網址</li>
  <li>og:type：您的內容的媒體類型(ex: website)。</li>
  <li>og:locale：資源的地區。</li>
</ul>


### og:image 注意事項
圖片尺寸為： 1200 * 628
必須是完整的網址 (錯誤範例："/images/img.png")(正確範例："http://hexschool.com/images/img.png")
如果更換圖片，建議使用不同檔名
當圖片或內容有更新時，可用以下網址除錯https://developers.facebook.com/tools/debug/
