# Dự án pilot: hybrid-video

Repo này là dự án pilot đầu tiên cho mục tiêu "Main agent điều phối các coding agent".

## Cách làm việc trong repo này

- Main agent là Muse, giữ vai trò chia việc, giao việc, kiểm chứng và gộp code.
- Mỗi phần việc có một phiếu trong thư mục `TASKS`, gồm mục tiêu, ngữ cảnh, tiêu chí hoàn thành và lệnh kiểm thử.
- Mỗi agent làm trên một branch riêng theo mẫu `agent/<agent>-<mã việc>`, chỉ gộp vào nhánh chính sau khi kiểm thử đạt.

## Trạng thái

- Đã chốt repo pilot ngày 2026-10-30 theo quyết định của Truong.
- Nội dung chức năng của dự án chưa được mô tả. Việc đầu tiên sẽ bắt đầu khi Truong chốt yêu cầu chức năng đầu tiên.
- Agent sẵn sàng ở thời điểm khởi tạo: Gemini qua API và các subagent của Muse. Codex và Claude Code đã cài trên máy của Muse nhưng chưa đăng nhập, đang bỏ qua theo quyết định của Truong.
