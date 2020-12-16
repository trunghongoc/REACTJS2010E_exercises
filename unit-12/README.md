
# Bài tập buổi 12, thứ 4 16-12-2020

## Bài 1
Hãy viết 1 hàm nhập vào 2 array, kiểm tra xem 2 array có khớp 100% các value với nhau về cả giá trị và index không

VD:
```javascript
const arr1 = [1, 2, 3, 4]
const arr2 = [1, 2, 3, 4]
const arr3 = [1, 2, 3, 5]
const arr4 = [1, 2, 3, 4, 5]


isEqual(arr1, arr2) // true
isEqual(arr1, arr3) // false
isEqual(arr1, arr4) // false
```

## Bài 2
Viết 1 hàm, nhập vào 1 array nhiều chiều (không xác định số chiều)
Hãy tạo thành array 1 chiều

VD:
```javascript
const data = [1, 2, [3, 4, [5]]]

flatten(data) // [1, 2, 3, 4, 5]
```

## Bài 3
Cắt nhỏ array thành nhiều đoạn, mỗi đoạn có `n` phần tử
Viết 1 hàm, nhập vào 1 array 1 chiều và 1 số (vd là `n`)
Hãy tạo array 2 chiều, với mỗi array con sẽ chứa `n` số trong array đã nhập

VD:
```javascript
const data = [1, 2, 3, 4, 5, 6, 7];

chunk(data, 2) // [[1, 2], [3, 4], [5, 6], [7]]
chunk(data, 3) // [[1, 2, 3], [4, 5, 6], [7]]
```

## Bài 4
Viết 1 hàm, nhập vào ít nhất 1 array
Tìm ra các phần tử xuất hiện trong tất cả các array truyền vào

VD:
```javascript
const arr1 = [1, 2]
const arr2 = [2, 3]
const arr3 = ['a', 'b']
const arr4 = ['b', 'c']
const arr5 = ['b', 'e', 'c']
const arr6 = ['b', 'b', 'e']
const arr7 = ['b', 'c', 'e']
const arr8 = ['b', 'e', 'c']

intersection(arr1, arr2) // [2]
intersection(arr3, arr4, arr5) // ['b']
intersection(arr6, arr7, arr8) // ['b', 'e']
```

## Bài 5
Sử dụng `Date` trong javascript

Hãy viết 1 hàm, nhập vào 1 giá trị date sau đó so sánh giá trị vừa nhập với giá trị thời gian sau đây
`12 giờ 30phút 32 giây ngày 30 tháng 10 năm 2020`

Kết quả cần return về: `equals`, `before`, `after`
Để biết thời gian nhập vào bằng, hay trước, hay sau mốc thời gian đã cho

## Bài 6
Viết regex để validate:
- Với email thì phải có định dạng email

## Bài 7
Viết regex để validate:
- Với userName thì tối thiểu phải có 2 ký tự, tối đa 10 ký tự. Các ký tự được phép sử dụng là `a-z` (viết thường), các số từ `0-9` và dấu `_`. userName không được bắt đầu bằng số, và không được có 2 dấu `_` đứng cạnh nhau.
