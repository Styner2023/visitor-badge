![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)  

#### Project Home
> [https://visitor-badge.laobi.icu](https://visitor-badge.laobi.icu)

#### Usage
- default style

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)

- customized left text (default is `visitors`)

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=MyPageVisitors)
```
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=MyPageVisitors)

- customized left text with a space between words

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=My%20Page%20Visitors)
```
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=My%20Page%20Visitors)

- customzied color(RGB colors see also [#6](/../../issues/6))

```markdown 
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green) 
RGB colors eg: #595959 needs to be %23595959 in the URL
```


![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green) (left_color=red, right_color=green)

- customized color and left text

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=HelloVisitors)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=HelloVisitors) (left_color=red, right_color=green, left_text=HelloVisitors)

- customized color and a space between words in left text

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=Hello%20Visitors)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=Hello%20Visitors) (left_color=red, right_color=green, left_text=Hello%20Visitors)

- Only query the counter state without updating it [#7](/../../issues/7)
```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge-query&query_only=true)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge-query&query_only=true)


#### Feature
- **2021.06.14**  
1. add new parameters: query_only

- **2020.07.19**  
1. Daily data backup: Perform data backup and push to GitHub warehouse at 0 o 'clock per day  

- **2020.07.18**  
1. You can use parameter 'title' to change badge's title！  
**tips: The title Poor compatibility to chines**  
Official: [link](https://pypi.org/project/pybadges/)  
pybadges uses a pre-calculated table of text widths and kerning distances (for western glyphs) to determine the size of the badge. So Eastern European languages  may be rendered less well than Western European ones:  
and glyphs not present in Deja Vu Sans (the default font) may be rendered very poorly:  
pybadges does not have any explicit support for languages that are written right-to-left (e.g. Arabic, Hebrew) and the displayed text direction may be incorrect:  
 
- **2020.07.17**  
1. Change count-api to my own service, optimize the counting speed.   
2. It facilitates later functions (data analysis, data backup, etc.)

#### Fork From
> jwenjian: [https://github.com/jwenjian/visitor-badge](https://github.com/jwenjian/visitor-badge)
