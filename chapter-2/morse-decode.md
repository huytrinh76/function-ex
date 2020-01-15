# Morse decode
Tên tiếng Việt: Giải mã morse

## Nguồn bài
[romacher/morse-decoder](https://github.com/romacher/morse-decoder)

## Yêu cầu
Hãy viết một ***function*** có tên là **morseDecode** gồm có một tham số là một chuỗi bao gồm các ký tự `0`,`1`,`*` biểu diễn một mã morse.

Hàm trả về một chuỗi là giải mã của mã morse được truyền vào.

**Lưu ý:** Trong link kiểm thử, khu vực bài làm sẽ có kèm theo một object có tên là **MORSE_TABLE** sẽ giúp ta biết được mỗi chuỗi morse sẽ ứng với ký tự latin nào.

## Mã hoá morse
- Mỗi ký biểu diễn theo mã morse sẽ có 2 ký tự là chấm (`.`) và gạch ngang (`-`). Ta sẽ định nghĩa `10` là đại diện cho dấu chấm, và `11` là đại diện cho dấu gạch ngang.
- Mỗi ký tự khi được đổi ra mã morse có **độ dài chính xác là 10**.
- Nếu độ dài của mã morse chưa đủ 10 thì hãy thêm vào trước chuỗi morse các số `0` cho đến khi đủ 10.
- Nếu là khoảng trống thì mã morse tương ứng là mười dấu sao(*).

## Ví dụ
```
> morseDecode("00101010100000001010")
> "hi"
```

## Kiểm thử
Nhấn [vào đây](https://repl.it/@rknguyen/Morse-decode) để kiểm thử hàm của mình.