# imageProcessing
imageProcessing materials

###this repo will show some image processing algorithms
----------------
* basic accepts of image processing
* some simple image processing algorithms
* image fusion algorithms
* image segmentation algorithms

1. first part
2. second part
3. third part

[links](http://www.appinn.com/markdown/)  
![images](http://www.nottingham.edu.cn/en/Engineering/departments/Computer-Science/images-multimedia/research/viplab-banner.jpg)  

> this is comment
>> this is second comment

*bold words*  
**light words**    

### tables
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |  

### table2
| table2 | is | cool |
| ------ |:---:| ---:|
| code   | is | cool |


### code block
`code section`
```python
import sys

for path in sys.path:
    pirnt path

print "end of for_loop"

```

------------
### to do list    
- [x] todo list1  
    - [ ] secdond todo list
- [x] todo list2  
- [x] todo list3  
- [ ] todo list4  


----
### to do list test   
- [ ] **Cmd Markdown 开发**
    - [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
    - [ ] 支持以 PDF 格式导出文稿
    - [x] 新增Todo列表功能 [语法参考](https://github.com/blog/1375-task-lists-in-gfm-issues-pulls-comments)
    - [x] 改进 LaTex 功能
        - [x] 修复 LaTex 公式渲染问题
        - [x] 新增 LaTex 公式编号功能 [语法参考](http://docs.mathjax.org/en/latest/tex.html#tex-eq-numbers)
- [ ] **七月旅行准备**
    - [ ] 准备邮轮上需要携带的物品
    - [ ] 浏览日本免税店的物品
    - [x] 购买蓝宝石公主号七月一日的船票
-------------------------------------

### flow chart  
```flow
st=>start: Start|past:>http://www.google.com[blank]
e=>end: End:>http://www.google.com
op1=>operation: My Operation|past
op2=>operation: Stuff|current
sub1=>subroutine: My Subroutine|invalid
cond=>condition: Yes 
or No?|approved:>http://www.baidu.com
c2=>condition: Good idea|rejected
io=>inputoutput: catch something...|request

st->op1(right)->cond
cond(yes, right)->c2
cond(no)->sub1(left)->op1
c2(yes)->io->e
c2(no)->op2->e
```
