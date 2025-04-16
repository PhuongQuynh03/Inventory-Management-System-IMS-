# Inventory-Management-System-IMS-
# Description 
Hệ thống quản lý kho hàng được xây dựng nhằm hỗ trợ doanh nghiệp kiểm soát toàn diện quá trình nhập, xuất và lưu trữ hàng hóa. Với mục tiêu tối ưu hóa quy trình vận hành, hệ thống giúp doanh nghiệp nâng cao hiệu suất làm việc, giảm thiểu sai sót và hạn chế thất thoát trong quản lý kho.

Phần mềm hướng đến các doanh nghiệp có quy mô kho vừa và lớn, cung cấp công cụ cho nhân viên thao tác dễ dàng trong việc quản lý sản phẩm, theo dõi số lượng tồn kho, cập nhật trạng thái hàng hóa theo thời gian thực. Mỗi mặt hàng đều được quản lý theo định danh rõ ràng (SKU, tên, đơn vị tính...), đồng thời ghi nhận chính xác lịch sử xuất – nhập cũng như vị trí lưu trữ.

Đặc biệt, hệ thống tích hợp mô hình sản xuất theo BOM (Bill of Materials), cho phép doanh nghiệp định nghĩa nguyên vật liệu cần thiết để sản xuất một thành phẩm cụ thể. Khi tạo lệnh sản xuất, nguyên vật liệu sẽ được tự động trừ kho, và hàng thành phẩm sẽ được ghi nhận sau khi sản xuất hoàn tất, giúp đảm bảo tính chính xác và minh bạch trong từng công đoạn.

Ngoài ra, hệ thống còn cung cấp các tính năng báo cáo trực quan về tồn kho, lịch sử giao dịch, tiến độ sản xuất, giúp nhà quản lý dễ dàng phân tích và đưa ra quyết định kịp thời. Chức năng cảnh báo tồn kho thấp hỗ trợ doanh nghiệp tránh tình trạng thiếu hụt nguyên liệu hoặc dư thừa hàng hóa không cần thiết.

Với khả năng tự động hóa cao và giao diện thân thiện, hệ thống không chỉ giúp tiết kiệm thời gian, mà còn nâng cao tính an toàn trong quản lý tài sản. Chủ doanh nghiệp có thể nắm bắt nhanh chóng số lượng, chủng loại hàng hóa, và tình trạng sản xuất một cách chính xác – từ đó nâng cao hiệu quả điều hành và phát triển kinh doanh bền vững.

Trong đó hệ thống sẽ đáp ứng được các yêu cầu sau:

- Quản lý sản phẩm & danh mục hàng hóa: Trong đó sẽ chứa thông tin hàng hóa như Mã SKU, Name, unit of measure, Description, Item. Ngoài ra User có quyền CRUD sản phẩm và Theo dỗi tồn kho của từng Sản phẩm.
  
- Quản lý Kho hàng:User có quyền tạo kho hàng (Ex: kho Hà Nội, Kho HCM), Kiểm soát hàng hóa theo từng kho, Lịch sử nhập kho, Cảnh báo tồn kho dưới mức tối thiểu.

- Quản lý nhập hàng: User Có quyền tạo phiếu nhập hàng, Chọn nhà cung cấp, ghi nhập ngày nhập (DD,MM,YYYY), Quantity, unit price, Update Số lượng tồn kho sau khi nhập, In và lưu trữ phiếu nhập.

- Quản lý xuất hàng: User tạo phiếu xuất kho cho sản phẩm, Chuyển kho, đơn hàng, Hệ thống sẽ tự động trừ tồn kho và update số lượng sau khi xuất, Ghi nhận lịch sử xuất kho và mục đích xuất.

- Quản lý sản xuất theo BOM: Tạo **bill of Materials** cho từng sản phẩm, User tạo lệnh sản uất và chọn sản phẩm cần sản xuất, số lượng, Hệ thống sẽ tự động trừ kho nguyên liệu theo POM, Cộng kho thành phẩm khi hoàn thành, Hệ thống liêu tục update tiến độ từng lệnh sản xuất và ghi nhận.
_EX: Để sản xuất 1 chiếc bàn, BOM sẽ ghi rõ cần 4 chân gỗ, 1 mặt bàn, 12 ốc vít → hệ thống dùng BOM để xử lý tồn kho đúng khi tạo lệnh sản xuất._

- Quản lý nhà cung cấp đối tác: User có quyền tạo doanh sách đối tác và có thể thêm sữa xóa, Hệ thống ghi nhận lịch sử giao dịch với từng nhà cung cấp kèm thền theo đó là sản phẩm nhận vào và xuất ra từ kho trong giao dịch với đối tác đó, Đánh giá mức độ cung ứng.

- Báo cáo & thống kê: Báo cáo tồn kho theo thời gian, Báo cáo nhập- xuất- tồn, Báo cáo sản lượng sản xuất, Báo cáo tình hình cung ứng nguyên liệu

- Phân quyền và Quản lý người dùng: Điều này giúp mọi hoạt động của user một cách minh bạch hơn như vai trò quản trị viên, nhận viên kho, nhân viên mua hàng, nhân viên sản xuất, Tên nhân viên sẽ đi cùng với vai trò (Vd Nguyễn văn A - Nhân viên xuất kho). Phân quyền thao tác từng vai trò, hệ thống tự động lưu lịch sử hoạt động của từng người dùng.
