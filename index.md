## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Hank8709/webprogram-hw1/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Hank8709/webprogram-hw1/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


![](https://steamuserimages-a.akamaihd.net/ugc/940592594233259534/3C63C305E487534B1CD905EEE3F25B9F225D596F/) 


  
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>你好，GitHub</title>
  </head>
  <body>
    <h1>覺得厲害</h1>
  </body>
</html>

![](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif) 

<!DOCTYPE html>
<html>
    <head>
    <title>Image preview on realtime</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <script src="http://libs.baidu.com/jquery/1.9.0/jquery.js"></script>
</head>
<body>
    
    <h3>即時預覽Image</h3>
    <form name="form0" id="form0" >
        <input type="file" name="file0" id="file0" multiple="multiple" /><br>
        <img src="" id="img0" >
    </form>

    <script>    
    /**
     * 使用HTML5 File API, 來即時預覽image
     */
    $("#file0").change(function(){
        var reader = new FileReader();

        reader.onload = function (event) {
            $("#img0").attr("src", event.target.result) ;
        }

        reader.readAsDataURL(this.files[0]);

    }) ;
   
    </script>
</body>
</html>


