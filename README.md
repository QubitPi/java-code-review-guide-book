The Art of Code Review
======================

Rick: "Jiaqi, I just reviewed your [PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) and you can work on it. Let me know if you have any questions."

Me: "(No way... You gotta be kidding me. Again???)"

I sent [Rick](https://github.com/cdeszaq) a thank-you note via Slack and, then, jumped into that PR. No surprise,
**30+** review comments:

* "Missing a period at the end of sentence"
* "This line break is not necessary"
* "The Javadoc of this class is a bit ambiguous, you don't want to lose all details when you read your code again in 6
  months"
* "By design, this object should not be passed to the next layer"
* ...

Rick was a Senior Software Engineer at Yahoo!. But I was a recent graduate who just learned there was something called
"code review" in this world few months ago.

This is probably the 20th code review on a single PR. It's not a bad PR to be honest with you. Regular feature
change in about 500 lines of code. I think I did a good job on that.

Chris: "How's everything going, Jiaqi? Work done already?"

Me: "Well, almost, except Rick just shot me another 30 comments. It'll probably take 2 hours"

Chris: "😊 Don't worry" 

Chris was my boss and he managed our team. He knew I was kinda green and needed more time to ramp up. But another 30 
comments on 20th review is probably a little bit of shock to him. I wish I could tell Chris "I promise the code works now 
already. I'm just trying to make Rick happy. You know, he is a perfectionism..."

Hoping to end this little miserable infinity in the next code review, I continued to working on Rick's comment until I
noticed one of his comments. It was more of like a "little-design-change & code-style" comment which didn't seem to
change any code logic. But as I implement his proposed change, I spotted a bug.

I sat back and thought about it for a while...

Look, this was simply a design change which doesn't imply any change of logic, let alone a bug fix. But Rick's better 
design literally avoided a potentially serious bug that could annoy users in production environment. 

"This is amazing!". It's like getting a job promotion simply by improving your daily dress code. A change of attitude 
towards code design can make your code 100 times better!

All of a sudden, I changed my view on Rick's code review and I started to learn from his thoughts. When everyone was 
reluctant to ask for his review, I grabbed every chance and ask him to do that for me everyday. At the end of the day,
**I learned, from Rick, that Software Engineering is not abot "making it work" at all. It's about "making it right"**.
To make it right, I have to make it perfect and it is only through this way I am approving to myself that I love what I
am doing. When I love it, I will make it good!

It is Rick who told me how perfectionlism can shape your view and action in SWE and, also, the reason I put together
this [book on code review](./main.pdf). 
