# Memo Teardown — Notion: The all-in-one workspace

**Nhóm:** Day16-01620-NguyenTrungHieu · **Thành viên:** Nguyễn Trung Hiếu (K4-Track 1, 2A202601620), Đặng Ngọc Anh (K4-Track 1, 2A202601706)

**Vì sao chọn sản phẩm này:** Notion là công cụ ghi chú cá nhân ra đời từ 2015, đã có lượng người dùng lớn (kể cả người trả phí) và giành nhiều giải thưởng trên Product Hunt. Notion không chỉ là app ghi chú mà nằm giữa bốn nhóm sản phẩm — ghi chú cá nhân, quản trị tri thức, wiki cộng tác và quản lý công việc — tạo thành một nền tảng all-in-one cho cá nhân lẫn doanh nghiệp, và chỉ tích hợp AI từ năm 2022, nên có đường dịch chuyển sản phẩm rõ để phân tích.

**§1. Timeline các cập nhật lớn**

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
|---|---|---|---|
| 17/09/2019 | [Notion for Students](https://www.producthunt.com/products/notion/launches/notion-for-students) | Notion vừa cán mốc 1 triệu người dùng; cạnh tranh với Evernote, OneNote, Google Docs ở mảng ghi chú, còn ở phân khúc sinh viên là Google Workspace (miễn phí email trường) và các app ghi chú thuần như Bear, Simplenote. | Mở khóa Personal Pro miễn phí cho sinh viên/giáo viên bằng email trường — chiến lược "chiếm lấy đại học" (campus land-grab) để xây thói quen dùng sớm, biến sinh viên thành user trung thành và đại sứ thương hiệu khi ra trường, mang Notion vào môi trường công sở. |
| 13/05/2021 | [Notion API (Public Beta)](https://www.producthunt.com/products/notion/launches/notion-api-beta) | Các nền tảng năng suất khác (Airtable, Coda, Slack) đã có API và hệ sinh thái tích hợp/automation (Zapier, IFTTT) từ trước; Notion vẫn là "walled garden" khiến dữ liệu khó kết nối ra ngoài. | Mở Notion từ ứng dụng đóng thành nền tảng: cho phép Zapier, Typeform, Automate.io và cộng đồng developer đọc/ghi dữ liệu Notion, đặt tiền đề cho hệ sinh thái tích hợp và công cụ bên thứ ba xây trên nền Notion. |
| 16/11/2022 | [Announce Notion AI (Alpha)](https://www.producthunt.com/products/notion/launches/notion-ai-alpha) | Evernote mạnh về capture nhanh, tìm kiếm, notebook/tag, web clipper. Microsoft OneNote mạnh về viết tay, ink, ghi âm/ghi hình. Obsidian mạnh về markdown cục bộ, backlinks, graph view và quyền kiểm soát dữ liệu. | Theo triết lý của Doug Engelbart về đưa máy tính vượt xa vai trò máy đánh chữ để trở thành công cụ giải quyết vấn đề phức tạp của con người — mang AI vào workspace của Notion để user không cần rời app để tìm kiếm, ghi chú, tóm tắt, lên kế hoạch. |
| 23/02/2023 | [Public Launch Notion AI](https://www.producthunt.com/products/notion/launches/notion-ai-097184fd-f5e4-4535-95ca-27899fdf79c9) | Đối thủ như Evernote, OneNote, Obsidian, Roam, Coda, Confluence, Google Docs vẫn mạnh ở từng ngách: ghi chú cá nhân, viết tay, quản trị tri thức, liên kết ý tưởng, automation, wiki doanh nghiệp, soạn thảo tài liệu. | Chuyển Notion từ "ghi chú thông minh" sang workspace tri thức + quản lý công việc, công khai AI cho toàn bộ user thay vì chỉ nhóm alpha. |
| 14/05/2026 | [Notion Developer Platform](https://www.producthunt.com/products/notion/launches/notion-developer-platform) | Sau giai đoạn AI hóa sản phẩm (Notion AI, Custom Agents), các nền tảng khác (Slack, Salesforce, Airtable) đã có developer platform/marketplace riêng để bên thứ ba xây app trên nền dữ liệu của họ. | "Build on Notion, not just inside it" — nâng cấp từ API đơn thuần (2021) thành nền tảng phát triển đầy đủ, cho phép developer xây ứng dụng và tích hợp chạy trên hạ tầng Notion, biến Notion thành platform thay vì chỉ là một app workspace. |

**Vì sao chọn những mốc này:** 5 mốc này vẽ ra đúng một đường cong tăng trưởng: mở tệp user (Students 2019) → mở nền tảng kỹ thuật (API 2021) → mở tính năng AI (Alpha 2022, Public Launch 2023) → mở hệ sinh thái ứng dụng bên thứ ba (Developer Platform 2026). Nhóm loại các mốc mang tính vận hành nội bộ như đổi pricing, redesign UI, hay các launch template/feature nhỏ lẻ trên Product Hunt (vd. Notion Calendar, Notion Mail) vì chúng không đại diện cho một bước ngoặt chiến lược, chỉ là mở rộng danh mục sản phẩm phụ trợ chứ không làm dịch chuyển tệp user hay mô hình sản phẩm cốt lõi.

**§2. Tệp user & JTBD**

| | Early adopters | Tệp hiện tại |
|---|---|---|
| Đặc điểm | **Không phải là fan của AI và chưa từng nghĩ tới sẽ dùng AI để hỗ trợ công việc.** Nhưng họ sẵn sàng thử nghiệm với những tính năng mới được tích hợp sẵn trong Notion. | User của Notion đã dùng Notion cho nhiều công việc khác nhau, từ ghi chú cá nhân đến quản lý dự án, và họ yêu thích sự linh hoạt và khả năng tùy chỉnh của Notion. Họ tin rằng Notion AI sẽ giúp họ làm việc hiệu quả hơn, tiết kiệm thời gian và tập trung vào những công việc quan trọng hơn. |
| JTBD chính | Viết nội dung từ đầu; Tóm tắt và trích xuất thông tin; Dịch và sửa ngữ pháp; Viết lại và cải thiện văn phong; Giải thích khái niệm | Tìm kiếm trong nội dung cá nhân; Thu thập và tổng hợp thông tin từ các nguồn; Sáng tạo nội dung dựa trên yêu cầu cụ thể; Phân tích và trích xuất dữ liệu có cấu trúc; Lên ý tưởng và lập kế hoạch chi tiết |
| Trước đó họ làm bằng cách nào | Viết nội dung từ đầu; Tự tóm tắt văn bản bằng tay; Copy nội dung sang Google Translate/DeepL rồi paste lại vào Notion; Tự viết lại đoạn văn để rõ ràng hơn; Chuyển sang Google/Wikipedia để tìm hiểu khái niệm rồi quay lại Notion ghi chú | AI tạo bản nháp, người dùng chỉnh sửa; AI tóm tắt nội dung; AI trích xuất tự động; AI dịch ngay trong Notion; AI sửa tự động; AI giải thích ngay trong Notion |

*(Nguồn tham khảo: [ledungthanh.vn — Cập nhật về Notion AI](https://ledungthanh.vn/cap-nhat-ve-notion-ai-cong-nghe-tri-tue-nhan-tao-hien-dai/))*

**Dịch chuyển tệp:** cột mốc nào ở §1 gây ra sự dịch chuyển? Tại sao?
> Cột mốc **Public Launch Notion AI (2023)** gây dịch chuyển lớn nhất vì mở rộng đối tượng người dùng từ early adopters sang đại đa số user của Notion, đồng thời đánh dấu sự chuyển dịch từ ghi chú thông minh sang workspace tri thức + quản lý công việc. Hai mốc nền tảng trước đó — **Notion for Students (2019)** và **Notion API Beta (2021)** — không trực tiếp gây dịch chuyển tệp user nhưng là điều kiện cần: tệp người dùng đông đảo từ sinh viên và hệ sinh thái tích hợp mở là nguyên liệu để cột mốc AI năm 2022–2023 phát huy tác dụng ở quy mô lớn.

**Switching cost (map 4 forces):** điều gì giữ user ở lại? Lực nào đang kéo họ đi / giữ họ lại?
> **Phân tích lực hút / đẩy:**
> * **Lực hút (attraction):**
>   * **Tính tích hợp (Integration):** Notion AI được tích hợp liền mạch vào không gian làm việc hiện có của người dùng, loại bỏ nhu cầu chuyển đổi ứng dụng.
>   * **Quen thuộc và tin cậy:** Người dùng đã quen thuộc với giao diện và quy trình làm việc của Notion, và tin tưởng vào nền tảng này cho nhu cầu công việc quan trọng của họ.
>   * **Giảm ma sát:** Thay vì phải học một công cụ mới, người dùng có thể bắt đầu sử dụng Notion AI ngay lập tức với những gì họ đã biết.
> * **Lực đẩy (repulsion - phá vỡ):**
>   * **Tính năng mạnh mẽ của đối thủ:** Đối thủ cạnh tranh như ChatGPT, Claude, Microsoft Copilot và Google Gemini cung cấp các mô hình ngôn ngữ mạnh mẽ hơn và nhiều tính năng chuyên biệt.
>   * **Chi phí và giới hạn sử dụng:** Notion AI là một tính năng trả phí và có giới hạn sử dụng hàng ngày/hàng tháng, điều này có thể là rào cản đối với một số người dùng.
>   * **Hiệu suất không đồng đều:** Notion AI có thể hoạt động không hiệu quả như mong đợi trong một số trường hợp, khiến người dùng thất vọng và tìm kiếm các giải pháp thay thế.
> * **Lực giữ (retention - rào cản):**
>   * **Hệ sinh thái Notion:** Người dùng đã đầu tư thời gian và công sức vào việc xây dựng các quy trình làm việc, template và cơ sở tri thức trong Notion.
>   * **Tính linh hoạt cao:** Notion cung cấp mức độ tùy chỉnh cao, cho phép người dùng tạo ra không gian làm việc phù hợp với nhu cầu cụ thể của họ.
>   * **Cộng đồng và hỗ trợ:** Cộng đồng người dùng Notion lớn mạnh và cung cấp nhiều tài nguyên hỗ trợ, template và tích hợp với các công cụ khác.
> * **Lực rời (switching - rời khỏi):**
>   * **Chi phí chuyển đổi cao:** Việc di chuyển dữ liệu và quy trình làm việc sang một nền tảng khác có thể tốn thời gian và công sức.
>   * **Tính quen thuộc và rào cản học hỏi:** Người dùng đã quen thuộc với Notion và không muốn học một công cụ mới.
>   * **Rủi ro không chắc chắn:** Không có gì đảm bảo rằng nền tảng thay thế sẽ cung cấp trải nghiệm tốt hơn hoặc đáp ứng nhu cầu của họ.

**§3. Ba dự đoán hướng đi (6–12 tháng tới)**

**Dự đoán 1** *(loại: mở rộng tính năng)*
- **Dự đoán:** Advanced Agent Orchestration — Notion sẽ phát triển khả năng orchestration nhiều agents phối hợp với nhau trong cùng một workflow phức tạp.
- **Lập luận:** Notion 3.6 đã giới thiệu External Agents, cho phép nhiều agents trong cùng UI. Bước tiếp theo là để các agents giao tiếp với nhau, chia sẻ trạng thái và phối hợp thực hiện workflow end-to-end — nối tiếp tự nhiên từ §1 (Developer Platform 2026 mở hệ sinh thái) và §2 (JTBD hiện tại đã thiên về "lên ý tưởng và lập kế hoạch chi tiết", cần agent phối hợp đa bước).

**Dự đoán 2** *(loại: mở rộng tính năng)*
- **Dự đoán:** Cross-Workspace Agent Queries — Notion sẽ cho phép agents truy vấn và thao tác across multiple workspaces.
- **Lập luận:** Hiện tại agents hoạt động trong một workspace. Các doanh nghiệp lớn thường có nhiều workspaces cho các team khác nhau. Agents cần khả năng làm việc across workspaces — logic tiếp nối của việc Notion đã mở API (§1, 2021) rồi mở cả nền tảng phát triển (§1, 2026), nên bước tự nhiên tiếp theo là xóa ranh giới dữ liệu giữa các workspace.

**Dự đoán 3** *(loại: mở rộng tính năng, tập khách hàng)*
- **Dự đoán:** Custom Model Support (Bring Your Own LLM) — Notion sẽ cho phép người dùng mang model AI riêng vào nền tảng.
- **Lập luận:** Hiện tại Notion hỗ trợ chọn model từ danh sách (GPT, Claude, Gemini). Các doanh nghiệp lớn có thể muốn dùng model riêng (fine-tuned, on-premise, hoặc model đặc thù ngành) — phù hợp với lực đẩy "đối thủ có model mạnh hơn" ở phần switching cost, và mở rộng tệp khách hàng enterprise vốn nhạy cảm về kiểm soát dữ liệu/model.

**§4. AI Log**

| Việc | AI làm hay nhóm làm? | Nhóm kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| Tổng hợp các insight từ user interview | Sử dụng AI để tìm kiếm thông tin | Chưa đủ thời gian để kiểm chứng |
| Tra cứu ngày launch và context các mốc trong §1 (Notion for Students, Notion API Beta, Notion Developer Platform) | AI tra cứu Product Hunt và web search | Đối chiếu chéo giữa nhiều nguồn (Product Hunt, notion.com/releases, báo chí công nghệ); với "Notion for Students" nhóm xác nhận lại ngày launch chính xác (17/09/2019) bằng ảnh chụp trực tiếp từ trang Product Hunt do thành viên cung cấp |
| | | |
