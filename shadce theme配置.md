1. 通过[在线生成预览网站](https://www.shadcndesign.com/theme-generator)找到与自己的主题色接近的预设配置，复制并替换`app\assets\css\tailwind.css`的`:root {}`和`.dark {}`相应的变量，尽量挑着替换。
2. 然后再通过自定义自己的主题色，修改`--primary、--ring、--chart-1、--chart-2、--chart-3、--chart-4、--chart-5`等变量，light 模式下，需要修改`--sidebar-primary`变量；dark 模式下，则需要修改`--sidebar-ring`变量。

具体参考以下提交记录：

    feat: 更换主品牌色
    feat: 更换主题色Amber
