## CSS规范、
*****
*****
*****
*****
*****

1. **css文件命名**
 + ***全局样式***. `layout.css` 全局样式为全站公用，为页面样式基础，页面中必须包含。保证您的代码规范，保证结构表现行为相互分离。
 + ***布局样式***. `layout.css` 页面结构类型复杂，并且公用类型较多时使用。多用在首页级页面和产品类页面中。
 + ***私有样式***. `style.css` 独立页面所使用的样式文件，页面中必须包含。
 + ***模块样式***. `module.css` 产品类页面应用，将可复用类模块进行剥离后，可与其它样式配合使用。
 + ***主题样式***. `theme.css` 实现换肤功能时应用。
 + ***补丁样式***. `mend.css` 基于以上样式进行的私有化修补。

2. **css命名规范**
 + ***头部***. `header`
 + ***内容***. `content/containe` 
 + ***底部***. `footer` 
 + ***导航***. `nav` 
 + ***侧栏***. `sidebar` 
 + ***栏目***. `column` 
 + ***页面外围控制整体布局宽度***. `wrapper` 
 + ***左右中***. `left right center` 
 + ***登录条***. `loginbar` 
 + ***标志***. `logo` 
 + ***广告***. `banner` 
 + ***页面主体***. `main` 
 + ***热点***. `hot` 
 + ***新闻***. `news` 
 + ***下载***. `download` 
 + ***子导航***. `subnav` 
 + ***菜单***. `menu` 
 + ***子菜单***. `submenu` 
 + ***搜索***. `search` 
 + ***友情链接***. `friendlink` 
 + ***版权***. `copyright` 
 + ***滚动***. `scroll` 
 + ***标签页***. `tab` 
 + ***提示信息***. `msg` 

 3. **空格**
 + **不需要空格**
   + 属性名后
   + 多个规则的分隔符','前
   + !important '!'后
   + 属性值中'('后和')'前
   + 行末不要有多余的空格
 + **需要空格**
   + 属性值前
   + 选择器'>', '+', '~'前后
   + '{'前
   + !important '!'前
   + @else 前后
   + 属性值中的','后
   + 注释'/*'后和'*/'前

 4. **空行**
  + 文件最后保留一个空行
  + '}'后最好跟一个空行，包括scss中嵌套的规则
  + 属性之间需要适当的空行，具体见属性声明顺序

 5. **命名**
  + 类名使用小写字母，以中划线分隔
  + id采用驼峰式命名
  + scss中的变量、函数、混合、placeholder采用驼峰式命名

 6. **属性顺序**
  + ***相关的属性声明按右边的顺序做分组处理，组之间需要有一个空行。***
  ```
    [
        [
            "display",
            "visibility",
            "float",
            "clear",
            "overflow",
            "clip",
            "zoom"
        ],
        [
            "table-layout",
            "empty-cells",
            "caption-side",
            "border-spacing",
            "border-collapse",
            "list-style",
        ],
        [
            "position",
            "top",
            "right",
            "bottom",
            "left",
            "z-index"
        ],
        [
            "margin",
            "box-sizing",
            "border",
            "border-radius",
            "border-image",
            "padding",
            "width",
            "height",
        ],
        [
            "font",
            "vertical-align",
            "white-space",
            "text-decoration",
            "text-emphasis",
            "text-indent",
            "text-justify",
            "letter-spacing",
            "word-spacing",
            "text-outline",
            "text-transform",
            "text-wrap",
            "word-wrap",
            "word-break"
        ],
        [
            "color",
            "background",
        ],
        [
            "outline",
            "opacity",
            "box-shadow",
            "text-shadow"
        ],
        [
            "transition",
            "transform",
            "transform-origin",
            "animation",
            "animation-name",
            "animation-duration",
            "animation-play-state",
            "animation-timing-function",
            "animation-delay",
            "animation-iteration-count",
            "animation-direction"
        ],
        [
            "content",
            "quotes",
            "counter-reset",
            "counter-increment",
            "resize",
            "cursor",
            "-webkit-user-select",
            "-moz-user-select",
            "-ms-user-select",
            "user-select",
            "nav-index",
            "nav-up",
            "nav-right",
            "nav-down",
            "nav-left",
            "-moz-tab-size",
            "-o-tab-size",
            "tab-size",
            "-webkit-hyphens",
            "-moz-hyphens",
            "hyphens",
            "pointer-events"
        ]
    ]
  ```
