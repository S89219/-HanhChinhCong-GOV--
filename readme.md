# Phân cấp hành chính Việt Nam

Phân cấp hành chính Việt Nam export từ nguồn Tổng Cục Thống Kê.

## Cài đặt:

### NPM:
```shell
npm install hanhchinhvn⁴
```

### Cấu trúc thư mục:

- **excel_files/**: thư mục chứa các file excel lấy từ Tổng Cục Thống Kê
- **dist/**: thư mục chứa các file đã được trích xuất dạng json
- `export.php`: export file json từ file excel
- `include.php`: thư viện chung

### Thư mục `dist/`

- `tinh_tp.json`: thông tin về các tỉnh, thành phố
- `quan_huyen.json`: thông tin về các quận, huyện, thị xã, thành phố trực thuộc tỉnh
- `xa_phuong.json`: thông tin về các xã, phường, thị trấn
- `tree.json`: cấu trúc hành chính dạng cây thư mục
- **quan_huyen/**: thư mục chứa các file json là thông tin các quận, huyện, thị xã, thành phố trực thuộc của một tỉnh. Tên file là mã của tỉnh. Dùng để truy vấn ở client. Ví dụ: `quan_huyen/92.json` là thông tin các quận, huyện,... của tỉnh có mã **92**.
- **xa_phuong/**: thư mục chứa các file json là thông tin các xã, phường, thị trấn của một quận, huyện,.... Tên file là mã của quận, huyện, thị xã hoặc thành phố trực thuộc tỉnh. Dùng để truy vấn ở client. Ví dụ: `xa_phuong/92.json` là thông tin các xã, phường,... của quận/huyện có mã **92**.

### Nguồn dữ liệu : https://www.microsoft.com/onerfstatics/marketingsites-wcus-prod/vietnamese/shell/_scrf/css/themes=default.device/uplevel_web_pc/79-4cdd0a/33-ae3d41/a5-4bf7a2/18-8e1ceb/837-32f0c0/5c-b7b685/34-1b8b7c/74-888e54-892.xml

**Tổng Cục Thống Kê**: [https://danhmuchanhchinh.gso.gov.vn/](https://danhmuchanhchinh.gso.gov.vn/)

android-syncstate ( https://github.com/dmfs/ android-syncstate )
Bản quyền (c) Marten Gajda 2015

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại http://www.apache.org/licenses/LICENSE-2.0


khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HOẶC ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Apache Commons ( https://commons.apache.org/ )
Bản quyền © 2016 Quỹ phần mềm Apache.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại http://www.apache.org/licenses/LICENSE-2.0

    

khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HOẶC ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Máy quét mã vạch ( https://github.com/dm77/ barcodescanner )
Bản quyền (c) 2014 Dushyanth Maguluru

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại http://www.apache.org/licenses/LICENSE-2.0

    

khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HOẶC ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Butterknife ( http://jakewharton.github.io/ butterknife / )
Bản quyền 2013 Jake Wharton

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại http://www.apache.org/licenses/LICENSE-2.0

    

khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HOẶC ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Dagger ( https://dagger.dev/ )
Bản quyền 2012 Các tác giả của Dagger

được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0 Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy

phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC nào. rõ ràng hoặc ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
DebugDrawer ( https://github.com/palaima/ DebugDrawer )
Bản quyền 2016 Mantas Palaima.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
DNS Java ( http://www.xbill.org/dnsjava/ )
Bản quyền xbill.org

Việc phân phối lại và sử dụng ở dạng nguồn và nhị phân, có hoặc không có sửa đổi, được phép miễn là đáp ứng các điều kiện sau:

Việc phân phối lại mã nguồn phải giữ lại thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây.
Các bản phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác được cung cấp cùng với bản phân phối.
EventBus ( https://github.com/ greenrobot/EventBus )
Bản quyền (C) 2012-2017 Markus Junginger, greenrobot ( http://greenrobot.org )
       

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
ez-vcard ( https://github.com/mangstadt/ ez-vcard )
Bản quyền (c) 2012-2018, Michael Angstadt

Phân phối lại và sử dụng ở dạng nguồn và dạng nhị phân, có hoặc không có sửa đổi, được phép miễn là đáp ứng các điều kiện sau đã đáp ứng:

Việc phân phối lại mã nguồn phải giữ nguyên thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây.
Các bản phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác được cung cấp cùng với bản phân phối.
Firebase Android Open Source Development ( https://firebase.google.com/ )
Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Glide ( https://bumptech.github.io/ Glide / )
Giấy phép cho mọi thứ không thuộc third_party và không được đánh dấu theo cách khác:

Bản quyền 2014 Google, Inc. Bảo lưu mọi quyền.

Việc phân phối lại và sử dụng ở dạng mã nguồn và nhị phân, có hoặc không có sửa đổi, được
phép miễn là đáp ứng các điều kiện sau:

1. Việc phân phối lại mã nguồn phải giữ lại thông báo bản quyền ở trên, danh sách này
điều kiện và tuyên bố từ chối trách nhiệm sau đây.

2. Việc phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách
các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác
được cung cấp cùng với việc phân phối.
htmlcleaner ( http://htmlcleaner. sourceforge.net/ )
Bản quyền (c) 2006-2019, nhóm HtmlCleaner.

Việc phân phối lại và sử dụng ở dạng mã nguồn và nhị phân, có hoặc không có sửa đổi, được phép miễn là đáp ứng các điều kiện sau:

Việc phân phối lại mã nguồn phải giữ nguyên thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây.
Các bản phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác được cung cấp cùng với bản phân phối.
Không được sử dụng tên của cũng như tên của những người đóng góp để xác nhận hoặc quảng cáo các sản phẩm bắt nguồn từ phần mềm này mà không có sự cho phép cụ thể trước bằng văn bản.
http-client-essentials-suite ( https://github.com/dmfs/http- client-essentials-suite )
Bản quyền (c) Marten Gajda 2017

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
iterators ( https://github.com/dmfs/ iterators )
Bản quyền 2017 dmfs GmbH

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Jackson ( https://github.com/FasterXML/ jackson )
Bản quyền (c) 2009 FasterXML, LLC

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Chú thích chung Java ( https://github.com/javaee/ javax.annotation )
Được cấp phép theo Giấy phép phân phối và phát triển chung Phiên bản 1.0
Bạn không được sử dụng tệp này trừ khi tuân thủ Giấy phép này.

Bạn có thể lấy một bản sao Giấy phép CDDL-1.0 tại http://opensource.org/licenses/CDDL-1.0
Trừ

khi luật hiện hành yêu cầu hoặc đồng ý bằng văn bản, phần mềm
được phân phối theo Giấy phép được phân phối trên CƠ SỞ "NGUYÊN TRẠNG",
KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý.
Xem Giấy phép để biết các quyền và
giới hạn quản lý ngôn ngữ cụ thể theo giấy phép.
Hỗ trợ bộ ký tự Java UTF-7 ( https://github.com/k9mail/ jutf7 )
Bản quyền (c) 2006,2008 JT Beetstra

Theo đây, quyền được cấp miễn phí cho bất kỳ người nào có được bản sao của phần mềm này và các tệp tài liệu liên quan ("Phần mềm"), để xử lý Phần mềm mà không bị hạn chế, bao gồm nhưng không giới hạn các quyền sử dụng, sao chép, sửa đổi, hợp nhất , xuất bản, phân phối, cấp phép lại và/hoặc bán các bản sao của Phần mềm và cho phép những người được cung cấp Phần mềm làm như vậy, tuân theo các điều kiện sau:

Thông báo bản quyền ở trên và thông báo cấp phép này sẽ được bao gồm trong tất cả các bản sao hoặc các phần đáng kể của Phần mềm.

PHẦN MỀM ĐƯỢC CUNG CẤP "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM DƯỚI BẤT KỲ HÌNH THỨC NÀO, RÕ RÀNG HAY NGỤ Ý, BAO GỒM NHƯNG KHÔNG GIỚI HẠN Ở CÁC BẢO ĐẢM VỀ KHẢ NĂNG BÁN ĐƯỢC, TÍNH PHÙ HỢP CHO MỘT MỤC ĐÍCH CỤ THỂ VÀ KHÔNG VI PHẠM. TRONG BẤT KỲ TRƯỜNG HỢP NÀO TÁC GIẢ HOẶC NGƯỜI GIỮ BẢN QUYỀN SẼ KHÔNG CHỊU TRÁCH NHIỆM PHÁP LÝ VỀ BẤT KỲ KHIẾU NẠI, THIỆT HẠI HOẶC TRÁCH NHIỆM PHÁP LÝ KHÁC NÀO, DÙ TRONG MỘT HÀNH ĐỘNG HỢP ĐỒNG, NGOẠI TỆ HOẶC CÁCH NÀO KHÁC, PHÁT SINH TỪ, NGOÀI HOẶC LIÊN QUAN ĐẾN PHẦN MỀM HOẶC VIỆC SỬ DỤNG HOẶC CÁC GIAO DỊCH KHÁC TRONG PHẦN MỀM.
jsoup: Trình phân tích cú pháp HTML Java ( https://jsoup.org/ )
Bản quyền © 2009 - 2019 Jonathan Hedley ( jonathan@hedley.net )

Theo đây, quyền được cấp miễn phí cho bất kỳ người nào có được bản sao của phần mềm này và các tệp tài liệu liên quan ("Phần mềm"), để xử lý Phần mềm mà không bị hạn chế, bao gồm nhưng không giới hạn các quyền sử dụng, sao chép, sửa đổi, hợp nhất , xuất bản, phân phối, cấp phép lại và/hoặc bán các bản sao của Phần mềm và cho phép những người được cung cấp Phần mềm làm như vậy, tuân theo các điều kiện sau:

Thông báo bản quyền ở trên và thông báo cấp phép này sẽ được bao gồm trong tất cả các bản sao hoặc các phần đáng kể của Phần mềm.

PHẦN MỀM ĐƯỢC CUNG CẤP "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM DƯỚI BẤT KỲ HÌNH THỨC NÀO, RÕ RÀNG HAY NGỤ Ý, BAO GỒM NHƯNG KHÔNG GIỚI HẠN Ở CÁC BẢO ĐẢM VỀ KHẢ NĂNG BÁN ĐƯỢC, TÍNH PHÙ HỢP CHO MỘT MỤC ĐÍCH CỤ THỂ VÀ KHÔNG VI PHẠM. TRONG BẤT KỲ TRƯỜNG HỢP NÀO TÁC GIẢ HOẶC NGƯỜI GIỮ BẢN QUYỀN SẼ KHÔNG CHỊU TRÁCH NHIỆM PHÁP LÝ VỀ BẤT KỲ KHIẾU NẠI, THIỆT HẠI HOẶC TRÁCH NHIỆM PHÁP LÝ KHÁC NÀO, DÙ TRONG MỘT HÀNH ĐỘNG HỢP ĐỒNG, NGOẠI TỆ HOẶC CÁCH NÀO KHÁC, PHÁT SINH TỪ, NGOÀI HOẶC LIÊN QUAN ĐẾN PHẦN MỀM HOẶC VIỆC SỬ DỤNG HOẶC CÁC GIAO DỊCH KHÁC TRONG PHẦN MỀM.
JZlib - zlib bằng Java thuần túy ( http://www.jcraft.com/jzlib/ )
Bản quyền (c) 2000-2011 ymnk, JCraft,Inc.

Việc phân phối lại và sử dụng ở dạng nguồn và dạng nhị phân, có hoặc không có sửa đổi, được cho phép với điều kiện đáp ứng các điều kiện sau:

Việc phân phối lại mã nguồn phải giữ lại thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây.
Các bản phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác được cung cấp cùng với bản phân phối.
Không được sử dụng tên của hoặc tên của những người đóng góp để xác nhận hoặc quảng cáo các sản phẩm bắt nguồn từ phần mềm này mà không có sự cho phép cụ thể trước bằng văn bản.
Kotlin ( https://kotlinlang.org/ )
Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/giấy phép/GIẤY ​​PHÉP-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", MÀ KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Leakcanary ( https://github.com/square/ leakcanary )
Bản quyền 2015 Square, Inc.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Thành phần Material cho Android ( https://github.com/material- components/material- components-android )
Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
oauth2-essentials ( https://github.com/dmfs/ oauth2-essentials )
Bản quyền dmfs GmbH 2017

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
OkHttp ( http://square.github.io/ okhttp/ )
Bản quyền 2019 Square, Inc.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
PinEntryView ( https://github.com/Philio/ PinEntryView )
Bản quyền 2014-2015 Phil Bayfield

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Trang bị thêm ( http://square.github.io/ trang bị thêm/ )
Bản quyền 2013 Square, Inc.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
rfc5545-datetime ( https://github.com/dmfs/ rfc5545-datetime )
Bản quyền 2015 Marten Gajda

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
RxAndroid ( https://github.com/ReactiveX/ RxAndroid )
Bản quyền 2015 Các tác giả RxAndroid

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
RxJava ( https://github.com/ReactiveX/ RxJava )
Bản quyền (c) 2016-nay, Người đóng góp RxJava.

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Sentry SDK cho Java ( https://github.com/getsentry/ sentry-java )
Được phép phân phối lại và sử dụng ở dạng nguồn và dạng nhị phân, có hoặc không có sửa đổi, miễn là đáp ứng các điều kiện sau:

Việc phân phối lại mã nguồn phải giữ nguyên thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây.
Các bản phân phối lại ở dạng nhị phân phải sao chép thông báo bản quyền ở trên, danh sách các điều kiện này và tuyên bố từ chối trách nhiệm sau đây trong tài liệu và/hoặc các tài liệu khác được cung cấp cùng với bản phân phối.
Không được sử dụng tên của hoặc tên của những người đóng góp để xác nhận hoặc quảng cáo các sản phẩm bắt nguồn từ phần mềm này mà không có sự cho phép cụ thể trước bằng văn bản.
ShortcutBadger ( https://github.com/ leolin310148/ShortcutBadger )
Bản quyền 2014 Leo Lin

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
SlimOrm ( https://github.com/ Neristance/slimorm/ )
Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Spongycastle ( https://rtyley.github.io/ spongycastle/ )
Bản quyền (c) 2000-2017 The Legion of the Bouncy Castle Inc. ( http://www.bouncycastle.org )

Theo đây, quyền được cấp miễn phí cho bất kỳ người nào có được bản sao của phần mềm này và các tệp tài liệu liên quan ("Phần mềm"), để xử lý Phần mềm mà không bị hạn chế, bao gồm nhưng không giới hạn các quyền sử dụng, sao chép, sửa đổi, hợp nhất , xuất bản, phân phối, cấp phép lại và/hoặc bán các bản sao của Phần mềm và cho phép những người được cung cấp Phần mềm làm như vậy, tuân theo các điều kiện sau:

Thông báo bản quyền ở trên và thông báo cấp phép này sẽ được bao gồm trong tất cả các bản sao hoặc các phần đáng kể của Phần mềm.

PHẦN MỀM ĐƯỢC CUNG CẤP "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM DƯỚI BẤT KỲ HÌNH THỨC NÀO, RÕ RÀNG HAY NGỤ Ý, BAO GỒM NHƯNG KHÔNG GIỚI HẠN Ở CÁC BẢO ĐẢM VỀ KHẢ NĂNG BÁN ĐƯỢC, TÍNH PHÙ HỢP CHO MỘT MỤC ĐÍCH CỤ THỂ VÀ KHÔNG VI PHẠM. TRONG BẤT KỲ TRƯỜNG HỢP NÀO TÁC GIẢ HOẶC NGƯỜI GIỮ BẢN QUYỀN SẼ KHÔNG CHỊU TRÁCH NHIỆM PHÁP LÝ VỀ BẤT KỲ KHIẾU NẠI, THIỆT HẠI HOẶC TRÁCH NHIỆM PHÁP LÝ KHÁC NÀO, DÙ TRONG MỘT HÀNH ĐỘNG HỢP ĐỒNG, NGOẠI TỆ HOẶC CÁCH NÀO KHÁC, PHÁT SINH TỪ, NGOÀI HOẶC LIÊN QUAN ĐẾN PHẦN MỀM HOẶC VIỆC SỬ DỤNG HOẶC CÁC GIAO DỊCH KHÁC TRONG PHẦN MỀM.
Dự án nguồn mở Android ( https://source.android.com/ setup/licenses/ )
Bản quyền (C) 2013 Dự án nguồn mở Android

được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại http://www.apache.org/licenses/LICENSE-2.0

    

khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HOẶC ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Gỗ ( https://github.com/ JakeWharton/timber )
Bản quyền 2013 Jake Wharton

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
xmlobjects ( https://github.com/dmfs/ xmlobjects )
Bản quyền (c) Marten Gajda 2014

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
Thư viện quét mã vạch ZXing ("Zebra Crossing") ( https://github.com/zxing/ zxing )
Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép.
LicensesDialog ( http://psdev.de/ LicensesDialog )
Bản quyền 2013-2016 Philip Schiffer

Được cấp phép theo Giấy phép Apache, Phiên bản 2.0 ("Giấy phép");
bạn không thể sử dụng tệp này trừ khi tuân thủ Giấy phép.
Bạn có thể lấy một bản sao của Giấy phép tại

    http://www.apache.org/licenses/LICENSE-2.0

Trừ khi luật hiện hành yêu cầu hoặc được đồng ý bằng văn bản, phần mềm được phân phối theo Giấy phép sẽ được phân phối trên CƠ SỞ "NGUYÊN TRẠNG", KHÔNG CÓ BẢO ĐẢM HAY ĐIỀU KIỆN DƯỚI BẤT KỲ HÌNH THỨC NÀO, rõ ràng hay ngụ ý. Xem Giấy phép để biết các quyền và giới hạn quản lý ngôn ngữ cụ thể theo Giấy phép. 

S89219-chính 

