# HW04 - Test Case & Mock Data

## Prompt
Sinh Test Case, Mock Data CSV và Unit Test.

## Test Cases

|ID|Loại|Mô tả|Kết quả|
|--|----|------|--------|
|TC01|Positive|Đầy đủ dữ liệu|PASS|
|TC02|Negative|Email sai|ERROR|
|TC03|Boundary|Tên 255 ký tự|PASS|

## Mock Data CSV
```csv
fullName,phone,email,citizenId
Nguyen Van A,0912345678,a@gmail.com,012345678901
Tran Thi B,0988888888,b@gmail.com,012345678902
```

## Unit Test
- Service Test
- Controller Test
- Mockito
