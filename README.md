# Project: HỆ THỐ TRỢ QUYẾT ĐỊNH -GVHD: TS.Lê Hải Hà

## Mô tả Dự Án

Dự án này sử dụng Data Mining, cụ thể là khai thác mỗi quan hệ (Association Rules), để phân tích và dự đoán xu hướng mua sắm dựa trên bộ dữ liệu **Customer Shopping Trend**. Mục đích chính là xây dựng một hệ thống khuyến nghị (Recommendation System) để gợi ý sản phẩm mới dựa trên hành vi mua sắm của khách hàng

## Các Bước Triển Khai

1. **Thu thập và tiền xử dữ liệu:**
   - Sử dụng bộ dữ liệu Customer Shopping Trend.
   - Tiến hành xử lý dữ liệu bao gồm: xóa dữ liệu khuyết, chuẩn hóa dữ liệu, v.v.

2. **Phân tích dữ liệu:**
   - Sử dụng các kỹ thuật phân tích hiển thị dữ liệu (như biểu đồ histogram, heatmap) để hiểu xu hướng.

3. **Đào tạo mô hình:**
   - Áp dụng thuật toán **Apriori** hoặc **FP-Growth** để khai thác luật kết hợp.
   - Xác định các luật kết hợp với mức **support** và **confidence** hợp lý.

4. **Xây dựng hệ thống gợi ý:**
   - Kết hợp các luật khai thác được để gợi ý sản phẩm có khả năng mua cao nhất.

5. **Đánh giá mô hình:**
   - Đánh giá độ chính xác của mô hình gợi ý bằng các metric như **precision**, **recall**, và **F1-score**.

## Công Nghệ Sử Dụng

- **Ngôn ngữ lập trình:** Python
- **Thư viện phân tích dữ liệu:** Pandas, NumPy
- **Thư viện trực quan hóa:** Matplotlib, Seaborn
- **Thuật toán khai thác mối quan hệ:** MLxtend
- **Môi trường triển khai:** Jupyter Notebook

## Kết Quả Mong Đợi

- Hiển thị các xu hướng mua sắm dựa trên dữ liệu phân tích.
- Khai thác được các luật kết hợp có giá trị để gợi ý sản phẩm mới.


