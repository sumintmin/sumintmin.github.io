---
layout: post
title:  "Hello"
date:   2024-07-27 15:50:39 +0900
categories: jekyll update
---

하하.... `하하`
`_posts` 폴더에서 이걸 찾을 수 있다. 가서 편집해! 그리고 다시 작성해라 사이트를 너의 수정 사항을 보기 위해서
너는 여러 방향으로 다시 작성할 수 있다. 그러나 가장 일반적인 방법은  `jekyll serve`를 활용하는 방법이다.  웹 서버를 열고 자동으로 동기화해준다.

지킬은 아래의 형식을 맞춰 작성해야한다.

`YEAR-MONTH-DAY-title.MARKUP`

YYYY-mm-DD 형식을 맞춰야되고 markup확장자를 사용한다.
이 파일을 보고 작동방식에 대한 아이디어를 얻어봐!

지킬은 또한 강력한 코드스니펫을 지원한다. 스니펫이란 짧은 발췌를 의미하며,
코드 조각이라는 뜻이 된다.
Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
