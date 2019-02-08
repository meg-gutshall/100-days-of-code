# 100 Days Of Code - Log

### Day 1: January 1, 2019

**Today's Progress**: I decided to try out a new code challenge site called HackerRank because I sort of committed to this #100DaysOfCode challenge at the last minute. You can read more about that in my blog post (COMING SOON!).

**Thoughts:** It was very basic Ruby code so I had to clean off the cobwebs in my brain kind of similar to what you did every school year after summer vacation ended. The only hang-up I had was that I had forgotten to increment the index number at the end of each iteration of the while loop but I caught on to that pretty quickly and it was smooth sailing from there! [Tweet](https://twitter.com/meg_gutshall/status/1080318946585333760)

**Link to work:** [HackerRank: Compare the Triplets](https://www.hackerrank.com/challenges/compare-the-triplets/submissions/code/94531465)

### Day 2: January 2, 2019

**Today's Progress**: Worked through some of Flatiron's Sinatra section curriculum: Intro to Capybara Tests, Dynamic Routes, and Dynamic Routes Lab.

**Thoughts**: I really like how the dynamic routes work! It's so intuitive and user-friendly-it just makes sense to me. I'm sooo looking forward to the Sinatra project coming up and working with this concept. [Tweet](https://twitter.com/meg_gutshall/status/1080654606613573633)

**Link to work**: [Sinatra Dynamic Routes Lab](https://github.com/meg-gutshall/sinatra-dynamic-routes-lab-v-000)

### Day 3: January 3, 2019

**Today's Progress**: Worked through some of Flatiron's Sinatra section curriculum: HTML Forms and Params. [Tweet](https://twitter.com/meg_gutshall/status/1081029912516067334)

**Thoughts**: Not gonna lie, I was doing this at a bar so I will probably have to review this again soon... ¯\_(ツ)_/¯

**Link to work**: [Sinatra HTML Form and Params](https://github.com/meg-gutshall/sinatra-forms-params-readme-walkthrough-v-000)

### Day 4: January 4, 2019

**Today's Progress**: Worked through some of Flatiron's section curriculum: Passing Data Between Views and Controllers and Basic Sinatra Forms Lab.

**Thoughts**: First off, LOVED the examples they used for this lab. Some of the greats... not basketball, but there's a team called the Utah Jazz, right? I found it fascinating how you can retrieve user input, manipulate it, and return it in another path on your site. I was confused though with the get and post methods and which paths they were supposed to use. (Again, why I need to review the HTML Forms and Params lesson.) If it still doesn't make sense after I review, I plan on using Flatiron's 'Ask A Question' feature to try to understand. [Tweet](https://twitter.com/meg_gutshall/status/1081388660174540801)

**Link to work**: [Basic Sinatra Forms Lab](https://github.com/meg-gutshall/basic-sinatra-forms-lab-v-000)

### Day 5: January 5, 2019

**Today's Progress**: Started working on a small program.

**Thoughts**: I wanted to work on some more of the curriculum today but didn't get to it until late and I am EXHAUSTED. I decided to stub out a little program that's been forming in the back of my mind instead. It's very simple and fun, I just have to find a way to execute it. I think this will turn into a 2-3 day project.

**Link to work**: It's a secret... for now.

### Day 6: January 6, 2019

**Today's Progress**: I went back and reviewed the HTML Forms and Params lesson. I also took another look at the Basic Sinatra Forms Lab.

**Thoughts**: Okay, I'm all good with the HTML Forms and Params. They basically provide hashes-the keys being the form's name attribute and the values created by user input. Again, this is super awesome and dynamic and I can't wait to implement it in a project!

A few days ago I was pretty confused by the post methods, the paths, and what should go in the app vs. the form but now I'm pretty sure I have it figured out:

In the app.rb file (the controller) it's saying that when the server receives a GET request with the '/newteam' path, it displays the code in the newteam.erb file (a view). This file contains the form which asks for the user's input to create a basketball team. Once submitted, this form sends data as a POST request to the '/team' path. The server receives this request, goes back to our controller, captures the data stored within the matching controller action block, and displays the team.erb view. Since we're using instance variables in the controller to store data collected from the form, we're able to broaden the scope of these variables to include the team.erb file. As a result, the browser automatically redirects to the '/team' page and displays the basketball roster. [Tweet](https://twitter.com/meg_gutshall/status/1082098520126050309)

**Link to work**: [Basic Sinatra Forms Lab](https://github.com/meg-gutshall/basic-sinatra-forms-lab-v-000)

### Day 7: January 7, 2019

**Today's Progress**: It's Monday so I had a Code Talk session this morning! We worked on a [codewars.com](codewars.com) code challenge called "Good vs. Evil".

**Thoughts**: I was in a group with Guy and Suchitra. We started out with psuedocode and once that was established we started writing the program. It was pretty straight forward, although we hit a small snag that Guy was able to solve right away. The part I liked best was when the groups met back together and shared their answers with one another. It's neat to see the similarities and differences in how we approach these problems. [Tweet](https://twitter.com/meg_gutshall/status/1082452964479037441)

**Links to work**: [Good vs. Evil Code Challenge](https://www.codewars.com/kata/52761ee4cffbc69732000738), [Good vs. Evil Solution](https://repl.it/@meg_gutshall/GoodVsEvil), and [Good vs. Evil Refactored Solution](https://repl.it/@meg_gutshall/GoodVsEvilRefactored)

### Day 8: January 8, 2019

**Today's Progress**: Attended a Flatiron study session on Capybara testing.

**Thoughts**: Capybara is definitely more readable than RSpec as far a testing frameworks go. I think I'm pretty comfortable with reading the tests but I'm not sure how well I'd do with writing the tests. I will definitely give that a shot as I go through this challenge. [Tweet](https://twitter.com/meg_gutshall/status/1082838809904074753)

### Day 9: January 9, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra MVC Lab, Sinatra Basic Forms Lab, Sinatra Nested Forms, and Sinatra Nested Forms Lab: Pirates!

**Thoughts**: I am definitely mentally exhausted right now. I feel like I understand the concepts behind MVC and nested forms, it's just writing out the code and the tediousness of making sure everything is going exactly the way it's supposed to is really frying my brain right now. I think I'll have to break out the whiteboard again for this last MVC lab in the section and see how that compares to writing psuedocode on the computer. [Tweet](https://twitter.com/meg_gutshall/status/1083139056161181697)

**Links to work**: [Pig Latinizer](https://github.com/meg-gutshall/sinatra-mvc-lab-v-000), [Puppy Adoption Site](https://github.com/meg-gutshall/sinatra-basic-forms-lab-v-000), and [Pirates!](https://github.com/meg-gutshall/sinatra-nested-forms-v-000)

### Day 10: January 10, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Nested Forms Lab: Superheros!, Sessions and Cookies, and Mechanics of Sessions

**Thoughts**: Compared to the Pirates! lab from yesterday, Superheros! was pretty easy... which I did NOT mind! I also started on the Sessions section, learning about sessions and cookies. It's pretty interesting stuff and I now know what "clearing my cookies" actually means. I plan on completing the section labs tomorrow and moving forward to ActiveRecord. [Tweet](https://twitter.com/meg_gutshall/status/1083537011825393664)

**Link to work**: [Superheros!](https://github.com/meg-gutshall/sinatra-nested-forms-lab-superheros-v-000)

### Day 11: January 11, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Sessions Lab

**Thoughts**: Okay, things didn't go exactly according to plan today... This is a HARD lab! I'm still trying to wrap my head around how sessions fit in with params and instance variables in these controller action blocks. I like that we're learning about session secrets though and I read more in the [Sinatra documentation](http://sinatrarb.com/intro) on how to generate a secret. I decided to give my brain a break for tonight and get back to it tomorrow. [Tweet](https://twitter.com/meg_gutshall/status/1083884128204926986)

### Day 12: January 12, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Sessions Lab and Sinatra Sessions Code Along

**Thoughts**: I opened up my Sinatra Sessions Lab in VS Code and deleted ONE line... now all my tests are passing. Haha! I was on to something last night, I was just lacking the mental energy to go all the way. Officially onto Sinatra's ActiveRecord section now!! [Tweet](https://twitter.com/meg_gutshall/status/1084196728914497539)

**Link to work**: [Sinatra Sessions Lab](link)

### Day 13: January 13, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: ActiveRecord Setup in Sinatra

**Thoughts**: I went through the first ActiveRecord lesson in Sinatra and I am done for the night. Too long of a day with other work and too late of a start on my school work. I'm going to totally kill it tomorrow... starting with CODE TALK!! [Tweet](https://twitter.com/meg_gutshall/status/1084637626848759812)

### Day 14: January 14, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: ActiveRecord in Sinatra and Sinatra ActiveRecord CRUD Lab

**Thoughts**: I think relating ActiveRecord's CRUD and Sinatra's MVC Controller will definitely take some practice, but I got a good start! So thankful to my fellow Flatiron students for helping me through the second half of this lab. They probably halved the time it would have taken me to complete it. [Twitter](https://twitter.com/meg_gutshall/status/1085020726372065280)

**Links to work**: [Sinatra ActiveRecord CRUD](https://github.com/meg-gutshall/sinatra-ar-crud-lab-v-000)

### Day 15: January 15, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: User Authentication in Sinatra

**Thoughts**: I've been waiting for this day!!! So happy that we're learning how to create and authenticate users! This opens up so many doors for future programs now! Also it was a pretty straightforward lab. Which is why I was so surprised that the solution in Flatiron's GitHub repo was wrong. Not the first time I've come across this and probably won't be the last but it's still really disappointing when it happens. I submitted a pull request for an alternate solution as well as raised an issue but, that's hasn't done shit in the past so I don't expect much now either... we'll have to wait and see I guess. [Twitter](https://twitter.com/meg_gutshall/status/1085345021094707200)

**Link to work**: [User Authentication in Sinatra](https://github.com/meg-gutshall/sinatra-user-auth-v-000)

### Day 16: January 16, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Sessions - User Logins Lab, Securing Passwords in Sinatra, and Secure Password Lab

**Thoughts**: This one was a bit tricky because we incorporated helper methods into this lab as well as dealt with redirects. That tripped me up a bit. I learned that in an action controller block, once you hit a redirect, the block stop executing the code. That is not the case once you call erb on a view page, it will keep going so if you're making a view conditional, you have to do it with an if/else statement.
I also learned about securing passwords, which can never be a bad thing. I like that there's a gem for this one as well and that it works right alongside an ActiveRecord macro. Makes things nice and easy! One thing that stuck out to me after reviewing Flatiron's solution to the Secure Password Lab is that you should test for valid username and password input upon registration first and depending on it's validity, redirect the user to an error page/show them an error message or create a new instance of the User class. That way you won't have bad data in your database!
[Tweet](https://twitter.com/meg_gutshall/status/1085717494118141952)

**Links to work**: [Sinatra Sessions – User Logins](https://github.com/meg-gutshall/sinatra-logging-in-and-out-v-000), [Securing Passwords in Sinatra](https://github.com/meg-gutshall/sinatra-password-security-v-000), and [Secure Password Lab](https://github.com/meg-gutshall/sinatra-secure-password-lab-v-000)

### Day 17: January 17, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra RESTful Routes and Sinatra RESTful Routes Lab

**Thoughts**: I'm not really sure what the difference was supposed to be between these and what we've been doing already. It seemed to me just like the params and sessions stuff with some dynamic routes thrown in. The big picture will probably become clearer as I go along. [Tweet](https://twitter.com/meg_gutshall/status/1086106867192000512)

**Link to work**: [Sinatra RESTful Routes Lab](https://github.com/meg-gutshall/sinatra-restful-routes-lab-v-000)

### Day 18: January 18, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Using Tux in Sinatra with ActiveRecord, ActiveRecord Associations in Sinatra, ActiveRecord Associations: Join Tables, Sinatra Multiple Controllers, and I revisited the Sinatra ActiveRecord CRUD Lab

**Thoughts**: I'm really cruising through this section but I'm about to start on the last three labs so we'll see how that goes... I found a new study buddy today!! We went over the CRUD lab and learned that the ActiveRecord::Base#update method has been depreciated. It was a lot of reading lessons and code-alongs today. [Tweet](https://twitter.com/meg_gutshall/status/1086425773664337921)

**Links to work**: [Using Tux in Sinatra with ActiveRecord](https://github.com/meg-gutshall/sinatra-activerecord-using-tux-v-000), [ActiveRecord Associations in Sinatra](https://github.com/meg-gutshall/sinatra-activerecord-associations-v-000), and [Sinatra ActiveRecord CRUD Lab](https://github.com/meg-gutshall/sinatra-ar-crud-lab-v-000)

### Day 19: January 19, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Complex Forms Associations... and played Git Game in a study group led by Guy!

**Thoughts**: Started my day with a Git study session led by fellow student [Guy Bryant](https://github.com/guysbryant). We worked on this repo called git-game which was pretty cool! It was like a ten level puzzle that taught you all different Git commands. There's a second level as well but I think we'll need some reinforcements to tackle that one. Also chatted with him afterward on various topics but he showed me some nice terminal shells that I hadn't gotten a chance to look into up to that point. I'll have to dedicate a bit of time soon to pick something that fits my programming style.

On another note, I started my Sinatra Complex Forms Associations lab at the bar and about 75 minutes into well... see for yourself. Haha! [Tweet](https://twitter.com/meg_gutshall/status/1086791494248419328)

**Link to work**: [Git Game](https://github.com/meg-gutshall/git-game)

### Day 20: January 20, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Complex Forms Associations

**Thoughts**: Didn't have as much time to code today as I would have liked but that's okay, I still got it in! I got finished about half (I think?) of the Sinatra Complex Forms Associations lab so I'll wrap that up tomorrow and see what the next one brings. [Tweet](https://twitter.com/meg_gutshall/status/1087212265667989509)

**Link to work**: [Sinatra Complex Forms Associations](https://github.com/meg-gutshall/sinatra-complex-forms-associations-v-000)

### Day 21: January 21, 2019

**Today's Progress**: Worked on this damn CodeWars code challenge today that I still haven't solved!

**Thoughts**: It was a complicated problem and I think I got a solution that would work except it involves an array that grows exponentially so every time I try to run my code it times out. So my solution may be correct, but it's not feasible as far as memory goes which is as good as incorrect. I'll get back to it another day. [Tweet](https://twitter.com/meg_gutshall/status/1087526258022469632)

**Link to work**: [Double Cola](https://github.com/meg-gutshall/sandbox/blob/master/lib/double_cola.rb)

### Day 22: January 22, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Complex Forms Associations

**Thoughts**: I'm still working through the second half of this Sinatra Complex Forms Associations lab. I'm going to have to go on Ask A Question tomorrow and get some help because I'm totally stuck on this new pets form and associating the owner back to them/creating a new owner. [Tweet](https://twitter.com/meg_gutshall/status/1087917812218241024)

**Link to work**: [Sinatra Complex Forms Associations](https://github.com/meg-gutshall/sinatra-complex-forms-associations-v-000)

### Day 23: January 23, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Complex Forms Associations

**Thoughts**: I FINALLY finished the Sinatra Complex Forms Associations lab!! Damn, that was hard! We had to use nested forms for the pets portion of the lab. Would have been nice to know that!!! TBH, if I was better at this I would have figured it out. A lesson I won't forget soon though (hopefully)! [Twitter](https://twitter.com/meg_gutshall/status/1088271074708590592)

**Link to work**: [Sinatra Complex Forms Associations](https://github.com/meg-gutshall/sinatra-complex-forms-associations-v-000)

### Day 24: January 24, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Playlister

**Thoughts**: This lab looks like it will be intense but I feel more confident going into this after completing my last lab. I actually pulled it up and compared it with the playlister and can see some similarities so I think it will be really helpful as I go along. I'm also starting to form some ideas for my project! :) [Tweet](https://twitter.com/meg_gutshall/status/1088655227446849536)

**Link to work**: [Sinatra Playlister](https://github.com/meg-gutshall/playlister-sinatra-v-000)

### Day 25: January 25, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Playlister and then I had some major computer issues that got me side tracked for a while.

**Thoughts**: Another student and I were pairing up on the Sinatra Playlister lab and were seeding the database. When I seed dbs I would get a weird error message and we figured out there was a conflicting gem I had installed in an rvm gemset. It took me probably 40 minutes to find out in rvm where I was supposed to go to find the gem and uninstall it and that is NOT the first time I've ended up wasting a good chunk of time because their documentation is horrible. I decided to switch to rbenv instead. [Tweet](https://twitter.com/meg_gutshall/status/1089043106824114177)

**Link to work**: [Sinatra Playlister](https://github.com/meg-gutshall/playlister-sinatra-v-000)

### Day 26: January 26, 2019

**Today's Progress**: rbenv installation headaches!!

**Thoughts**: I worked for ~12 hours today to get rbenv, my gems, and ruby to play nicely on my computer. Thankfully, I had another student help me out with troubleshooting. Again, it came down to unclear documentation. I plan to write a PR later this week or next weekend to submit explaining that they need more beginner-friendly language. [Tweet](https://twitter.com/meg_gutshall/status/1089370671774425088)

### Day 27: January 27, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Playlister

**Thoughts**: Finally got back to work again today! I got through my migrations, seeding, set up my models, but now I've started with the controllers and for some reason I'm getting 404 errors all around. I'm going to take another look at it tomorrow and see what I can do. [Tweet](https://twitter.com/meg_gutshall/status/1089727212645949440)

**Link to work**: [Sinatra Playlister](https://github.com/meg-gutshall/playlister-sinatra-v-000)

### Day 28: January 28, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Playlister and hosted Code Talk!

**Thoughts**: Did some pseudocode this morning at Code Talk on a pretty difficult problem involving balancing two sides of a scale. Paired up with Heather again for the Sinatra Playlister lab. We put a good 3.5 hours in today but still have 7 more tests to pass. Hopefully can wrap this up tomorrow! [Tweet](https://twitter.com/meg_gutshall/status/1090063576470093826)

**Links to work**: [Sinatra Playlister](https://github.com/meg-gutshall/playlister-sinatra-v-000) and [ScaleBalancing](https://repl.it/@meg_gutshall/ScaleBalancing)

### Day 29: January 29, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra Playlister

**Thoughts**: SO GLAD TO BE DONE THIS LAB!!! [Tweet](https://twitter.com/meg_gutshall/status/1090429558493466624)

**Link to work**: [Sinatra Playlister](https://github.com/meg-gutshall/playlister-sinatra-v-000)

### Day 30: January 30, 2019

**Today's Progress**: Went to a Sinatra office hour session and updated my pinned repositories on GitHub.

**Thoughts**: I found the contact info for a woman who works on the WW app - a company I've been trying to get in touch with for a while - so I went through my GitHub and made sure my pinned repos looked good. Grammy Googles still needs some work but it's passing for now. [Tweet](https://twitter.com/meg_gutshall/status/1090787657041375232)

**Links to work**: [Grammy Googles Repo](https://github.com/meg-gutshall/grammy-googles) and [Grammy Googles Site](https://meghangutshall.com/grammygoogles/)

### Day 31: January 31, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra NYC

**Thoughts**: Started on the Sinatra NYC lab. I think my brain is just too fried right now to concentrate on anything. I got an hour of code in but I don't feel like I did an hour's worth of work. [Tweet](https://twitter.com/meg_gutshall/status/1091140382971305984)

**Link to work**: [Sinatra NYC](https://github.com/meg-gutshall/nyc-sinatra-v-000)

### Day 32: February 1, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra NYC

**Thoughts**: Got stuck alternating between two errors and it's driving me crazy!! I don't want this lab to be like the Playlister!!! I lost too much time on that one as it is!!

**Link to work**: [Sinatra NYC](https://github.com/meg-gutshall/nyc-sinatra-v-000)

### Day 33: February 2, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Sinatra NYC

**Thoughts**: Awesome! Finished the NYC lab today! One of my stupid errors was that for my model for my join table class, the `belongs_to` relationship was written as plural when it should've been singular. Another was that I was trying to submit data through an edit form without sending a `PATCH` request to the server. Derp! I think I'm trying to rush these because I'm so close to the end of this section and really want to get to ActiveRecord. [Tweet](https://twitter.com/meg_gutshall/status/1091892130845519874)

**Link to work**: [Sinatra NYC](https://github.com/meg-gutshall/nyc-sinatra-v-000)

### Day 34: February 3, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Fwitter

**Thoughts**: Oh wow, Fwitter is definitely going to get me ready for the upcoming project! I chose to work solo since no one is online today but hopefully I can pair up with someone tomorrow! [Tweet](https://twitter.com/meg_gutshall/status/1092169078511489024)

**Link to work**: [Fwitter](https://github.com/meg-gutshall/sinatra-fwitter-group-project-v-000)

### Day 35: February 4, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Fwitter

**Thoughts**: Yes! I paired with Heather and she helped me through that dumb error I had yesterday. We got further in the 90 minutes we coded but still, it's a hard lab! Can't wait to finish and move on to my project. [Tweet](https://twitter.com/meg_gutshall/status/1092636293127913473)

**Link to work**: [Fwitter](https://github.com/meg-gutshall/sinatra-fwitter-group-project-v-000)

### Day 36: February 5, 2019

**Today's Progress**: Did some review today with another student working on Tic Tac Toe with AI and also attended another Sinatra live build session hosted by section lead Howard.

**Thoughts**: I refactored one of my methods in the Tic Tac Toe lab and it's so much simpler now! Still haven't hit the AI logic but I have plenty of time to get that done. The Sinatra live build session was great today! I feel like we got a lot of the app built out. It's still pretty slow progress though doing only one hour at a time. [Tweet](https://twitter.com/meg_gutshall/status/1092929099671265287)

**Links to work**: [Sinatra Community Gardener](https://github.com/meg-gutshall/sinatra-community-gardener) and [Tic Tac Toe with AI](https://github.com/meg-gutshall/ttt-with-ai-project-v-000)

### Day 37: February 6, 2019

**Today's Progress**: Mainly dropped in on Sinatra study sessions today and coded along with those.

**Thoughts**: I think the repetition of going to the same sessions over and over again is starting to help things really sink in. I'm identifying common problems and able to give correct answers that I know I couldn't have come up with before. Practice is key!!

### Day 38: February 7, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: Fwitter

**Thoughts**: Debugged some routing issues I was having and am finally moving forward with what feels like tangible progress that I actually understand, not just stumble through. This bodes well for my upcoming project!! [Tweet](https://twitter.com/meg_gutshall/status/1093718735590998017)

**Link to work**: [Fwitter](https://github.com/meg-gutshall/sinatra-fwitter-group-project-v-000)

<!-- ### Day 39: February 8, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 40: February 9, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 41: February 10, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 42: February 11, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 43: February 12, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 44: February 13, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 45: February 14, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 46: February 15, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 47: February 16, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 48: February 17, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 49: February 18, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 50: February 19, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 51: February 20, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 52: February 21, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 53: February 22, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 54: February 23, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 55: February 24, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 56: February 25, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 57: February 26, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 58: February 27, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 59: February 28, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 60: March 1, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 61: March 2, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 62: March 3, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 63: March 4, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 64: March 5, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 65: March 6, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 66: March 7, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 67: March 8, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 68: March 9, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 69: March 10, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 70: March 11, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 71: March 12, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 72: March 13, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 73: March 14, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 74: March 15, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 75: March 16, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 76: March 17, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 77: March 18, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 78: March 19, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 79: March 20, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 80: March 21, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 81: March 22, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 82: March 23, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 83: March 24, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 84: March 25, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 85: March 26, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 86: March 27, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 87: March 28, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 88: March 29, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 89: March 30, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 90: March 31, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 91: April 1, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 92: April 2, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 93: April 3, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 94: April 4, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 95: April 5, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 96: April 6, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 97: April 7, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 98: April 8, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 99: April 9, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 100: April 10, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 101: April 11, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 102: April 12, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 103: April 13, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 104: April 14, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 105: April 15, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 106: April 16, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 107: April 17, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 108: April 18, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 109: April 19, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 110: April 20, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 111: April 21, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 112: April 22, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 113: April 23, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 114: April 24, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 115: April 25, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 116: April 26, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 117: April 27, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 118: April 28, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 119: April 29, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link)

### Day 120: April 30, 2019

**Today's Progress**: Worked through some of Flatiron's curriculum: lesson names

**Thoughts**: Thoughts and observations here...

**Link to work**: [Title](link) -->