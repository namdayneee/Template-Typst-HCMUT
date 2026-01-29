# Assignment Template - Discrete Structures for Computing

Template Typst cho bài tập lớn môn Cấu trúc rời rạc (CO1007) - Đại học Bách Khoa TP.HCM.

## Cấu trúc thư mục

```
├── main.typ              # File chính
├── metadata.typ          # Thông tin metadata (tên, MSSV, ...)
├── assets/
│   └── hcmut.png         # Logo trường
├── contents/
│   ├── 1_member_list.typ     # Danh sách thành viên
│   ├── 2_relation_counting.typ
│   ├── 3_probability.typ
│   └── 4_graph.typ
└── layouts/
    └── template.typ      # Template định dạng
```

## Hướng dẫn sử dụng

1. Chỉnh sửa thông tin trong `metadata.typ`:
   - Tên giảng viên
   - Danh sách sinh viên (tên, MSSV, công việc)
   - Năm học

2. Viết nội dung bài tập trong các file ở thư mục `contents/`

3. Compile:
   ```bash
   typst compile main.typ
   ```

## Yêu cầu

- [Typst](https://typst.app/) >= 0.11
- Font: Times New Roman
