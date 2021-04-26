npx degit "sooboy/sapper-template" my-app



# 具体

## npm install --save-dev smui-theme
## npx smui-theme template src/theme

```
"prepare": "npm run smui-theme-light && npm run smui-theme-dark",
"smui-theme-light": "smui-theme compile static/smui.css -i src/theme",
"smui-theme-dark": "smui-theme compile static/smui-dark.css -i src/theme/dark",
```


## 步骤 

```
 yarn prepare   // 生成一个全局css
 yarn dev       //开发
```