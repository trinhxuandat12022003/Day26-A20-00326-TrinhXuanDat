## So sánh giá và tín hiệu người dùng

### 1. Cursor (được gắn với mô hình như Claude 3.5 Sonnet)
- Giá công khai trên trang `cursor.com/pricing`:
  - `Hobby / Free`: có giới hạn, không cần thẻ
  - `Individual`: khoảng **$20 / tháng**
  - `Teams`: khoảng **$40 / người / tháng**
  - `Enterprise`: giá tuỳ chỉnh, có invoice/PO, SCIM, audit log, quản lý tập trung
- Tín hiệu người dùng / adoption:
  - Trang chủ nhấn mạnh “trusted every day by teams that build world-class software”
  - Nêu “over half of the Fortune 500”
  - Có trích dẫn khách hàng lớn: Stripe, NVIDIA, OpenAI, Figma, Adobe, Datadog…
  - Một câu trích dẫn cụ thể: NVIDIA “every one of our engineers, some 40,000, are now assisted by AI”
- Ghi chú: trang chưa liệt kê số người dùng chính xác công khai, nhưng rõ ràng định vị là giải pháp enterprise + team.

### 2. GitHub Copilot (GPT-4o / Copilot ecosystem)
- Giá công khai trên trang `github.com/features/copilot`:
  - `Free`: **0 USD**
    - 50 agent/chat requests mỗi tháng
    - 2.000 completion mỗi tháng
    - truy cập Haiku 4.5, GPT-5 mini, Copilot CLI
  - `Pro`: **$10 / người / tháng**
    - thêm Copilot cloud agent, code review
    - Claude và Codex trên GitHub & VS Code
    - 300 premium requests + mua thêm
    - unlimited agent mode & GPT-5 mini chat
    - unlimited inline suggestions
  - `Pro+`: **$39 / người / tháng**
    - toàn bộ Pro
    - truy cập “all models” bao gồm Claude Opus 4.7
    - 5× premium requests
    - truy cập GitHub Spark
- Tín hiệu người dùng / adoption:
  - Trang chủ nhấn mạnh Copilot có mặt “where you do” trong GitHub, VS Code, Visual Studio, Xcode, JetBrains, Neovim…
  - Có nhiều khách hàng doanh nghiệp lớn nhưng không liệt kê con số người dùng cụ thể trên trang.
  - Định vị là sản phẩm “native” trong hệ sinh thái GitHub, dễ tiếp cận với devs.

---

## Nháp ý tưởng về moat

### Điểm mạnh moat cho Cursor kiểu “agentic dev platform”
- Ưu tiên: “agent + tự động hóa + codebase context”
- Giá team cao hơn, có thể chứng minh ROI qua:
  - Cloud agents làm việc song song
  - Quản lý team rules / plugin marketplace
  - Audit, SSO, privacy mode
- Moat: “Giữ team ở lại với bạn bằng context, automations, reporting và model choice”

### Điểm mạnh moat cho Copilot kiểu “ecosystem lock-in”
- Ưu tiên: “GitHub/Git + IDE integration + distribution”
- Free entry giúp thu hút devs, sau đó upsell Pro/Pro+
- Moat:
  - Tích hợp sâu với GitHub, PR review, issue, repo, terminal
  - Phân phối qua VS Code, GitHub web, nhiều IDE
  - Khả năng dùng nhiều model nhưng vẫn giữ trong cùng một UX Copilot
- Đây là một moat bằng “mạng lưới sản phẩm” hơn là bằng giá rẻ.

### Nếu xây moat cho sản phẩm mới
1. Chọn một trong hai đường:
   - “Agent first”: tự động hoàn toàn, team workflow, kết quả dev tự động
   - “Ecosystem first”: tích hợp sâu, dùng ngay trong code + repo mà không phải chuyển kênh
2. Cố gắng khác biệt với:
   - chất lượng context repository + semantic search
   - billing đơn giản, minh bạch
   - trải nghiệm “switch model / run locally / hook external tools”
   - enterprise trust + audit / compliance
3. Tránh chỉ cạnh tranh bằng giá:
   - Copilot đã có free/pro thấp
   - Cursor định vị vào team enterprise, nên moat cần là “giá trị năng suất” và “sự phụ thuộc của team”.

> Tổng kết: Copilot là một moat về hệ sinh thái GitHub và phân phối; Cursor là một moat về agentic dev flow và enterprise team controls.