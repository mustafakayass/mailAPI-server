POST /api/email HTTP/1.1
Host: localhost:8080
Content-Type: application/json

{
"to": "alıcı@example.com",
"subject": "Konu",
"text": "Mailin içeriği."
}

- http://localhost:8080/api/email --POST 
- 
- client tarafı için de basit bir geliştirme yapıldı onu da client adıyla profilimde farklı bir repo'da bulabilirsiniz
- application.properties dosyasındaki host,port,username,password bilgilerini kendi bilgilerinize göre düzenleyiniz.