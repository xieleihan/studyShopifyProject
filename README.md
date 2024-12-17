
shopify login --store (如果没登录需要先执行这一步，后续考虑用环境变量优化这一步)

npm run dev (1.tailwind监听编译  2.运行程序)

#### Tailwind
注意每次需要将asset目录下重新编译的 tailwind.css文件提交上去

使用tailwind语法需要前缀加上 tw- 目的是防止类名覆盖

text-xs font-size: 0.75rem;  line-height: 1rem;
text-sm font-size: 0.875rem;  line-height: 1.25rem; 
text-base font-size: 1rem;line-height: 1.5rem; 
text-lg font-size: 1.125rem; line-height: 1.75rem;
text-xl font-size: 1.25rem;  line-height: 1.75rem; 
text-2xl font-size: 1.5rem;  line-height: 2rem; 
text-3xl font-size: 1.875rem; line-height: 2.25rem; 
text-4xl font-size: 2.25rem; line-height: 2.5rem; 
text-5xl font-size: 3rem; line-height: 1; 
text-6xl font-size: 3.75rem; line-height: 1; 
text-7xl font-size: 4.5rem; line-height: 1; 
text-8xl font-size: 6rem; line-height: 1; 
text-9xl font-size: 8rem;  line-height: 1;

请将我的liquid代码中的tailwind转化为原生css，注意1rem=10px。要求转成一个liquid文件，一个原生css文件，并在liquid中引入css
代码如下
其他间距 0 为0rem， 1为0.25rem， 2为0.5rem，以此类推

[tailwind官网](https://tailwindcss.com/)



