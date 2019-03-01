# Mima.rs

- It's a password manager using Rust, Rocket, Diesel and PostgreSQL.
- 这是一个密码管理器，采用技术：Rust, Rocket, Diesel, PostgreSQL。

## 不是网站

- 本软件虽然采用了网站框架来制作，但只是为了方便而已。
- 制作时只考虑了在本地使用的情形，未考虑联网安全，不宜联网使用。
- 这是一个单用户系统，使用时只需要输入密码，不需要输入用户名，也无法新建第二个用户。

## 安装

- 先参照 `create_role_and_database.md` 进行操作.
- 由于采用了 sodiumoxide, 因此需要设定相关的环境变量 https://crates.io/crates/sodiumoxide

## 安全提示

## 特点

本程序具有以下优点，其他密码管理器大多不具备这些优点。

- 有修改历史
- 简洁模式
