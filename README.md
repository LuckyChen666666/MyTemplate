# 0. 使用环境

`Windows` + `TeX Live 2021` + `XeLaTeX` + `TeXstudio`.

# 1. 学习笔记模板 (Times风格)

- 中文正文字体为 `宋体`, 加粗为 `黑体`, 加斜为 `楷体`. 
- 英文正文字体为 `Times New Roman`, 公式字体为 `mtpro2`.
- 单独设置了偏导 `\partial`、圆周率 `\pi`、积分 `\int`与花括号 `\{\}` 的样式. 
- 定义了带编号的数学环境: `dl` (定理)、`yl` (引理)、`tl` (推论)、`dy` (定义)、`xz` (性质)、`mt` (命题)、`zhu` (注)、`li` (例). 按 `section` 编号, 且这些环境共用一个编号体系 (例如 `定义 1.1` 后跟 `定理 1.2`).
- 定义了不带编号的数学环境: `jie` (解)、`zm` (证明)、`note` (注), 其中 `jie` 与 `zm` 环境自带结束符号. 要使用没有结束符号的解环境与证明环境, 可分别使用 `bjie` 与 `bzm`.
- 公式、图片与表格按 `section` 编号(例如 `图 2.1`).
- 定义了框框环境: 蓝色 `blue`、紫色 `purple`、绿色 `green`、橘色 `orange`.
- 定义了带框框的数学环境: (都是在相应的环境名称前面加 `b`, 这里的 `b` 代表 “box”)
    - 带橘色框框的定义环境: `bdy`.
    - 带蓝色框框的结论类环境: `bdl`、`btl`、`bxz`、`bmt`、`byl`.
- 定义了带有结束符号 `//` 的例题环境 `bli`. (为了与上一条一致, 也是在例题环境的名称前加 `b`)
- 定义了框框内的有序列表环境 `luolie` (“罗列” 的拼音). 
- 图片统一放在文件夹 `图片` 下.
- 交换图使用 `tikz-cd` 绘制, 箭头样式为
```tex
\tikzcdset{
 arrow style=tikz,
 diagrams={>={Classical TikZ Rightarrow[width=0pt 11, length=5pt]}}
 }
```

![学习笔记模板 (Times风格)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607271028311.png)

# 2. 学习笔记模板

英文与除 `mathcal` 外的公式字体采用 LaTeX 的默认样式, 交换图也采用 LaTeX 的默认样式, 其余与 `学习笔记模板 (Times风格)` 相同.

![学习笔记模板](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607271033555.png)

# 3. 学习笔记模板 (CM加粗版)

英文与公式采用比 LaTeX 的默认样式 `Computer Modern` 稍微粗一点的 `New Computer Modern`,  其余与 `学习笔记模板 (Times风格)` 相同.

![学习笔记模板 (CM加粗版)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607271034189.png)

# 4. 学习笔记模板 (Times风格+每章都有参考文献)

为每章罗列参考文献进行了设置, 其余和 `学习笔记模板 (Times风格)` 相同.

![学习笔记模板 (Times风格+每章都有参考文献)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281025761.png)

![学习笔记模板 (Times风格+每章都有参考文献)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281026103.png)

# 5. beamer模板

中文正文字体使用 `微软雅黑`, 英文与数学字体使用 `arev` 宏包, 主题使用 `Madrid`, 每一个 `section` 前设置了目录导航页.

![beamer模板](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281714988.png)

![beamer模板](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281715066.png)

![beamer模板](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281715212.png)

![beamer模板](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607281716726.png)

# 6. beamer模板 (中文字体稍细版)

中文正文字体使用华文细黑 `STXihei` (这是一种更细的无衬线字体), 英文与公式字体使用默认样式, 主题使用 `Madrid`, 每一个 `section` 前设置了目录导航页.

![beamer模板 (中文字体稍细版)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607291044865.png)

![beamer模板 (中文字体稍细版)](https://cdn.jsdelivr.net/gh/LuckyChen666666/MyImage@main/202607291044265.png)