## คําสั่ง git
# ส่วนที่ 1 
- git clone https://github.com/mix93123/css-fundamentals-lab.git
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/mix93123/css-fundamentals-lab.git
- git push -u origin main
# ส่วนที่ 2
- git checkout -b feature/main
- git add . 
- git commit -m "create main page"
# ส่วนที่ 3
- git checkout -b feature/css
- git add . 
- git commit -m "add basic CSS selectors"
# ส่วนที่ 4
- git add .
- git commit -m "add box model styles"
# ส่วนที่ 5
- git add .
- git commit -m "add flexbox layouts"
# ส่วนที่ 6
- git checkout main
- git merge feature/main
- git merge feature/css
- git push