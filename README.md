# GitHub_Learning

# GitHub Learning

## Phần 01: Set config

### Set config

```bash
git config --global user.name "Tên của bạn"
git config --global user.email "email@example.com"
```

### Get config

```bash
git config --global user.name
git config --global user.email
```

---

## Phần 02: Creating repo / Cloning repo

### Khởi tạo repository

```bash
git init
```

### Kết nối với GitHub

```bash
git remote add origin <git_url>         // tạo kết nối
git remote -v                           // Kiểm tra xem đã kết nối chưa
```

### Push/Pull lên GitHub

```bash
git add .  
git add 'filename'
git commit -m "Initial commit"
git push -u origin main
```
## Các bước push code lên github
``` bash
Viet code
Add code
Commit code
Push code
```