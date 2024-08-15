---
title: Cat In The Forest    
date: 2024-08-15T03:33:15+07:00
lastmod: 2024-08-15T03:33:15+07:00
author: Doan Thanh Dat
# avatar: /me/me.png
authorlink: https://github.com/datthanhdoan
cover: cat-in-the-forest.png
# images:
#   - /img/cover.jpg
categories:
  - game development
tags:
  - indie-game
nolastmod: true
---
Genre: Simulation, Casual </br> 
<!--more-->

### Chi tiết Dự án

**Cat In The Forest** là dự án mà tôi đã tự thiết kế và lập trình. Trong quá trình phát triển, tôi đã áp dụng các **design pattern** chính như **Singleton**, **Observer**, và **State**. Tôi cũng sử dụng lập trình hướng đối tượng (OOP) và tích hợp các nguyên tắc **SOLID**, bao gồm **SRP (Single Responsibility Principle)**, **OCP (Open/Closed Principle)**, và **ISP (Interface Segregation Principle)**.

Để quản lý đường đi và các hành vi của nhân vật, tôi đã sử dụng **navMesh**. Các animation trong trò chơi được tạo ra bằng **DoTween**, giúp cải thiện hiệu suất và chất lượng chuyển động. Dữ liệu trò chơi, bao gồm các thông tin về nhiệm vụ và trạng thái, được lưu trữ tại **persistentDataPath** (thư mục dữ liệu trên máy người chơi) và quản lý dưới định dạng **JSON** thông qua **JsonUtility**, cho phép cập nhật dữ liệu một cách linh hoạt mà không cần thay đổi mã nguồn.

Video Gameplay:
[Cat In The Forest](https://youtu.be/UwWd7r4fbKk)<br/>
Link download: [Windows 🪟](https://github.com/datthanhdoan/Cat-In-The-Forest/releases)

