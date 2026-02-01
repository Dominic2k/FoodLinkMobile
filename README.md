
### 3. README cho Mobile App (React Native)

File này dựa trên template chuẩn của React Native và đã được tùy chỉnh cho dự án của bạn.

```markdown
# FoodLink Mobile

Ứng dụng di động của dự án FoodLink, được phát triển bằng **React Native**.

## 🚀 Bắt đầu

Hướng dẫn này sẽ giúp bạn cài đặt môi trường và chạy ứng dụng trên máy ảo hoặc thiết bị thật.

### 📋 Yêu cầu cài đặt

Hãy chắc chắn rằng bạn đã hoàn thành hướng dẫn **Set Up Your Environment** của React Native trước khi tiếp tục. Các yêu cầu chính bao gồm:

*   Node.js (LTS) & Watchman
*   Java Development Kit (JDK)
*   Android Studio & Android SDK
*   Xcode (cho macOS) & CocoaPods

### 🔧 Cài đặt

1.  **Clone repository**
    ```sh
    git clone <your-mobile-repo-url>
    cd FoodLinkMobile
    ```

2.  **Cài đặt dependencies**
    Sử dụng npm:
    ```sh
    npm install
    ```
    Hoặc sử dụng Yarn:
    ```sh
    yarn install
    ```

3.  **Cài đặt cho iOS**
    Di chuyển vào thư mục `ios` và cài đặt các Pods:
    ```sh
    cd ios && pod install
    ```

### 🏃 Chạy ứng dụng

**Lưu ý:** Trước khi chạy ứng dụng, bạn cần khởi động Metro bundler.

1.  **Khởi động Metro**
    ```sh
    # Sử dụng npm
    npm start

    # Hoặc sử dụng Yarn
    yarn start
    ```

2.  **Chạy trên Android hoặc iOS**
    Mở một cửa sổ terminal mới tại thư mục gốc của dự án và chạy lệnh tương ứng:

    *   **Android**
        ```sh
        # Sử dụng npm
        npm run android

        # Hoặc sử dụng Yarn
        yarn android
        ```

    *   **iOS**
        ```sh
        # Sử dụng npm
        npm run ios

        # Hoặc sử dụng Yarn
        yarn ios
        ```

Nếu mọi thứ được thiết lập chính xác, bạn sẽ thấy ứng dụng chạy trên máy ảo Android, iOS Simulator hoặc thiết bị đã kết nối.

### ✨ Bắt đầu đóng góp

Bây giờ bạn đã sẵn sàng để chỉnh sửa và phát triển ứng dụng! Mở file `App.tsx` và bắt đầu code. Tính năng **Fast Refresh** sẽ tự động cập nhật ứng dụng khi bạn lưu file.

Chúc team của bạn có một trải nghiệm phát triển dự án suôn sẻ!
<!--
[PROMPT_SUGGESTION]Tạo giúp tôi một file CONTRIBUTING.md với các quy tắc đóng góp cơ bản cho dự án.[/PROMPT_SUGGESTION]
[PROMPT_SUGGESTION]Làm thế nào để tôi có thể thiết lập CI/CD cho cả ba dự án này với GitHub Actions?[/PROMPT_SUGGESTION]
-->
