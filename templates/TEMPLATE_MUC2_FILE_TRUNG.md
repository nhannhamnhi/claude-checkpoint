# CHECKPOINT - MỨC 2 (File Trung Bình 100KB-5MB + Link)

**Dùng cho:** Code project vừa, dataset vừa, nhiều link, tài nguyên ngoài

---

## 1. TÓM TẮT (2-3 câu)
[Mô tả ngắn gọn công việc bạn đang làm]

Ví dụ:
- "Refactor backend API và tối ưu database queries"
- "Phân tích data ecommerce để tìm pattern bán hàng"
- "Xây dựng mobile app dashboard với React Native"

---

## 2. FILES LIÊN QUAN

Liệt kê các file bạn sẽ upload lại:

```
📁 File 1: [Tên file]
   - Kích thước: [KB/MB]
   - Loại: [code/data/document]
   - Chứa: [Mô tả nội dung]
   - Vấn đề cần giải quyết: [Mô tả vấn đề]

📁 File 2: [Tên file]
   - Kích thước: [KB/MB]
   - Loại: [code/data/document]
   - Chứa: [Mô tả nội dung]
   - Vấn đề cần giải quyết: [Mô tả vấn đề]
```

Ví dụ:
```
📁 File 1: app.py
   - Kích thước: 250 KB
   - Loại: Python code
   - Chứa: Flask app chính, 5 route endpoints
   - Vấn đề: N+1 query problem, timeout 5 giây

📁 File 2: database.csv
   - Kích thước: 1.5 MB
   - Loại: Data
   - Chứa: 50,000 users, products, orders
   - Vấn đề: Data inconsistency ở 200 rows
```

---

## 3. LINKS & TÀI NGUYÊN NGOÀI

```
🔗 Link 1: [URL]
   - Loại: [Documentation/Tutorial/GitHub/Dataset]
   - Nội dung liên quan: [Mô tả]

🔗 Link 2: [URL]
   - Loại: [Documentation/Tutorial/GitHub/Dataset]
   - Nội dung liên quan: [Mô tả]
```

Ví dụ:
```
🔗 Link 1: https://docs.sqlalchemy.org/orm/loading_strategies.html
   - Loại: Documentation
   - Nội dung: Eager loading để tránh N+1 queries

🔗 Link 2: https://youtube.com/watch?v=xyz (Database Optimization Tips)
   - Loại: Tutorial
   - Nội dung: Cách optimize SQL queries
```

---

## 4. KEY CONTEXT (3-5 thông tin quan trọng)

- [Tech stack dùng]
- [Mục tiêu chính]
- [Constraint/Giới hạn]
- [Best practice/Convention]
- [Thông tin khác]

Ví dụ:
- Tech: Python 3.11, Flask 2.3, SQLAlchemy, PostgreSQL
- Database: 3 tables (users, products, orders) với 50K rows
- Mục tiêu: Giảm response time từ 5s xuống 1s
- Constraint: Không được change database schema
- Best practice: Follow PEP 8, sử dụng eager loading

---

## 5. TRẠNG THÁI HIỆN TẠI

- ✅ Đã xong: [Liệt kê những gì hoàn thành]
- → Đang làm: [Công việc hiện tại]
- ○ Cần làm: [Những gì còn lại]

Ví dụ:
- ✅ Database analysis
- ✅ Identify N+1 queries
- → Đang: Implement eager loading
- ○ Optimize SELECT queries
- ○ Benchmark & testing
- ○ Deploy changes

---

## 6. NEXT STEP (Bước tiếp theo cụ thể)

[Mô tả rõ ràng bước tiếp theo]

Ví dụ:
- "Analyze app.py để tìm tất cả N+1 queries"
- "Implement eager loading cho User.products relationship"
- "Run benchmark trước/sau optimization"

---

## CÁCH SỬ DỤNG TEMPLATE NÀY

### Trên Tài khoản A (Khi sắp hết token):
1. Điền đầy đủ các section từ 1-6
2. Copy toàn bộ checkpoint này

### Trên Tài khoản B (Tiếp tục):
1. **Upload lại tất cả files** ở section "2. FILES LIÊN QUAN"
2. **Dán toàn bộ checkpoint**
3. Viết: "Đây là files và checkpoint của project. Tiếp tục từ bước 'NEXT STEP'"
4. Claude sẽ xem files + checkpoint và tiếp tục ngay

---

**Lưu ý:** 
- Nếu file > 5MB, nên dùng Template Mức 3
- Việc upload lại file chỉ mất vài giây
- Checkpoint giúp Claude không quên context
