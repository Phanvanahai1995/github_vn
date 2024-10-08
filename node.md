# Terms

- Git là một hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS), nó là một trong những hệ thống quản lý phiên bản phân tán phổ biến nhất hiện nay. Git cung cấp cho mỗi lập trình viên kho lưu trữ (repository) riêng chứa toàn bộ lịch sử thay đổi.

- GitHub là một hệ thống quản lý dự án và phiên bản code, hoạt động giống như một mạng xã hội cho lập trình viên. Các lập trình viên có thể clone lại mã nguồn từ một repository và Github chính là một dịch vụ máy chủ repository công cộng, mỗi người có thể tạo tài khoản trên đó để tạo ra các kho chứa của riêng mình để có thể làm việc.

- Repository (Repo)
- Branch: Nhánh
- Conflict: Xung đột
- Local
- Remote

# Commands

- git init
- git status: Trạng thái dự án (xem được tất cả các thay đổi)
- git add: Chuẩn bị lưu lại thời điểm hiện tại của dự án
- git reset: reset lại trạng thái trước đó
- git commit: Ghi chú lại trước khi lưu
- git log: Xem lại các commit đã lưu
- git log --oneline
- git checkout id_commit : Quay lại thời điểm commit của id
- git checkout {branch name}: Quay lại thời điểm hiện tại
- git branch
- git checkout -b {branch name}: Tạo nhánh mới
- git merge {branch name}: Gộp nhánh (git checkout master, đứng từ nhánh master để gộp lại)
- git branch -d {branch name}
- git push {url repo} {branch}
