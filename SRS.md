1. Business context & Business problem

  Business context:
Công ty ABC là doanh nghiệp cung cấp dịch vụ đặt xe trực tuyến, phục vụ ba nhóm người dùng chính:
- Khách hàng:
- Tài xế
- Nhân viên vận hành
  
Hiện tại doanh nghiệp đang sử dụng tổng đài và một ứng dụng đơn giản để tiếp nhận yêu cầu đặt xe. Tuy nhiên, nhiều hoạt động quan trọng vẫn phụ thuộc vào xử lý thủ công.

 Business problem:
 
Công ty ABC đang phụ thuộc nhiều vào quy trình đặt xe và phân công tài xế thủ công, hệ thống hiện tại chưa quản lý tập trung và chưa có khả năng mở rộng, dẫn đến khó khăn trong việc phục vụ khách hàng, điều hành chuyến đi, quản lý thanh toán và kiểm soát hoạt động kinh doanh.

2. Stakeholders

| Stakeholder | Vai trò |
|---|---|
| Khách hàng | Đặt xe nhanh, biết trạng thái chuyến, thanh toán và đánh giá |
| Tài xế | Nhận chuyến phù hợp, cập nhật trạng thái, quản lý phương tiện |
| Nhân viên vận hành | Quản lý và giám sát hoạt động đặt xe |
| Ban lãnh đạo | Theo dõi doanh thu, hiệu quả vận hành, báo cáo |
| Business Analyst | Làm rõ nghiệp vụ, yêu cầu và vấn đề còn chưa xác định |
| Nhà cung cấp thanh toán | Xử lý giao dịch thanh toán điện tử |
| Nhà cung cấp thông báo | Cung cấp các kênh gửi thông báo |
| Nhóm phát triển | Phân tích, thiết kế và xây dựng hệ thống |

Stakeholder Matrix mức ảnh hưởng của các stakehoder trong hệ thống
<img width="599" height="557" alt="Stakeholder Analysis Map Template" src="https://github.com/user-attachments/assets/3a68c918-63a6-4f98-bfea-9697d41fcd7e" />


3. Business Goal
- BG01: Tự động hóa quy trình đặt xe và phân công tài xế
- BG02: Nâng cao trải nghiệm khách hàng
- BG03: Nâng cao hiệu quả vận hành
- BG04: Tối ưu hóa việc sử dụng tài xế
- BG05: Quản lý doanh thu và thanh toán tập trung
- BG06: Cải thiện khả năng giám sát và ra quyết định
- BG07: Đảm bảo hệ thống hoạt động ổn định và liên tục
- BG08: Đảm bảo an toàn và bảo mật dữ liệu
- BG09: Đảm bảo khả năng mở rộng của nền tảng
- BG10: Tạo nền tảng linh hoạt cho phát triển trong tương lai

4. Scope(Phạm vi):
   
Phạm vi của dự án CAB System bao gồm việc phân tích, thiết kế, xây dựng và triển khai nền tảng đặt xe phục vụ khách hàng, tài xế và nhân viên vận hành. Hệ thống hỗ trợ quản lý tài khoản, đặt xe, tìm kiếm và phân công tài xế, theo dõi chuyến đi, quản lý vị trí, tính cước, thanh toán, thông báo, đánh giá, quản trị, báo cáo, phân quyền và lưu vết hoạt động. Hệ thống có khả năng tích hợp với các dịch vụ bên ngoài như thanh toán, bản đồ và thông báo nhằm đảm bảo tính linh hoạt và khả năng mở rộng. Các chức năng nâng cao như hệ thống thanh toán riêng, CRM/ERP, AI dự đoán nhu cầu, chương trình điểm thưởng và các dịch vụ vận tải mới chưa thuộc phạm vi của giai đoạn triển khai hiện tại.

5. Business Requirement

| Mã | Business Requirement | Mô tả |
|---|---|---|
| **BR01** | **Quản lý tài khoản** | Hệ thống phải hỗ trợ quản lý tài khoản và thông tin cá nhân của khách hàng, tài xế và nhân viên vận hành. |
| **BR02** | **Đặt chuyến** | Hệ thống phải cho phép khách hàng nhập điểm đón, điểm đến, lựa chọn loại xe và gửi yêu cầu đặt chuyến. |
| **BR03** | **Tìm kiếm và phân công tài xế** | Hệ thống phải tự động tìm và ưu tiên tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| **BR04** | **Xử lý phản hồi của tài xế** | Hệ thống phải xử lý trường hợp tài xế chấp nhận, từ chối hoặc không phản hồi và tiếp tục tìm tài xế khác khi cần thiết. |
| **BR05** | **Quản lý chuyến đi** | Hệ thống phải quản lý toàn bộ vòng đời của chuyến từ khi tạo yêu cầu đến khi hoàn thành hoặc hủy chuyến. |
| **BR06** | **Theo dõi vị trí và trạng thái chuyến** | Hệ thống phải hỗ trợ theo dõi vị trí tài xế và cung cấp trạng thái chuyến cho khách hàng và nhân viên vận hành. |
| **BR07** | **Quản lý tài xế và phương tiện** | Hệ thống phải hỗ trợ quản lý hồ sơ tài xế, thông tin phương tiện và trạng thái hoạt động của tài xế. |
| **BR08** | **Tính cước chuyến đi** | Hệ thống phải xác định số tiền khách hàng cần thanh toán dựa trên loại dịch vụ và thông tin chuyến đi. |
| **BR09** | **Thanh toán** | Hệ thống phải hỗ trợ thanh toán tiền mặt và thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| **BR10** | **Quản lý thông báo** | Hệ thống phải gửi thông báo đến khách hàng và tài xế về các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến. |
| **BR11** | **Quản lý lịch sử và đánh giá** | Hệ thống phải lưu lịch sử chuyến đi, thông tin thanh toán và cho phép khách hàng đánh giá tài xế sau chuyến. |
| **BR12** | **Quản lý và giám sát vận hành** | Hệ thống phải cung cấp chức năng để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và theo dõi các chuyến đang diễn ra. |
| **BR13** | **Quản lý sự cố và giao dịch** | Hệ thống phải hỗ trợ nhân viên vận hành xử lý các chuyến bị lỗi và tra cứu lịch sử giao dịch. |
| **BR14** | **Báo cáo và phân tích hoạt động** | Hệ thống phải cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| **BR15** | **Quản lý bảo mật và phân quyền** | Hệ thống phải xác thực người dùng, kiểm soát quyền truy cập và lưu vết các thao tác quản trị quan trọng. |
| **BR16** | **Mở rộng và tích hợp hệ thống** | Hệ thống phải cho phép bổ sung loại dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và các thành phần mới trong tương lai. |

## 6. Business Process

```mermaid
flowchart TD
    A([Khách hàng có nhu cầu đặt xe]) --> B[Nhập điểm đón và điểm đến]
    B --> C[Chọn loại xe]
    C --> D[Gửi yêu cầu đặt chuyến]

    D --> E[Hệ thống tiếp nhận yêu cầu]
    E --> F[Thông báo yêu cầu được tiếp nhận]
    F --> G[Tìm kiếm tài xế phù hợp]

    G --> H{Có tài xế phù hợp?}

    H -- Không --> I[Thông báo không tìm được tài xế]
    I --> J([Kết thúc yêu cầu])

    H -- Có --> K[Gửi yêu cầu đến tài xế phù hợp]
    K --> L{Tài xế phản hồi?}

    L -- Không phản hồi --> M[Chờ hết thời gian phản hồi]
    M --> N[Tìm tài xế tiếp theo]
    N --> G

    L -- Từ chối --> N

    L -- Chấp nhận --> O[Xác nhận tài xế nhận chuyến]
    O --> P[Thông báo thông tin tài xế cho khách hàng]
    P --> Q[Tài xế di chuyển đến điểm đón]

    Q --> R[Cập nhật trạng thái: Đã đến điểm đón]
    R --> S[Thông báo cho khách hàng]

    S --> T[Tài xế đón khách]
    T --> U[Cập nhật trạng thái: Đã đón khách]

    U --> V[Thực hiện chuyến đi]
    V --> W[Cập nhật trạng thái: Đang di chuyển]

    W --> X[Tài xế hoàn thành chuyến]
    X --> Y[Cập nhật trạng thái: Hoàn thành]

    Y --> Z[Tính cước chuyến đi]
    Z --> AA{Phương thức thanh toán}

    AA -- Tiền mặt --> AB[Khách hàng thanh toán tiền mặt]
    AA -- Điện tử --> AC[Gửi yêu cầu đến nhà cung cấp thanh toán]

    AC --> AD{Thanh toán thành công?}

    AD -- Không --> AE[Thông báo thanh toán thất bại]
    AE --> AF[Xử lý thanh toán lại theo chính sách]
    AF --> AC

    AD -- Có --> AG[Ghi nhận giao dịch thành công]
    AB --> AG

    AG --> AH[Thông báo kết quả thanh toán]
    AH --> AI[Khách hàng đánh giá tài xế]
    AI --> AJ[Lưu lịch sử chuyến đi và đánh giá]
    AJ --> AK([Kết thúc chuyến])
```
7. Functional Requirement Decompositon

| Mã | Functional Requirement |
|---|---|
| **FR01** | Đăng ký, đăng nhập và quản lý tài khoản người dùng. |
| **FR02** | Cập nhật thông tin cá nhân và trạng thái tài khoản. |
| **FR03** | Khách hàng nhập điểm đón, điểm đến và lựa chọn loại xe/dịch vụ. |
| **FR04** | Khách hàng gửi và kiểm tra trạng thái yêu cầu đặt chuyến. |
| **FR05** | Hệ thống tìm kiếm và lựa chọn tài xế phù hợp. |
| **FR06** | Hệ thống gửi yêu cầu chuyến đến tài xế. |
| **FR07** | Tài xế chấp nhận hoặc từ chối yêu cầu chuyến. |
| **FR08** | Hệ thống xử lý trường hợp tài xế không phản hồi và tìm tài xế thay thế. |
| **FR09** | Hệ thống thông báo khi không tìm được tài xế. |
| **FR10** | Hệ thống tạo và quản lý thông tin chuyến đi. |
| **FR11** | Tài xế cập nhật trạng thái chuyến đi. |
| **FR12** | Hệ thống xử lý hủy chuyến của khách hàng hoặc tài xế. |
| **FR13** | Hệ thống ghi nhận và cập nhật vị trí tài xế. |
| **FR14** | Khách hàng theo dõi trạng thái và vị trí chuyến đi. |
| **FR15** | Khách hàng xem thông tin tài xế và thời gian dự kiến đến. |
| **FR16** | Tài xế quản lý hồ sơ và thông tin phương tiện. |
| **FR17** | Tài xế chuyển trạng thái sẵn sàng hoặc không sẵn sàng nhận chuyến. |
| **FR18** | Nhân viên vận hành quản lý khách hàng, tài xế và phương tiện. |
| **FR19** | Hệ thống tính và lưu thông tin cước chuyến đi. |
| **FR20** | Khách hàng lựa chọn phương thức thanh toán. |
| **FR21** | Hệ thống xử lý thanh toán tiền mặt và thanh toán điện tử. |
| **FR22** | Hệ thống ghi nhận và thông báo kết quả thanh toán. |
| **FR23** | Hệ thống gửi thông báo đến khách hàng và tài xế. |
| **FR24** | Khách hàng xem lịch sử chuyến đi. |
| **FR25** | Khách hàng đánh giá tài xế sau khi hoàn thành chuyến. |
| **FR26** | Hệ thống lưu trữ lịch sử chuyến đi và đánh giá. |
| **FR27** | Nhân viên vận hành theo dõi các chuyến đang diễn ra và trạng thái tài xế. |
| **FR28** | Nhân viên vận hành xử lý các chuyến và giao dịch bị lỗi. |
| **FR29** | Nhân viên vận hành tra cứu thông tin chuyến đi và giao dịch. |
| **FR30** | Hệ thống cung cấp báo cáo về chuyến đi, doanh thu và hiệu quả tài xế. |
| **FR31** | Hệ thống xác thực và phân quyền người dùng theo vai trò. |
| **FR32** | Hệ thống bảo vệ dữ liệu cá nhân, vị trí và giao dịch. |
| **FR33** | Hệ thống lưu vết các thao tác quan trọng. |
| **FR34** | Hệ thống hỗ trợ tích hợp với các dịch vụ bên ngoài. |
| **FR35** | Hệ thống hỗ trợ mở rộng loại dịch vụ, phương thức thanh toán và kênh thông báo. |

8. Business Rules & Exception

| Mã | Business Rule | Mô tả |
|---|---|---|
| **BRL01** | **Xác thực tài khoản** | Người dùng phải đăng nhập và được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| **BRL02** | **Tài xế sẵn sàng nhận chuyến** | Chỉ tài xế có trạng thái **sẵn sàng** mới được hệ thống xem xét để phân công chuyến. |
| **BRL03** | **Phân công tài xế** | Hệ thống ưu tiên tài xế phù hợp và gần vị trí đón khách dựa trên các tiêu chí vận hành được doanh nghiệp xác định. |
| **BRL04** | **Thời gian phản hồi tài xế** | Tài xế phải phản hồi yêu cầu chuyến trong khoảng thời gian do doanh nghiệp quy định. |
| **BRL05** | **Tìm tài xế thay thế** | Nếu tài xế từ chối hoặc không phản hồi, hệ thống phải tiếp tục tìm tài xế phù hợp khác mà không yêu cầu khách hàng tạo lại chuyến. |
| **BRL06** | **Không tìm được tài xế** | Nếu không còn tài xế phù hợp, hệ thống phải thông báo rõ ràng cho khách hàng và kết thúc yêu cầu đặt chuyến. |
| **BRL07** | **Trạng thái chuyến** | Chuyến đi phải được quản lý theo các trạng thái hợp lệ và chỉ được chuyển sang trạng thái tiếp theo khi thỏa điều kiện nghiệp vụ. |
| **BRL08** | **Hoàn thành chuyến** | Chỉ chuyến đã được tài xế thực hiện và cập nhật hoàn thành mới được chuyển sang bước tính cước và thanh toán. |
| **BRL09** | **Tính cước** | Số tiền phải trả được xác định dựa trên loại dịch vụ và các thông tin chuyến đi theo chính sách giá của doanh nghiệp. |
| **BRL10** | **Thanh toán điện tử** | Giao dịch điện tử phải được thực hiện thông qua nhà cung cấp thanh toán bên ngoài; hệ thống CAB không lưu thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán. |
| **BRL11** | **Thanh toán thất bại** | Khi giao dịch điện tử thất bại, hệ thống phải thông báo cho khách hàng và cho phép xử lý lại theo chính sách của doanh nghiệp. |
| **BRL12** | **Đánh giá tài xế** | Khách hàng chỉ được đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **BRL13** | **Phân quyền** | Người dùng chỉ được thực hiện các chức năng phù hợp với vai trò và quyền được cấp. |
| **BRL14** | **Quản trị nhạy cảm** | Các thao tác quản trị nhạy cảm chỉ được thực hiện bởi nhân viên có quyền phù hợp. |
| **BRL15** | **Bảo vệ dữ liệu** | Thông tin cá nhân, phương tiện, vị trí và giao dịch phải được bảo vệ và chỉ được truy cập bởi các đối tượng được cấp quyền. |
| **BRL16** | **Lưu vết hoạt động** | Các thao tác quản trị và nghiệp vụ quan trọng phải được ghi nhận để phục vụ kiểm tra và xử lý sự cố. |
| **BRL17** | **Trạng thái tài xế** | Tài xế đang thực hiện một chuyến không được đồng thời nhận một chuyến khác nếu chính sách vận hành không cho phép. |
| **BRL18** | **Thông báo sự kiện** | Các sự kiện quan trọng như nhận chuyến, tài xế đến, hoàn thành chuyến và kết quả thanh toán phải được thông báo đến đối tượng liên quan. |


| Mã | Exception | Điều kiện | Cách xử lý |
|---|---|---|---|
| **EX01** | **Không tìm được tài xế** | Không có tài xế phù hợp hoặc tất cả tài xế đều từ chối | Thông báo cho khách hàng và kết thúc yêu cầu. |
| **EX02** | **Tài xế không phản hồi** | Tài xế không phản hồi trong thời gian quy định | Hệ thống bỏ qua tài xế và tìm tài xế khác. |
| **EX03** | **Tài xế từ chối chuyến** | Tài xế từ chối yêu cầu | Hệ thống tiếp tục tìm tài xế khác. |
| **EX04** | **Mất kết nối khi đặt chuyến** | Khách hàng mất kết nối trong quá trình gửi yêu cầu | Hệ thống phải đảm bảo không tạo chuyến trùng và cho phép khách hàng kiểm tra lại trạng thái yêu cầu. |
| **EX05** | **Mất kết nối tài xế** | Không nhận được cập nhật từ tài xế | Giữ trạng thái hiện tại trong khoảng thời gian cho phép và thông báo cho bộ phận vận hành nếu cần. |
| **EX06** | **Thanh toán điện tử thất bại** | Nhà cung cấp thanh toán trả về kết quả thất bại | Thông báo khách hàng và cho phép thực hiện lại theo chính sách. |
| **EX07** | **Nhà cung cấp thanh toán không khả dụng** | Không thể kết nối với Payment Provider | Ghi nhận lỗi, thông báo khách hàng và không làm ảnh hưởng đến các chức năng khác của hệ thống. |
| **EX08** | **Lỗi dịch vụ thông báo** | Không thể gửi thông báo đến khách hàng hoặc tài xế | Ghi nhận lỗi và thực hiện cơ chế gửi lại theo chính sách. |
| **EX09** | **Tài xế hủy chuyến** | Tài xế hủy sau khi đã nhận chuyến | Cập nhật trạng thái và kích hoạt quy trình tìm tài xế thay thế nếu chính sách cho phép. |
| **EX10** | **Khách hàng hủy chuyến** | Khách hàng yêu cầu hủy chuyến | Kiểm tra điều kiện hủy và thực hiện theo chính sách của doanh nghiệp. |
| **EX11** | **Sai dữ liệu chuyến đi** | Thông tin điểm đón, điểm đến hoặc loại xe không hợp lệ | Không tạo chuyến và yêu cầu khách hàng nhập lại thông tin. |
| **EX12** | **Không cập nhật được vị trí** | Hệ thống không nhận được vị trí tài xế | Sử dụng vị trí gần nhất nếu có và thông báo tình trạng cho các bên liên quan. |
| **EX13** | **Lỗi hệ thống** | Một thành phần của hệ thống gặp sự cố | Cô lập thành phần lỗi, ghi log và đảm bảo các chức năng độc lập khác tiếp tục hoạt động nếu có thể. |
| **EX14** | **Trùng yêu cầu đặt chuyến** | Khách hàng gửi lại yêu cầu do mạng chậm/mất kết nối | Hệ thống kiểm tra yêu cầu trước đó để tránh tạo nhiều chuyến giống nhau. |


9. Data Modeling
    khách hàng có những thuộc tính gì...

### 9.1 Customer – Khách hàng

| Thuộc tính | Mô tả |
|---|---|
| CustomerID | Mã khách hàng |
| FullName | Họ và tên |
| Phone | Số điện thoại |
| Email | Email |
| PasswordHash | Mật khẩu đã mã hóa |
| DateOfBirth | Ngày sinh |
| Gender | Giới tính |
| Address | Địa chỉ |
| Status | Trạng thái tài khoản |
| CreatedAt | Thời gian tạo tài khoản |

### 9.2 Driver – Tài xế

| Thuộc tính | Mô tả |
|---|---|
| DriverID | Mã tài xế |
| FullName | Họ và tên |
| Phone | Số điện thoại |
| Email | Email |
| PasswordHash | Mật khẩu đã mã hóa |
| LicenseNumber | Số giấy phép lái xe |
| Status | Trạng thái tài khoản |
| AvailabilityStatus | Trạng thái sẵn sàng nhận chuyến |
| CurrentLocation | Vị trí hiện tại |
| Rating | Điểm đánh giá |
| CreatedAt | Thời gian tạo tài khoản |

### 9.3 Vehicle – Phương tiện

| Thuộc tính | Mô tả |
|---|---|
| VehicleID | Mã phương tiện |
| DriverID | Mã tài xế |
| LicensePlate | Biển số xe |
| VehicleType | Loại xe |
| Brand | Hãng xe |
| Model | Model xe |
| Color | Màu xe |
| Status | Trạng thái phương tiện |

### 9.4 Trip – Chuyến đi

| Thuộc tính | Mô tả |
|---|---|
| TripID | Mã chuyến |
| CustomerID | Mã khách hàng |
| DriverID | Mã tài xế |
| VehicleID | Mã phương tiện |
| PickupLocation | Điểm đón |
| Destination | Điểm đến |
| TripType | Loại dịch vụ |
| Status | Trạng thái chuyến |
| Distance | Khoảng cách |
| EstimatedFare | Cước dự kiến |
| ActualFare | Cước thực tế |
| StartTime | Thời gian bắt đầu |
| EndTime | Thời gian kết thúc |
| CreatedAt | Thời gian tạo chuyến |

### 9.5 Payment – Thanh toán

| Thuộc tính | Mô tả |
|---|---|
| PaymentID | Mã thanh toán |
| TripID | Mã chuyến |
| Amount | Số tiền thanh toán |
| PaymentMethod | Phương thức thanh toán |
| PaymentStatus | Trạng thái thanh toán |
| TransactionID | Mã giao dịch từ nhà cung cấp |
| PaymentTime | Thời gian thanh toán |

### 9.6 Rating – Đánh giá

| Thuộc tính | Mô tả |
|---|---|
| RatingID | Mã đánh giá |
| TripID | Mã chuyến |
| CustomerID | Mã khách hàng |
| DriverID | Mã tài xế |
| Score | Điểm đánh giá |
| Comment | Nội dung đánh giá |
| CreatedAt | Thời gian đánh giá |

### 9.7 Notification – Thông báo

| Thuộc tính | Mô tả |
|---|---|
| NotificationID | Mã thông báo |
| UserID | Mã người nhận |
| Type | Loại thông báo |
| Title | Tiêu đề |
| Content | Nội dung thông báo |
| Status | Trạng thái thông báo |
| CreatedAt | Thời gian tạo |

### 9.8 Staff – Nhân viên vận hành

| Thuộc tính | Mô tả |
|---|---|
| StaffID | Mã nhân viên |
| FullName | Họ và tên |
| Phone | Số điện thoại |
| Email | Email |
| PasswordHash | Mật khẩu đã mã hóa |
| RoleID | Mã vai trò |
| Status | Trạng thái tài khoản |
| CreatedAt | Thời gian tạo tài khoản |

### 9.9 Role – Vai trò

| Thuộc tính | Mô tả |
|---|---|
| RoleID | Mã vai trò |
| RoleName | Tên vai trò |
| Description | Mô tả vai trò |

11. Non-functional Requirement

| Mã | Tên | Mô tả |
|---|---|---|
| **NFR01** | **Hiệu năng** | Hệ thống phải có thời gian phản hồi phù hợp đối với các chức năng đặt chuyến, tìm tài xế và theo dõi trạng thái. |
| **NFR02** | **Khả năng chịu tải** | Hệ thống phải có khả năng phục vụ số lượng lớn khách hàng, tài xế và yêu cầu đặt chuyến đồng thời. |
| **NFR03** | **Khả năng mở rộng** | Các thành phần của hệ thống phải có khả năng mở rộng độc lập khi tải tăng cao. |
| **NFR04** | **Tính sẵn sàng** | Hệ thống phải hoạt động ổn định và hạn chế gián đoạn dịch vụ, đặc biệt trong thời gian nhu cầu tăng cao. |
| **NFR05** | **Độ tin cậy** | Lỗi tại một thành phần như thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động. |
| **NFR06** | **Khả năng phục hồi** | Hệ thống phải có khả năng xử lý và phục hồi khi xảy ra lỗi kết nối hoặc lỗi từ các dịch vụ bên ngoài. |
| **NFR07** | **Bảo mật** | Hệ thống phải bảo vệ thông tin cá nhân, phương tiện, vị trí và dữ liệu giao dịch khỏi truy cập trái phép. |
| **NFR08** | **Xác thực và phân quyền** | Hệ thống phải đảm bảo người dùng chỉ được truy cập các chức năng và dữ liệu phù hợp với quyền được cấp. |
| **NFR09** | **Bảo mật thanh toán** | Hệ thống không được lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán. |
| **NFR10** | **Ghi log và kiểm toán** | Hệ thống phải lưu vết các thao tác quan trọng và lỗi để phục vụ kiểm tra, giám sát và xử lý sự cố. |
| **NFR11** | **Toàn vẹn dữ liệu** | Hệ thống phải đảm bảo dữ liệu chuyến đi, thanh toán và trạng thái được lưu trữ chính xác và nhất quán. |
| **NFR12** | **Khả năng bảo trì** | Hệ thống phải dễ dàng bảo trì, sửa lỗi và nâng cấp các thành phần. |
| **NFR13** | **Khả năng triển khai** | Hệ thống phải cho phép triển khai hoặc cập nhật từng thành phần mà hạn chế ảnh hưởng đến các chức năng đang hoạt động. |
| **NFR14** | **Khả năng tích hợp** | Hệ thống phải có khả năng tích hợp với các dịch vụ bên ngoài như thanh toán, bản đồ và thông báo. |
| **NFR15** | **Khả năng sử dụng** | Giao diện phải rõ ràng, dễ sử dụng đối với khách hàng, tài xế và nhân viên vận hành. |
| **NFR16** | **Khả năng mở rộng chức năng** | Hệ thống phải cho phép bổ sung loại dịch vụ, phương thức thanh toán và kênh thông báo mới mà không cần thay đổi lớn toàn bộ hệ thống. |
| **NFR17** | **Khả năng giám sát** | Hệ thống phải hỗ trợ theo dõi trạng thái, lỗi và hiệu năng của các thành phần để phát hiện và xử lý sự cố kịp thời. |

11. Use case

12.  đặc tả Use case

13. Tiêu chí chấp nhận (AC) acceptance criteria: Quy tắc để xác nhận chức năng đấp ứng yêu cầu khách hàng

14. Truy xuất nguồn gốc yêu cầu (RTM)

