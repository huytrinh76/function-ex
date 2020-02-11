# Sleep sort
Tên tiếng Việt: Sắp xếp ngủ

## Yêu cầu
Hãy viết một ***function*** có tên là **sleepSort** gồm có một tham số là một mảng các số nguyên.

Hàm trả về một mảng được sắp xếp tăng dần theo thuật toán **sleep sort**.

## Mô tả
**Sleep sort** Là một cách sắp xếp thú vị được nảy ra từ ý tưởng ngây thơ như sau.

Định nghĩa ***sleep(x)*** là chờ trong *x* giây. Vậy sleep sort chính là sử dụng sleep, mỗi số mang giá trị là bao nhiêu sẽ cho sleep bấy nhiêu.

Ví dụ: a = [5, 2, 7];

Số 5 sẽ chờ 5 mili-giây, số 2 chờ 2 mili-giây, số 7 chờ 7 mili-giây.
Vậy thì sẽ tạo một mảng mới có giá trị [2, 5, 7] được sắp xếp tăng dần.

**Hãy áp dụng ý tưởng trên để cài đặt sleep sort!!!**

## Ví dụ
```
> sleepSort([4, 3, 2, 2])
> [2, 2, 3, 4]
```

## Kiểm thử
Nhấn [vào đây](https://repl.it/@rknguyen/Sleep-sort) để kiểm thử hàm của mình.
