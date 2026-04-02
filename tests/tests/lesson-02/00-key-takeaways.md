1. Version Control System

Version Control System quản lý phiên bản source code theo thời gian.

Lợi ích:

Xem được lịch sử thay đổi
Làm việc nhóm
Rollback code khi lỗi
So sánh sự khác nhau giữa các version

2. Git

Git là distributed version control system phổ biến nhất.

Các lệnh Git cơ bản

Kiểm tra trạng thái file:

git status

Thêm file vào staging:

git add .

Commit code:

git commit -m "message"

Push code:

git push origin main

Clone repo:

git clone <repo-url>

Pull code mới nhất:

git pull

kiểm tra danh sách commit
 
git log

3. JavaScript Basic
Khai báo biến
let name = "Huong"
const age = 18
var city = "HN"

Kiểu dữ liệu
string
number
boolean
null
undefined
object
So sánh

Strict equality (khuyên dùng):

5 === "5" // false

Loose equality (có ép kiểu):

5 == "5" // true
True/ False
False values:

false
0
""
null
undefined
NaN

Ví dụ:

if ("") {
  // không chạy
}
Best Practice
Luôn dùng === thay vì ==
