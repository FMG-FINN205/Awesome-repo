<div align="center">

# 🌟 AWESOME REPOSITORIES
### 🚀 Kho Lưu Trữ & Tuyển Chọn Các GitHub Repositories Đỉnh Cao

*Nơi tổng hợp những công cụ mã nguồn mở, thư viện tiên tiến, framework hiện đại và tài nguyên học tập giá trị nhất dành cho lập trình viên.*

<p align="center">
  <a href="https://github.com/FMG-FINN205/Awesome-repo/stargazers">
    <img src="https://img.shields.io/github/stars/FMG-FINN205/Awesome-repo?style=for-the-badge&logo=github&color=f59e0b&logoColor=white" alt="GitHub Stars">
  </a>
  <a href="https://github.com/FMG-FINN205/Awesome-repo/network/members">
    <img src="https://img.shields.io/github/forks/FMG-FINN205/Awesome-repo?style=for-the-badge&logo=github&color=3b82f6&logoColor=white" alt="GitHub Forks">
  </a>
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://img.shields.io/badge/Awesome-Lists-fc28a8?style=for-the-badge&logo=awesomelists&logoColor=white" alt="Awesome">
  </a>
  <a href="https://github.com/FMG-FINN205/Awesome-repo/pulls">
    <img src="https://img.shields.io/badge/PRs-Welcome-10b981?style=for-the-badge&logo=git&logoColor=white" alt="PRs Welcome">
  </a>
  <a href="https://github.com/FMG-FINN205/Awesome-repo/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-8b5cf6?style=for-the-badge" alt="License">
  </a>
</p>

---

</div>

## 📑 Mục Lục

- [⚡ Skill Tối Ưu Token & Giao Tiếp](#-skill-tối-ưu-token--giao-tiếp)
- [🎨 Skill Thiết Kế Giao Diện & UI/UX](#-skill-thiết-kế-giao-diện--uiux)
- [💻 Skill Lập Trình & Tái Cấu Trúc Code](#-skill-lập-trình--tái-cấu-trúc-code)
- [🤖 Skill Tự Động Hóa & Multi-Agent](#-skill-tự-động-hóa--multi-agent)

---

## ⚡ Skill Tối Ưu Token & Giao Tiếp

> Các skill giúp rút gọn câu trả lời, tiết kiệm chi phí token và tinh chỉnh phong cách phản hồi của AI.

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)**: Công cụ tối ưu hóa chi phí và token cho các AI coding agent (Claude Code, Cursor, Gemini...). Ép AI trả lời theo phong cách "người tiền sử" (ngắn gọn, trực diện, loại bỏ văn phong rườm rà) giúp giảm tới 65% token output mà vẫn đảm bảo 100% chất lượng code.
  - 🏷️ **Tags**: `AI-Agent`, `Token-Optimization`, `CLI`, `Cost-Saving`
  - ⭐ **Tính năng chính**:
    - **Skill**: Cắt gọt câu trả lời của AI, bỏ các lời chào và diễn giải dư thừa.
    - **Proxy**: Nén dữ liệu đầu vào nặng nề (terminal logs, test outputs, git diffs) trước khi gửi tới API.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**:
      ```bash
      npx skills add JuliusBrussee/caveman -g
      ```
    - **Lệnh điều khiển trong khung chat AI**:
      - `/caveman`: Kích hoạt chế độ người tiền sử.
      - `/caveman lite`: Rút gọn vừa phải, giữ tính lịch sự.
      - `/caveman ultra`: Rút gọn tối đa để tiết kiệm token cao nhất.
      - `stop caveman`: Tắt chế độ, trở lại cách phản hồi thông thường.

- **[barkleesanders/claude-hud](https://github.com/barkleesanders/claude-hud)**: Thanh trạng thái HUD trực quan thời gian thực trên terminal cho Claude Code và Codex. Hiển thị % dung lượng context (cảnh báo khi sắp đầy để compact), theo dõi giới hạn rate limit API, tiến độ subagent và trạng thái Git.
  - 🏷️ **Tags**: `HUD`, `Terminal-UI`, `Context-Health`, `Rate-Limits`, `Claude-Code`, `Codex`
  - ⭐ **Tính năng chính**:
    - **Đo lường Context Health**: Thanh màu cảnh báo trực quan lượng token đã dùng để kịp thời compact ngữ cảnh.
    - **Quản lý Rate Limits**: Theo dõi hạn ngạch API 5h/7 ngày và chi phí tiêu thụ.
    - **Giám sát Subagent & Tools**: Theo dõi trực tiếp tác vụ ngầm và các file đang được AI chỉnh sửa.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: Build repo và cấu hình `statusLine` trong `~/.claude/settings.json`.

---

## 🎨 Skill Thiết Kế Giao Diện & UI/UX

> Các skill trang bị tư duy thiết kế, hệ thống design system, màu sắc và typography chuyên nghiệp cho AI.

- **[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)**: Skill cung cấp tri thức thiết kế chuyên sâu của Senior UI/UX Designer cho các AI agent. Tự động tạo Design System hoàn chỉnh (màu sắc, font chữ, layout) chuẩn theo từng ngành, loại bỏ hoàn toàn giao diện "AI generic" xấu xí.
  - 🏷️ **Tags**: `UI-UX`, `Design-System`, `AI-Skill`, `Frontend`, `Web-Design`
  - ⭐ **Tính năng chính**:
    - **Bộ máy suy luận 192 quy tắc**: Nhận diện lĩnh vực dự án để chọn style (Bento grid, Glassmorphism, Minimalist...) và bảng màu chuẩn xác.
    - **Checklist bàn giao chuẩn**: Đảm bảo tương phản WCAG, responsive đa màn hình, loại bỏ màu neon chói và anti-patterns.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**:
      ```bash
      npx skills add nextlevelbuilder/ui-ux-pro-max-skill -g
      ```
    - **Sử dụng**: Ra lệnh cho AI tạo giao diện trong chat (ví dụ: *"Thiết kế landing page cho SaaS"*), AI sẽ tự động kích hoạt skill để xây dựng Design System trước khi sinh code.

- **[senlindesign/taste-skill](https://github.com/senlindesign/taste-skill)**: Skill dịch ngược gu thẩm mỹ và triết lý thiết kế (Taste DNA) từ bất kỳ website nào (Linear, Stripe...). Tự động bóc tách quy tắc thị giác và xuất thành file rules cho Cursor, Claude Code, Antigravity để AI code theo chuẩn phong cách mong muốn.
  - 🏷️ **Tags**: `UI-UX`, `Design-Taste`, `Reverse-Engineering`, `AI-Skill`, `Styling`
  - ⭐ **Tính năng chính**:
    - **Trích xuất "Taste DNA"**: Phân tích triết lý thiết kế đằng sau các con số (spacing, border, tương phản màu sắc) thay vì chỉ sao chép CSS thô.
    - **Tự sinh file Rules**: Tự tạo cấu hình chuẩn cho `.cursor/rules`, `CLAUDE.md`, `GEMINI.md` từ link website được cung cấp.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Yêu cầu**: Cần cài đặt kèm **Playwright MCP** (để AI có thể mở và xem website).
    - **Thực thi**: Chạy lệnh `/taste <URL>` trong khung chat (ví dụ: `/taste https://linear.app`).

- **[pbakaus/impeccable](https://github.com/pbakaus/impeccable)**: Bộ công cụ chỉ dẫn và kiểm thử thiết kế frontend đỉnh cao cho AI coding agents. Cung cấp 24 lệnh thiết kế chuyên biệt (audit, polish, critique, animate) cùng 61 quy tắc tự động phát hiện và loại bỏ các lỗi thiết kế "AI generic".
  - 🏷️ **Tags**: `UI-UX`, `Design-System`, `Design-Audit`, `Frontend-Polish`, `AI-Skill`
  - ⭐ **Tính năng chính**:
    - **24 lệnh thiết kế mạnh mẽ**: Tinh chỉnh giao diện chuyên sâu (`polish`, `audit`, `critique`, `animate`, `bolder`...).
    - **61 bộ lọc lỗi cục bộ**: Quét sạch các anti-pattern (card lồng card, màu tím hồng AI, font mặc định).
    - **Quản lý ngữ cảnh**: Tạo `PRODUCT.md` và `DESIGN.md` giúp AI nắm vững kiến trúc giao diện dài hạn.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**:
      ```bash
      npx impeccable install
      ```
    - **Thực thi**: Gõ lệnh trực tiếp trong chat AI (ví dụ: `/impeccable init` để khởi tạo, `/impeccable polish` để hoàn thiện giao diện).

- **[delphi-ai/animate-skill](https://github.com/delphi-ai/animate-skill)**: Skill cung cấp các quy tắc và mẫu animation đỉnh cao cho React/Next.js dựa trên triết lý của Emil Kowalski. Giúp AI tạo ra các hiệu ứng vi mô (micro-interactions), modal, toast và hover mượt mà 60 FPS chuẩn GPU.
  - 🏷️ **Tags**: `Animation`, `Micro-interactions`, `Framer-Motion`, `React`, `UI-UX`
  - ⭐ **Tính năng chính**:
    - **Spring physics & Easing chuẩn**: Áp dụng thời gian và quán tính chuyển động chân thực, không đơ cứng.
    - **Tối ưu hiệu năng GPU**: Bắt buộc chỉ animate thuộc tính `transform` và `opacity` để tránh drop frame.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**:
      ```bash
      npx skills add https://github.com/delphi-ai/animate-skill --skill animate
      ```

- **[iotron/gsap-cookbook](https://github.com/iotron/gsap-cookbook)**: Tuyển tập 12 skills chuyên sâu giúp AI lập trình animation GSAP chuẩn Awwwards. Bao gồm ScrollTrigger (cuộn parallax, pin section), tương tác chuột 3D (magnetic button, tilt card) và tối ưu GPU 60 FPS cho Next.js, React, Vue.
  - 🏷️ **Tags**: `GSAP`, `Animation`, `ScrollTrigger`, `Awwwards`, `UI-UX`
  - ⭐ **Tính năng chính**:
    - **12 modules hoạt ảnh chuyên sâu**: Bao phủ toàn diện từ ScrollTrigger, SplitText, SVG morphing đến hiệu ứng tương tác chuột.
    - **Tối ưu chuẩn Production**: Tự động dọn dẹp bộ nhớ (cleanup), chống lỗi SSR và tối ưu render GPU.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**:
      ```bash
      npx skills add iotron/gsap-cookbook
      ```

---

## 💻 Skill Lập Trình & Tái Cấu Trúc Code

> Các skill chuyên sâu nâng cao chất lượng code, refactoring, debug và tối ưu hóa logic phần mềm.

- **[m8e/graphify](https://github.com/m8e/graphify)**: Skill biến toàn bộ thư mục code hoặc tài liệu thành Đồ thị tri thức (Knowledge Graph) trực quan. Giúp AI hiểu sâu kiến trúc dự án lớn, giảm 71.5x token mỗi lần truy vấn và xuất ra giao diện web tương tác hoặc Obsidian vault.
  - 🏷️ **Tags**: `Knowledge-Graph`, `Codebase-Analysis`, `Architecture`, `Token-Saving`, `Obsidian`
  - ⭐ **Tính năng chính**:
    - **Dựng đồ thị tri thức**: Tự động phát hiện liên kết giữa các file, module và khái niệm ẩn trong code.
    - **Tiết kiệm 71.5x Token**: Truy vấn cấu trúc tức thì từ graph có sẵn mà không cần đọc lại toàn bộ file thô.
    - **Xuất đa nền tảng**: Sinh file `graph.html` tương tác, wiki tài liệu nội bộ và Obsidian vault.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: `pip install graphifyy && graphify install`
    - **Thực thi**: Chạy lệnh `/graphify .` trong chat AI để quét dự án.

---

## 🤖 Skill Tự Động Hóa & Multi-Agent

> Các skill hỗ trợ điều phối đa tác nhân, lập lịch công việc và tự động hóa quy trình làm việc phức tạp.

- **[somasays/skill-creator](https://github.com/somasays/skill-creator)**: Meta-Skill giúp AI tự thiết kế, viết và đóng gói các AI Skill mới chuẩn production. Tự động phỏng vấn nhu cầu, tạo file SKILL.md, tài liệu tham khảo và script hỗ trợ theo chuẩn kiến trúc chuyên nghiệp.
  - 🏷️ **Tags**: `Meta-Skill`, `Skill-Builder`, `Workflow`, `Automation`, `Agent-Development`
  - ⭐ **Tính năng chính**:
    - **Tự động hóa tạo Skill**: AI tự nghiên cứu và sinh ra bộ skill hoàn chỉnh từ yêu cầu ngôn ngữ tự nhiên của bạn.
    - **4 mẫu cấu trúc chuẩn**: Hỗ trợ đầy đủ các dạng skill (Workflow, Task-based, Reference, Capabilities).
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: Clone vào thư mục `~/.claude/skills/skill-creator` (hoặc dùng `npx skills add somasays/skill-creator`).
    - **Thực thi**: Gọi lệnh trong chat AI (ví dụ: `/skill-creator --user "<Tên skill mong muốn>"`).

- **[Emily27-alt/find-skill](https://github.com/Emily27-alt/find-skill)**: Meta-Skill tự động tìm kiếm và gợi ý các AI Skill phù hợp khi bạn gặp bế tắc trong lập trình. Tự quét kho skill có sẵn trên máy hoặc tìm kiếm skill uy tín trên GitHub và chỉ cài đặt khi được bạn xác nhận.
  - 🏷️ **Tags**: `Meta-Skill`, `Skill-Discovery`, `Troubleshooting`, `Workflow`, `Claude-Code`
  - ⭐ **Tính năng chính**:
    - **Tìm kiếm 2 tầng**: Quét kho skill cục bộ trên máy trước, nếu không có mới tìm kiếm trên GitHub.
    - **Phân tích bế tắc tự động**: Nhận diện lỗi từ ngữ cảnh trò chuyện để đề xuất đúng công cụ gỡ rối.
    - **An toàn & Minh bạch**: Cho xem trước nội dung skill và cảnh báo bảo mật trước khi cài.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: Clone vào `~/.claude/skills/find-skill`.
    - **Thực thi**: Gõ lệnh `/find-skill` trong chat AI để tìm công cụ giải quyết vấn đề.

