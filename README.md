# README

学习Udemy上的[【how-to-build-instagram-using-ruby-on-rails】](https://www.udemy.com/how-to-build-instagram-using-ruby-on-rails/) 项目。

* 版本
  * Ruby 2.5.1
  * Rails 5.2.1

* 流程
  * [x] Section1 ： Introduction
    * 制作登陆验证： gem：‘devise’ 
    * 创建登陆页面和用户数据库
    * 大部分时间都在写CSS，使用Bootstrap
  * [x] Section2 ： Basic Project
    * 制作通知提醒框：gem：'toastr-rails' 
    * 使用TwitterAPI登陆 gem： 'omniauth', 'omniauth-twitter'
      * 目前机制为初次登陆依据邮箱创建用户，邮箱重复无法登陆
    * 修改用户信息功能： gem：‘devise’的【registrations】方法
  * [ ] Section3 ： Gravatar, Twitter Authentication, User Profile
  * [ ] Section4 ： Post Feature
  * [ ] Section5 ： Like, Comment and Bookmark Feature
  * [ ] Section6 ： Search
  * [ ] Section7 ： Miscellaneous
