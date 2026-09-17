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
- [🎬 Skill Đồ Họa Động & Tạo Video](#-skill-đồ-họa-động--tạo-video)
- [📐 Skill Thiết Kế 3D, CAD & Phần Cứng](#-skill-thiết-kế-3d-cad--phần-cứng)
- [🎙️ AI Âm Thanh & Xử Lý Giọng Nói](#️-ai-âm-thanh--xử-lý-giọng-nói)
- [🕹️ Kỹ Thuật Đảo Ngược & Phân Tích Game](#️-kỹ-thuật-đảo-ngược--phân-tích-game)
- [🎮 Skill Phát Triển Game](#-skill-phát-triển-game)

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

- **[tjboudreaux/humanizer](https://github.com/tjboudreaux/humanizer)**: Skill loại bỏ hoàn toàn "mùi AI" khỏi văn bản dựa trên nghiên cứu chống AI của Wikipedia. Nhận diện và thanh lọc 24 mẫu câu sáo rỗng đặc trưng của LLM (thổi phồng tính quan trọng, từ vựng rập khuôn, cấu trúc "không chỉ... mà còn") giúp câu chữ gãy gọn, tự nhiên như người viết.
  - 🏷️ **Tags**: `Humanizer`, `Writing-Style`, `Prompting`, `Anti-AI-Slop`, `Productivity`
  - ⭐ **Tính năng chính**:
    - **Bộ lọc 24 mẫu nhận dạng AI**: Tẩy sạch các thói quen hành văn cố hữu của LLM.
    - **Văn phong tự nhiên & trực diện**: Thay thế từ ngữ hoa mỹ bằng dữ kiện thực tế, bỏ các câu mở đầu/kết bài rườm rà.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: `npx skills add tjboudreaux/humanizer`
    - **Thực thi**: Dùng lệnh `/humanizer <đoạn văn>` trong chat AI.

- **[diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)**: Cổng AI Gateway mã nguồn mở kết nối 352 nhà cung cấp AI (khai thác ~1.51 tỷ token miễn phí/tháng từ 90+ gói Free Tier). Hỗ trợ Claude Code, Cursor, Antigravity với cơ chế auto-fallback chống nghẽn và tích hợp nén token RTK + Caveman giảm tới ~89% dung lượng.
  - 🏷️ **Tags**: `AI-Gateway`, `Free-Tokens`, `Token-Optimization`, `Proxy`, `Multi-Provider`
  - ⭐ **Tính năng chính**:
    - **Tận dụng 1.51B Free Tokens**: Tự động tổng hợp các dịch vụ AI miễn phí qua một endpoint chuẩn OpenAI duy nhất.
    - **Auto-fallback 0s**: Tự động nhảy sang nhà cung cấp dự phòng khi chạm rate limit.
    - **Nén token tích hợp**: Kết hợp thuật toán RTK và Caveman giảm tải chi phí token tối đa.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: `npm install -g omniroute` (hoặc qua Docker).
    - **Thực thi**: Chạy `omniroute start` và trỏ Base URL của AI Agent về `http://localhost:3000/v1`.

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

- **[nilbuild/page-mascot](https://github.com/nilbuild/page-mascot)**: Skill và component React nhúng linh vật tương tác lên trang web. Linh vật tự động dõi mắt nhìn theo con trỏ chuột và biểu cảm khi click; AI có khả năng tự vẽ 9 hướng nhìn và 9 trạng thái cảm xúc từ mô tả của bạn để chèn thẳng vào code.
  - 🏷️ **Tags**: `Mascot`, `Interactive-UI`, `Sprite-Animation`, `React`, `UI-UX`
  - ⭐ **Tính năng chính**:
    - **Tương tác chuột 360°**: Chuyển động quay đầu theo tọa độ chuột và phản hồi khi người dùng chạm vào.
    - **AI tự tạo Sprite Sheet**: AI tự sinh toàn bộ frame góc nhìn và biểu cảm, kiểm tra độ mượt chuyển cảnh trước khi gắn vào page.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: `npx skills add nilbuild/page-mascot --skill page-mascot --global --yes`

- **[lnkiai/m3e-canvas](https://github.com/lnkiai/m3e-canvas)**: Công cụ phác thảo UI Material 3 Expressive trên web và tự động dịch bản vẽ thành Prompt kỹ thuật chuẩn xác cho AI coding agents. Hỗ trợ kéo thả component, kết nối luồng màn hình tương tác và xuất prompt sinh mã nguồn cho Android hoặc Web.
  - 🏷️ **Tags**: `Material-Design`, `M3-Expressive`, `UI-Canvas`, `Design-to-Prompt`, `React`, `UI-UX`
  - ⭐ **Tính năng chính**:
    - **Thư viện Material 3 Expressive đầy đủ**: Kéo thả linh hoạt các nút magnetic, adaptive layouts, shape-morphing loaders.
    - **Tạo Prompt cho AI một chạm**: Tự động chuyển đổi toàn bộ visual layout, màu sắc và hành vi thành câu lệnh tối ưu cho Claude Code, Cursor, Antigravity.
  - 🛠️ **Sử dụng trực tiếp**: Mở web [lnkiai.github.io/m3e-canvas](https://lnkiai.github.io/m3e-canvas/), thiết kế và sao chép prompt dán vào AI chat.

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

---

## 🎬 Skill Đồ Họa Động & Tạo Video

> Các skill giúp AI lập trình video, motion graphics, hiệu ứng chuyển động và render video tự động từ code (Video as Code).

- **[haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill)**: Biến AI thành Motion Designer chuyên nghiệp lập trình video MP4 từ React và Remotion. Tạo video chính xác 100% về text, màu sắc và timeline, hỗ trợ animation cao cấp (spring, film grain, word-synced captions) và tự soi frame sửa lỗi trước khi xuất video.
  - 🏷️ **Tags**: `Remotion`, `React-Video`, `Motion-Graphics`, `Video-Editor`, `AI-Skill`
  - ⭐ **Tính năng chính**:
    - **Lập trình Video bằng React**: Không bị ảo giác méo hình như AI tạo video pixel, chỉnh sửa code linh hoạt.
    - **Tự động hóa toàn diện**: Tự dựng cảnh, canh nhịp nhạc, phụ đề tự động và vòng lặp render-tự kiểm tra frame.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: Clone vào `~/.claude/skills/remotion`.
    - **Thực thi**: Yêu cầu tạo video trực tiếp trong chat AI (ví dụ: *"Tạo video intro 15s chuẩn Reels bằng Remotion"*).

---

## 📐 Skill Thiết Kế 3D, CAD & Phần Cứng

> Các skill giúp AI thiết kế mô hình 3D kỹ thuật, cơ khí chính xác, vỏ hộp linh kiện và xuất file chuẩn in 3D / gia công CNC.

- **[earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)**: Thư viện AI skills chuyên sâu cho CAD, CAE và CAM. Cho phép AI thiết kế mô hình 3D cơ khí chính xác (vỏ hộp, giá đỡ, bản lề) từ mô tả văn bản, tự động đo đạc dung sai và xuất ra file STEP (chuẩn CAD) hoặc STL/3MF (in 3D).
  - 🏷️ **Tags**: `CAD`, `3D-Modeling`, `3D-Printing`, `STEP-Export`, `STL`, `Hardware`
  - ⭐ **Tính năng chính**:
    - **Mô hình hóa tham số bằng Python**: Sử dụng engine `build123d` tạo chi tiết cơ khí chuẩn xác thay vì vẽ lưới polygon lộn xộn.
    - **Xuất file chuẩn công nghiệp**: Xuất trực tiếp định dạng STEP cho phần mềm cơ khí, STL cho máy in 3D và URDF cho mô phỏng robot.
  - 🛠️ **Cách sử dụng nhanh**:
    - **Cài đặt**: Cài đặt runtime Python và Playwright (`pip install build123d cadgen && python -m playwright install chromium`).
    - **Thực thi**: Yêu cầu thiết kế chi tiết 3D trực tiếp trong chat AI (ví dụ: *"Tạo hộp đựng mạch Raspberry Pi chuẩn ốc M3"*).

---

## 🎙️ AI Âm Thanh & Xử Lý Giọng Nói

> Các công cụ và skill giúp nhân bản giọng nói, lồng tiếng video, đọc chính tả và sản xuất âm thanh chạy cục bộ (Local AI Audio).

- **[debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)**: Bộ công cụ mã nguồn mở nhân bản giọng nói (Voice Cloning) và lồng tiếng video chạy 100% cục bộ (Local AI). Hỗ trợ clone giọng từ audio mẫu, lồng tiếng video đa nhân vật, đọc chính tả và sản xuất sách nói chất lượng phòng thu không phụ thuộc API đám mây.
  - 🏷️ **Tags**: `Voice-Cloning`, `TTS`, `Video-Dubbing`, `Local-AI`, `Audiobook`, `Audio-Engine`
  - ⭐ **Tính năng chính**:
    - **Nhân bản giọng nói siêu tốc**: Clone chính xác chất giọng, cảm xúc từ đoạn âm thanh ngắn chỉ trong vài giây.
    - **Lồng tiếng video thông minh**: Tự động chuyển lời thành chữ, dịch thuật, chia vai người nói và khớp thời gian video.
    - **100% Riêng tư & Miễn phí**: Chạy trực tiếp trên phần cứng máy tính cá nhân, tích hợp sẵn Whisper, F5-TTS, CosyVoice.
  - 🛠️ **Sử dụng**: Tải bản cài đặt tại GitHub Releases hoặc truy cập [voicestudio.sh](https://voicestudio.sh).

---

## 🕹️ Kỹ Thuật Đảo Ngược & Phân Tích Game

> Các công cụ dịch ngược (Reverse Engineering), bóc tách metadata, phân tích nhị phân và modding cho game, ứng dụng.

- **[dsgaming-mrd/Il2CppDumper-GUI-Fixed](https://github.com/dsgaming-mrd/Il2CppDumper-GUI-Fixed)**: Công cụ giao diện đồ họa (GUI) hỗ trợ trích xuất metadata và khôi phục dummy DLLs từ game Unity biên dịch dạng IL2CPP (Android/iOS). Tự động tạo script hỗ trợ nạp tên hàm và cấu trúc vào IDA Pro, Ghidra.
  - 🏷️ **Tags**: `Reverse-Engineering`, `Unity`, `IL2CPP`, `Game-Modding`, `IDA-Pro`, `Ghidra`
  - ⭐ **Tính năng chính**:
    - **Giao diện trực quan**: Thao tác chọn file và xuất cấu trúc chỉ với vài cú click chuột.
    - **Hỗ trợ đa nền tảng game**: Xử lý mượt mà cả APK Android (`libil2cpp.so`) lẫn binary iOS.
    - **Xuất script phân tích**: Tự sinh script map tên hàm cho các disassembler hàng đầu (IDA Pro, Ghidra).
  - 🛠️ **Cách sử dụng**: Chạy file GUI trên Windows, nạp file nhị phân của game cùng `global-metadata.dat` để xuất DLLs.

---

## 🎮 Skill Phát Triển Game

> Các skill giúp AI thiết kế, lập trình game 2D/3D trên trình duyệt, vẽ sprite pixel art, tạo âm thanh chiptune và tự động kiểm thử gameplay.

- **[PlayableIntelligence/game-creator](https://github.com/PlayableIntelligence/game-creator)**: Bộ AI skill biến ý tưởng thành game trình duyệt 2D (Phaser) hoặc 3D (Three.js) hoàn chỉnh chỉ trong vài phút. Tự động vẽ sprite pixel art, tạo âm thanh chiptune, có subagent QA tự chơi thử để vá lỗi và hỗ trợ deploy kiếm tiền.
  - 🏷️ **Tags**: `Game-Development`, `Phaser`, `ThreeJS`, `Pixel-Art`, `Web-Game`, `Playwright-QA`
  - ⭐ **Tính năng chính**:
    - **Tạo game trọn gói một lệnh**: Dựng khung kiến trúc chuẩn (EventBus, GameState, Scenes), vẽ đồ họa và chèn nhạc nền tự động.
    - **Vòng lặp tự test (Automated QA)**: Mở trình duyệt ẩn chơi thử, chụp màn hình và tự fix code nếu phát hiện bug gameplay.
  - 🛠️ **Cách sử dụng**: Cài đặt bằng `npx skills add playableintelligence/game-creator`, sau đó gõ `/game-creator:viral-game 2d <tên-game>` trong chat AI.
- **[Gamezxz/pixel-art-studio](https://github.com/Gamezxz/pixel-art-studio)**: Skill biến AI thành họa sĩ Pixel Art thực thụ bằng Python/Pillow. Tự vẽ chuẩn xác từng pixel trên lưới (grid-perfect), tự soi frame phê bình sửa lỗi, vẽ animation nhân vật 4 hướng và xuất spritesheet kèm file JSON tương thích Aseprite, Godot, Phaser.
  - 🏷️ **Tags**: `Pixel-Art`, `Spritesheet`, `Game-Art`, `Game-Development`, `Animation`, `Python-Pillow`
  - ⭐ **Tính năng chính**:
    - **Vẽ pixel có tính toán**: Tự đặt từng hạt màu trên lưới tọa độ, loại bỏ hoàn toàn lỗi nhòe viền và méo hình của AI diffusion.
    - **Tạo Spritesheet game chuyên nghiệp**: Tự làm animation bước đi 4 hướng, idle, bảng màu chuẩn retro (PICO-8, Game Boy).
    - **Vòng lặp tự thẩm định (Self-critique loop)**: Tự trích xuất hình ảnh, soi lỗi tương phản và bóng đổ để vẽ lại trước khi bàn giao.
  - 🛠️ **Cách sử dụng**: Cài đặt vào thư mục skill và yêu cầu vẽ sprite trực tiếp trong chat AI (ví dụ: *"Vẽ quái vật rồng 64x64 dạng GIF"*).







