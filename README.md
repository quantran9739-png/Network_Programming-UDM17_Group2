
#  Multiplayer Caro Game 
**Project Code:** UDM_17
**Course:** Network Programming (Lập trình mạng)

---

##  Team Members & Roles (Thông tin nhóm)
Với đội hình 6 thành viên, nhóm áp dụng mô hình phát triển phần mềm cơ bản để tối ưu hiệu suất:

1. **Quan** - *Product Owner / Project Manager:* Quản lý tiến độ (Timeline), viết Proposal, chốt Requirement và điều phối task.
2. **[Tên TV 2]** - *System Architect / Backend Dev:* Thiết kế kiến trúc mạng (Client-Server), xử lý logic truyền tải dữ liệu (Socket/TCP).
3. **[Tên TV 3]** - *Game Logic Developer:* Xử lý thuật toán bàn cờ (kiểm tra thắng/thua ngang, dọc, chéo).
4. **[Tên TV 4]** - *UI/UX Designer & Frontend Dev:* Lên bản vẽ Figma và code giao diện người dùng (GUI), đồng hồ đếm ngược.
5. **[Tên TV 5]** - *QA Engineer (Tester):* Chịu trách nhiệm viết script chạy Stress Test, Performance Test theo yêu cầu của giảng viên.
6. **[Tên TV 6]** - *Technical Writer:* Tổng hợp tài liệu, chụp ảnh minh chứng, làm slide PPTX và quay video Demo cuối kỳ.

---

## 📁 Repository Structure (Cấu trúc thư mục)
Theo đúng tiêu chuẩn đánh giá của giảng viên / *Following the lecturer's strict requirements*:

- 📂 `Code/`: Contains all source code (Server, Client, GUI).
- 📂 `DOCX/`: Contains project proposals, business requirements, and system design documents.
- 📂 `Extra/`: Contains UI mockup images (Figma), proof of Stress/Performance tests, and demo videos.
- 📂 `PPTX/`: Contains presentation slides for the final report.

---

##  Project Scope & Requirements (Phạm vi dự án)

### Functional Requirements (Yêu cầu chức năng)
- **EN:** Client connects to Server via IP/Port. Automatic matchmaking for 2 players.
- **VI:** Client kết nối Server qua IP/Port. Tự động ghép bàn cho 2 người chơi.
- **EN:** Turn-based gameplay (X/O) with win/loss detection (5 in a row).
- **VI:** Chơi luân phiên (X/O), nhận diện thắng thua (5 quân liên tiếp).
- **EN:** Countdown timer for each turn. Auto-loss if time runs out.
- **VI:** Đồng hồ đếm ngược mỗi lượt. Hết giờ tự động xử thua.

### Non-Functional Requirements (Yêu cầu phi chức năng)
- **EN:** Must be a Windows GUI Application (No Web App).
- **VI:** Ứng dụng Desktop có giao diện đồ họa chạy trên Windows.
- **EN:** Must pass Stress Test and Performance Test with visual proof.
- **VI:** Hệ thống chịu tải tốt, cung cấp bằng chứng (hình ảnh/video) cho Stress Test.

---

##  Technology Stack (Công nghệ sử dụng)
- **Programming Language:** Python
- **Network Protocol:** TCP/IP Socket
- **GUI Framework:** Tkinter / PyQt
- **Design Tool:** Figma (for UI Mockups)

---

##  Project Progress (Tiến độ dự án)
*Checklist này sẽ được cập nhật hàng tuần (EOW) để tracking tiến độ / This checklist is updated weekly to ensure continuous progress.*

- [x] **Week 1:** Initialize GitHub structure, assign roles, draft ReadMe.
- [ ] **Week 2:** Finalize Proposal (`DOCX`), design UI Mockup (`Extra`), define network data structure.
- [ ] **Week 3:** Implement Core Socket Server/Client and basic UI (`Code`).
- [ ] **Week 4:** Integrate Game Logic and Countdown Timer.
- [ ] **Week 5:** Conduct Stress Tests (`Extra`), bug fixing.
- [ ] **Week 6:** Finalize Presentation (`PPTX`) and record Demo Video.
