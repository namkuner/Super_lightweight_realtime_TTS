# 🚀 Hệ thống Text-to-Speech (TTS) Thời gian thực - Siêu nhanh & Tiết kiệm tài nguyên

Dự án này giới thiệu một mô hình TTS tối ưu hóa cho hiệu suất và khả năng hoạt động trong thời gian thực. Dựa trên một kiến trúc mô hình đã được công bố, mình đã thực hiện các cải tiến (thay đổi mô hình và cách inference) để tăng tốc quá trình suy luận và giảm độ trễ.

## 🌟 Các tính năng nổi bật

- ⚙️ **Nhanh hơn 2 lần** so với mô hình gốc.
- ⚡ **Nhanh hơn 10 lần** so với XTTS và **60 lần** so với F5 TTS.
- 🚀 Đạt được **Real-Time Factor (RTF) ~0.055** trên **NVIDIA T4 GPU**.
- 🧠 Cải tiến cấu trúc mô hình và quy trình suy luận để tối ưu hiệu suất.
- 🧩 Thiết kế cho các ứng dụng cần tạo âm thanh theo thời gian thực.
- 🔥 Mô hình **80M tham số** rất nhỏ gọn, có thể chạy trên các thiết bị tài nguyên hạn chế.
- 🎤 Có thể sao chép giọng tham chiếu, tạo ra âm thanh gần giống như giọng nói thật (càng nhiều dữ liệu thì càng giống âm thanh gốc).

## 📊 Kết quả kiểm thử

| Mô hình    | RTF (↓)     | Tốc độ tương đối | Model Size (↓) | Dữ liệu huấn luyện  |
|------------|-------------|------------------|-----------------|------------------------|
| Mô hình này | **0.055**   | 1.0× (Cơ sở)     | **80M**         | **6h** âm thanh         |
| XTTS       | ~0.58       | 10× chậm hơn     | **343M**        | **1000h** âm thanh    |
| F5 TTS     | ~3.3        | 60× chậm hơn     | **336M**        |     |

> *RTF: Real-Time Factor (số nhỏ hơn là tốt hơn)*

## Demo

https://github.com/user-attachments/assets/422d0df7-8eb5-4333-88cd-b6a0564e19b6

## 🌐 Các ứng dụng của Real-Time TTS
- **Trợ lý ảo**: Các hệ thống như Siri, Google Assistant, Alexa đều sử dụng TTS để cung cấp phản hồi âm thanh trực tiếp cho người dùng.
- **Ứng dụng học ngôn ngữ**: TTS giúp người học ngôn ngữ phát âm chính xác từ mới và cải thiện kỹ năng nghe và thời gian thực
- **Hỗ trợ giao tiếp trong các thiết bị thông minh**: Các thiết bị IoT (Internet of Things) như smart speakers sử dụng TTS để giao tiếp với người dùng.
- **Chatbot Marketing và Chăm sóc khách hàng**: TTS được tích hợp trong các chatbot để cung cấp phản hồi âm thanh tự động trong các ứng dụng chăm sóc khách hàng, hỗ trợ bán hàng và tiếp thị.
