---
layout: post
title: "Announcing Code Health Guardian: The Old-New Role of Human Programmers in the AI Era"
date: 2024-10-30 00:00:00 +0
categories: [Book Launch]
---

I am thrilled to announce the launch of my new book, *Code Health Guardian*, which was designed to prepare software engineers for the upcoming changes in their duties. As AI reshapes the tech industry, how can we ensure our skills remain indispensable? It’s unlikely that attempting to pivot and rapidly become AI experts, as some suggest, is the best strategy for most of us. After all, AI development and integration appear to be tasks perfectly suited for AI itself. Instead of trying to beat AI agents at their own game, I believe a far better approach is to grow faster and deepen our expertise in managing code complexity, which is the topic of this book. Complex reasoning is hard for AI, and in programming, that’s the most intellectually challenging problem—keeping our codebases reasonably simple.

<img src="/images/front_cover.jpg" alt="Cover image" width="400" />

Although the skill of keeping code healthy has been a hallmark of seniority for decades, I believe it’s going to become even more crucial in the brand new era we’re entering, as AI agents are highly likely to take over routine coding tasks. This book aims to prepare you for that moment: when the day comes, to qualify for the old–new role of human software engineers in the AI era—the role of a Code Health Guardian.

## What makes this book special

You may be wondering: Isn't this just another book on software design and code quality? Well, there are two aspects that make this book very special. The first one is the code complexity model introduced in Chapter 2, which further develops the model proposed by John Ousterhout in *[A Philosophy of Software Design](https://www.amazon.com/Philosophy-Software-Design-2nd/dp/173210221X/)* five years ago. The two causes of complexity (dependencies and obscurity) are replaced with seven more specific ones:

- Duplication
- Too many dependencies
- Unstable dependencies
- Untrue interfaces
- Complex interfaces
- Obscurity
- Unfamiliarity

Most of the book is built around these seven complexity causes and the three practical problems they create: change amplification, cognitive load, and unknown unknowns.

Second, what makes this book different is my experience at Google, which is renowned for its code quality practices (internally also known as "code health practices"). When the book *[Software Engineering at Google](https://www.amazon.com/Software-Engineering-Google-Lessons-Programming/dp/B08VKLTB9X/)* was published, I found myself thinking, “Well, it looks great, but it's mostly about building an engineering organization, not about software design or actual coding at Google.” So, I reached out to the lead author, Titus Winters (who also wrote the foreword for this book), with one very specific question: Why is the section on design docs so small? I then outlined what I expected to be there and shared it with him. That’s how the first version of Chapter 8: “Trade-off Analysis and Design Docs” was born. And it’s not just design docs; there are several other code health practices that were either completely out of scope in *Software Engineering at Google* or didn’t receive enough coverage for various reasons. This book aims to close that gap.

Finally, I hope you'll find *Code Health Guardian* less dogmatic, more pragmatic, and more fun to read than most other books on code quality. Happy coding today, and likely, happy reviewing tomorrow!
 
—
Artie Shevchenko

## What others are saying

"In the brave new world of AI-generated codebases, this work is an essential companion for every aspiring programmer. A must-read for anyone aiming to go from a 'coding monkey' to 'system architect.'" —Dr. Jesse Lu, Engineering Lead, SPINS Photonics Inc

"Filled with actionable guidance and helpful examples. A must-read for software professionals looking to level up their skills." —Jeff Doolittle, Senior Software Architect, Trimble

"An excellent read, covering often overlooked software development quality practices. An invaluable resource for writing sustainable and maintainable code." —Laurynas Kavaliauskas, Senior Principal Architect, Zscaler

"Offers solid theoretical advice while staying practical. Reading this book helped me refine my views on various aspects of software engineering." —Sergey Tselovalnikov, Staff Software Engineer, Canva

"Bridges the gap between theoretical learning and practical application. Highly recommended for anyone wanting to write software that stands the test of time." —Dr. Andrew Stankevich, Associate Professor and Dean, ITMO University

"An excellent collection of practical advice for reducing risks in software development. I hope you all enjoy it as much as I have." —Titus Winters, Lead Author, *Software Engineering at Google*.

## Try it out

You can find a **[sample chapter here](https://github.com/artie-shevchenko/code-health-guardian/blob/main/book/CodeHealthGuardian_SampleChapter.pdf)**. The book is [available on Amazon](https://amzn.to/3Uva6uK) starting today! The Kindle version is in review and should be available within 24 hours. If you care a lot about the look and feel, it may be worth waiting for the hardcover version (ETA by the end of November). I was thinking about doing an audiobook as well, but there's a lot of visual content there, so it would be challenging. But why not? Please upvote [this ticket](https://github.com/artie-shevchenko/code-health-guardian/issues/1) if you think it’s a good idea.

## Share your thoughts

I'd love to hear from you! Share your thoughts and join the conversation in the [code-health-guardian Google Group](https://groups.google.com/g/code-health-guardian). On social media, please use the #codehealth tag.

Finally, if you enjoy the book please [leave a review](https://amzn.to/3YIuzyL)! I would greatly appreciate it.

<br/>

---

<br/>

<div style="overflow: hidden;">
  <img src="/images/artie_avatar.jpg" alt="Artie avatar" style="float: left; margin-right: 15px; margin-bottom: 15px" width="200">
  <small>
    <p style="margin-bottom: 15px;">Artie Shevchenko is a former Google software engineer, ex-CEO, and founder of a startup. Currently, he’s a software engineer at Canva and a lecturer at ITMO University. Although this is his first book, he’s not new to technical writing and educational projects. Specifically:</p>

    <ul style="list-style-position: inside; margin-left: 0">
      <li>He is the creator of internal “Good Code Reviewer” classes at Google, with the 4.5/5 rating based on 100+ reviews. In one year, over a thousand Google engineers took the classes.</li>
      <li>He is also the author of the Productive Software Engineering university course and has been teaching it for several years now (NPS > 50%).</li>
    </ul>

    <p style="margin-bottom: 15px;">Artie has over 10 years of diverse industry experience, which informs his pragmatic approach to code health. He has been working:</p>

    <ul style="list-style-position: inside; margin-left: 0">
      <li>As a software engineer, engineering manager, and CEO; and</li>
      <li>For tech giants such as Google (2015–2019) and Canva (2023–), in medium-sized companies, and in small startups.</li>
    </ul>

  </small>
</div>