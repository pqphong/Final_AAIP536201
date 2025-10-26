# Final_AAIP536201
# 2D Object Detection and Tracking Vehicles from Traffic Camera for Analysis

## Các tính năng chính

* **Phát hiện phương tiện (Object Detection):** Sử dụng mô hình YOLO (You Only Look Once) được huấn luyện tùy chỉnh để phát hiện chính xác nhiều lớp phương tiện (ô tô, xe tải, xe máy, v.v.).
* **Theo dõi đa đối tượng (Multi-Object Tracking - MOT):** Tích hợp thuật toán BoT-SORT để theo dõi và duy trì ID nhất quán cho từng phương tiện, ngay cả khi bị che khuất tạm thời.
* **Trực quan hóa quỹ đạo (Trajectory Visualization):** Vẽ lại đường đi (vệt/trail) của từng đối tượng được theo dõi để dễ dàng phân tích hành vi chuyển động.
* **Phân tích (Analysis):** Cung cấp nền tảng dữ liệu (ID, tọa độ, thời gian) cho các phân tích sâu hơn như:
    * Đếm phương tiện qua các khu vực quan tâm (Region of Interest - ROI).
    * Ước tính vận tốc.
    * Phát hiện ùn tắc hoặc các hành vi bất thường.