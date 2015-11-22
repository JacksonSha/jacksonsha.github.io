---
layout: post
title:  "Hello World!"
date:   2015-11-12 22:39:54
categories: java开发
figure: "/assets/helloworld.png"
---

使用 Bootstrap 中文网提供的免费 CDN 加速服务（同时支持 http 和 https 协议）
Bootstrap 中文网 为 Bootstrap 专门构建了自己的免费 CDN 加速服务。基于国内云厂商的 CDN 服务，访问速度更快、加速效果更明显、没有速度和带宽限制、永久免费。Bootstrap 中文网还对大量的前端开源工具库提供了 CDN 加速服务，请进入BootCDN 主页查看更多可用的工具库。

<img class="img-responsive" src="{{site.url}}/assets/helloworld.png"/>

复制

{% highlight scala %}
String name="jack";
Integer age=25;
{% endhighlight %}

{% highlight javascript %}
<!-- 新 Bootstrap 核心 CSS 文件 -->
<link rel="stylesheet" href="//cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap.min.css">

<!-- 可选的Bootstrap主题文件（一般不用引入） -->
<link rel="stylesheet" href="//cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">

<!-- jQuery文件。务必在bootstrap.min.js 之前引入 -->
<script src="//cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>

<!-- 最新的 Bootstrap 核心 JavaScript 文件 -->
<script src="//cdn.bootcss.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
{% endhighlight %}

	You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
