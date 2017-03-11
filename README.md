# blog
我的博客


#### 前言
今天给大家介绍下markdown的一些基本使用，这些东东是自己在学习markdown的时候做的一些总结，如有错误，还望积极指正，谢谢。

#### markdown是什么？
markdown是一种简单的标记语言。它与html标签对应，我们可以通过一些转换库可以将markdown转换为html或html转换为markdown.

####markdown基本的标签使用
**1.#** 
[#] 用于定义标题,共1-6个等级，随着#号的添加等级相应的减少

*注：#号加[]为了更好标注内容，切记当做语法使用*

*example:*
```
    # 标题1
        ## 标题2  
	    ### 标题3 

	    ```
	    **效果图**：
	    # 标题1
	    ## 标题2
	    ### 标题3
	    **2.+、- 、数字1~9**
	    [+]、[-]用于无序列表，数字1-9用于有序列表

	    *exmaple1*
	    ```
	        + 篮球
		    + 足球
		        + 排球
			```
			**效果图**
			+ 篮球
			+ 足球
			+ 排球

			*example2*
			```
			    - 篮球
			        - 足球
				    - 排球
				    ```
				    **效果图**
				    - 篮球
				    - 足球
				    - 排球

				    *example3*
				    ```
				      1. 篮球
				        2. 足球
					  3. 排球
					  ```
					  **效果图**
					  1. 篮球
					  2. 足球
					  3. 排球

					  **3.** \`\` 和 \`\`\` \`\`\`     
					  example1:单行用 \`\` 

					  **效果图**       
					  `var number1 =2; ` 

					  example2:多行用 \`\`\` \`\`\`
					  **效果图**
					  ```
					  function(name,age,gender){
					      this.name = name;
					          this.age =age;
						      this.gender = gender;
						      }
						      ```  
						      **4.\[]() **
						      \[]()用于插入链接
						      `语法：[链接显示的文字](url)`
						      *example*
						      [转载markdown语法说明](http://wowubuntu.com/markdown/index.html)

						      **5.\!\[]() **
						      \!\[]()用于插入图片
						      *example*
						      `![安吉丽娜朱莉](http://upload-images.jianshu.io/upload_images/5003721-22f7fe4afa825411.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/12)`
						      **效果图**

						      ![安吉丽娜朱莉](http://upload-images.jianshu.io/upload_images/5003721-22f7fe4afa825411.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

						      **6.表格使用**

						      *example1*
						      ```
						      | Tables        | Are           | Cool  |
						      | ------------- |:-------------:| -----:|
						      | col 3 is      | right-aligned | $1600 |
						      | col 2 is      | centered      |   $12 |
						      | zebra stripes | are neat      |    $1 |```
						      **效果图**

						      | Tables        | Are           | Cool  |
						      | ------------- |:-------------:| -----:|
						      | col 3 is      | right-aligned | $1600 |
						      | col 2 is      | centered      |   $12 |
						      | zebra stripes | are neat      |    $1 |

						      *example2*
						      ```
						      dog | bird | cat
						      ----|------|----
						      foo | foo  | foo
						      bar | bar  | bar
						      baz | baz  | baz
						      ```
						      **效果图**

						      dog | bird | cat
						      ----|-----|----
						      foo | foo  | foo
						      bar | bar  | bar
						      baz | baz  | baz

						      综上就是markdown的一些基本标签的使用，本人还在学习阶段，后续还会补充。本文章归[饥人谷_nanhai](http://www.jianshu.com/users/86c6b4b96019/timeline)和饥人谷所有，转载须说明来源。
