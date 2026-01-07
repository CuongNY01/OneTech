# Dự án: Website Thương mại điện tử OneTech

## Mục lục
1.  [Giới thiệu](#giới-thiệu)
2.  [Tính năng chính](#tính-năng-chính)
3.  [Yêu cầu phi chức năng](#yêu-cầu-phi-chức-năng)
4.  [Kiến trúc & Công nghệ](#kiến-trúc--công-nghệ)
5.  [Kết quả đạt được](#kết-quả-đạt-được)
6.  [Thông tin dự án](#thông-tin-dự-án)

## 1. Giới thiệu

Trong bối cảnh bùng nổ của thương mại điện tử và quá trình chuyển đổi số, dự án **"Phát triển website thương mại điện tử OneTech"** được triển khai nhằm cung cấp một giải pháp bán hàng trực tuyến toàn diện, hiệu quả và tối ưu trải nghiệm người dùng. Mục tiêu chính của dự án là tối ưu hóa quy trình kinh doanh, tăng cường khả năng tiếp cận khách hàng và tạo lợi thế cạnh tranh mạnh mẽ trên thị trường số.

Website OneTech được xây dựng để trở thành một nền tảng vững chắc, linh hoạt và dễ dàng mở rộng, đáp ứng nhu cầu ngày càng cao của các doanh nghiệp và người tiêu dùng trong kỷ nguyên số.

## 2. Tính năng chính

Dự án đã triển khai các chức năng cốt lõi sau:

*   **Quản lý Sản phẩm (Product Management System - PMS):**
    *   Thêm, sửa, xóa sản phẩm một cách dễ dàng.
    *   Quản lý thông tin chi tiết sản phẩm: tên, mô tả, giá (gốc, khuyến mãi), danh mục, thương hiệu, số lượng tồn kho, hình ảnh, SKU, và các thuộc tính khác (màu sắc, kích thước).
    *   Tổ chức sản phẩm theo danh mục và danh mục con.
    *   Theo dõi tồn kho tự động và cảnh báo khi số lượng thấp.

*   **Quản lý Đơn hàng (Order Management System - OMS):**
    *   Tự động tạo đơn hàng khi khách hàng hoàn tất thanh toán.
    *   Quản lý thông tin chi tiết đơn hàng: mã đơn hàng, thông tin khách hàng, danh sách sản phẩm, tổng tiền, phương thức thanh toán, trạng thái đơn hàng (chờ xử lý, đã xác nhận, đang giao, đã giao, đã hủy).
    *   Quản trị viên có thể cập nhật trạng thái đơn hàng theo tiến độ.
    *   Khách hàng có thể xem lịch sử các đơn hàng đã đặt.

*   **Quản lý Khách hàng & Phân quyền:**
    *   Đăng ký và đăng nhập tài khoản (bằng tài khoản hiện có hoặc mạng xã hội).
    *   Khách hàng có thể xem và chỉnh sửa thông tin cá nhân.
    *   Định nghĩa các vai trò người dùng (khách hàng, quản trị viên, nhân viên bán hàng) và gán quyền truy cập tương ứng.
    *   Quản trị viên có thể thêm, sửa, xóa tài khoản quản trị.

*   **Tìm kiếm & Lọc Sản phẩm:**
    *   Tìm kiếm sản phẩm theo từ khóa (tên, mô tả, SKU).
    *   Lọc sản phẩm theo danh mục, thương hiệu, khoảng giá, thuộc tính (màu sắc, kích thước), đánh giá.
    *   Sắp xếp sản phẩm theo giá (tăng/giảm dần), tên (A-Z/Z-A), sản phẩm mới nhất, bán chạy nhất.

*   **Giỏ hàng & Quy trình Thanh toán:**
    *   Thêm, xóa, cập nhật số lượng sản phẩm trong giỏ hàng.
    *   Tự động cập nhật tổng giá trị giỏ hàng.
    *   Quy trình thanh toán an toàn, linh hoạt: nhập thông tin giao hàng, lựa chọn phương thức vận chuyển và tính toán chi phí.
    *   Hỗ trợ nhiều phương thức thanh toán: COD (thanh toán khi nhận hàng), chuyển khoản ngân hàng, ví điện tử, cổng thanh toán trực tuyến.
    *   Cho phép áp dụng mã giảm giá.
    *   Xác nhận đơn hàng trước khi thanh toán.

*   **Quản lý Khuyến mãi & Mã giảm giá:**
    *   Quản trị viên có thể tạo các mã giảm giá với điều kiện áp dụng linh hoạt (phần trăm giảm, số tiền giảm, giá trị đơn hàng tối thiểu, sản phẩm áp dụng, thời hạn sử dụng).
    *   Thiết lập và quản lý các chương trình khuyến mãi theo thời gian, sản phẩm hoặc danh mục.
    *   Hiển thị các khuyến mãi và mã giảm giá có sẵn cho khách hàng.

*   **Phân tích dữ liệu & Báo cáo:**
    *   Thống kê doanh thu theo ngày, tuần, tháng, năm.
    *   Liệt kê các sản phẩm bán chạy nhất.
    *   Phân tích hành vi mua sắm của khách hàng, danh sách khách hàng mới.
    *   Theo dõi số lượng tồn kho và cảnh báo liên quan.
    *   Dashboard tổng quan hiển thị các chỉ số kinh doanh quan trọng.

*   **Hệ thống Thông báo (Notification System):**
    *   Gửi email/SMS xác nhận đơn hàng, cập nhật trạng thái đơn hàng cho khách hàng.
    *   Thông báo cho quản trị viên về đơn hàng mới, sản phẩm tồn kho thấp hoặc vấn đề hệ thống.
    *   Gửi thông báo về các chương trình khuyến mãi mới.

## 3. Yêu cầu phi chức năng

Dự án chú trọng các yêu cầu phi chức năng để đảm bảo chất lượng, hiệu suất và khả năng vận hành lâu dài:

*   **Hiệu năng (Performance):**
    *   Tốc độ tải trang nhanh: Trang tĩnh <4s, trang động <5s, thao tác xử lý dữ liệu <2s.
    *   Khả năng xử lý đồng thời: >= 300 yêu cầu/giây, có thể chịu tải tăng đột biến 2-3 lần.
    *   Tối ưu hóa: Caching (client-side & server-side), nén/lazy loading hình ảnh, Content Delivery Network (CDN), tối ưu truy vấn cơ sở dữ liệu.
    *   Thời gian xử lý giao dịch quan trọng: Hoàn tất <2s.

*   **Tính sẵn sàng và tin cậy (Availability & Reliability):**
    *   Thời gian hoạt động (Uptime): Tối thiểu 99.2% mỗi tháng.
    *   Khả năng phục hồi sau sự cố: Sao lưu dữ liệu định kỳ (hàng ngày/giờ), cơ chế khôi phục dữ liệu nhanh chóng, tự động chuyển đổi sang máy chủ dự phòng (Failover).
    *   Xử lý lỗi (Error Handling): Bắt và xử lý lỗi duyên dáng (Graceful Degradation), cung cấp trang lỗi thân thiện (404, 500), ghi nhật ký lỗi chi tiết.
    *   Kiến trúc chịu lỗi (Fault Tolerance): Các thành phần độc lập, chịu lỗi cục bộ.

*   **Bảo mật (Security):**
    *   Mã hóa dữ liệu nhạy cảm (thông tin cá nhân, mật khẩu, thẻ tín dụng) cả khi lưu trữ và truyền tải. Mật khẩu hash và salt.
    *   Xác thực và phân quyền (Authentication & Authorization): Yêu cầu mật khẩu phức tạp, tích hợp 2FA, cơ chế RBAC chặt chẽ.
    *   Chống tấn công mạng: ORM/parameterized queries (chống SQL Injection), mã hóa đầu ra/làm sạch dữ liệu (chống XSS), token CSRF, giới hạn số lượng yêu cầu (chống Brute Force, DDoS nhẹ).
    *   Giao thức HTTPS: Mã hóa mọi kết nối.
    *   Kiểm tra lỗ hổng bảo mật: Định kỳ quét lỗ hổng, cập nhật thư viện/framework.
    *   Input Validation: Kiểm tra và xác thực dữ liệu đầu vào kỹ lưỡng.

*   **Khả năng mở rộng và bảo trì (Scalability & Maintainability):**
    *   Khả năng mở rộng (Scalability): Thiết kế hỗ trợ mở rộng ngang (Horizontal Scaling) và dọc (Vertical Scaling), thiết kế phi trạng thái (Stateless Design).
    *   Khả năng bảo trì (Maintainability): Kiến trúc module rõ ràng, mã nguồn sạch (Clean Code), tài liệu hóa chi tiết, kiểm thử tự động (Unit/Integration/End-to-end Tests).
    *   Tương thích (Compatibility): Hiển thị và hoạt động tốt trên các trình duyệt phổ biến và mọi thiết bị (Responsive Web Design).

## 4. Kiến trúc & Công nghệ

Dự án được xây dựng dựa trên kiến trúc Client-Server với mô hình API-driven (headless) và sử dụng các công nghệ hiện đại:

*   **Kiến trúc hệ thống:** Client-Server (API-driven/headless)

*   **Frontend:**
    *   **Ngôn ngữ/Thư viện:** `ReactJS`, `HTML5`, `CSS3`, `JavaScript`
    *   **Framework CSS:** `Tailwind CSS` (ưu tiên) hoặc `Bootstrap` (nếu cần UI components sẵn có).
    *   **Framework (tùy chọn cho SEO/trang tĩnh):** `Next.js` (dựa trên React) để hỗ trợ SSR và SSG.
    *   **Công cụ build:** `Webpack`/`Vite`

*   **Backend:**
    *   **Ngôn ngữ lập trình:** `Python`
    *   **Framework Web:** `Django REST Framework (DRF)`
    *   **Thư viện phụ trợ:** `Pillow` (xử lý hình ảnh), `django-filter` (lọc dữ liệu), `djangorestframework-simplejwt` (xác thực JWT), các SDK tích hợp cổng thanh toán.

*   **Cơ sở dữ liệu (Database):**
    *   `PostgreSQL` (hệ quản trị cơ sở dữ liệu quan hệ mạnh mẽ và ổn định).

*   **Hạ tầng & DevOps:**
    *   **Nhà cung cấp đám mây (Cloud Provider):** `AWS` (Amazon Web Services)
        *   `Amazon EC2`: Máy chủ ảo cho backend.
        *   `Amazon RDS for PostgreSQL`: Dịch vụ CSDL quản lý.
        *   `Amazon S3`: Lưu trữ tệp tĩnh (hình ảnh, CSS, JS).
        *   `Amazon CloudFront`: CDN để phân phối nội dung tĩnh.
        *   `Elastic Load Balancing (ELB)`: Phân phối lưu lượng truy cập.
    *   **Hệ thống quản lý mã nguồn:** `Git`/`GitHub`
    *   **Containerization:** `Docker` (đóng gói ứng dụng vào container), `Docker Compose` (quản lý đa container môi trường phát triển).
    *   **CI/CD (Tích hợp & Triển khai liên tục):** `GitHub Actions` (tự động hóa kiểm thử, build, deploy).

## 5. Kết quả đạt được

Dự án "Phát triển website thương mại điện tử OneTech" đã hoàn thành trong 9 tuần và đạt được các kết quả quan trọng:

*   Xây dựng thành công một website thương mại điện tử với giao diện người dùng thân thiện, responsive, và đầy đủ các chức năng cốt lõi (quản lý sản phẩm, đơn hàng, khách hàng, giỏ hàng, thanh toán, khuyến mãi, báo cáo, thông báo).
*   Tích hợp thành công với API backend mạnh mẽ được phát triển bằng Django REST Framework, đảm bảo hiển thị dữ liệu động và xử lý tương tác người dùng.
*   Triển khai hệ thống quản trị Django Admin trực quan, giúp quản lý dữ liệu hiệu quả.
*   Áp dụng các công nghệ hiện đại và quy trình DevOps (Docker, AWS, CI/CD) để tối ưu hóa quá trình phát triển và triển khai.
*   Dự án đã tạo ra một nền tảng vững chắc, có tiềm năng lớn cho việc phát triển và mở rộng các tính năng trong tương lai.

## 6. Thông tin dự án

*   **Tên dự án**: Phát triển website thương mại điện tử OneTech
*   **Sinh viên thực hiện**: Hà Đình Cường
*   **Mã sinh viên**: 20220425
*   **Lớp hành chính**: DCCNTT13.10.3
*   **Giảng viên hướng dẫn**: Thầy Nguyễn Trường Giang
*   **Đơn vị thực tập**: Công ty Cổ phần Giải pháp Công nghệ VOTC
*   **Năm hoàn thành**: 2025
