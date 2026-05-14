# BÁO CÁO PHÂN TÍCH LAB 2: CURSOR VS GITHUB COPILOT

## Thông tin Nhóm
1. **2A202600076** - Hoàng Văn Bắc
2. **2A202600326** - Trịnh Xuân Đạt

---

## S1. Product Moment (Khoảnh khắc Sản phẩm)
- **Ngành**: Lập trình (Programming).
- **Nhiệm vụ thử nghiệm**: "Viết một trang Landing Page hiện đại cho ứng dụng đặt đồ ăn trực tuyến bằng HTML và Tailwind CSS, yêu cầu có form đăng ký và tính năng responsive".
- **Sản phẩm so sánh**: 
    - **Cursor**: Sử dụng model Claude 3.5 Sonnet.
    - **GitHub Copilot**: Sử dụng model GPT-4o.

## S2. Workflow Evidence (Bằng chứng Quy trình)
- **Cursor**: Sử dụng tính năng `Composer` (Cmd + I) hoặc `Inline Edit` (Cmd + K). Cursor hiểu được toàn bộ cấu trúc thư mục, cho phép tạo file `index.html` và `styles.css` đồng thời. Quy trình diễn ra trơn tru ngay trong IDE.
- **GitHub Copilot**: Sử dụng Chat Panel trong VS Code. Copilot trả về các đoạn code block lớn. Người dùng cần nhấn "Insert" hoặc copy-paste vào file thủ công.
- **Đánh giá**: Cursor mang lại trải nghiệm "Agentic" thực thụ, giảm bớt 2-3 bước trung gian so với Copilot.

## S3. Output & Trust (Kết quả & Tin cậy)
- **Chất lượng code**: 
    - **Cursor**: Code Tailwind CSS rất hiện đại, sử dụng các class utility chuẩn xác, giao diện Landing Page nhìn chuyên nghiệp hơn.
    - **GitHub Copilot**: Code sạch, dễ đọc nhưng phong cách thiết kế hơi cơ bản, cần chỉnh sửa nhiều để đạt độ thẩm mỹ cao.
- **Tín hiệu tin cậy**: Cả hai đều hiển thị các file tham chiếu (Reference) giúp người dùng biết AI đang đọc dữ liệu từ đâu.

## S4. Business Signal (Tín hiệu Kinh doanh)
### 1. Cursor
- **Giá**: Gói `Individual` là **$20/tháng**.
- **Adoption**: Được tin dùng bởi các đội ngũ tại Stripe, NVIDIA, OpenAI, Figma... NVIDIA đã trang bị cho toàn bộ 40.000 kỹ sư của họ.
- **Điểm mạnh**: Định vị vào năng suất của các Team Enterprise.

### 2. GitHub Copilot
- **Giá**: Gói `Pro` là **$10/tháng** (Ưu thế về giá). Gói `Pro+` là **$39/tháng** với nhiều model hơn.
- **Adoption**: Là công cụ phổ biến nhất thế giới nhờ tích hợp sẵn trong hệ sinh thái GitHub và VS Code.
- **Điểm mạnh**: Độ phủ lớn (Distribution) và giá rẻ cho người mới bắt đầu.

## S5. Product Judgment (Nhận định Chiến lược)
### S5.1 Verdict (Kết luận)
- **Cursor thắng** trong nhiệm vụ này nhờ khả năng thấu hiểu ngữ cảnh (Context) và quy trình làm việc không gián đoạn.

### S5.4 Moat (Hào kinh tế)
- **Copilot**: Moat nằm ở **Distribution** và **Ecosystem lock-in** (Tích hợp sâu với GitHub, Repo, PR).
- **Cursor**: Moat nằm ở **Product Experience** (Trải nghiệm Agentic) và **Switching Cost** (Khi team đã quen với workflow của Cursor thì rất khó quay lại VS Code thuần).

### S5.7 Spark → Loop → System
- Cursor đang chuyển dịch từ **Spark** (Sự kinh ngạc khi lần đầu dùng Cmd+K) sang **Loop** (Dùng càng nhiều, AI càng hiểu codebase -> càng hiệu quả).

### S5.8 Liên hệ Lab 1
- Giống như case FPT Software phải chuyển mình để tránh bị Big Tech nuốt chửng, Cursor là minh chứng cho việc một startup có thể thắng Big Tech nếu chọn đúng ngách (Niche) và tập trung tối đa vào trải nghiệm người dùng (UX) mà các ông lớn khó thay đổi nhanh được.