---
layout: post
title: Demonstration of knowledge of blog posts
subtitle: Testing different functions
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Ryo Ebihara
---

{: .box-success}
This is a piece of my progress in CSE 232, mainly from this [website](https://cse232summer-msu.github.io/home/)<br/> The purpose of this blog is to test different skills of this website

**Bold Text Test**

## Secondary Heading Test {#url_test}

[Link to different site test](https://cse232summer-msu.github.io/home/) <br/> [Link to locat site test](#url_test).

Table test:

| Table | Test | 4 | Columns |
| :------ |:--- | :--- | :--- |
| Week | One | Quiz | [Link](https://cse232summer-msu.github.io/assets/week1/quizzes/Week1_Sample_Questions_1.pdf) |
| Week | Two | Quiz | [Link](https://cse232summer-msu.github.io/assets/week2/quizzes/CSE_232_Flash_Quiz_2.pdf)|
| Week | Three | Quiz | [Link](https://cse232summer-msu.github.io/assets/week3/quizzes/CSE_232_Flash_Quiz_4.pdf) |
| Week| Four | Quiz | [Link](https://cse232summer-msu.github.io/assets/week4/quizzes/Week4_Sample_Questions_1.pdf) |

Favorite formula: <br\> \\(e^(i \pi) + 1 = 0\\) 

Image of crepe centered test:
![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Code chunk test:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites 

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
