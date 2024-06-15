---
layout: post
title: Demonstration of knowledge of blog posts
subtitle: Testing different functions
gh-repo: daattali/beautiful-jekyll
tags: [test]
comments: true
mathjax: true
author: ebiharar
---

{: .box-success}
This is a piece of my progress in CSE 232, mainly from this [website](https://cse232summer-msu.github.io/home/)<br/> The purpose of this blog is to test different skills of this website

**Bold Text Test**

## Secondary Heading Test 

[Link to different site test](https://cse232summer-msu.github.io/home/) <br/> [Link to locat site test](#url_test).

Table test:

| Table | Test | 4 | Columns |
| :------ |:--- | :--- | :--- |
| Week | One | Quiz | [Link](https://cse232summer-msu.github.io/assets/week1/quizzes/Week1_Sample_Questions_1.pdf) |
| Week | Two | Quiz | [Link](https://cse232summer-msu.github.io/assets/week2/quizzes/CSE_232_Flash_Quiz_2.pdf)|
| Week | Three | Quiz | [Link](https://cse232summer-msu.github.io/assets/week3/quizzes/CSE_232_Flash_Quiz_4.pdf) |
| Week| Four | Quiz | [Link](https://cse232summer-msu.github.io/assets/week4/quizzes/Week4_Sample_Questions_1.pdf) |

Favorite formula: <br/> \\(e ^i ^pi + 1 = 0)\\ 

Image of crepe centered test:
![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Code chunk test:

~~~
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
~~~

Code with syntax highlighting test:

```C++
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```

Code with line numbers test:

{% highlight javascript linenos %}
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
{% endhighlight %}

### Notification test {#url_test}

{: .box-note}
Notification box test

### Warning test

{: .box-warning}
Warning box test

### Error test

{: .box-error}
Error box test
