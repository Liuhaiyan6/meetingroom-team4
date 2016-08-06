1.创建一个src 文件；
2.依次输入以下命令：
 mkdir filename
npm init -y
npm install --save lodash
touch .gitignore
 echo 'node_modules/' >> .gitignore 
cat .gitignore 
3.然后在src 文件下建立hello.js 文件
4.打开webstorm 中hello.js 文件
5.input:
let _=require('lodash')
console.log('Hello world!')
let a=[1,2,3];
let b=_.sum(a);
console.log(b);
5.运行 ：jasmine init 
jasmine

