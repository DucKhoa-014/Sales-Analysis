# Sales Analysis
## Dự án thuộc chương trình: STARTTRAIN - THE NEXT ANALYST

![Power BI](https://img.shields.io/badge/Tools-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Domain-Sales%20%26%20Retail-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)

---

## 📌 1. Tổng quan dự án

Dự án tập trung vào việc phân tích dữ liệu kinh doanh của một doanh nghiệp bán lẻ gồm 18 mặt hàng hỗn hợp (điện thoại, thiết bị điện tử, game, sách, máy tính,...) bán hàng qua nhiều kênh khác nhau[cite: 1]. Khoảng thời gian dữ liệu kéo dài 3 năm, từ ngày 01/01/2016 đến ngày 31/12/2018[cite: 1].

Các kênh bán hàng của doanh nghiệp bao gồm[cite: 1]:
*   **Kênh Online:** Telephone, website, email, fax,...[cite: 1]
*   **Kênh Offline:** Local store[cite: 1].

### 🎯 Yêu cầu & Mục tiêu
Doanh nghiệp yêu cầu xây dựng khoảng 8 trang dashboard nhằm đánh giá tổng quan, phân tích và tìm ra cơ hội có thể cải thiện hiệu suất kinh doanh[cite: 1]. Công cụ thực hiện chính được chỉ định là Power BI[cite: 1].

---

## 📊 2. Các chỉ số cốt lõi & Hướng phân tích (Key Metrics)

Dự án tiến hành đo lường và đánh giá dựa trên các chỉ số và khía cạnh cốt lõi sau[cite: 1]:
*   **Revenue:** Doanh thu[cite: 1].
*   **Quantity:** Số lượng[cite: 1].
*   **Average selling price:** Giá bán trung bình[cite: 1].
*   **Gross profit:** Lợi nhuận gộp[cite: 1].
*   **Gross profit margin:** Biên lợi nhuận gộp[cite: 1].
*   **Number of orders:** Số lượng đơn hàng[cite: 1].
*   **Product performance:** Phân tích hiệu suất sản phẩm[cite: 1].
*   **Sales channel performance:** Phân tích hiệu suất kênh bán hàng[cite: 1].

### 🔍 Các câu hỏi lớn cần giải quyết
Hệ thống báo cáo được thiết kế nhằm trả lời toàn diện các câu hỏi sau[cite: 1]:
*   Doanh thu sản phẩm đến từ đâu[cite: 1].
*   Xu hướng thay đổi của doanh thu theo thời gian[cite: 1].
*   So sánh hiệu quả doanh thu giữa các kênh bán hàng[cite: 1].
*   Xác định rõ sản phẩm nào đạt hiệu suất tốt nhất và kém nhất xét trên các tiêu chí về doanh thu (revenue), số lượng bán (qty sold) và lợi nhuận gộp (gross profit)[cite: 1].

---

## 🛠️ 3. Quy trình thực hiện dự án (Step-by-Step Process)

Quy trình triển khai xây dựng hệ thống báo cáo được thực hiện qua các bước tiêu chuẩn:

### Bước 1: Tiếp nhận Yêu cầu & Xác định bài toán (Business Understanding)
*   Nghiên cứu yêu cầu phân tích hoạt động kinh doanh bán lẻ đa kênh dựa trên tài liệu mô tả bài toán[cite: 1].
*   Xác định rõ mục tiêu cần đạt được và các câu hỏi kinh doanh cốt lõi cần trả lời[cite: 1].

### Bước 2: Thu thập & Tiền xử lý Dữ liệu (ETL - Data Cleansing)
*   Kết nối nguồn dữ liệu chứa thông tin vận hành trong vòng 3 năm (2016 - 2018) vào Power BI[cite: 1].
*   Sử dụng Power Query để làm sạch dữ liệu, xử lý các giá trị trống (Null), loại bỏ trùng lặp và chuẩn hóa định dạng dữ liệu của 18 mặt hàng cũng như các kênh bán hàng[cite: 1].

### Bước 3: Xây dựng Mô hình Dữ liệu (Data Modeling)
*   Thiết kế mô hình dữ liệu dạng hình sao (Star Schema) để tối ưu hóa hiệu suất tính toán.
*   Tạo mối quan hệ (Relationships) chặt chẽ giữa bảng nghiệp vụ bán hàng (Fact Sales) và các bảng danh mục (Dim Products, Dim Channels, Dim Date).

### Bước 4: Xây dựng các chỉ số đo lường (DAX Measures)
*   Viết các công thức DAX để tính toán chính xác các chỉ số yêu cầu bao gồm Revenue, Quantity, Average selling price, Gross profit, Gross profit margin và Number of orders[cite: 1].
*   Phát triển các chỉ số so sánh theo thời gian (Time Intelligence) để làm rõ xu hướng tăng trưởng doanh thu qua các năm[cite: 1].

### Bước 5: Thiết kế & Trực quan hóa dữ liệu (Dashboard Design)
Xây dựng và hoàn thiện cấu trúc khoảng 8 trang dashboard trên Power BI bao gồm[cite: 1]:
1.  **Overview Dashboard:** Đánh giá và tổng quan toàn bộ hoạt động kinh doanh[cite: 1].
2.  **Revenue & Trend Analysis:** Phân tích chi tiết xu hướng biến động doanh thu theo dòng thời gian 3 năm[cite: 1].
3.  **Product Performance Deep-dive:** Đi sâu vào hiệu suất của 18 mặt hàng, phân tách rõ nhóm tốt nhất và kém nhất về doanh thu, số lượng bán và lợi nhuận gộp[cite: 1].
4.  **Channel Performance Analysis:** So sánh và đánh giá hiệu quả chi tiết giữa các kênh Online (telephone, website, email, fax) và Offline (local store)[cite: 1].
5.  **Profitability Analysis:** Tập trung theo dõi sát sao Gross Profit và Gross Profit Margin nhằm tìm kiếm cơ hội tối ưu chi phí[cite: 1].
6.  **Order & Transaction Insights:** Phân tích hành vi mua sắm thông qua chỉ số Number of Orders và quy mô đơn hàng[cite: 1].
7.  **Regional/Customer Analysis:** Khám phá nguồn gốc doanh thu đến từ các tệp khách hàng hoặc khu vực địa lý.
8.  **Business Opportunities:** Tổng hợp các phát hiện độc đáo từ dữ liệu để đề xuất giải pháp cải thiện cho doanh nghiệp[cite: 1].

### Bước 6: Phân tích & Trích xuất Insights (Data Analysis)
*   Sử dụng các bộ lọc tương tác để tìm ra các yếu tố cấu thành nên doanh thu và lợi nhuận gộp[cite: 1].
*   Đánh giá sự chênh lệch hiệu suất giữa các kênh bán hàng và các dòng sản phẩm để tìm ra nguyên nhân cốt lõi[cite: 1].

### Bước 7: Tổng hợp Khuyến nghị (Actionable Recommendations)
*   Dựa trên kết quả phân tích từ các trang báo cáo để đề xuất giải pháp cải thiện và tối ưu hóa vận hành cho doanh nghiệp[cite: 1].
*   Đưa ra phương án phân bổ nguồn lực hợp lý cho các kênh bán hàng tiềm năng và tối ưu chiến lược cho các sản phẩm hiệu suất kém[cite: 1].

---

## 📂 4. Cấu trúc thư mục dự án

```text
├── data/                  # Thư mục chứa file dữ liệu gốc của doanh nghiệp
├── pbix/                  # Thư mục chứa file dự án Power BI (.pbix)
├── screenshots/           # Hình ảnh chụp giao diện các trang Dashboard
└── README.md              # Tài liệu hướng dẫn và mô tả dự án
