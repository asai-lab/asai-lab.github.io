# 改網站
直接pull code下來改完commit再推上Github即可
push code的時候記得改local git configuration
git config user.name "asai-lab"
git config user.email "your-email@example.com"

# Github Page
- 可直接展示repository(Settings>Pages>Build and Development>set branch>Save)
- 無法連結Database
- repository必須為public

# 想Run在localhost
- terminal執行`python -m http.server 8000`
- browser開啟localhost:8000

# CSS問題
以前學長用Elementor寫，所以有些由Elementor產生的ID不用管
例如:
CSS一樣的話不用管elementor-element-ff3e223中的ff3e223