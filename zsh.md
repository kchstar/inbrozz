# ZSH 
kch@gimcheonhos-Mac-mini ~ % pwd
/Users/kch
kch@gimcheonhos-Mac-mini ~ % cd /
kch@gimcheonhos-Mac-mini / % pwd
/
kch@gimcheonhos-Mac-mini / % ls
Applications	System		Volumes		cores		etc		opt		sbin		usr
Library		Users		bin		dev		home		private		tmp		var
kch@gimcheonhos-Mac-mini / % cd ~
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						node_modules
Desktop						Pictures					package-lock.json
Documents					Public						package.json
Downloads					anaconda3					src
Library						card_swipe					사용권 계약.pdf
Movies						javaScript_8min_svg
kch@gimcheonhos-Mac-mini ~ % pwd
/Users/kch
kch@gimcheonhos-Mac-mini ~ % cd /Users
kch@gimcheonhos-Mac-mini /Users % pwd
/Users
kch@gimcheonhos-Mac-mini /Users % cd ~
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						node_modules
Desktop						Pictures					package-lock.json
Documents					Public						package.json
Downloads					anaconda3					src
Library						card_swipe					사용권 계약.pdf
Movies						javaScript_8min_svg
kch@gimcheonhos-Mac-mini ~ % cd src
kch@gimcheonhos-Mac-mini src % pwd
/Users/kch/src
kch@gimcheonhos-Mac-mini src % cd ..
kch@gimcheonhos-Mac-mini ~ % pwd    
/Users/kch
kch@gimcheonhos-Mac-mini ~ % md test
zsh: command not found: md
kch@gimcheonhos-Mac-mini ~ % touch index.html
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						javaScript_8min_svg
Desktop						Pictures					node_modules
Documents					Public						package-lock.json
Downloads					anaconda3					package.json
Library						card_swipe					src
Movies						index.html					사용권 계약.pdf
kch@gimcheonhos-Mac-mini ~ % touch styles.css script.js
kch@gimcheonhos-Mac-mini ~ % touch paths/index.html
touch: paths/index.html: No such file or directory
kch@gimcheonhos-Mac-mini ~ % cd paths
cd: no such file or directory: paths
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Pictures					package-lock.json
Desktop						Public						package.json
Documents					anaconda3					script.js
Downloads					card_swipe					src
Library						index.html					styles.css
Movies						javaScript_8min_svg				사용권 계약.pdf
Music						node_modules
kch@gimcheonhos-Mac-mini ~ % rm index.html
kch@gimcheonhos-Mac-mini ~ % rem styles.css script.js
zsh: command not found: rem
kch@gimcheonhos-Mac-mini ~ % rm styles.css script.js
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						node_modules
Desktop						Pictures					package-lock.json
Documents					Public						package.json
Downloads					anaconda3					src
Library						card_swipe					사용권 계약.pdf
Movies						javaScript_8min_svg
kch@gimcheonhos-Mac-mini ~ % mkdir web-dev
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						node_modules
Desktop						Pictures					package-lock.json
Documents					Public						package.json
Downloads					anaconda3					src
Library						card_swipe					web-dev
Movies						javaScript_8min_svg				사용권 계약.pdf
kch@gimcheonhos-Mac-mini ~ % rmdir web-dev
kch@gimcheonhos-Mac-mini ~ % ls
Applications					Music						node_modules
Desktop						Pictures					package-lock.json
Documents					Public						package.json
Downloads					anaconda3					src
Library						card_swipe					사용권 계약.pdf
Movies						javaScript_8min_svg
kch@gimcheonhos-Mac-mini ~ % 
  [복원됨 2024. 3. 10. 오전 9:05:48]
Last login: Sun Mar 10 09:05:46 on console
kch@gimcheonhos-Mac-mini ~ % zsh --version
zsh 5.9 (x86_64-apple-darwin23.0)
kch@gimcheonhos-Mac-mini ~ % which zsh
/bin/zsh
kch@gimcheonhos-Mac-mini ~ % 

