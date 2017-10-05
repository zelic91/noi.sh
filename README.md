# noi.sh
Sử dụng Google Translate để nói tiếng Việt :D Chỉ sử dụng được trên `MacOS` nhé! Mục đích mình viết ra tool này để `chấm dứt việc chửi thề` nơi làm việc (tất nhiên là thất bại).

Cài đặt
------

Trước hết, bạn phải cài `NodeJS` trước đã. Hơi ngớ ngẩn nhưng mà bạn phải cài, vậy thôi :)

Chạy các dòng lệnh sau trong Terminal

```
sudo curl -o /usr/local/bin/noi.sh "https://raw.githubusercontent.com/zelic91/noi.sh/master/noi.sh"
sudo chmod +x /usr/local/bin/noi.sh
alias noi="/usr/local/bin/noi.sh"
```

Để dùng lệnh `noi` mỗi khi mở Terminal, chèn dòng sau vào `.bash_profile` hay `.zshrc` (nếu bạn hiểu tui đang nói gì).

```
alias noi="/usr/local/bin/noi.sh"
```

Sử dụng
------

```
noi "Nhưng bạn ơi, tiền đâu mà đi?"
```

Lưu ý
------

Lệnh `noi` có thể không chạy được với nội dung quá dài.
