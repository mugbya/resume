本简历 fork 自 xuxiaodong 的 [resume][r]。

## 准备环境

1. 安装 Node.js 模块：
   `npm install`
2. 将本目录中的 CSS 文件复制到 *node_modules/markdown-resume/assets/css*：
   
    `cp *.css node_modules/markdown-resume/assets/css`


## 生成简历


# For usage on the command line
    
    npm install -g markdown-resume

# Generate HTML file

    md2resume my-resume-file.md

# Generate PDF file

    md2resume --pdf my-resume-file.md


[r]: https://github.com/xuxiaodong/resume
