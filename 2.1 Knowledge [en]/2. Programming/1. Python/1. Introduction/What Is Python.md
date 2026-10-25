<details>
<summary>📌 Meta · ID: PR-001_en</summary>

<br>

> **Author:** ThuongDev  
>
> **Created:** 2026-08-18  
>
> **Context:** Python Curriculum  
> **Status:** Active  
> **Tags:** [#python](/.hub/tag/python.en.md)    

</details>

<style>h1{color:#e5533d;text-align:center}h2{color:#1f6feb}h3{color:#8e44ad}h4{color:#2ea44f}</style>

# What Is Python? 

Python is a programming language widely used in:

* Web applications
* Software development
* Data science
* Machine learning

Developers use Python because it is efficient, easy to learn, and runs on various platforms.

Python software is free to download, integrates well with all types of systems, and helps accelerate development.

<br>

---

## ⭐ 1. What Are the Advantages of Python?

* Simple, English-like syntax → easy to read and understand code
* Fewer lines of code compared to many other languages ​​→ greater productivity
* Extensive standard library with reusable code → no need to write code from scratch
* Easily integrates with other popular programming languages ​​like Java, C, and C++
* Vibrant community of millions of developers → quick support
* Abundance of useful free resources available online
* ​​Compatible with various operating systems such as Windows, macOS, Linux, and Unix

<br>

---

## 🧩 2. In Which Fields Is Python Applied?

Python is widely applied in various fields.


<br>

### 🔹 2.1 Server-Side Web Development

Server-side web development involves the complex backend functions that websites perform to display information to users.

📌 Examples include interacting with databases, communicating with other websites, and securing data during network transmission.

Python is highly useful for server-side development because it offers numerous libraries containing built-in functions, which simplify the creation of complex components.

Developers also utilize Python frameworks, which provide the necessary structure and tools to build web applications more quickly and efficiently.

📌 For instance, a framework can help generate the initial structure of a web application, eliminating the need to build every component from scratch. Additionally, many frameworks include built-in testing tools, making the development and testing process more convenient.

<br>

### 🔹 2.2 Task Automation

> A **scripting language** is a type of programming language used to write scripts that automate tasks, control other programs, or handle specific operations. Python is one such scripting language.

📌 With Python, you can write scripts to:

* Rename a large number of files at once
* Convert files from one format to another
* Remove duplicate words from a text file

<br>

### 🔹 2.3 Data Science and Machine Learning

> Data Science involves **extracting valuable insights from data**, whereas Machine Learning (ML) enables computers to **learn automatically from data and make accurate predictions**.

📌 Data scientists use Python for data science tasks such as:

*   Correcting and removing inaccurate data, also known as data cleaning
*   Extracting and selecting various data features
*   Labeling data—that is, assigning meaningful names to the data
*   Deriving various statistical metrics from the data
*   Visualizing data using charts and graphs, such as line charts, bar charts, frequency plots, and pie charts

<br>

### 🔹 2.4 Software Development

📌 Software developers often use Python for a variety of tasks, such as:

*   Tracking software bugs
*   Automating software builds
*   Managing software projects
*   Developing software prototypes
*   Developing desktop applications with a graphical user interface (GUI)
*   Developing games ranging from simple to complex

<br>

### 🔹 2.5 Software Test Automation

> **Software Testing** is the process of verifying whether the actual output of software matches the expected output, ensuring the software functions correctly and is free of errors.

Developers often use Python testing frameworks—such as **Unittest, Robot, and PyUnit**—to verify the functions and features they build.

📌 Additionally, testers use Python to write test cases for various scenarios, such as:

* Testing the user interface (UI) of web applications
* Testing interactions between software components
* Testing new features

To automate the testing process, developers and testers utilize **CI/CD (Continuous Integration / Continuous Deployment)** tools.

Popular tools like **Travis CI** and **Jenkins** can:

* Automatically execute Python test scripts
* Perform tests whenever changes are made to the source code
* Quickly report test results

As a result, the software development process becomes faster and more stable, while minimizing errors.

<br>

---

## ⚙️ 3. What Are the Characteristics of Python?

👉 **Interpreted language**

> Python is an interpreted language, meaning it executes code directly, line by line. If an error occurs in the code, the program stops immediately. This allows programmers to quickly identify and fix errors.

<br>

👉 **Easy-to-use language**

> Python uses English-like syntax. Unlike many other languages, Python does not use curly braces {}; instead, it relies on indentation.

📌 Example:

``` python
if x > 5:
    print("x is greater than 5")
    print("This is inside the if block")

print("This line is outside the if block")
```

<br>

👉 **Dynamically typed language**

> Programmers do not need to declare data types for variables because Python determines them at runtime. This allows you to write code faster.

📌 Example:

``` python
a = 10          # int
b = 3.14        # float
c = "Hello"     # string
d = [1, 2, 3]   # list
```

<br>

👉 **High-level language**

> Python is closer to natural language than many other languages. Consequently, programmers do not need to concern themselves with complex technical details such as machine architecture or memory management.

📌 Example: You do not need `malloc` or `free` as you would in C.

<br>

👉 **Object-oriented language**

> Python treats everything as an object, but it also supports other programming paradigms, such as structured programming and functional programming.

📌 Example: Creating a `Player` class in game programming.

``` python
class Player:
    def __init__(self, name, health):
        self.name = name
        self.health = health
        self.level = 1

    def take_damage(self, damage):
        self.health -= damage

    def level_up(self):
        self.level += 1


player = Player("Knight", 100)

player.take_damage(30)
player.level_up()

print(player.health)
print(player.level)
```

<br>

---

## 📚 4. What Is a Python Library?

> A **library** is a collection of code written by other programmers that you can incorporate into your Python program to avoid writing code from scratch.

By default, Python comes with a **Standard Library** containing a vast array of reusable functions.

Additionally, the Python ecosystem features hundreds of thousands of libraries and packages developed for various fields, including:

* Web Development
* Data Science
* Machine Learning (ML)

<br>

### 🔹 Popular Python Libraries

👉 **Matplotlib**

> Matplotlib is a Python library used for **data visualization** through 2D and 3D plots. It supports various types of charts, such as line and bar charts, and is commonly used in data science, scientific research, and data analysis.

<br>

👉 **Pandas**

> Pandas is a Python library used for **processing and analyzing tabular data**. It provides powerful data structures such as Series and DataFrames, supporting operations like reading, filtering, merging, and grouping data. Pandas is widely used in data science, data analysis, and machine learning.

<br>

👉 **NumPy**

> NumPy is a Python library specialized for **high-performance numerical computing**.
> It is particularly important in:
>
> *   Data Science
> *   Machine Learning
> *   Scientific computing
> *   Engineering simulations
>
> If Pandas is like Excel for handling tabular data, then NumPy is like a mathematical tool for working with numerical arrays.

<br>

👉 **Requests**

> Requests is a Python library used to **interact with the web** via HTTP.
>
> 📌 You can use it to:
>
> * Send HTTP requests
> * Add headers
> * Add URL parameters
> * Send data
> * Perform various other tasks when working with APIs and web services.

<br>

👉 **OpenCV-Python**

> **OpenCV (Open Source Computer Vision Library)** is an open-source library dedicated to **Computer Vision**, providing tools for various tasks such as:
>
> * Image Processing
> * Image Recognition
> * Video Analysis
> * Object Detection & Tracking
>
> **OpenCV-Python** is the version of OpenCV used with Python.

<br>

👉 **Keras**

> Keras is a Python library used to **build and train deep learning models**.
>  
> It provides components that allow for the flexible creation of neural networks, supports various architectures such as CNNs and RNNs, and is commonly used in AI applications like image recognition, natural language processing, and data prediction.

<br>

---

## 🏗️ 5. What Is a Python Framework?

> A **framework** is a pre-built structure for developing applications.

> Instead of creating everything from scratch, developers use frameworks to leverage:
>
> * Project structure
> * Code organization
> * Common functionalities
> * Development guidelines

Python has two main types of frameworks:

**Full-stack frameworks** provide almost all the components necessary to build a large-scale application.

**Microframeworks** provide the minimum functionality needed to build simple Python applications. They also offer extensions when the application requires more complex features.

<br>

### 🔹 5.1 What Is the Difference Between a Module, a Package, and a Framework?

You can visualize it as follows:

```
Module
│
└──  A Python file (.py)
    Example: user.py
    Can be imported and used elsewhere
    Does not necessarily have to belong to a package

Package
│
└── A directory containing multiple modules (and potentially sub-packages)
    Does not necessarily have to belong to a framework
    (Python 3.3+ does not require an __init__.py file)
    Example:

    users/
    ├── user.py
    ├── auth.py
    └── permission.py

Framework
│
└── A collection of packages + rules + architecture
    Used to build complete applications
    Example:

    Web Framework
    ├── Routing
    ├── Database
    ├── Security
    └── Template
```

<br>

### 🔹 5.2 Popular Python Frameworks

Developers can use various Python frameworks to optimize their workflow, including the following:

👉 **Django**

> **Django** là một trong những **framework web full-stack của Python** được sử dụng rộng rãi nhất để phát triển các ứng dụng web quy mô lớn.
>
> Nó cung cấp nhiều tính năng hữu ích, bao gồm **máy chủ web dùng cho phát triển và kiểm thử**, **template engine để xây dựng giao diện frontend**, và **nhiều cơ chế bảo mật**.

<br>

👉 **Flask**

> **Flask** là một **micro-framework** dùng để phát triển các ứng dụng web nhỏ.
>
> Nó có các đặc điểm như **cộng đồng hỗ trợ mạnh, tài liệu rõ ràng, template engine, hỗ trợ unit testing,** và **web server tích hợp sẵn**.
>
> Ngoài ra, Flask còn cung cấp các extension để bổ sung các chức năng như **xác thực dữ liệu (validation), làm việc với cơ sở dữ liệu (ORM)** và **bảo mật web**.

<br>

👉 **TurboGears**

> **TurboGears** là một framework được thiết kế để giúp xây dựng ứng dụng web **nhanh chóng và dễ dàng hơn**.
>
> Một số tính năng nổi bật của nó bao gồm:
>
> * Cấu trúc làm việc với cơ sở dữ liệu được định nghĩa sẵn
> * Công cụ hỗ trợ tạo và quản lý project
> * Template engine để xây dựng giao diện frontend
> * Công cụ làm việc với cơ sở dữ liệu (ORM)
> * Các cơ chế bảo mật cho ứng dụng web

<br>

👉 **Apache MXNet**

> **Apache MXNet** là một framework học sâu (deep learning) **nhanh, linh hoạt và có khả năng mở rộng**, được các nhà phát triển sử dụng để xây dựng **prototype nghiên cứu** và **các ứng dụng học sâu**.
>
> Nó hỗ trợ nhiều ngôn ngữ lập trình như **Java, C++, R** và **Perl**.
>
> Ngoài ra, MXNet cung cấp một hệ sinh thái phong phú gồm các công cụ và thư viện hỗ trợ phát triển, ví dụ như:
>
> * Sách học máy (Machine Learning) dạng tương tác
> * Bộ công cụ cho thị giác máy tính (Computer Vision)
> * Các mô hình học sâu cho Natural Language Processing (NLP) – lĩnh vực xử lý ngôn ngữ tự nhiên như văn bản và giọng nói

<br>

👉 **PyTorch**

> **PyTorch** là một framework học máy (ML) được xây dựng dựa trên thư viện **Torch**, một thư viện học máy mã nguồn mở khác.
>
> Các nhà phát triển sử dụng PyTorch cho nhiều ứng dụng như **Xử lý ngôn ngữ tự nhiên (Natural Language Processing - NLP)**, robot và thị giác máy tính (computer vision), nhằm trích xuất thông tin có ý nghĩa từ hình ảnh và video.
>
> Ngoài ra, PyTorch có thể chạy các ứng dụng này trên cả **CPU** và **GPU**.

<br>

---

## 💻 6. IDE Python là gì?

> Môi trường phát triển tích hợp (Integrated Development Environment - IDE) là phần mềm cung cấp cho các nhà phát triển những công cụ cần thiết để viết, chỉnh sửa, kiểm thử và gỡ lỗi mã nguồn trong cùng một nơi.

<br>

### 🔹 Những IDE Python phổ biến

👉 **PyCharm**

**JetBrains**, một công ty của Cộng hòa Séc chuyên phát triển các công cụ phần mềm, đã tạo ra PyCharm.

PyCharm có phiên bản Community miễn phí phù hợp cho các ứng dụng Python nhỏ và phiên bản Professional trả phí phù hợp để xây dựng các ứng dụng Python quy mô lớn, với đầy đủ các tính năng sau:

<details>
<summary>Tính năng đầy đủ của <b>PyCharm</b></summary>

<br>

> * Tự động hoàn thành mã và kiểm tra mã nguồn
> * Phát hiện lỗi và đưa ra cách sửa nhanh
> * Làm sạch mã nguồn mà không thay đổi chức năng
> * Hỗ trợ các framework web như Django và Flask
> * Hỗ trợ các ngôn ngữ lập trình khác như JavaScript, CoffeeScript, TypeScript, AngularJS và Node.js
> * Hỗ trợ các công cụ và thư viện khoa học như Matplotlib và NumPy
> * Chạy, gỡ lỗi, kiểm thử và triển khai ứng dụng trên máy ảo từ xa
> * Cung cấp trình gỡ lỗi, trình phân tích hiệu suất và công cụ chạy kiểm thử tự động
> * Hỗ trợ làm việc với cơ sở dữ liệu

</details>

<br>

👉 **IDLE**

**Integrated Development and Learning Environment (IDLE)** là IDE Python được **cài đặt sẵn theo mặc định**. Nó được phát triển hoàn toàn bằng Python, sử dụng bộ công cụ giao diện Tkinter.

<details>
<summary>Tính năng của <b>IDLE</b></summary>

<br>

> * Hoạt động trên nhiều hệ điều hành như Windows, Unix và macOS
> * Cung cấp cửa sổ Python shell để chạy lệnh và hiển thị kết quả
> * Có trình soạn thảo nhiều cửa sổ với tính năng tô sáng cú pháp và tự động hoàn thành mã
> * Có trình gỡ lỗi riêng

</details>

<br>

👉 **Spyder**

**Spyder** là một IDE mã nguồn mở được nhiều nhà khoa học và nhà phân tích dữ liệu sử dụng. Nó cung cấp một môi trường phát triển toàn diện với các tính năng **phục vụ phân tích dữ liệu nâng cao, trực quan hóa dữ liệu** và **gỡ lỗi**.

<details>
<summary>Tính năng của <b>Spyder</b></summary>

<br>

> * Có trình soạn thảo hỗ trợ nhiều ngôn ngữ
> * Chạy thử code ngay lập tức (qua IPython console)
> * Trình gỡ lỗi cơ bản
> * Hỗ trợ các thư viện khoa học như Matplotlib, SciPy, và NumPy
> * Khả năng khám phá và quản lý biến
> * Hiển thị tài liệu sử dụng của hàm và thư viện trong IDE

</details>

<br>

---

## 🧰 7. SDK là gì?

**Bộ công cụ phát triển phần mềm (SDK)** là một tập hợp các công cụ phần mềm mà lập trình viên có thể sử dụng để tạo ra ứng dụng trong một ngôn ngữ cụ thể. Hầu hết các SDK được thiết kế riêng cho từng nền tảng phần cứng và hệ điều hành khác nhau.

Các SDK cho Python bao gồm nhiều công cụ như thư viện, ví dụ mã nguồn (code samples) và tài liệu hướng dẫn dành cho lập trình viên, giúp họ viết ứng dụng một cách dễ dàng và hiệu quả hơn.

### 🔹 IDE, SDK, Code Editor khác nhau thế nào?

**So sánh nhanh**

| Tiêu chí       | Code Editor 📝    | IDE 🧰                          | SDK 🧩                       |
| -------------- | ----------------- | ------------------------------- | ---------------------------- |
| Mục đích       | Viết code         | Phát triển full                 | Cung cấp công cụ để build    |
| Có chạy/debug? | ❌ (ít hoặc không) | ✅                               | ❌                            |
| Có UI hỗ trợ?  | ❌                 | ✅ rất nhiều                     | ❌                            |
| Thành phần     | Text editor       | Editor + debugger + build tools | API, thư viện, docs          |
| Dùng độc lập?  | ✅                 | ✅                               | ❌ (phải dùng với IDE/editor) |
| Đối tượng      | Người thích nhẹ   | Dev chuyên nghiệp               | Dev theo platform            |

<br>

**Sơ đồ quan hệ**

```
       ┌──────────────┐
       │     SDK      │  (Bộ công cụ để build)
       │ APIs + libs  │
       └──────┬───────┘
              │ dùng trong
    ┌─────────▼─────────┐
    │        IDE        │ (Môi trường full)
    │ Editor + Debug +  │
    │ Build + SDK       │
    └────────┬──────────┘
             │ chứa
       ┌─────▼───────┐
       │ Code Editor │ (chỉ viết code)
       └─────────────┘
```
<br>

* Code Editor → nơi viết code
* IDE → nơi viết + chạy + debug + build
* SDK → thứ giúp bạn build cho 1 nền tảng cụ thể

📌 Ví dụ:

* Bạn code Android:
    * IDE: Android Studio
    * SDK: Android SDK

👉 IDE dùng SDK bên trong

<br>

---

> [!TIP]  
> 💰 **Support my work for just \$1/Python guide** — helps keep this project alive!  
>
> ☕ **Buy Me a Coffee:** [buymeacoffee.com/devthuong](https://buymeacoffee.com/devthuong) *(Supports Cards, Apple Pay, Google Pay)*  
> 💳 **PayPal:** [paypal.me/thuongnguyen156](https://paypal.me/thuongnguyen156)  
> 
> ![Scan to Donate](/.hub/img/buy-me-a-coffee-url-qrcode.png)



<br>

<div style="display:flex;justify-content:flex-end;margin-top:40px;">

<a href="next.md" style="width:50%;padding:12px 16px;border:1px solid #d0d7de;border-radius:8px;text-align:right;text-decoration:none;">
<small>Next</small> →<br>
<strong>History</strong>
</a>

</div>

<br>

---


**Tài liệu tham khảo**

- [AWS – What is Python?](https://aws.amazon.com/what-is/python/)