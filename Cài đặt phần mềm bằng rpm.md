## I. Chương trình RPM.
- RPM (RedHat Package Manager) là hệ thống quản lý package (gói phần mềm) được Linux hỗ trợ cho người dùng. Nó cung cấp cho người dùng nhiều tính năng để duy trì hệ thống của mình.
- Người dùng có thể cài đặt, xóa hoặc nâng cấp các package trực tiếp bằng lệnh. RPM có một cơ sở dữ liệu chứa các thông tin của các package đã cài và các tập tin của chúng, nhờ vậy RPM cho phép bạn truy vấn các thông tin, cũng như xác thực các package trong hệ thống.
- Trong quá trình nâng cấp package, RPM thao thác trên tập tin cấu hình rất cẩn thận, do vậy mà bạn không bao giờ bị mất các lựa chọn trước đó của mình. Trên phương diện các nhà phát triển, nó cho phép các nhà phát triển đóng gói chương trình nguồn của phần mềm thành các package
dạng nguồn hoặc binary đưa tới người dùng.

### II. Đặc tính của RPM.
- Khả năng nâng cấp phần mềm: Với RPM bạn có thể nâng cấp các thành phần riêng biệt của hệ thống mà không cần phải cài lại. Khi có một phiên bản mới của hệ điều hành dựa trên
RPM (như RedHat Linux chẳng hạn) thì bạn không phải cài lại hệ thống mà chỉ cần nâng cấp
thôi. RPM cho phép nâng cấp hệ thống một cách tự động, thông minh. Các tập tin cấu hình
được gìn giữ cẩn thận qua các lần nâng cấp, vì thế bạn không sợ thay đổi các tuỳ chọn sẵn
có của hệ thống được nâng cấp.
- Truy vấn thông tin hiệu quả: RPM cũng được thiết kế cho mục đích truy vấn các thông tin
về các package trong hệ thống. Bạn có thể tìm kiếm thông tin các package hoặc các tập tin
cài đặt trong toàn bộ cơ sở dữ liệu. Bạn cũng có thể hỏi tập tin cụ thể thuộc về package nào
và nó ở đâu. Package RPM có các tập tin chứa các thông tin rất hữu ích về package này và
nội dung của package. Các tập tin này cho phép người dùng tìm kiếm thông tin dễ dàng
trong một package riêng lẻ.
- Thẩm tra hệ thống (System Verification): Một đặc tính rất mạnh của RPM là cho phép bạn
thẩm tra lại các package. Nếu bạn nghi ngờ một tập tin nào bị xóa hay bị thay thế trong
package, bạn có thể kiểm tra lại rất dễ dàng. Bạn cần phải chú ý đến các dấu hiệu bất bình
thường của hệ thống, nên kiểm tra và cài lại nếu cần thiết.
