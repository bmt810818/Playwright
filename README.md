# Playwright
- Run your tests with UI Mode: $ yarn playwright test --ui

## 1. Syntax
### 1.1 Selectors:
- Các selector là cách xác định các phần tử trên trang web để tương tác với chúng.
- Playwright hỗ trợ các loại selector như CSS selector, XPath, text content, attribute, và nhiều hơn nữa.

### 1.2 Page navigation:
- Cách điều hướng giữa các trang web và tương tác với URL.
Ví Dụ: page.goto(), page.goBack(), page.goForward().
### 1.3 Interactions with elements:
- Cho phép tôi thực hiện các hoạt động như click, điền dữ liệu vào các trường input, di chuột qua các phần tử, cuộn trang, kéo và thả các phần tử, và nhiều hành động khác.
- Ví Dụ: page.click(), page.fill(), page.hover(), page.scroll(), page.dragAndDrop

### 1.4 Assertions và expectations:
-  Các phương thức để kiểm tra trạng thái hoặc tính chất của các phần tử và trạng thái của trang web.
-  Ví dụ: expect(page).toHaveTitle(), expect(page).toHaveURL().

### 1.5 Waiting for elements:
- Các phương thức và API để chờ cho đến khi các phần tử hoặc điều kiện được đáp ứng trên trang web. Ví dụ: page.waitForSelector(), page.waitForFunction().

### 1.6 Frame và context switching:
- Cách chuyển đổi giữa các frame và context trên trang web.
- Ví dụ: page.frame(), page.waitForFrame().

### 1.7 Event handling:
- Cách xử lý các sự kiện trên trang web như click, submit, input, và các sự kiện khác.
- Ví dụ: page.on('dialog'), page.once('console').

### 1.8 Configuration và environment setup:
- Cách cấu hình và thiết lập môi trường cho test cases.
- Ví dụ: browserType.launch(), browser.newContext().

### 1.9 Test lifecycle và hooks: 
- Cách quản lý và tùy chỉnh vòng đời của test cases, bao gồm trước và sau khi mỗi test case chạy.
- Ví dụ: beforeAll(), afterEach().

### 1.10 Error handling và debugging: 
- Cách xử lý lỗi và debug các test cases khi chúng thất bại.
- Ví dụ: sử dụng try-catch để bắt lỗi, sử dụng console.log() để ghi log.
