# Rootme 

## ***Web - Server***

### 1.HTTP - IP restriction bypass

Sau khi mở challenge ta được chuyển hướng đến 1 website.
![1](/images/1.PNG)

Ở đây, ta cần dùng ip của mạng LAN để có thể lấy flag.

Note: hệ thống mạng LAN và có dạng 192.168.1.1 đến 192.168.1.255

Ở đây mình dùng Burpsuit, và thêm vào Request headers `X-Forwarded-For: 192.168.1.2`

Và giờ thì mình có flag.
![2](/images/2.PNG)

## ***Web - Client***