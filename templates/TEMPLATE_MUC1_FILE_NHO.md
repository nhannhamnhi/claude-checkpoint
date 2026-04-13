# CHECKPOINT - MỨC 1 (File Nhỏ < 100KB)

**Dùng cho:** Code nhỏ, snippet, bài viết ngắn, file dữ liệu nhỏ

---

## 1. TÓM TẮT (2-3 câu)
[Mô tả ngắn gọn công việc bạn đang làm]

Ví dụ:
- "Đang viết API endpoint GET /users bằng Python Flask"
- "Đang viết bài blog về Machine Learning cho người mới"
- "Đang tối ưu hóa SQL query cho hiệu năng tốt hơn"

---

## 2. NỘI DUNG FILE (Copy toàn bộ nội dung)

```[ngôn ngữ]
[Nội dung file ở đây]
```

Ví dụ với Python:
```python
def get_users(db):
    users = db.query(User).all()
    return [{'id': u.id, 'name': u.name} for u in users]
```

---

## 3. KEY CONTEXT (3-5 thông tin quan trọng)

- [Công nghệ/Framework dùng]
- [Yêu cầu chính của project]
- [Constraint/Giới hạn]
- [Chuẩn/Best practice cần tuân theo]
- [Thông tin khác quan trọng]

Ví dụ:
- Tech: Python 3.11, Flask 2.3, SQLAlchemy ORM
- Database: PostgreSQL
- Mục tiêu: Response time < 100ms
- Error handling: Custom exceptions
- Code style: PEP 8

---

## 4. TRẠNG THÁI HIỆN TẠI

- ✅ Đã xong: [Liệt kê những gì hoàn thành]
- → Đang làm: [Công việc hiện tại]
- ○ Cần làm: [Những gì còn lại]

Ví dụ:
- ✅ Database schema
- ✅ User authentication
- → Đang: Product API endpoints
- ○ Order API endpoints
- ○ Testing & debugging

---

## 5. NEXT STEP (Bước tiếp theo cụ thể)

[Mô tả rõ ràng bước tiếp theo]

Ví dụ:
- "Viết GET /products endpoint với pagination"
- "Thêm error handling cho invalid input"
- "Viết section 'Functions' cho bài blog"

---

## CÁCH SỬ DỤNG TEMPLATE NÀY

### Trên Tài khoản A (Khi sắp hết token):
1. Điền đầy đủ các section từ 1-5
2. Copy toàn bộ checkpoint này

### Trên Tài khoản B (Tiếp tục):
1. Dán toàn bộ checkpoint
2. Viết: "Tiếp tục từ bước 'NEXT STEP' nhé"
3. Claude sẽ có toàn bộ ngữ cảnh ngay lập tức

---

**Lưu ý:** Template này phù hợp khi file < 100KB. Nếu file lớn hơn, dùng Template Mức 2.
