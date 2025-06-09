# 📘 Cấu trúc Dữ liệu & Giải thuật - Bài tập Thực hành

Khóa học này sẽ giúp hiểu thuật toán cũng như hiểu rõ bản chất của các cấu trúc dữ liệu.

## 🎯 Mục tiêu

- Củng cố kiến thức nền tảng về Cấu trúc dữ liệu và Giải thuật.
- Rèn luyện kỹ năng giải quyết vấn đề với nhiều cấp độ.
- Viết code rõ ràng, tối ưu, dễ đọc.
- Sẵn sàng cho các vòng phỏng vấn tại công ty công nghệ.

## 🧠 Nội dung chính

### 🗂 Cấu trúc Dữ liệu

- Mảng (Array)
- Danh sách liên kết (Linked List)
- Ngăn xếp (Stack) & Hàng đợi (Queue)
- Cây nhị phân (Binary Tree), Cây tìm kiếm nhị phân (BST)
- Heap / Priority Queue
- Hash Table
- Đồ thị (Graph)

### 🧮 Giải thuật

- Đệ quy (Recursion).
- Sắp xếp & Tìm kiếm (Sorting & Searching).
- Quy hoạch động (Dynamic Programming).
- Duyệt đồ thị (DFS, BFS).
- Quay lui (Backtracking).
- Thuật toán tham lam (Greedy).
- Kỹ thuật hai con trỏ, trượt cửa sổ (Two Pointers, Sliding Window).

### 🏋️ Thực hành

- Bài tập theo từng chủ đề.
- Các bài toán nổi bật từ LeetCode, HackerRank, Codeforces.

## ⚙️ Cài đặt & khởi chạy

### 🗔 Windows:

1. Cài đặt [Visual Studio Code](https://code.visualstudio.com/download).
2. Cài đặt [C/C++ extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) bằng cách tìm 'C++' trong giao diện Extensions (Ctrl+Shift+X).
3. Sử dụng phiên bản mới nhất của MinGW-w64 thông qua [MSYS2](https://www.msys2.org), cung cấp các bản dựng gốc mới nhất của GCC, MinGW-w64 và các công cụ và thư viện C++.
4. MSYS2 đã sẵn sàng và cửa sổ lệnh [UCRT64 environment](https://www.msys2.org/docs/environments) sẽ khởi chạy, cài đặt trình biên dịch GCC:

```bash
pacman -S mingw-w64-ucrt-x86_64-gcc
```

5. Thêm đường dẫn đến thư mục bin MinGW-w64 vào biến môi trường PATH của Windows
   - Tìm kiếm **Edit environment variables for your account**.
   - Trong **User variables**, chọn biến `PATH` rồi chọn **Edit**.
   - Chọn **New** và thêm thư mục đích MinGW-w64 đã ghi lại trong quá trình cài đặt vào danh sách. Nếu sử dụng thiết lập mặc định, thì đây sẽ là đường dẫn: `C:\msys64\ucrt64\bin`.
   - Chọn **OK**, sau đó chọn **OK** lần nữa trong cửa sổ Environment Variables để cập nhật biến môi trường `PATH`.
6. Để kiểm tra xem công cụ MinGW-w64 của bạn đã được cài đặt đúng cách và có sẵn hay chưa, mở **Command Prompt**:

```bash
gcc --version
g++ --version
gdb --version
```

#### Tham khảo

- [Using GCC with MinGW](https://code.visualstudio.com/docs/cpp/config-mingw)
- [Editing and Navigating C++ Code](https://code.visualstudio.com/docs/cpp/cpp-ide)
- [MSYS2](https://www.msys2.org) (Run as administrator)
- [Clang-Format Style](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)

## 📁 Cấu trúc thư mục

```css
root/
│
├── README.md
│
├── data_structures/
│ ├── arrays/
│ ├── linked_lists/
│ ├── stacks/
│ ├── queues/
│ ├── trees/
│ ├── graphs/
│ └── hash_tables/
│ └── ...
│
├── algorithms/
│ ├── sorting/
│ ├── searching/
│ ├── recursion/
│ ├── dynamic_programming/
│ ├── greedy/
│ ├── backtracking/
│ └── graph_algorithms/
│ └── ...
│
├── interview_problems/
│ ├── easy/
│ ├── medium/
│ └── hard/
│ └── ...
│
└── ...
```

---

> 🔁 Luôn cải tiến – Góp ý hoặc pull request luôn được hoan nghênh!
