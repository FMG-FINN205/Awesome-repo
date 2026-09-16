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

- [🤖 AI / LLM Tools & Agents](#-ai--llm-tools--agents)

---

## 🤖 AI / LLM Tools & Agents

> Tổng hợp các công cụ, tiện ích mở rộng, framework và giải pháp tối ưu giúp phát triển, tương tác và làm việc hiệu quả với các mô hình AI/LLM và AI Coding Agents.

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
