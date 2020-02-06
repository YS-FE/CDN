# CDN 静态资源

## jsDelivr
[官网](https://www.jsdelivr.com/)

## URL

`https://cdn.jsdelivr.net/gh/user/repo@version/file.js`
`https://cdn.jsdelivr.net/npm/jquery/dist/jquery.min.js`

### 示例
`https://cdn.jsdelivr.net/gh/ys-fe/cdn/img/test/01.png`
`https://cdn.jsdelivr.net/gh/ys-fe/cdn@0.0.1-alpha/img/test/01.png`



## 流程

```
before_install 安装依赖前
install 安装依赖时
before_script 执行脚本前
script 执行脚本时
after_success 或 after_failure 执行脚本成功（失败）后
before_deploy 部署前
deploy 部署时
after_deploy 部署后
after_script 执行脚本后
```