# 1. Sơ lượt về phầm mềm:
* Ứng dụng được lập trình ra để rút ngắn khoảng cách giữa sinh viên và giảng viên. 
* Giúp Giảng viên có thể gửi các thông báo quan trọng đến các Sinh viên. 
* Bên cạnh đó Giảng viên và Sinh viên có thể nói chuyện với nhau qua chức năng "Nhắn tin" ngay trong ứng dụng. 
* Song đó, trong ứng dụng còn tích hợp thêm các tính năng giao tiếp qua các phần mềm bên ngoài như Gmmail, Điện thoại,...

# 2. Mục tiêu của phần mềm:
* Phần mềm tạo ra nhằm đáp ứng nhu cầu hỏi đáp giữa Sinh viên với Giảng viên.
* Phần mềm còn dành cho Giảng viên có thể đăng các thông báo cần thiết cho Sinh viên.
* Trong phần mềm còn tích hợp thêm tính năng dịch ngữ Anh - Việt giúp cho Sinh viên có thể dịch các câu - từ tiếng Anh sang tiếng Việt thuận tiện hơn cho việc học ( Tương lai sẽ có thêm các ngôn ngữ khác).

# 3. Công nghệ sử dụng trong phần mềm:

## Phần mềm biên dịch (IDE):

#### Android studio:
* Android Studio là môi trường phát triển tích hợp (IDE) chính thức dành cho phát triển nền tảng Android.
* Phiên bản hiện tại của Android Studio : 4.0.1 .
* Ngôn ngữ có thể sử dụng: Java, Kotlin.
* Visual studio code:
* Visual Studio Code là một trình biên tập mã được phát triển bởi Microsoft dành cho Windows, Linux và macOS.
* Ngôn ngữ có thể sử dụng: Batch, C++, Clojure, CoffeeScript, DockerFile, Elixir, F#, Go, Java, HandleBars, Ini, Lua, Makefile, Objective-C, Perl, PowerShell, Python, R, Razor, Ruby, Rust, SQL, Visual Basic, XML.
* Visual Studio Code có thể được mở rộng qua plugin.

## Ngôn ngữ lập trình:
#### Kotlin:
* Kotlin là một ngôn ngữ lập trình kiểu tĩnh chạy trên máy ảo Java (JVM) và có thể được biên dịch sang mã nguồn Java hay sử dụng cơ sở hạ tầng trình biên dịch LLVM.
* Kể từ Android Studio 3.0 (phát hành vào tháng 10 năm 2017), Kotlin được Google hỗ trợ đầy đủ để sử dụng cho việc lập trình ứng dụng cho hệ điều hành Android.
* Kotlin được thiết kế để trở thành một ngôn ngữ hướng đối tượng công nghiệp mạnh mẽ, và là một "ngôn ngữ tốt hơn" Java, nhưng vẫn có thể tương thích hoàn toàn với mã Java.
* Kotlin có thể được xem là 1 Swift của Android.
* Một trong những thế mạnh lớn nhất của Kotlin như là một ứng viên để thay thế cho Java là khả năng tương tác rất tốt giữa Java và Kotlin—bạn có thể thậm chí có code Java và Kotlin tồn tại song song trong cùng dự án, và tất cả mọi thứ vẫn sẽ được biên dịch một cách hoàn hảo.
* Kotlin có thể giúp code ngắn hơn Java rất nhiều và dễ quản lý code.
#### Java:
* Java là một ngôn ngữ lập trình hướng đối tượng (OOP) và dựa trên các lớp (class).
* Khác với phần lớn ngôn ngữ lập trình thông thường, thay vì biên dịch mã nguồn thành mã máy hoặc thông dịch mã nguồn khi chạy, Java được thiết kế để biên dịch mã nguồn thành bytecode, bytecode sau đó sẽ được môi trường thực thi (runtime environment) chạy.
* Java được tạo ra với tiêu chí "Viết (code) một lần, thực thi khắp nơi" ("Write Once, Run Anywhere" (WORA)) nhờ công cụ JDK của Java.
* JavaScript:
* JavaScript, theo phiên bản hiện hành, là một ngôn ngữ lập trình thông dịch được phát triển từ các ý niệm nguyên mẫu.
* Ngôn ngữ này được dùng rộng rãi cho các trang web (phía người dùng) cũng như phía máy chủ (với Nodejs).
* Java Script gồm 2 mảng là client-server thực hiện lệnh trên máy của end-user và web-server.

## Hệ quản trị dữ liẹu:
#### Firebase:
* Xây dựng ứng dụng nhanh chóng mà không cần quản lý cơ sở hạ tầng. Firebase cung cấp cho bạn các chức năng như phân tích, cơ sở dữ liệu, nhắn tin và báo cáo sự cố để bạn có thể di chuyển nhanh chóng và tập trung vào người dùng của mình.
* Được hỗ trợ bởi Google, được các ứng dụng hàng đầu tin cậy. Firebase được xây dựng trên cơ sở hạ tầng của Google và tự động mở rộng quy mô, ngay cả những ứng dụng lớn nhất.
* Một nền tảng, với các sản phẩm hoạt động tốt hơn cùng nhau. Các sản phẩm Firebase hoạt động hiệu quả riêng lẻ nhưng chia sẻ dữ liệu và thông tin chi tiết để chúng hoạt động cùng nhau tốt hơn.
#### Thư viện:
````
dependencies {
    // ...

    implementation 'com.firebaseui:firebase-ui-auth:6.4.0'

}
````
#### Firebase Authentication:
* Hầu hết các ứng dụng cần biết danh tính của người dùng. Việc biết danh tính của người dùng cho phép ứng dụng lưu dữ liệu người dùng một cách an toàn trên đám mây và cung cấp trải nghiệm được cá nhân hóa giống nhau trên tất cả các thiết bị của người dùng.
* Xác thực Firebase cung cấp các dịch vụ phụ trợ, SDK dễ sử dụng và thư viện giao diện người dùng được tạo sẵn để xác thực người dùng với ứng dụng của bạn. Nó hỗ trợ xác thực bằng mật khẩu, số điện thoại, các nhà cung cấp danh tính liên hợp phổ biến như Google, Facebook và Twitter, v.v.
* Firebase Realtime Database:
* Lưu trữ và đồng bộ dữ liệu với cơ sở dữ liệu đám mây NoSQL của chúng tôi. Dữ liệu được đồng bộ hóa trên tất cả các ứng dụng khách trong thời gian thực và vẫn có sẵn khi ứng dụng của bạn ngoại tuyến.
* Cơ sở dữ liệu thời gian thực của Firebase là cơ sở dữ liệu được lưu trữ trên đám mây. Dữ liệu được lưu trữ dưới dạng JSON và được đồng bộ hóa trong thời gian thực cho mọi máy khách được kết nối. Khi bạn tạo ứng dụng đa nền tảng với SDK iOS, Android và JavaScript của chúng tôi, tất cả khách hàng của bạn đều chia sẻ một phiên bản Cơ sở dữ liệu thời gian thực và tự động nhận các bản cập nhật với dữ liệu mới nhất.
##### Thư viện:
````
dependencies {
    // Import the BoM for the Firebase platform
    implementation platform('com.google.firebase:firebase-bom:26.0.0')

    // Declare the dependency for the Realtime Database library
    // When using the BoM, you don't specify versions in Firebase library dependencies
    implementation 'com.google.firebase:firebase-database'
}
````
#### Firebase Cloud Store:
* Sử dụng cơ sở dữ liệu đám mây NoSQL linh hoạt, có thể mở rộng của chúng tôi để lưu trữ và đồng bộ dữ liệu để phát triển phía máy khách và phía máy chủ.
* Cloud Firestore là một cơ sở dữ liệu linh hoạt, có thể mở rộng để phát triển thiết bị di động, web và máy chủ từ Firebase và Google Cloud Platform. Giống như Cơ sở dữ liệu thời gian thực của Firebase, nó giữ cho dữ liệu của bạn được đồng bộ hóa trên các ứng dụng khách thông qua trình xử lý thời gian thực và cung cấp hỗ trợ ngoại tuyến cho thiết bị di động và web để bạn có thể tạo các ứng dụng đáp ứng hoạt động bất kể độ trễ mạng hoặc kết nối Internet. Cloud Firestore cũng cung cấp khả năng tích hợp liền mạch với các sản phẩm Firebase và Google Cloud Platform khác, bao gồm cả Chức năng đám mây.
##### Thư viện:
````
dependencies {
    // Import the BoM for the Firebase platform
    implementation platform('com.google.firebase:firebase-bom:26.0.0')

    // Declare the dependency for the Realtime Database library
    // When using the BoM, you don't specify versions in Firebase library dependencies
    implementation 'com.google.firebase:firebase-database'
}
````
#### Firebase Storage:
* Cloud Storage được xây dựng cho các nhà phát triển ứng dụng cần lưu trữ và phân phát nội dung do người dùng tạo, chẳng hạn như ảnh hoặc video.
* Cloud Storage cho Firebase là một dịch vụ lưu trữ đối tượng mạnh mẽ, đơn giản và tiết kiệm chi phí được xây dựng cho quy mô của Google. SDK Firebase cho Bộ nhớ đám mây bổ sung tính năng bảo mật của Google cho các tệp tải lên và tải xuống cho các ứng dụng Firebase của bạn, bất kể chất lượng mạng như thế nào. Bạn có thể sử dụng SDK của chúng tôi để lưu trữ hình ảnh, âm thanh, video hoặc nội dung khác do người dùng tạo. Trên máy chủ, bạn có thể sử dụng Google Cloud Storage , để truy cập vào các tệp giống nhau.
##### Thư viện:
````
dependencies {
    // Import the BoM for the Firebase platform
    implementation platform('com.google.firebase:firebase-bom:26.0.0')

    // Declare the dependency for the Cloud Storage library
    // When using the BoM, you don't specify versions in Firebase library dependencies
    implementation 'com.google.firebase:firebase-storage'
}
````
#### Firebase Cloud Function:
* Chức năng đám mây cho Firebase là một khuôn khổ không máy chủ cho phép bạn tự động chạy mã phụ trợ để phản hồi các sự kiện được kích hoạt bởi các tính năng Firebase và các yêu cầu HTTPS. Mã JavaScript hoặc TypeScript của bạn được lưu trữ trong đám mây của Google và chạy trong môi trường được quản lý. Không cần phải quản lý và mở rộng các máy chủ của riêng bạn.

#### Firebase Cloud Messaging:
* Nhắn tin qua đám mây Firebase (FCM) là giải pháp nhắn tin đa nền tảng cho phép bạn gửi tin nhắn miễn phí một cách đáng tin cậy.
* Sử dụng FCM, bạn có thể thông báo cho ứng dụng khách rằng email mới hoặc dữ liệu khác có sẵn để đồng bộ hóa. Bạn có thể gửi tin nhắn thông báo để tăng mức độ tương tác lại và giữ chân người dùng. Đối với các trường hợp sử dụng như nhắn tin nhanh, tin nhắn có thể chuyển tải trọng lên tới 4KB cho ứng dụng khách.
##### Thư viện:
````
dependencies {
    // Import the BoM for the Firebase platform
    implementation platform('com.google.firebase:firebase-bom:26.0.0')

    // Declare the dependencies for the Firebase Cloud Messaging and Analytics libraries
    // When using the BoM, you don't specify versions in Firebase library dependencies
    implementation 'com.google.firebase:firebase-messaging'
    implementation 'com.google.firebase:firebase-analytics'
}
````
## Lập trình hướng đối tượng:
#### LiveData:
* LiveData là một lớp lưu trữ dữ liệu có thể quan sát được.  Không giống như một LiveData có thể quan sát thông thường, LiveData nhận biết được vòng đời, có nghĩa là nó tôn trọng vòng đời của các thành phần ứng dụng khác, chẳng hạn như hoạt động, phân đoạn hoặc dịch vụ.  Nhận thức này đảm bảo LiveData chỉ cập nhật trình quan sát thành phần ứng dụng đang ở trạng thái vòng đời hoạt động.
* LiveData coi một người quan sát, được đại diện bởi lớp Người quan sát, đang ở trạng thái hoạt động nếu vòng đời của nó ở trạng thái BẮT ĐẦU hoặc KẾT QUẢ.  LiveData chỉ thông báo cho những người quan sát tích cực về các bản cập nhật.  Những người quan sát không hoạt động đã đăng ký để xem các đối tượng LiveData không được thông báo về các thay đổi.
#### Singleton:
* Singleton là 1 trong các dạng Design Pattern.
* Trong kỹ thuật phần mềm, một mẫu thiết kế phần mềm là một giải pháp chung, có thể tái sử dụng cho một vấn đề thường xảy ra trong một bối cảnh nhất định trong thiết kế phần mềm. Nó không phải là một thiết kế hoàn thiện có thể được chuyển đổi trực tiếp thành mã nguồn hoặc mã máy.  Đúng hơn, nó là một mô tả hoặc khuôn mẫu về cách giải quyết một vấn đề có thể được sử dụng trong nhiều tình huống khác nhau.  Các mẫu thiết kế là các phương pháp hay nhất được chính thức hóa mà lập trình viên có thể sử dụng để giải quyết các vấn đề chung khi thiết kế một ứng dụng hoặc hệ thống.

## Mô hình MVVM:
#### Mô hình MVVM viết tắt của Model - View - ViewModel.

#### Các điểm chính của MVVM là:
* Các phương thức gọi tương tác của người dùng trên ViewModel.
* ViewModel lưu trữ trạng thái, quản lý trạng thái và hiển thị các sự kiện thay đổi khi trạng thái thay đổi.
* Model là dữ liệu được ánh xạ vào các trường có thể quan sát được (hoặc bất kỳ dạng phát xạ sự kiện nào khác).
* View đăng ký các sự kiện thay đổi do chế độ xem hiển thị để tự cập nhật.

## ViewBinding:
* Ràng buộc dạng xem là một tính năng cho phép bạn viết mã tương tác với dạng xem dễ dàng hơn.  Khi tính năng liên kết dạng xem được bật trong một mô-đun, nó tạo ra một lớp liên kết cho mỗi tệp bố cục XML có trong mô-đun đó.  Một thể hiện của lớp liên kết chứa các tham chiếu trực tiếp đến tất cả các dạng xem có ID trong bố cục tương ứng.
##### Thư viện:
````
android {
    ...
    buildFeatures {
        viewBinding true
    }
}
````
## DataBinding:
*  Là một thư viện hỗ trợ cho phép bạn liên kết các thành phần giao diện người dùng trong bố cục với các nguồn dữ liệu trong ứng dụng của bạn bằng cách sử dụng định dạng khai báo thay vì theo chương trình.
* Bố cục thường được định nghĩa trong các hoạt động với mã gọi các phương thức khung giao diện người dùng.  Ví dụ: mã bên dưới gọi findViewById () để tìm tiện ích TextView và liên kết nó với thuộc tính userName của viewModel:
##### Ví dụ:
````
<TextView
    android:text="@{viewmodel.userName}" />
````
##### Thư viện:
````
android {
    ...
    buildFeatures {
        dataBinding true
    }
}
````
# 4. Các tính năng trong phần mềm: