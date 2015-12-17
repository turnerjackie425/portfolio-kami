---
layout: post
title: Scrap Happy
thumbnail-path: "assets/scraphappy_index_page_img.png"
short-description: Digital scrapbooking application and capstone project.
---

{:.center}
![]({{https://scraphappy.herokuapp.com/}}/assets/scraphappy_index_page_img.png)

##Explanation
I spent most of my bloc.io course wondering what I would do for a capstone project. The thought of it was almost overwhelming. Then I realized that I should do something that shows what am I most passionate about. And that, of course, is my family. A digital scrapbook with a Pinterest type layout is the result of that thought.


##Problem
My mentor with Bloc was scarcely available for guidance, so I flew solo on this project and it took me a lot longer than I had anticipated. I went back and forth on what sort of pages this application should have. Should a user be able to have multiple scrapbooks with multiple pages? What about adding a collaboration feature where other users can add to a scrapbook, with permission from the scrapbooks owner, of course. These ideas were great but I needed a good backbone first. I quickly learned that I was making it too complicated. 

##Solution
I needed to simplify this application. It is now a simple one page scrapbook. A user can sign-up with an email verification through send grid and upload photos using the paperclip gem. I added a like feature as well in preparation for the user collaboration that will follow eventually.


##Results
Production went much smoother and faster after simplifying the problem. Until I went to add the masonry gem. It wasn’t working. The layout was horrible! Being a ‘Ruby Newbie’ meant I would have to find a way to make this work via the internet. I followed the instructions on the masonry gem documentation, but was still having problems. The layout wasn't working anything like I had expected. So, I scoured the internet for a solution. Stack overflow didn’t have the answer (which was really surprising to me. I have found many answers on that site). YouTube was my saving grace. I watched a tutorial and VIOLA! It was finally working.

Masonry working correctly

{:.center}
![]({{ https://scraphappy.herokuapp.com/ }}/assets/scraphappy_index_page_img.png)


##Conclusion

Out of all the projects I have done so far, I learned the most from this one. I even went back and made some adjustments on my older projects with my new found  knowledge! 

The app is still in ‘simple form’ (Ruby pun intended!). This is version one of this application. I will keep working on it for practice! It’s a great way to learn.

<p><a href="https://scraphappy.herokuapp.com/">Scrap Happy on Heroku</a></p>

<p><a href="https://github.com/turnerjackie425/Scrap-Happy" title="Scrap Happy code">Scrap Happy GitHub repo</a></p>