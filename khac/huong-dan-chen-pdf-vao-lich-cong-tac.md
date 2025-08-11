# Hướng dẫn chèn PDF vào Lịch công tác

\[1] Chọn biểu tượng <mark style="color:yellow;">**Hyperlink Manager**</mark>

<figure><img src="../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

\[2] Click biểu tượng <mark style="color:yellow;">**Document Manager**</mark>

<figure><img src="../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

\[3] \[4] Upload file PDF và click <mark style="color:yellow;">**Insert**</mark>

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

\[5] Click OK để chèn vào phần Nội dung

<figure><img src="../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

\[6] Copy tạm đường dẫn trong phần nội dung ra notepad để ghi nhớ

<figure><img src="../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

\[7] Click thẻ <mark style="color:yellow;">**HTML**</mark> để chuyển sang kiểu xem code

\[8] Copy phần code bên dưới vào, thay đoạn <mark style="color:yellow;">**\[link\_file\_pdf]**</mark> thành đường dẫn đã lưu ra notepad ở bước 6.

{% code overflow="wrap" %}
```html
<div>
<object type="application/pdf" data="[link_file_pdf]" width="95%" height="650px" style="margin: 15px 2%;"></object>
</div>
```
{% endcode %}

<figure><img src="../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

Kết quả  (ví dụ):

<pre class="language-html" data-overflow="wrap"><code class="lang-html">&#x3C;div>
&#x3C;object type="application/pdf" data="<a data-footnote-ref href="#user-content-fn-1">/SiteFolders/Root/BRVTedu/LichCongTac/2024/TUAN 11.pdf</a>" width="95%" height="650px" style="margin: 15px 2%;">&#x3C;/object>
&#x3C;/div>
</code></pre>

<figure><img src="../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

\[9] \[10] Quay lại tab <mark style="color:yellow;">**Design**</mark> để xem thử và click <mark style="color:yellow;">**Cập nhật**</mark> để lưu

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

[^1]: link\_file\_pdf
