# Hướng dẫn chỉnh Banner Tiêu đề thành dạng Text có thể Sửa

\[1] Vào <mark style="color:yellow;">**Quản trị Banner**</mark>, ở khung soạn thảo chọn thẻ <mark style="color:yellow;">**HTML**</mark>

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

\[2] Copy toàn bộ đoạn mã trong đầy dán vào

{% code overflow="wrap" %}
```html
<div style="position: relative; width: 100%; text-align: center;">
<div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 100%; z-index: 10; pointer-events: auto;">
<table style="margin: 0 auto; background: rgba(255, 255, 255, 0.6); border-collapse: collapse; border-radius: 8px; padding: 10px 20px;">
    <tbody>
        <tr>
            <td style="text-align: center;">
            <h4 contenteditable="true" style="font-size: 20px; color: rgba(0, 176, 240, 1); margin: 0;">
            Ủy Ban Nhân Dân Xã Abc
            </h4>
            </td>
        </tr>
        <tr>
            <td style="text-align: center;">
            <h1 contenteditable="true" style="font-size: 48px; color: rgba(255, 0, 0, 1); margin: 5px 0 0;">
            Trường Mầm Non Abc</h1>
            </td>
        </tr>
    </tbody>
</table>
</div>
<img loading="lazy" alt="image banner" src="https://storage-edu.vnpt.vn/edu-vtu/4930/Banner/header.png" style="width: 100%; height: auto; display: block; z-index: 0; pointer-events: none;" />
</div>
```
{% endcode %}

\[3] Chuyển qua mục <mark style="color:yellow;">**Design**</mark>

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

\[4] Click vào các dòng **UBND** và **Tên Trường** để sửa cho phù hợp
