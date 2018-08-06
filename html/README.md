# DOCTYPE

DOCTYPE文档类型指出浏览器按照什么规则解释HTML或XHTML中的标记。DOCTYPE不存在或格式不正确会导致文档以兼容模式呈现

在 HTML 4.01 中，<!DOCTYPE> 声明引用 DTD，因为 HTML 4.01 基于 SGML。DTD 规定了标记语言的规则，这样浏览器才能正确地呈现内容

HTML5 不基于 SGML，所以不需要引用 DTD

DTD: [Document Type Definition](https://zh.wikipedia.org/wiki/%E6%96%87%E6%A1%A3%E7%B1%BB%E5%9E%8B%E5%AE%9A%E4%B9%89) 文档类型定义

SGML：[Standard Generalized Markup Language](https://zh.wikipedia.org/wiki/SGML) 标准通用标记语言

# 标签

每个标签都有默认的display值，div的默认display为block,意为“块级”，span的默认display值为inline，意为“行内”

常见的块级元素有：**div p ul li dl dt dd h1-h6 table**

常见的行内元素有：**a b span img input label strong button**

空元素：**br hr img imput link meta**

# meta 标签的巧用及seo优化

**SEO（Search Engine Optimization）**:汉译为搜索引擎优化。 是一种方式:利用搜索引擎的规则提高网站在有关搜索引擎内的自然排名

## seo常用的标签:

- h1 确保页面只有一个h1标签，不要给h1标签添加多余的class

- title 标题

- strong 对内容进行强调（ b 标签和 strong 标签在网页上的显示效果一样，意义却不同。b 标签只是单纯的对文本进行加粗，仅仅是样式需求(视觉要素)。strong 是一个带有着重意味的标签，表示该文本比较重要，提醒终端/读者注意（表达要素）。同理 i 和 em）

- meta &lt;meta name="description" content="网站描述" /&gt;和&lt;meta name="keywords" content="网站关键词" /&gt;

- a &lt;a href="链接地址" title="链接说明"&gt;链接关键词&lt;/a&gt;

- img &lt;img src="图片链接地址" alt="图片替代文字" / &gt;、&lt;img src="图片链接地址" title="图片说明" /&gt;（alt 是当图片不存在时的替代文字，title 是对图片的描述，鼠标经过时，title值会显示。搜索引擎对图片意思的理解，主要靠 alt）

- mate 标签提供页面的元信息，元信息总是以名称/值的方式存在。  http-equiv 和 name 属性 提供名称，content 属性提供值。http-equiv 把 content 属性关联到http头部。name 主要用于描述网页，比如关键词、网站描述、作者信息等
