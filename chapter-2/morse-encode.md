# Morse encode
Tên tiếng Việt: Mã hoá morse

## Nguồn bài
[romacher/morse-decoder](https://github.com/romacher/morse-decoder)

## Yêu cầu
Hãy viết một ***function*** có tên là **morseEncode** gồm có một tham số là một chuỗi bao gồm các chữ latin viết thường, và khoảng trống.

Hàm trả về một chuỗi là mã hoá morse của chuỗi đầu vào.

**Lưu ý:** Trong link kiểm thử, khu vực bài làm sẽ có kèm theo một object có tên là **MORSE_TABLE** sẽ giúp ta biết được mỗi chuỗi morse sẽ ứng với ký tự latin nào.

## Mã hoá morse
- Mỗi ký biểu diễn theo mã morse sẽ có 2 ký tự là chấm (`.`) và gạch ngang (`-`). Ta sẽ định nghĩa `10` là đại diện cho dấu chấm, và `11` là đại diện cho dấu gạch ngang.
- Mỗi ký tự khi được đổi ra mã morse có **độ dài chính xác là 10**.
- Nếu độ dài của mã morse chưa đủ 10 thì hãy thêm vào trước chuỗi morse các số `0` cho đến khi đủ 10.
- Nếu là khoảng trống thì mã morse tương ứng là mười dấu sao(*).

## Ví dụ
```
> morseEncode("hi")
> "00101010100000001010"
```

## Giải thích
Chữ `h` có mã morse là `....`, mà dấu chấm (`.`) tương ứng với `10`. Vì vậy ta có mã morse của `m` là `0010101010`. Lý do có `00` ở đầu vì `10101010` chưa đủ 10 ký tự.

Tương tự ta có chữ `i` có mã morse là `..`, tương ứng với `0000001010`.

Vậy chữ `hi` sẽ có mã morse là kết hợp của `h` và `i`, ta được `00101010100000001010`.

## Kiểm thử
Nhấn [vào đây](https://repl.it/@rknguyen/Morse-encode) để kiểm thử hàm của mình.

## Bài tiếp theo
[Bài 4: Morse decode](./morse-decode.md)