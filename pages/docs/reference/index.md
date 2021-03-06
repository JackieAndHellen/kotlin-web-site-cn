---
layout: reference
title: "Reference"
---

# **Learn Kotlin**
<div style="display: inline-flex; border: 1px solid rgb(229, 229, 229); border-radius: 40px;" >
 <div id="material" onmouseover="this.style.backgroundColor='#F0F0F0'" onmouseout="this.style.backgroundColor=''" style="cursor: pointer; padding: 1rem 2rem;border-radius: 40px; border: 1px solid transparent;" >All Materials</div>
 <div id="start" onmouseover="this.style.backgroundColor='#F0F0F0'" onmouseout="this.style.backgroundColor=''" style="cursor: pointer; padding: 1rem 2rem;border-radius: 40px;">Getting Started</div>
 <div id="migrate" onmouseover="this.style.backgroundColor='#F0F0F0'" onmouseout="this.style.backgroundColor=''" style="cursor: pointer; padding: 1rem 2rem;border-radius: 40px;">Migrating from Java</div>
</div>
<div style="display:grid; grid-template-columns: 1fr 1fr;">
    <div style="padding: 5px;">
        <h3 style="font-weight: bold">Documentation</h3>
        <p>Kotlin documentation is a good step to start, check out these links for the beginning:</p>
        <ul>
            <li class="start">   <a style="text-decoration: none;" href="/docs/reference/basic-syntax.html">Basics</a> </li>
            <li class="migrate"> <a style="text-decoration: none;" href="/docs/reference/idioms.html">Idioms</a> </li>
            <li class="migrate"> <a style="text-decoration: none;" href="/docs/reference/java-interop.html">Interop with Java</a>  </li>
        </ul>
    </div>
     <div style="padding: 5px;">
         <h3 style="font-weight: bold">IDE</h3>
         <p>Kotlin is supported in many IDEs, it helps writing idiomatic Kotlin code:</p>
         <ul>
             <li class="start">         <a style="text-decoration: none;" href="https://www.jetbrains.com/help/education/learner-start-guide.html?section=Kotlin%20Koans">Kotlin Educational Plugin</a> </li>
             <li class="migrate start"> <a style="text-decoration: none;" href="https://www.jetbrains.com/help/idea/converting-a-java-file-to-kotlin-file.html">Java2Kotlin converter</a>  </li>
         </ul>
     </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Ask community</h3>
          <p>Kotlin community is open, helpful and welcoming. Don't hesitate to join and ask on any platform you like:</p>
          <ul>
              <li class="migrate"> <a style="text-decoration: none;" href="https://blog.jetbrains.com/kotlin/">Blog</a> </li>
              <li class="start"> <a style="text-decoration: none;" href="https://discuss.kotlinlang.org/">Forum</a>  </li>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://surveys.jetbrains.com/s3/kotlin-slack-sign-up">Slack</a> </li>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://stackoverflow.com/questions/tagged/kotlin">Stack overflow</a> </li>
          </ul>
      </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Playground</h3>
          <p>Heads on experience is the way to master your Kotlin skills on real examples right in the browser</p>
          <ul>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://play.kotlinlang.org">Playground</a> </li>
              <li class="migrate"> <a style="text-decoration: none;" href="https://play.kotlinlang.org/byExample">Kotlin Examples</a>  </li>
              <li class="start"> <a style="text-decoration: none;" href="https://play.kotlinlang.org/koans">Koans</a> </li>
          </ul>
      </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Books</h3>
          <p>All Kotlin aspects are well covered in <a>Books</a>, check out these books to start:</p>
          <ul>
              <li class="start"> <a style="text-decoration: none;" href="https://www.amazon.com/Kotlin-Programming-Nerd-Ranch-Guide/dp/0135161630">Kotlin Programming: The Big Nerd Ranch Guide</a> </li>
              <li class="migrate"> <a style="text-decoration: none;" href="https://leanpub.com/kotlin-for-android-developers">Kotlin for Android Developers</a> </li>
              <li class="start"> <a style="text-decoration: none;" href="https://www.atomickotlin.com/atomickotlin/">Atomic Kotlin</a> </li>
              <li class="migrate">   <a style="text-decoration: none;" href="https://www.manning.com/books/kotlin-in-action">Kotlin in Action</a> </li>
          </ul>
      </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Online Courses</h3>
          <p>Kotlin is well covered in online courses, check out recommended courses here</p>
          <ul>
            <li class="start">   <a style="text-decoration: none;" href="http://shop.oreilly.com/product/0636920052982.do">Introduction to Kotlin Programming</a></li>
            <li class="migrate"> <a style="text-decoration: none;" href="http://shop.oreilly.com/product/0636920052999.do">Advanced Kotlin Programming</a></li>
            <li class="start">   <a style="text-decoration: none;" href="https://www.coursera.org/learn/vvedenie-v-yazyk-kotlin">Introduction to Kotlin (in russian)</a></li>
            <li class="migrate"> <a style="text-decoration: none;" href="https://coursera.org/learn/kotlin-for-java-developers">Kotlin for Java Developers</a></li>
          </ul>
      </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Certified Training</h3>
          <p>Certified by JetBrains is a program created to work with training providers to verify their existing Kotlin training programs and at the same time,
             build a trusted network of global partners:</p>
          <ul>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://www.jetbrains.com/company/partners/kotlin/">Training Partners</a></li>
          </ul>
      </div>
      <div style="padding: 5px;">
          <h3 style="font-weight: bold">Community Resources</h3>
          <p>Check out these community resources for more information</p>
          <ul>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://kotlin.link">kotlin.link</a></li>
              <li class="start migrate"> <a style="text-decoration: none;" href="https://superkotlin.com/blog/">superkotlin blog</a></li>
          </ul>
      </div>
</div>




<script>
window.addEventListener('load', function () {
    function switchDisplay(element, targetClass) {
        if (!element.classList.contains(targetClass)) {
            element.style.display = "none";
        } else {
            element.style.display = "list-item";
        }
    }

    const material = document.getElementById('material');
    const start = document.getElementById('start');
    const migrate = document.getElementById('migrate');
    const selectedBorder = '1px solid #5585B8';

    material.style.border = selectedBorder;

    const elements = Array.from(document.querySelectorAll(".start, .migrate"));
    material.addEventListener('click', function (event) {
        event.target.style.border = selectedBorder;
        [start, migrate].forEach(el => el.style.border = 'none');
        elements.forEach(el => {
            el.style.display = "list-item"
        })
    });

    start.addEventListener('click', function (event) {
        event.target.style.border = selectedBorder;
        [material, migrate].forEach(el => el.style.border = 'none');
        elements.forEach(el => switchDisplay(el, "start"));
    });

    migrate.addEventListener('click', function (event) {
        event.target.style.border = selectedBorder;
        [start, material].forEach(el => el.style.border = 'none');
        elements.forEach(el => switchDisplay(el, "migrate"));
    });
});
</script>

---

### 离线文档
下载离线文档：
- [PDF 文件](https://www.kotlincn.net/docs/kotlin-docs.pdf)
- [PDF 文件 GitBook 版（字大一些）](https://www.gitbook.com/download/pdf/book/hltj/kotlin-reference-chinese)
- [ePUB 文件](https://www.gitbook.com/download/epub/book/hltj/kotlin-reference-chinese)
- [Mobi 文件](https://www.gitbook.com/download/mobi/book/hltj/kotlin-reference-chinese)

其中 ePUB、 Mobi 以及字大版 PDF 文件都是 GitBook 上自动构建的，也可同时关注 GitBook 上的电子书：[gitbook.com/book/hltj/kotlin-reference-chinese](https://www.gitbook.com/book/hltj/kotlin-reference-chinese/details)。

关于网站与 PDF 有任何问题请在[这里](https://github.com/hltj/kotlin-web-site-cn/issues)反馈；
关于 ePUB、Mobi 以及字大版 PDF 有任何问题请在[这里](https://github.com/hltj/kotlin-reference-chinese/issues)反馈。

欢迎关注我的博客《灰蓝时光》（[https://hltj.me/](https://hltj.me/)）以及公众号与微博：

| ![wechat_qr.png](/assets/wechat_qr.png) | ![weibo_qr.png](/assets/weibo_qr.png) |
|:------:|:----:|
| 公众号 | 微博 |
