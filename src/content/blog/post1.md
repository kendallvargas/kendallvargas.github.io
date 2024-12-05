---
title: "My experience with Cypress Automation Framework: Tips and Insights."
description: "I share my experience on my journey with Cypress, mistakes I made and some tips by learning from the mistakes I made along the way."
pubDate: "Nov 26 2024"
heroImage: "/ExperienceCypress.png"
badge: "NEW"
tags: ["Cypress","Automation", "Testing", "Programming", "Tips"]
---

<h2 class="text-2xl font-bold mb-4">🚀 My Journey with Cypress</h2>

When I started in the world of automation, one of the first tools I heard about, which I knew was well-positioned in the market, was Cypress. During my transition to learning automation, having already established a solid foundation in manual testing, I decided to learn how to use Cypress.<br/><br/>
With little to no programming knowledge, in this blog, I’ll share my experience with this tool by highlighting the challenges I faced, the mistakes I made, and the tips that may help you overcome them. These insights might be useful if you’re interested in learning about automation or are just starting out.<br/><br/>

<h2 class="text-2xl font-bold mb-4">💻 Programming</h2>

Although I had some understanding of programming concepts, one mistake I made was trying to dive into automation without solid programming knowledge. Why? Many times, automation scripts can become <b>redundant</b>. This is where creating modular code becomes important. <b>Modular code</b> is maintainable and easy to understand. After all, you’re not the only one who will read it; developers, POs, and other testers will too.<br/><br/>

A common example is iterating over objects in a dropdown menu. For this, you can use loops, which simplify handling such elements. Similarly, you can manage errors with JSON files and 'for' loops.<br/><br/>

It’s useless to copy code from an AI or other sources without understanding <b>why and when</b> to apply these structures. Trust me, it’s far better to know how to implement them. Even if you copy code, understanding its functionality is key to handling errors efficiently and avoiding spending three times longer debugging due to a mistake.<br/><br/>

<h2 class="text-2xl font-bold mb-4">🔄 Cypress</h2>

At the beginning of my journey with Cypress, my first impression was that it was easy to understand the UI part, having a dashboard and a free cloud where you can see the test results, and so on. I liked the way Cypress has the commands file, which for repetitive actions was really useful.<br/><br/>

This can be a personal opinion, but I felt that, compared to other frameworks I have used (Selenium), the code looks much cleaner and more understandable, the assertions are more readable, and the way it handles the elements is more intuitive.<br/><br/>

Additionally, I found API testing very helpful, specifically using `cy.intercept()`. Intercepting APIs on the website and validating their responses can make your code more robust and help you avoid some errors when testing websites. <br/><br/>

However, I struggled with certain locators, particularly the family locators (parent, child, siblings, and methods like nextUntil and parentsUntil). Sometimes they worked, but other times I had to find alternative approaches to handle elements. This largely depends on the website you’re testing and how it is structured. Sometimes, you won’t even need these locators. My conclusion is that understanding CSS and HTML is essential for effectively handling such elements.<br/><br/>

<h2 class="text-2xl font-bold mb-4">📚 What resources do I recommend for learning programming and Cypress?</h2>

It depends on the programming language you want to learn and, above all, studying object-oriented programming. However, to use Cypress, you can only code in <b>JavaScript or TypeScript.</b><br/><br/>

There are hundreds of free programming courses on YouTube, Udemy, and w3schools that have excellent documentation and exercises. From my perspective, practicing while learning helped me understand the concepts. The key is being repetitive, curious, and consistent.<br/><br/>

Learning loops and functions was very complex for me at first, but with practice, I understood the logic behind them, which is essential for programming.<br></br>

For <b>Cypress</b>, I recommend starting with the official documentation. It's well-structured, easy to understand, and the best way to learn how to use the tool. After that, you can look for courses on Udemy, YouTube, or <a href="https://testautomationu.applitools.com/learningpaths.html?id=cypress-path" style="text-decoration: underline;">🔗 Test Automation University 🔗</a>, which offers different automation paths and teaches you the programming language needed for the respective path you choose. <br/><br/>

<h2 class="text-2xl font-bold mb-4">💡 Things I would have liked to know before starting with Cypress</h2>

<ol class="list-decimal ml-5">
  <li> Initially, I thought Cypress documentation wasn't good enough to help with certain cases or as an introduction. I only watched YouTube and Udemy tutorials. However, Cypress has excellent documentation that covers topics like Continuous Integration, best practices, variables, and a lot of other things. If I had started by reading the documentation, it would have been much easier to apply these concepts in practice. <br/><br/>

  <li> Don’t try to learn everything right away; programming and automation are complex and require time to understand everything and perform best practices. Each time you learn a new concept, apply it and practice it until you feel comfortable. Trust me, that will save you a lot of time. <br><br> 
  A good way to learn is by exploring another repository and trying to understand the ‘why’ of some techniques. That’s something that helped me gain more knowledge and apply those techniques in ‘real-life’ scenarios, both for, automation and programming.<br/><br/>

  <li> I made this mistake when I started developing my Cypress project: even though in practice you just create random test cases for some features, this is not the way you should handle your project. I strongly believe that first having an idea is key for the techniques you are going to use, understanding the website you are going to test and many other fundamentals like the Testing Pyramid will help you create a more solid project. <br><br> 
  In automation, we don't need to automate everything (depending on the context), so if I were to try again from scratch, I would make a <b>test plan or strategy</b> about it before starting to automate.<br/><br/>

  <li> Dependency: We must not have test cases that depend on some other feature, we need to have independent test cases because if we have 15 test cases and the first one fails, imagine having all 15 test cases fail because we depend on test case 1. <br><br> 
  For personal projects this sometimes cannot be controlled, since you’re limited to a third-party website and you can’t have some additional control on your side to avoid dependencies on some feature, however, whenever test cases can be independent, it’s better.<br/><br/>

  <li> Speaking of personal projects, when choosing a website to create your portfolio, select a website that doesn't constantly change or is publicly editable. Sometimes sandboxes or free pages for automation are open for anyone to modify, and this can affect your test cases.<br> <br> 

  It happened to me that some websites had significant traffic for automation, so people changed the language of the website, which affected my locators. Also, people deleted profiles, causing my tests to fail, and many other things that were a bit stressful. Try avoiding this kind of website.<br> <br> 

  
  <a href="https://federico-toledo.com/sitios-de-prueba-para-practicar/" style="text-decoration: underline;">🔗 Link 🔗</a> where you can find websites to practice your automation tests.<br/><br/>

</ol>

<h2 class="text-2xl font-bold mb-4">🕯 Additional Tips</h2>

<ol class="list-decimal ml-5">
  <li> Knowing the basics of testing is essential before starting automation. You won’t be able to apply testing concepts and a critical eye to features just because you’re using automation. It’s like driving a car without taking a theoretical exam, having prior knowledge is <b>essential.</b> <br/><br/>

  <li> Don’t be afraid to ASK for help! Asking allowed me to connect with incredible people and learn a lot from them. If you’re stuck and don’t know what to do, ask a colleague, even on Reddit, Stack Overflow, or Udemy (mainly for paid courses), they always answer your questions. <br/><br/>

</ol>

---
<br></b>
I like to compare programming and automation with this phrase I heard a while ago: <b>Practice makes progress, not perfection.</b> <br></br>


---
<br>
Thanks for reading, and happy testing!


