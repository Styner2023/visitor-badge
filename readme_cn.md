![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge-cn)

[English](https://github.com/hehuapei/visitor-badge/blob/master/README.md)

#### 项目首页
> [https://visitor-badge.laobi.icu](https://visitor-badge.laobi.icu)

#### 使用说明
```
快速使用: 
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=keyword)

自定义徽章标题: 
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=keyword&title=viewers)

```

#### 新特性

- **2020.07.18**  
1. 你可以使用'title'参数来改变徽章的标题，使用此参数只会影响标题，不会对计数有任何影响！   
**提示: 徽章标题对中文兼容性不友好，请谨慎使用中文！**  
官方文档说明: [链接](https://pypi.org/project/pybadges/)  
pybadges uses a pre-calculated table of text widths and kerning distances (for western glyphs) to determine the size of the badge. So Eastern European languages  may be rendered less well than Western European ones:  
and glyphs not present in Deja Vu Sans (the default font) may be rendered very poorly:  
pybadges does not have any explicit support for languages that are written right-to-left (e.g. Arabic, Hebrew) and the displayed text direction may be incorrect:  
 
- **2020.07.17**  
1. 切换计数接口为我自己的服务，优化计数速度，可承受更大数量的并发访问。（计数会继承之前公共接口中的数量，不用担心会从1开始计算！）  
2. 切换为自己的服务，有利于只要要开发的新功能（如：数据备份，数据分析等等...）

#### 原作者
> jwenjian：[https://github.com/jwenjian/visitor-badge](https://github.com/jwenjian/visitor-badge)
