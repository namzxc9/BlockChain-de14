ỨNG DỤNG BÌNH CHỌN DỰA TRÊN SỐ LƯỢNG TOKEN SỞ HỮU

Đề tài xây dựng một hệ thống bình chọn phi tập trung, nơi quyền bỏ phiếu được xác định dựa trên số lượng token mà người dùng sở hữu. Hệ thống thay thế nguyên tắc “mỗi người một phiếu” bằng cơ chế Voting Power – quyền biểu quyết tỉ lệ thuận với lượng token nắm giữ.

Toàn bộ quá trình bình chọn được triển khai trên nền tảng blockchain, đảm bảo tính minh bạch, bảo mật và không thể thay đổi kết quả sau khi được ghi nhận. Ứng dụng phù hợp với các hệ sinh thái Web3, tổ chức tự trị phi tập trung (DAO), hoặc những mô hình cần sự tham gia biểu quyết minh bạch từ cộng đồng.

🧠 Chức năng chính

- Kết nối ví người dùng thông qua Metamask.

- Tự động truy xuất số lượng token đang sở hữu.

- Giao diện thân thiện, hiển thị lựa chọn và tiến trình bình chọn.

- Bình chọn theo trọng số tương ứng với số token.

- Lưu trữ kết quả bình chọn trực tiếp trên blockchain.

- Cập nhật kết quả thời gian thực, không thể bị thay đổi.

Công nghệ sử dụng

- Frontend: ReactJS, Web3.js

- Smart Contract: Solidity

- Blockchain: Ethereum Testnet (Goerli, Sepolia,...)

- Ví điện tử: Metamask

🔁Chu trình hoạt động

Kết nối ví: Người dùng kết nối ví Metamask vào hệ thống.

Truy xuất token: Hệ thống đọc số lượng token người dùng sở hữu.

Hiển thị lựa chọn: Người dùng chọn phương án muốn bình chọn.

Xác nhận giao dịch: Người dùng xác nhận phiếu bầu qua ví.

Ghi nhận trên blockchain: Phiếu bầu (gồm địa chỉ ví và số token) được ghi nhận và tính vào tổng điểm bình chọn.

Tổng hợp kết quả: Kết quả bình chọn được cập nhật theo thời gian thực dựa trên tổng số token bình chọn cho từng phương án.

💡 Mục tiêu mở rộng trong tương lai

- Hỗ trợ nhiều loại token: Cho phép người dùng bình chọn bằng nhiều loại token tùy cấu hình dự án.

- Thêm cơ chế delegation (ủy quyền): Người dùng có thể ủy quyền quyền biểu quyết cho người khác.

- Tích hợp DAO framework: Mở rộng để vận hành trong một tổ chức tự trị hoàn chỉnh.

- Hệ thống chống spam và lạm dụng: Kết hợp các phương pháp kiểm soát Sybil Attack (như KYC hoặc Proof of Identity).

- Dashboard quản trị nâng cao: Giao diện cho quản trị viên theo dõi quá trình và thiết lập các đợt bình chọn dễ dàng.

👨‍💻 Tác giả: Nguyễn Hoài Nam
