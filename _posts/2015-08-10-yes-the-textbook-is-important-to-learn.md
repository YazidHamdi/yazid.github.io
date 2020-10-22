---
layout: post
title: Yes, The Textbook IS Important To Learn Development
date: '2015-08-10T12:18:34+02:00'
tags:
- software
- development
- coding
- learning
- university
categories: SE
---
An attempt to analyze the weaknesses of software development learning in the French system, let me know what you think:)
[Yes, the textbook IS important to learn development](https://www.linkedin.com/pulse/yes-textbook-important-learn-development-yazid-hamdi)

---
There you have it in the title.

But wait a minute, isn't that so obvious that it's kinda naive to write an article about it? Well, it is. However, the fact that it took me some time after graduation to figure out how critical this is attests to the importance of this issue, because when I say "it took me", I think it's legitimate to assume it would be the case for many of my peers who graduated from the same kind of engineering schools and studied in the same system. It's really a cultural issue, as I will explain.

To clarify this, here's how we (by "we" I designate computer engineering students in University of Tunis, might even be legitimate for those who studied in any university in Tunisia, might even be legitimate for those who studied in any French-system university, since the organization of learning is very similar) learned how to write software: teacher comes in, shows a slideshow, does examples, and we exercise. This is usually sufficient for C, Assembly, etc... but moving up to object-oriented languages, and web development languages (HTML, CSS, JS, etc...) this method becomes largely deficient for three reasons:

1. These languages are not important as languages, their industry practice has evolved so much that it is no longer an achievement to just understand the syntax or be able to write some basic code: Platforms (mobile, cloud...), architecture (SOA...), frameworks, best practices, design patterns... these become the real goals when learning these languages. You're not really proficient in a language, more like a whole software development context, which is exactly what software development teams are looking for in new comers, even at basic awareness level. But this is only a part of the problem. Thing is, at school, and through school work, you only learn to work with a tiny fraction of a language's full potential (take Java or C# for example), which is quite a handicap and might cause you to write code reinventing the wheel (inefficiently most of the time), and that is a bad, very bad thing.
2. The above method is usually one where the student is mostly a recipient of theoretical course, there's not much practice, and even the practical labs or projects are not structured or designed to raise awareness of point 1. I have seen myself develop a campus management web app with PHP5 and Zend framework, and it was really hard work since the classes didn't really prepare us for it, I might even say they didn't point us to the right direction. Instead of raising awareness of the right (or best) way of coding things, the focus is DIY coding, even DIAYHYL (Do It All Yourself, However You Like), which might be a good method to practice the language itself, but a very bad one to deliver working software.
3. An additional problem is the astonishing absence of software project management practice. I'm not talking about the big courses about life cycles etc... I am talking about version control, bug tracking, coding policies synchronization between team members, well documented code, etc... As important as these elements are in the industry, their practice is quite rare in learning contexts.

But what does all this have to do with textbooks? Well, half a year into my work as a software development engineer, and having realized the above points, I reopened the textbooks. These were mostly design methodology, beautiful code, and in depth C# books. And in fact, the C# book was also to prepare for MCP certification 70-483: programming in C#. And boy did I discover new things, see point 1 above. I discovered the hard way that all this time, my work with C# was like having a Swiss knife and only using it to cut cheese. It made me realize how much learning one must do before tackling big projects, because when you want to take a mountain apart and use the blocks to build a castle, it helps if you have more than a small shovel. Learning about the full potential of the language/platform/framework makes your code far more usable and improves its quality, because using well placed collections, LINQ, Tasks, logging classes etc... is sure far better than writing your own code to do the same thing.

In conclusion, this is my advice to students and graduates: read reference books. In the English-speaking countries' software engineering education system, textbooks are systematically recommended as reading material and reading them is sometimes a requirement for passing the subsequent exams. In the Tunisian and French system (exceptions aside), fully relying on the teacher's course (which is and will always be only a starting point) is common practice, and it is a bad, very bad thing, as I have come to discover. So you should really seek further training and knowledge and be aware that what you learn in class is but a fraction of what you need to learn to meet the job market requirements.

Also, and these are final subjective recommendations:

* English is your friend. Reading textbooks in English is almost a must, since most (if not all) the technology being dealt with originates in English-speaking countries, mainly the US. It is the language of CS and software development everywhere, and sooner or later (if you don't want to be left behind that is) you'll have to shift to the English terminology. Translated versions or books in languages other than English in general are bad because they set you aside from the community's terminology (present in online forums, products documentation, etc...), thus hurting your ability to communicate with other developers, and also because in terms of publication, there is often a delay between the English literature publications and the other languages' publications, so you'll be forced to be several months behind.
* Try to pick your textbooks from sources with creator/contributor credentials when you make your choices. These people are often the ones who understand the technology/methodology most and who are bound to provide unique perspectives that no one else no matter how senior can provide.