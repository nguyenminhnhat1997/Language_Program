## XML là gì ?

- Ngoài lưu trữ dữ liệu trong CSDL thì bạn cũng có thể lưu trữ dữ liệu trong file TXT, file Json hay XML đều đc, là phương tiện, ngôn ngữ giúp các ngôn ngữ khác giao tiếp được với nhau

### Cú pháp.

- cú pháp `<a> content </a>`

- có thể thêm <a owner="Minh Nhat" email="dd">Web</a>

- Cú pháp thẻ chỉ thị xử lý 

```javascript
<?xml version="1.0" encoding="UTF-8"?>
```
- kết hợp lại như vầy :

```javascript
<?xml version="1.0" encoding="UTF-8"?>
<domain>minhnhat.com</domain>
<me owner="Minh Nhật" email="stuckonyou113@gmail.com">minhnhat.com</me>
```

### Cấu trúc cây trong XML

- Cấu trúc thẻ lồng lên nhau, thẻ ngoài là cha, thẻ bên trong là con.

```javascript
<?xml version="1.0" encoding="UTF-8"?>
<company>
  <domain>
    <family>
      <persion>
      <name> name </name>
      </persion>
      <persion>
      <name> dat </name>
      </persion>
    </family>
  </domain>
</company>
```
