# IMC-UX

![Banner](https://user-images.githubusercontent.com/12947776/274178530-186b0518-d0ba-47b6-ac6a-7644ccb9d8e5.png)

##  休息一会儿

🍕 []~(￣▽￣)~* 🍹

##  常用设定

### GIT用户连接超时的处理方案

> 原文：https://docs.github.com/en/authentication/troubleshooting-ssh/using-ssh-over-the-https-port#enabling-ssh-connections-over-https

1. 跳转到`C:\Users\imc\.ssh` 目录
2. 新建`config`文件, 内容如下，保存结束。
```bash
Host github.com
Hostname ssh.github.com
Port 443
User git
```
## 备忘一下

### 常见Issue标签

- 💡 Feature Request
- 🐛 Bug
- 🎨 Design
- 🙅🏻‍♀️ WON'T DO
- 📝 Documentation
- ✈️ priority: normal
- 🚀 priority: high
- ⛔️ can be closed
- 👷🏻‍♂️ Someone working on it
