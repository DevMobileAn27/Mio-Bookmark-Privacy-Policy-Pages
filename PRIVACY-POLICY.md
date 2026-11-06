# Mio Bookmark Privacy Policy

Updated / Cập nhật: 06 November 2026 / 06/11/2026. Mio Bookmark 0.2.0.

## English

Your bookmark library and preferences stay in your Chrome profile. Mio Bookmark does not upload them to a developer server.

### 1. Purpose and scope

Mio Bookmark helps you save, organize, customize, search, and open Chrome bookmarks through a side panel, popup, and full-page library. This policy describes version 0.2.0.

The extension does not require an account, an email address, an activation key, or Premium registration.

### 2. Data the extension accesses and stores

Bookmark data: folder names, bookmark titles and URLs, identifiers, folder relationships, ordering, and available bookmark metadata. Importing from the current Chrome profile creates or updates a copy in the extension’s local storage.

Current tab data: the active tab’s title, URL, and available favicon URL when you save the current page. Favicon metadata may also be updated when you open a bookmark.

Preferences and interface state: folder icons and colors, favorite icons, language, appearance, sorting, the destination folder for saved pages, the direct-editing setting, import timestamps and counts, and temporary folder-expansion and side-panel window state.

Search terms are used within the extension to filter bookmarks. The extension does not send search terms to a search provider or developer server.

### 3. How data is used and stored

Data is used to display and search your library, save pages, manage bookmarks and folders, remember preferences, and operate the side panel. Persistent data is stored in chrome.storage.local in your Chrome profile. Temporary interface state uses chrome.storage.session, sessionStorage, or memory.

The extension has no developer-operated backend, analytics, advertising, or telemetry. It does not upload your bookmark library or settings to the developer. It does not use chrome.storage.sync for its own data.

Importing from the current profile is not a developer cloud-sync service. If you enable direct bookmark management, creating, renaming, moving, or deleting items can change the bookmarks in Chrome itself. Chrome’s own bookmark synchronization, if enabled in your browser, is governed by your Chrome settings and Google’s policies.

### 4. Permissions

bookmarks — Read bookmarks when you import them; create, rename, move, or delete browser bookmarks when you enable direct management and perform those actions.

storage — Save the local bookmark copy, preferences, favicon metadata, and temporary extension state.

sidePanel — Display and control the bookmark manager beside your current webpage.

tabs — Read the current tab’s title, URL, and favicon for saving; open bookmarked pages and the full-page library; update available favicon metadata. The extension does not read page bodies, passwords, or messages, and does not use Chrome’s history API to collect your browsing history.

### 5. Sharing and third-party requests

The developer does not sell or rent your bookmark data, use it for advertising, or transfer it for purposes unrelated to bookmark management. The extension does not transmit your library to a developer server.

Opening a bookmark connects your browser to that website. Displaying a stored remote favicon can request an image from the favicon’s host. These third parties can receive ordinary connection data, such as your IP address and browser request headers, under their own policies. This is separate from uploading your complete bookmark library.

If you email the developer for support, your email address and the contents you choose to send are used to respond to that request. Please avoid sending private bookmark lists or other sensitive information unless needed for your support request.

This policy website is hosted on GitHub Pages. GitHub may process technical request data under its own privacy statement. This page contains no analytics scripts, advertising, or tracking cookies.

### 6. Retention and deletion

Local extension data remains in your Chrome profile until you remove the relevant items, clear the extension’s storage, or uninstall the extension. Temporary state is kept only for the relevant tab, browser session, or running interface.

You can delete bookmarks and folders through the extension. In direct-management mode, deletion can also remove the corresponding browser bookmarks. Uninstalling the extension removes its own stored data from that Chrome installation; it does not remove bookmarks stored independently in Chrome or restore bookmarks you previously deleted.

The developer has no server copy of your bookmark library to retrieve or delete. Any browser synchronization or backups managed outside the extension are controlled by their respective providers.

### 7. Your choices and security

You choose when to import bookmarks, save a page, customize a folder, or enable direct management. You can stop using the extension or remove it in Chrome’s extension settings.

The extension relies on Chrome’s storage and extension-permission protections and does not add separate encryption to its local data. Access to your device, Chrome profile, and backups should be protected using your own device and browser settings. No method of storage or transmission is completely secure.

### 8. Changes to this policy

This policy will be updated when the extension’s data practices change. The updated date is shown on this page. Review this policy when updating the extension.

### 9. Contact

For questions about Mio Bookmark or this privacy policy, contact the developer at nguyenquocan841@gmail.com.

## Tiếng Việt

Thư viện bookmark và tùy chọn được lưu trong profile Chrome của bạn. Mio Bookmark không tải chúng lên máy chủ của nhà phát triển.

### 1. Mục đích và phạm vi

Mio Bookmark giúp bạn lưu, sắp xếp, tùy chỉnh, tìm kiếm và mở bookmark Chrome thông qua side panel, popup và trang thư viện đầy đủ. Chính sách này mô tả phiên bản 0.2.0.

Tiện ích không yêu cầu tài khoản, địa chỉ email, khóa kích hoạt hoặc đăng ký Premium.

### 2. Dữ liệu tiện ích truy cập và lưu trữ

Dữ liệu bookmark: tên thư mục, tiêu đề và URL bookmark, mã định danh, quan hệ thư mục, thứ tự và thông tin bookmark có sẵn. Thao tác nhập từ profile Chrome hiện tại tạo hoặc cập nhật một bản sao trong bộ nhớ cục bộ của tiện ích.

Dữ liệu tab hiện tại: tiêu đề, URL và URL favicon có sẵn của tab đang hoạt động khi bạn lưu trang. Thông tin favicon cũng có thể được cập nhật khi bạn mở bookmark.

Tùy chọn và trạng thái giao diện: icon và màu thư mục, icon yêu thích, ngôn ngữ, giao diện, cách sắp xếp, thư mục đích khi lưu trang, chế độ chỉnh sửa trực tiếp, thời điểm và số lượng khi nhập bookmark, cùng trạng thái tạm thời của nhánh thư mục và cửa sổ side panel.

Từ khóa tìm kiếm được xử lý trong tiện ích để lọc bookmark. Tiện ích không gửi từ khóa đến công cụ tìm kiếm hoặc máy chủ của nhà phát triển.

### 3. Cách sử dụng và lưu trữ dữ liệu

Dữ liệu được dùng để hiển thị và tìm kiếm trong thư viện, lưu trang, quản lý bookmark và thư mục, ghi nhớ tùy chọn và vận hành side panel. Dữ liệu lâu dài được lưu bằng chrome.storage.local trong profile Chrome. Trạng thái tạm thời dùng chrome.storage.session, sessionStorage hoặc bộ nhớ khi đang chạy.

Tiện ích không có máy chủ do nhà phát triển vận hành, công cụ phân tích, quảng cáo hoặc telemetry. Tiện ích không tải thư viện bookmark hay tùy chọn của bạn lên nhà phát triển và không dùng chrome.storage.sync cho dữ liệu riêng của tiện ích.

Nhập từ profile hiện tại không phải dịch vụ đồng bộ đám mây của nhà phát triển. Nếu bạn bật quản lý bookmark trực tiếp, thao tác tạo, đổi tên, di chuyển hoặc xóa có thể thay đổi bookmark trong Chrome. Tính năng đồng bộ bookmark riêng của Chrome, nếu bạn bật, tuân theo cài đặt Chrome và chính sách của Google.

### 4. Các quyền truy cập

bookmarks — Đọc bookmark khi bạn nhập dữ liệu; tạo, đổi tên, di chuyển hoặc xóa bookmark trình duyệt khi bạn bật quản lý trực tiếp và thực hiện các thao tác đó.

storage — Lưu bản sao bookmark cục bộ, tùy chọn, thông tin favicon và trạng thái tạm thời của tiện ích.

sidePanel — Hiển thị và điều khiển trình quản lý bookmark bên cạnh trang web hiện tại.

tabs — Đọc tiêu đề, URL và favicon của tab hiện tại để lưu trang; mở bookmark và trang thư viện đầy đủ; cập nhật thông tin favicon có sẵn. Tiện ích không đọc nội dung trang, mật khẩu hoặc tin nhắn và không sử dụng API history của Chrome để thu thập lịch sử duyệt web.

### 5. Chia sẻ dữ liệu và yêu cầu tới bên thứ ba

Nhà phát triển không bán hoặc cho thuê dữ liệu bookmark, không dùng dữ liệu này để quảng cáo hoặc chuyển dữ liệu cho mục đích không liên quan đến quản lý bookmark. Tiện ích không gửi thư viện của bạn đến máy chủ của nhà phát triển.

Khi mở bookmark, trình duyệt kết nối đến trang web đó. Khi hiển thị favicon từ xa đã lưu, trình duyệt có thể gửi yêu cầu tải ảnh đến máy chủ lưu favicon. Những bên này có thể nhận dữ liệu kết nối thông thường, như địa chỉ IP và thông tin header của trình duyệt, theo chính sách riêng của họ. Hoạt động này khác với việc tải toàn bộ thư viện bookmark của bạn lên.

Nếu bạn gửi email hỗ trợ, địa chỉ email và nội dung bạn chủ động gửi được sử dụng để phản hồi yêu cầu đó. Vui lòng hạn chế gửi danh sách bookmark riêng tư hoặc thông tin nhạy cảm nếu không cần thiết để hỗ trợ.

Trang chính sách này được lưu trữ trên GitHub Pages. GitHub có thể xử lý dữ liệu kỹ thuật của yêu cầu truy cập theo chính sách riêng của họ. Trang này không có mã phân tích, quảng cáo hoặc cookie theo dõi.

### 6. Thời gian lưu và xóa dữ liệu

Dữ liệu cục bộ của tiện ích được giữ trong profile Chrome cho đến khi bạn xóa các mục tương ứng, xóa bộ nhớ của tiện ích hoặc gỡ tiện ích. Trạng thái tạm thời chỉ được giữ trong tab, phiên trình duyệt hoặc giao diện đang chạy tương ứng.

Bạn có thể xóa bookmark và thư mục trong tiện ích. Khi bật quản lý trực tiếp, thao tác xóa có thể xóa cả bookmark tương ứng của trình duyệt. Gỡ tiện ích sẽ xóa dữ liệu riêng của tiện ích tại bản cài Chrome đó; thao tác này không xóa bookmark được lưu riêng trong Chrome và không khôi phục bookmark bạn đã xóa trước đó.

Nhà phát triển không có bản sao thư viện bookmark trên máy chủ để truy xuất hoặc xóa. Dữ liệu đồng bộ hoặc sao lưu bên ngoài tiện ích do nhà cung cấp tương ứng kiểm soát.

### 7. Lựa chọn và bảo mật

Bạn quyết định khi nào nhập bookmark, lưu trang, tùy chỉnh thư mục hoặc bật quản lý trực tiếp. Bạn có thể ngừng sử dụng hoặc gỡ tiện ích trong phần quản lý tiện ích của Chrome.

Tiện ích dựa vào cơ chế lưu trữ và bảo vệ quyền của Chrome, không bổ sung lớp mã hóa riêng cho dữ liệu cục bộ. Bạn nên bảo vệ thiết bị, profile Chrome và bản sao lưu bằng cài đặt thiết bị và trình duyệt của mình. Không có phương thức lưu trữ hoặc truyền dữ liệu nào an toàn tuyệt đối.

### 8. Thay đổi chính sách

Chính sách sẽ được cập nhật khi cách xử lý dữ liệu của tiện ích thay đổi. Ngày cập nhật được hiển thị trên trang này. Bạn nên xem lại chính sách khi cập nhật tiện ích.

### 9. Liên hệ

Nếu có câu hỏi về Mio Bookmark hoặc chính sách quyền riêng tư, vui lòng liên hệ nhà phát triển qua nguyenquocan841@gmail.com.
