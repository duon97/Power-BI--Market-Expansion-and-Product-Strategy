# Market-Expansion-and-Product-Strategy
Use Power BI to analyze business data to find new market opportunities, and find  strategic product
## I. Giới thiệu
### 1. Bộ dữ liệu
#### Orders Table

| Column Name   | Data Type | Description |
|----------------|----------|-------------|
| Category       | STRING   | Product category |
| City           | STRING   | Customer city |
| Country        | STRING   | Customer country |
| Customer ID    | STRING   | Unique customer identifier |
| Customer Name  | STRING   | Customer full name |
| Market         | STRING   | Sales market region |
| Order Date     | DATE     | Date when the order was placed |
| Order ID       | STRING   | Unique order identifier |
| Postal Code    | INTEGER  | Customer postal code |
| Product ID     | STRING   | Unique product identifier |
| Product Name   | STRING   | Product name |
| Profit         | FLOAT    | Profit generated from the order |
| Quantity       | INTEGER  | Quantity of products ordered |
| Region         | STRING   | Sales region |
| Sales          | FLOAT    | Total sales amount |
| Segment        | STRING   | Customer segment |
| Ship Date      | DATE     | Date when the order was shipped |
| Ship Mode      | STRING   | Shipping method |
| State          | STRING   | Customer state/province |
| Sub-Category   | STRING   | Product sub-category |

---

## People Table

| Column Name | Data Type | Description |
|-------------|----------|-------------|
| Person      | STRING   | Regional manager or sales representative name |
| Region      | STRING   | Assigned sales region |

## Returns Table

| Column Name | Data Type | Description |
|-------------|----------|-------------|
| Order ID    | STRING   | Unique order identifier |
| Returned    | STRING   | Return status of the order |

### 2. Vấn đề cần giải quyết 
- Trình bày tình hình kinh doanh tại các thị trường quốc tế cho Giám đốc cấp cao.
- Nhấn mạnh các chỉ số quan trọng để Giám đốc cấp cao quyết định thị trường nào cần phát triển và sản phẩm nào phù hợp cho từng thị trường quốc tế.
## II. Design Thinking ( Tư duy thiết kế )
## STEP 1: Empathyze (Thấu cảm)

<img width="1277" height="537" alt="image" src="https://github.com/user-attachments/assets/28b3a22a-9290-4c91-8529-0e2c7e7ff34e" />
<img width="756" height="598" alt="image" src="https://github.com/user-attachments/assets/ee405424-b44e-4376-a45c-9fbea2407517" />
<img width="1176" height="641" alt="image" src="https://github.com/user-attachments/assets/a526f7c9-8126-43d2-99b0-4060979fc7e4" />

## STEP 2: Define POV (Nhìn sâu)

<img width="1121" height="628" alt="image" src="https://github.com/user-attachments/assets/88e7d85a-662d-487f-9fad-33f2520796b7" />
<img width="1033" height="506" alt="image" src="https://github.com/user-attachments/assets/2ca99ce5-7506-4b82-9c9f-91f7b3269a56" />

## STEP 3: Ideate (Lên ý tưởng)

<img width="1416" height="630" alt="image" src="https://github.com/user-attachments/assets/9ec6309c-5dc0-4f22-ba90-b82e6f50fcee" />

## STEP 4:  Prototype and review (tạo mẫu thữ nghiệm và đánh giá)

Choose the type of chart suitable for the questions
Presentation, layout of each part of the report(size, chart arrangement...)
Choose the color of the report
Self-review and edit my report
## III. VISUALIZATION (TRỰC QUAN)
## OVERVIEW 

<img width="1153" height="647" alt="image" src="https://github.com/user-attachments/assets/33547721-26b7-4e86-b225-3f10dbc812f4" />

## MARKET ANALYSIS

<img width="1167" height="648" alt="image" src="https://github.com/user-attachments/assets/ddfeeebb-7527-4ccc-93af-3a420d309bab" />

## PRODUCT ANALYSIS

<img width="1162" height="655" alt="image" src="https://github.com/user-attachments/assets/7ed40459-43c8-4581-b3f8-7edcec3587b3" />
<img width="1167" height="652" alt="image" src="https://github.com/user-attachments/assets/021f7fd7-b7b8-4cf4-8ed7-a61162171657" />

## CUSTOMER ANALYSIS

<img width="1157" height="652" alt="image" src="https://github.com/user-attachments/assets/8fe9682c-5bdf-46fe-b44f-8255681ad2d9" />

## IV. INSIGHT AND RECOMENDATION
#### 1. Hiệu suất kinh doanh tổng thể

Tín hiệu tích cực
Revenue tăng 51.5% YoY: 8.34M → 12.64M
Profit tăng 52.3%: 963K → 1.47M
Customer tăng nhẹ: 1575 → 1590
→ Công ty đang tăng trưởng mạnh, đồng thời khách hàng hiện tại có xu hướng chi tiêu nhiều hơn.
Vấn đề cần chú ý
Revenue tăng mạnh nhưng Margin chỉ tăng 0.1%
Doanh thu tăng nhanh nhưng lợi nhuận không cải thiện tương ứng, cho thấy discount và chi phí có thể đang tăng theo doanh thu.
Đề xuất
KPI Sales:
60% Profit
40% Revenue
Loại bỏ cơ chế thưởng chỉ dựa trên Revenue
Thiết lập Profit Floor = 8% cho mọi đơn hàng
Các deal dưới 8% cần được Regional Manager phê duyệt
Rủi ro khách hàng
Customer chỉ tăng 15 khách nhưng Revenue tăng gần gấp đôi
Điều này cho thấy doanh thu có thể đang phụ thuộc vào một vài khách hàng lớn.
Đề xuất
Mở rộng customer base song song với mở rộng thị trường
Giảm phụ thuộc vào 2–3 key accounts lớn

#### 2. Thị trường & sản phẩm nên mở rộng

Africa — Thị trường tiềm năng chưa khai thác
Hiệu suất
Revenue: $784K
Margin: 11.34%
Return Rate: 0%
Đề xuất
Tăng đầu tư và mở rộng hiện diện thị trường
Đẩy mạnh sales tại các phân khúc đang tăng trưởng tốt
Canada — Thị trường chất lượng cao
Hiệu suất
Margin: 26.62%
Chỉ mới 201 orders
Đề xuất
Tăng ngân sách marketing và sales
Scale thị trường để tận dụng margin cao
Copiers — Sub-category chiến lược
Hiệu suất
Profit và Margin cao nhất trong các sub-category
Đề xuất
Đẩy mạnh bán tại EU và Canada
Tăng inventory cho các market có margin tốt
Phones — Revenue cao nhưng margin thấp
Vấn đề
Revenue dẫn đầu nhưng margin mỏng, khả năng cao do discount quá sâu.
Đề xuất
Đo lường tác động của discount đến margin
Giảm discount để tối ưu lợi nhuận

#### 3. Tối ưu các thị trường hiện tại

APAC — Thị trường hoạt động tốt nhất
Hiệu suất
Market có hiệu quả tổng thể cao nhất
Technology và Furniture đều tạo hơn 1.3M revenue
Return Rate khoảng 6–7%
Đề xuất
Tiếp tục duy trì chiến lược hiện tại
Tăng đầu tư vào Technology và Furniture
Giảm nhẹ return rate để cải thiện profit margin
EU — Thị trường tăng trưởng ổn định
Hiệu suất
Revenue khoảng 3M
Profit Margin: 10–13%
YoY Growth khoảng 55%
Return Rate ổn định: 6–6.8%
Đề xuất
Mở rộng Technology và Office Supplies
Duy trì chất lượng sản phẩm
Không cần tăng discount để bảo vệ margin
US — Thị trường lợi nhuận tốt
Hiệu suất
Profitability cao nhưng còn dư địa tăng revenue
Đề xuất
Mở rộng danh mục sản phẩm
Tăng đầu tư marketing và sales
LATAM — Tăng trưởng cao nhưng margin thấp
Vấn đề
Doanh thu tăng tốt nhưng profitability chưa cao.
Đề xuất
Kiểm soát chi phí chặt hơn
Tăng AOV (Average Order Value)
Đầu tư thận trọng để tránh ảnh hưởng margin
Africa & EMEA — Thị trường underperform
Vấn đề
Có lượng customer cao nhưng tổng profit âm.
Đề xuất
Điều tra nguyên nhân gây lỗ:
Discount quá cao
Logistics cost
Return rate
Product mix
Xây dựng chiến lược cải thiện hoặc cân nhắc rút khỏi thị trường

#### 4. Sản phẩm cần tối ưu

Tables — Hiệu suất kém
Vấn đề
Profit margin âm liên tục trong 4 năm, đồng nghĩa công ty đang lỗ trên mỗi đơn bán.
Đề xuất
Cân nhắc discontinue sản phẩm
Hoặc điều chỉnh pricing strategy





