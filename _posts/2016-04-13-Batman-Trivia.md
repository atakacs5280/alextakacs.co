---
layout: post
title: Batman Trivia and Amazon Alexa
---

There is something so special about Batman. In the cannon of superheros he is, in my opinion, the most honorable. He has a deep dark sad soul that is in constant self repression. He hides it, loses loved ones, and still manages to keep Gotham safe.

No one can forget the scene in The Dark Knight after Rachel dies, where he is sitting in his chair, looking out the window, holding his mask/cowl off to the side of the arm rest. We see him at his lowest, and he stands up and continues to fight crime. Albeit 8 years later but you get the point!

Tonight I saw Deadpool for the 3rd time. Yes I spent hard earned money to see the same thing 3 times. As superheros go, he is the anthesis of Batman. Rude, crass, amazingly obnoxious, and incredibly funny.

I like these superhero's equally. Polar opposites, but I have a hard time choosing which one I like more.

What could Batman use? some humor. When I dove into coding today I decided that Amazon Alexa was going to get some Batman Trivia with a twist.

If you don't know what Amazon Alexa is (no its not a large amazonian woman named Alexa), stop what you're doing and google it (or hold your horses and wait to seconds until I tell you). This is a game changer and Amazon has made it incredibly easy to play with.

Alexa is the software that is running the Amazon Echo, the Dot, and a few other products. It's a voice activated software that is woken up when the user says the word/name "Alexa". Once it's uttered a whole world is opened up to the user. Alexa has "skills", essentially apps that are specific in use, such as one that looks up zip codes, one that tells "yo mama" jokes, and numerous others that can be games an much more.
Alexa, and the numerous Amazon products will be the future of the IOT (Internet Of Things). Today I programmed my first skill in Alexa.

Most people when they interact with Siri or Cortana, the simply chalk it up to magic. They understand it's complicated and most users would consider the code behind both so complex that they could never tackle a project in either. Amazon changed that.

My first step was to create an Amazon Developer account and sign up with Amazon Web Services. Let me say, I had no idea Amazon went so deep, it was impressive to interact with a whole other side of Amazon.

My second step was to get to coding. The Amazon Developer site has a phenomenal guide to building your first skill in less than an hour (link below). The guide gave me examples and templates I could use build my skill. All of it was hosted on GitHub and I simply cloned and made it my own.

"Alex, this code is in Node.js and I only know Ruby"

Fear not, this template is so simple all you have to edit is the strings in the code. Essentially keeping the backbone of the code, putting in your own guts, sewing it back up and releasing your new hybrid animal/skill to the world.

As I said before, Batman needed humor so I gave him some. In my case the skill I created was a simple trivia game. It started off as trivia about Reindeer, and I made it a game about Batman. Here is a sample question from my trivia....

"When batman was a child, his parents did what specific thing?": [
            "Died",
            "Lied",
            "Bought batman a kickass motorcycle",
            "Entered him into beauty pagents"
            ]

Yes, thats a sensitive topic, but also true. His parents died and without that event we wouldn't have batman. Silver lining?

Anyway, you're probably wondering how this all comes to be. After you set up theses accounts you will use both and they're equally important. AWS (Amazon Web Services), will give you the tools to host the site, it will set you up with a unique ARN (essentially an SSH key) that you can enter into your code on the Development side of things. They make it so easy, you can edit in their handy dandy text editor and they test your code for you. No writing test code! How nice.

The testing is very unique, When it comes to testing the code, the Development portal has you covered with built in tests for your language you choose to code in (currently Node.js, JS, and python). The other side of testing is in the AWS portal. Amazon has created a place where you can type in what the user would say (the intent) and it will spit out what the response from Alexa would be. Not only will it show you the output of the code, it will speak it back to you if you choose. You do not need the amazon products to test the user experience.

I had a lot of fun creating this skill, and yes there is a lot more that goes into this but it is super easy. Also lets not forget you get to build something cool! I did notice a little bug in the tutorial, if you don't change the name of the skill in the getWelcomeResponse method, it will continue to call your new skill Reindeer Games. The tutorial doesn't tell you to do this. Change the string to the name of your skill, and you are good to go!

Thanks for reading as always and go build a skill!

***Amazon Tutorial***
https://developer.amazon.com/appsandservices/community/post/TxDJWS16KUPVKO/New-Alexa-Skills-Kit-Template-Build-a-Trivia-Skill-in-under-an-Hour

Ps: Go see Deadpool. If you're easily offended go see something else or sack up and see Deadpool anyway.
