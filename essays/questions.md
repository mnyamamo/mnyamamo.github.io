---
layout: essay
type: essay
title: "Asking smarter questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: true
labels:
  - Stack Overflow
  - Questions
---

People ask questions all the time. Why is the sky blue? Can I pet your dog? Is it a bird, a plane, or Superman? These questions are simple and typically easy to answer. In fact, a Google search will answer most questions posed by people, although more research is usually necessary to understand them. While teachers may say "There are no stupid questions" and this may be true in a classroom setting, where people should be asking questions, it is usually less true online, where Google searches are abundant and clear and concise information is everywhere. In fact, if an answer can be obtained through a quick Google search, it is typically considered a stupid question. However, on the flip side, if a user has already done a Google search and cannot understand the answer, then it may be considered to be a better question. In this way, there are good questions and bad questions. Good questions tend to be questions that show that the asker has done their homework and specific about the details, while bad questions tend to be ones that do not show that the asker has done their homework and are very unspecific about the details.

## [Smart Questions](https://stackoverflow.com/questions/477816/which-json-content-type-do-i-use)
Stack Overflow is a site for people to ask questions and get answers. However, not every question is always good, and often, bad questions get ignored or even downvoted. On the contrary, good questions often get many quality answers.  

in the following example, the user asks about JSON standards and when they should be used. Let's examine why this is a good question, and how it might be better.

```
Q: Which JSON content type do I use?
There are many standards for the JSON content type:
application/json
application/x-javascript
text/javascript
text/x-javascript
text/x-json
Which one do I use, and where? I assume security and support issues are a factor.
Related: What MIME type if JSON is being returned by a REST API?
```

Although this asker does not directly state what they have searched, they have shown that they have done their homework by linking a related question at the bottom. In addition, they list several different standards for the JSON content type. In fact, this question was so good that it recieved 39 different answers, including a recent answer from July 29, 2023. However, following the standards set out in the [paper](http://www.catb.org/esr/faqs/smart-questions.html) by Eric Steven Raymond and Rick Moen, it could be improved. The most obvious (and easy) is to thank the people who are going to answer. 

## [Bad Questions](https://stackoverflow.com/questions/77001136/how-to-check-if-a-string-is-random-in-python)
In contrast, this next example showcases a bad way of asking a question. Let's examine why this is a bad question.
```
Q: How to check if a string is random in Python?
On social media, people send messages like "cjhdfsjnsnjd", "skhjfvhjdyg", "dpaopdjjjg" to get a laugh. But some people also add swearing to these random messages. I made a
discord bot with python to find this, but the program doesn't search for the word as a whole in the sentence, so it can find it even if the person who integrated the swear word
into the text of random letters places the letters in different places. But in these normal sentences it combines the scattered characters and recognizes it as a swear word. Is
there any function or library in Python that can recognize if the text is random text or a normal sentence?
```
First of all, the question is not very precise. As one person points out in the comments, "How would you define 'random text'? How would you define 'normal sentence'?" Some people do try to answer the question seriously, but another person points out "What if the messages are Polish or Czech? This might appear random to you?" Ultimately, the question is downvoted because people think that this person doesn't really understand what they're asking. 

The person could improve the question by specifying what is random and what is not, but my thoughts are that they are trying to tackle an impossible problem. It is good of them to ask, but they appear to be looking for an easy solution where there is none. 

## Conclusion
Ultimately both questions show that good answers are likely to get more answers, more views, and more upvotes, which in turn help more people see the page and give more answers. On the other side, bad questions will get downvoted and are seen less often, which makes the question less likely to be answered, even if there is a valid answer (which is not in this case). However, even bad questions get answered sometimes by someone who is merciful, and vice versa, good questions sometimes get ignored. It's always important to ask the good questions, but more important to keep trying.
