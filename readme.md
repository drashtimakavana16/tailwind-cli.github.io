#Tailwind css CLI

<h1>Website</h1>
1.Copy  - npm install tailwindcss @tailwindcss/cli

<h1>VS Code</h1>
1.Open Terminal
2.Paste cmd
3.Enter
4.Create index.html and input.css
5.Open package.json


6.Copy  - npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch From tailwindcss
write into package.json "scripts": {
    "start": "npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch"
  }
7.Remove src from link
8.Open input.css and paste @import "tailwindcss";
9.Open index.html link -  <link rel="stylesheet" href="./output.css">
10.Open Terminal npm run start


Method - 1
git - repo create
git clone <link>
git add . / git add index.html
git commit -m "msg"
git push origin main

Method - 2
Folder - Computer
git init
git remote add <link>
git add .
git commit -m "tailwind-cli"
git push origin main

git branch
git branch <name>
