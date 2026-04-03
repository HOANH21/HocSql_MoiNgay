# 📊 SQL Practice (LeetCode)

Repository này dùng để lưu lại quá trình luyện SQL trên LeetCode.

## 🎯 Mục tiêu

* Cải thiện tư duy xử lý dữ liệu
* Thành thạo các câu lệnh SQL quan trọng
* Chuẩn bị cho vị trí Data Engineer Intern

---

## 🧠 Nội dung đã học

### 🔹 Basic

* SELECT
* WHERE
* ORDER BY
* LIMIT

### 🔹 Intermediate

* JOIN (INNER, LEFT)
* GROUP BY
* HAVING

### 🔹 Advanced

* Subquery
* CTE
* Window Functions

---

## 📂 Cấu trúc thư mục

```text
sql-practice/
│
├── easy/
├── medium/
└── hard/
```

---

## 📝 Cách mình giải bài

Mỗi bài SQL đều có:

* Link bài gốc (LeetCode)
* Ý tưởng giải
* Query SQL

Ví dụ:

```sql
-- Problem: Combine Two Tables
-- Link: https://leetcode.com/problems/combine-two-tables/
-- Ý tưởng: Dùng LEFT JOIN để nối 2 bảng

SELECT p.firstName, p.lastName, a.city, a.state
FROM Person p
LEFT JOIN Address a
ON p.personId = a.personId;
```

---

## 🚀 Tiến độ

* Easy: ...
* Medium: ...
* Hard: ...

(Cập nhật theo quá trình học)

---

## 📌 Ghi chú

Đây là repo phục vụ học tập, tập trung vào:

* Hiểu cách viết query
* Tối ưu logic
* Không chỉ copy lời giải

---

## 👨‍💻 Tác giả

* Tự học SQL mỗi ngày 💪
