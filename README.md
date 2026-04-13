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
# CHECKPOINT - MỨC 3 (Manifest File - Project Phức Tạp)

**Dùng cho:** Project lớn, nhiều files (5+), nhiều links, dữ liệu khổng lồ, phụ thuộc phức tạp

---

## 1. THÔNG TIN PROJECT

**Project:** [Tên project]  
**Ngôn ngữ/Framework:** [Tech stack]  
**Mục tiêu chính:** [Mục tiêu]  
**Thời gian ước tính:** [Thời gian còn lại]  

Ví dụ:
```
Project: E-commerce Backend Optimization
Framework: Python 3.11 + Flask 2.3 + PostgreSQL
Mục tiêu: Giảm API response time từ 5s → 1s
Thời gian: 2 tuần
```

---

## 2. DANH SÁCH FILES CẦN DÙNG

```
📁 [Tên folder 1]/
├── 📄 [File 1] - [Kích thước]
│   └─ Mô tả: [Nội dung & vấn đề]
├── 📄 [File 2] - [Kích thước]
│   └─ Mô tả: [Nội dung & vấn đề]

📁 [Tên folder 2]/
├── 📄 [File 3] - [Kích thước]
│   └─ Mô tả: [Nội dung & vấn đề]
```

Ví dụ cụ thể:
```
📁 backend/
├── 📄 app.py - 250 KB
│   └─ Mô tả: Flask main app, 8 routes, N+1 query problem
├── 📄 models.py - 180 KB
│   └─ Mô tả: SQLAlchemy models (User, Product, Order)
├── 📄 database.py - 80 KB
│   └─ Mô tả: Database connection & session management
├── 📄 utils.py - 150 KB
│   └─ Mô tả: Helper functions, data processing

📁 data/
├── 📄 users.csv - 2 MB
│   └─ Mô tả: 50K user records (ID, name, email)
├── 📄 products.csv - 1.5 MB
│   └─ Mô tả: 10K product records (ID, name, price)
└── 📄 analysis.xlsx - 800 KB
    └─ Mô tả: Performance metrics, benchmark results

📁 tests/
└── 📄 test_api.py - 200 KB
    └─ Mô tả: Unit tests cho 8 endpoints
```

---

## 3. LINKS & TÀI NGUYÊN NGOÀI

```
🔗 [Tên tài nguyên 1]
   URL: [https://...]
   Loại: [Documentation/Tutorial/GitHub/Dataset/Paper]
   Tương quan với: [Files nào trong project]
   Thông tin: [Nội dung liên quan]

🔗 [Tên tài nguyên 2]
   URL: [https://...]
   Loại: [Documentation/Tutorial/GitHub/Dataset/Paper]
   Tương quan với: [Files nào trong project]
   Thông tin: [Nội dung liên quan]
```

Ví dụ:
```
🔗 SQLAlchemy Eager Loading Docs
   URL: https://docs.sqlalchemy.org/orm/loading_strategies.html
   Loại: Official Documentation
   Tương quan với: models.py, app.py
   Thông tin: Cách implement eager loading để tránh N+1 queries

🔗 Flask Best Practices
   URL: https://flask.palletsprojects.com/patterns/
   Loại: Official Documentation
   Tương quan với: app.py
   Thông tin: Structure, error handling, database patterns

🔗 Database Optimization (YouTube)
   URL: https://youtube.com/watch?v=xyz
   Loại: Tutorial Video
   Tương quan với: app.py, database.py
   Thông tin: Index strategies, query optimization tips

🔗 GitHub Repo (Reference Code)
   URL: https://github.com/username/similar-project
   Loại: GitHub Repository
   Tương quan với: Cấu trúc project
   Thông tin: Cách structure Flask project chuẩn
```

---

## 4. PHỤ THUỘC & DEPENDENCIES

```
📦 Python Packages:
   - [Package]: [Version] (dùng cho [mục đích])
   - [Package]: [Version] (dùng cho [mục đích])

🔌 External Services:
   - [Service Name]: [Kết nối cách] (dùng cho [mục đích])

⚙️ Configuration:
   - [Config]: [Value] (tác dụng [gì])
```

Ví dụ:
```
📦 Python Packages:
   - Flask==2.3.0 (REST API framework)
   - SQLAlchemy==2.0.0 (ORM)
   - psycopg2==2.9.0 (PostgreSQL adapter)
   - pandas==2.0.0 (Data analysis)

🔌 External Services:
   - PostgreSQL (Database) - localhost:5432
   - Redis (Cache) - localhost:6379

⚙️ Configuration:
   - SQLALCHEMY_ECHO=False (Tắt query logging)
   - CACHE_TIMEOUT=3600 (Cache 1 giờ)
```

---

## 5. KEY CONTEXT (Thông tin quan trọng)

```
🎯 Mục tiêu hiện tại:
   - [Mục tiêu 1]
   - [Mục tiêu 2]

📊 Metrics/KPI cần achieve:
   - [Metric 1]: [Target]
   - [Metric 2]: [Target]

⚠️ Constraint/Limitation:
   - [Constraint 1]
   - [Constraint 2]

✅ Convention/Best Practice:
   - [Convention 1]
   - [Convention 2]

🔍 Known Issues:
   - [Issue 1] (severity: [High/Medium/Low])
   - [Issue 2] (severity: [High/Medium/Low])
```

Ví dụ:
```
🎯 Mục tiêu hiện tại:
   - Giảm API response time từ 5s → 1s
   - Fix N+1 query problem
   - Optimize database indexes

📊 Metrics/KPI cần achieve:
   - Response time: < 1 second
   - Database queries per request: < 3 queries
   - CPU usage: < 30%

⚠️ Constraint/Limitation:
   - Không được thay đổi database schema
   - Phải backward compatible với client cũ
   - Production là PostgreSQL 12

✅ Convention/Best Practice:
   - Follow PEP 8 code style
   - Tất cả queries phải có eager loading
   - Error handling dùng custom exceptions

🔍 Known Issues:
   - GET /users timeout sau 5 giây (HIGH)
   - Product images load chậm (MEDIUM)
   - Missing indices trên orders table (HIGH)
```

---

## 6. TRẠNG THÁI HIỆN TẠI

```
✅ ĐẦTÀM:
   - [Task 1]
   - [Task 2]

→ ĐANG LÀM:
   - [Task hiện tại]

○ CẦN LÀM:
   - [Task 1]
   - [Task 2]
   - [Task 3]
```

Ví dụ:
```
✅ ĐẦTÀM:
   - Database analysis & profiling
   - Identify N+1 queries
   - Document performance issues

→ ĐANG LÀM:
   - Implement eager loading cho User.orders

○ CẦN LÀM:
   - Add database indices
   - Optimize SELECT queries
   - Run benchmark testing
   - Update API documentation
   - Deploy & monitor
```

---

## 7. NEXT STEPS (Chi tiết từng bước tiếp theo)

```
Step 1: [Mô tả]
        Files liên quan: [File nào]
        Expected output: [Kết quả mong đợi]

Step 2: [Mô tả]
        Files liên quan: [File nào]
        Expected output: [Kết quả mong đợi]

Step 3: [Mô tả]
        Files liên quan: [File nào]
        Expected output: [Kết quả mong đợi]
```

Ví dụ:
```
Step 1: Analyze app.py để tìm tất cả N+1 queries
        Files liên quan: app.py, models.py
        Expected output: Danh sách 5-10 N+1 query spots

Step 2: Implement eager loading cho relationship
        Files liên quan: models.py, app.py
        Expected output: Updated code với eager loading

Step 3: Run benchmark & so sánh performance
        Files liên quan: test_api.py, analysis.xlsx
        Expected output: Performance report (before/after)

Step 4: Add database indices
        Files liên quan: database.py
        Expected output: Migration script + new indices

Step 5: Final testing & deployment
        Files liên quan: test_api.py, app.py
        Expected output: All tests pass + ready to production
```

---

## CÁCH SỬ DỤNG MANIFEST FILE

### Trên Tài khoản A (Khi sắp hết token):
1. Điền đầy đủ tất cả section (1-7)
2. Lưu file này (có thể lưu vào Google Drive, Notepad, hay khác)
3. Copy toàn bộ nội dung

### Trên Tài khoản B (Tiếp tục):

**Lần đầu tiên (Setup):**
```
Tôi: "[Dán toàn bộ Manifest File]

Tôi có một Manifest File cho project phức tạp. 
Vui lòng đọc toàn bộ, giúp tôi hiểu project này."

Claude: "Tôi đã đọc manifest. Tôi hiểu:
- Project là Flask backend optimization
- Có [X] files, [Y] links liên quan
- Mục tiêu là giảm response time 5s → 1s
- Hiện tại đang ở Step 1

Sẵn sàng. Bạn upload files trong section 2 nhé?"
```

**Lần tiếp theo (Tiếp tục công việc):**
```
Tôi: "[Upload lại files từ section 2]

[Dán lại Manifest File]

Tiếp tục từ bước 'NEXT STEPS' nhé."

Claude: "Perfect! Tôi có đầy đủ context. 
Chúng ta tiếp tục Step [X]..."
```

---

## TIPS & TRICKS

1. **Lưu Manifest ở nhiều nơi:** Google Drive, GitHub Gist, Notion, hay local file
2. **Update Manifest thường xuyên:** Mỗi khi status thay đổi, update NEXT STEPS
3. **Tái sử dụng template:** Copy template này cho các project khác
4. **Tên file rõ ràng:** `MANIFEST_[ProjectName]_[Date].md`

---

**Lưu ý cuối cùng:** Template này rất chi tiết nhưng giúp bạn quản lý project phức tạp mà không bị mất context khi chuyển tài khoản!
