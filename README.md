📊 Social Listening: Thống kê Luồng Thông Tin Nhân Sự Cấp Cao 2026
📌 Tổng quan dự án (Overview)
Dự án tập trung vào việc thu thập, xử lý và phân tích các luồng thông tin, đồn đoán trên mạng xã hội liên quan đến vị trí Thủ tướng kế nhiệm trong bối cảnh giả định năm 2026 tại Việt Nam. Kết quả cung cấp cái nhìn đa chiều về thái độ dư luận, các nhóm vấn đề nổi bật và định vị các nguồn phát tin có tầm ảnh hưởng lớn.
_________________________________________________________________________________________________________________________________

🏗️ Cấu trúc dự án theo mô hình S.T.A.R
1. Situation (Bối cảnh)
- Thị trường: Mạng xã hội (Facebook, YouTube) tại Việt Nam.
- Vấn đề: Các luồng thông tin đồn đoán về nhân sự cấp cao thường phân tán, thiếu cấu trúc và chứa đựng nhiều sắc thái cảm xúc phức tạp, gây khó khăn cho việc quản trị rủi ro thông tin.

2. Task (Nhiệm vụ)
- Thống kê: Định lượng các luồng đồn đoán về số lượng ứng viên, nền tảng phân bổ và tần suất thảo luận.
- Phân tích Sắc thái: Phân loại nội dung theo Tích cực, Tiêu cực, Trung lập cho từng ứng viên.
- Định vị Rủi ro: Xác định các nhóm vấn đề (Kinh tế, Nhân sự, Đời tư...) và các kênh/tài khoản có tần suất tán phát thông tin cao.

3. Action (Hành động)
- Data Extraction (Cào dữ liệu):
    + Sử dụng Apify API để quét dữ liệu bình luận từ các URL thu thập qua Google Search.
    + Tập trung vào bộ từ khóa chuyên ngành (Jargon) như: "Kiện toàn", "Nhân sự cấp cao", "Thủ tướng kế nhiệm" để lọc bỏ tin tức rác.
- Data Cleaning & Modeling:
    + Xử lý dữ liệu bằng Python (Pandas): Làm sạch text, xử lý giá trị thiếu.
    + Gán nhãn thực thể đa trục: Đối tượng (Candidate), Chủ đề (Field), và Thái độ (Sentiment).
- Analysis: Xây dựng Dashboard rủi ro và báo cáo Deep-dive để tìm mối liên hệ giữa "nguồn phát" và "luồng tin độc hại".

4. Result (Kết quả)
- Volume: Tổng cộng 137 luồng thảo luận hợp lệ. Facebook chiếm ưu thế tuyệt đối với ~92% lưu lượng.
- Sentiment: Phần lớn dư luận ở trạng thái "nghe ngóng" (Trung lập). Tuy nhiên, xuất hiện các "nhân tố bí ẩn" nhận được lượng tương tác (Like) khổng lồ, cho thấy sự kỳ vọng thay đổi của đám đông.
- Insight: Xác định được các "điểm nóng" dư luận tập trung vào năng lực điều hành kinh tế và uy tín đời tư của các ứng viên hàng đầu.
__________________________________________________________________________________________________________________________________
📂 Cấu trúc thư mục

- SocialListening_DAtest.ipynb: Source code xử lý dữ liệu và tích hợp API.
- Description_process.docx: Tài liệu mô tả quy trình và giải pháp kỹ thuật.
- Dataset_Candidate.csv: Tập dữ liệu sạch sau khi đã gán nhãn.
- Deep_Dive_Analysis.csv: Báo cáo chi tiết các chỉ số và Insight.
- Risk_Dashboard.csv: Các bảng thống kê tổng hợp phục vụ trực quan hóa.

Link google drive: https://drive.google.com/drive/folders/13ESO3tVxYRzliKp1Ih9OwQRI0Yz0BfBE?usp=sharing