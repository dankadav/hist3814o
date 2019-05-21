# Blog for Module 1

This week's exercises went smoothly, for the most part. However, there were some fails, outlined below. Overall, though, there was MUCH less confusion than last week, and I feel like I'm getting the hang of it. Also, I found the readings really interesting and enjoyed learning more about why open access research matters and how it fits into my life.

## Activities

### Exercise 1

This exercise went well. Steps 1-3 posed no challenges, but step 4 resulted in minimal confusion. Once I had identified which images I wanted to include, I had trouble finding the addresses for the actual pictures to put those links in Dillinger. Took some trial and error to realize that if I simply right clicked, "Copy Image Address" would give me what I needed. However, linking the 4 articles was not a challenge, nor were the last few steps. 

### Exercise 2

I had been working on setting up DHBox since May 10th, and, finally, on the 17th it worked! I had messaged Dr. Graham a few times during that period for advice on what I could try to make it work, but nothing seemed to make a difference. Each separate time I tried to make an account (I think there were 5 attempts before success), I used different usernames and passwords, but my email was always my Carleton email address. So, it occurred to me that maybe my email address was the problem? I then tried again, but listed a personal email, and it worked. I don't know enough about DHBox to say whether this was actually the reason it finally worked, or whether something behind-the-scenes clicked into place right when I decided to try a different email, but I'm just happy I don't have to worry about this anymore.

Once I had DHBox, I began the exercise Using the Command Line. At step 2, something went wrong and I did not get a copy of Pandoc after typing in the wget code. Thankfully, this issue was resolved quickly because my first instinct was to reread what I had typed, and I found that I had accidentally written "amd.64.deb" at the end, instead of "amd64.deb". I tried again and all was good! Everything else went as it was supposed to.

### Exercise 3

Nothing much to say for this exercise because I encountered no problems at all! I do want to mention, though, that I did the GitHub hello-world tutorial in the Getting Started week because it popped up when I first made my account. But in case you will be looking for it, I made it private at the time because I didn't think it mattered for the class, I just wanted a bit of practice. I don't know how to switch it to public (or if that's even possible) so if you would like proof, I can take a screenshot of my page or something.

### Exercise 4

There is much to say about this one, so I will break it down by sub-exercise. I am very surprised at how smoothly this exercise actually went for me, because I am not tech savvy. When the course first started, I assumed I'd probably start out only being able to get through half of the exercises in each module, so I thought 4 would stump me no doubt. It is very encouraging that it didn't. Also, for some reason, DHBox kept freezing on me. I checked that I was still connected to the VPN and I always was, so I had to refresh the page every time. Because of this, I didn't have any lists of my recent commands, BUT I am lucky because I kept a few notes on the side when things went wrong, detailing how I fixed them.

#### 4.1

Creating the repository went well. The only thing I had trouble with was answering the question "what do you (not) see?" in step 8. I turned to Slack for some help and Maggie Sherwin informed me that you could no longer see the /.git/ folder. Also, when I first got into Nano, I tried to type ctrl+X to exit, but instead typed command+X because I have a Mac and assumed it would be command not control for Macs. Instead, this disabled help mode, but I just typed the same command and re-enabled help mode, so this was not an issue. It will take some time for me to get used to using control instead of command, and also to get used to having to use the arrow keys to move around instead of my cursor.

#### 4.2

Clicking through the annotations provided some useful information about how to complete 4.2. A comment by jordenlee on step 2 informed me that the commands are case-sensitive, and a comment by arborlux on step 10 reminded me to stage my files before committing. Having this information available made 4.2 go completely smoothly.

#### 4.3

In this sub-exercise, lots went wrong. One of the times DHBox froze was right when I started 4.3, and it confused me because I had thought it would remember what I had been doing, so I was not aware I wasn't in the repository I made in 4.1 anymore. So, when I made a new file and tried to stage it, I got an error message about there being no git repository. I forgot about the command "cd first-repo" so I tried "git init" instead, and created /home/ddavidovic/.git/. I knew this didn't look right but I decided to push on and try to get myself onto the right track. 

I checked the status and every file I had made since first creating DHBox (minus the ones in first-repo) was listed as untracked, but I thought "git add -A" would single out the last file I made so I typed in that command. I checked the status again and all of the files were in green, so it was clear that I was not getting any closer to working this out. I decided to make another text file in Nano, stage and commit it, and then type git log to see if maybe that revealed what might have gone wrong. Git log showed only those 2 commits, so I decided to stop pushing on and go back and reread all of exercise 4. Doing this reminded me of "cd first-repo" and everything went perfectly from there.

#### 4.4

When I executed the merger and typed in my message, I did not have the option of saving before it exited. I typed ctrl+X (I did not accidentally type command this time) and it just exited immediately. To try to check if it worked, I typed git log and saw a merger recorded as the most recent event, so I believe everything worked well.

#### 4.5

There is nothing to say about 4.5. It went perfectly.

#### 4.6

In 4.6, I encountered more problems, which I still do not understand. Steps 1-4 went well, but upon doing step 5, I got a "permission denied" error message. I tried starting from the top and typing "cd .." and "pwd" and I learned I was in /home/. I tried a few more times to continue as instructed and kept getting the same error message. I then watched the instructional video and noticed that the instructor was in /home/demonstration, so I realized I probably need to be in /home/ddavidovic and not just /home/. I refreshed DHBox because I didn't know how else to get out of /home/ and typed "cd .." and got /home/ddavidovic this time. I don't understand the difference between the two is or why it stopped showing /home/ after I refreshed DHBox, but everything worked smoothly after that.

#### 4.7

Sub-exercise 4.7 went perfectly.

#### 4.8

At the time of submission, I do not have any pull requests, so I can't complete this step. Also, I can't create a document of recent commands because DHBox stopped working so many times.

## Annotations

### Annotation 1

This [annotation](https://hyp.is/dPDGVnpjEem9cGMVrl8krA/programminghistorian.org/en/lessons/getting-started-with-markdown) is a record of my first experience with Markdown. It connects to this [annotation](https://hyp.is/sRSFknpiEemlfmPOPQKliA/programminghistorian.org/en/lessons/getting-started-with-markdown) which came before it. I was following all of the steps in "Getting Started with Markdown" but my writing was not rendering correctly in HTML, and, at first, I didn't understand why. Eventually, I realized there was an extra set of three back-ticks in there, which I had not written in myself, and I thought maybe something would change if I deleted them. Doing this caused everything to render correctly, and I learned more about what effect back-ticks have and what purpose they serve.

### Annotation 2

[This](https://hyp.is/NXSFMHnSEemH08N2f6fhUQ/www.lotfortynine.org/2017/06/my-digital-publishing-update-nothing/) is another annotation which stood out to me this week because Sheila Brennan revealed a completely new reason for why historians are so reluctant to enter into the digital world. Based on her own experiences with publishing digital-first material, she explains that publishers aren't advanced enough to accomodate a shift to the digital. Her project has been stuck in limbo for years because of this.

Furthermore, Maggie Sherwin [replied](https://hyp.is/NXSFMHnSEemH08N2f6fhUQ/www.lotfortynine.org/2017/06/my-digital-publishing-update-nothing/) to my annotation and pointed out that on top of a lack of advancement, publishers also don't want digital publishing to become a mainstream practice because it doesn't make them as much money. I had never considered this. I had just assumed that, since audiobooks and the like are becoming more common, publishers aren't pushing back, they're just slow to mobilize. This whole interaction has been very eye-opening as to the realities of the digital humanities. It's not just reluctant scholars, it's a much bigger struggle. 

### Annotation 3

Aside from learning more and more about how scholars are viewing the digital humanities, I am also still learning more about how the digital humanities can be useful to me, as a student. In this [annotation](https://hyp.is/dJ_mIHdzEemC6WuXxDLv0w/www.trevorowens.org/2008/03/sunrise-on-methodology-and-radical-transparency-of-sources-in-historical-writing/) I reflected on Trevor Owens' discussion of the Jeremi Suri article in which there were sources directly linked, and how useful this would be when I'm writing a paper. I often find sources by looking at relevant articles' bibliographies and searching around for what they cite, and having links to openly-available material would make my life so much easier. For me, being able to see how something's useful to me helps me focus better on what I'm learning, so I find it really valuable to identify connections.

Like in annotation 2, a [reply](https://hyp.is/dJ_mIHdzEemC6WuXxDLv0w/www.trevorowens.org/2008/03/sunrise-on-methodology-and-radical-transparency-of-sources-in-historical-writing/) to my annotation, this time by staceysentdoux, taught me even more. Across disciplines, students find it hard to find the sources they want/enough sources for a given topic due to inaccessibility. Despite this, I haven't had many problems finding other credible sources that aren't ideal but I could still use. It had not occurred to me that this differs in a program like COMS, as staceysentdoux points out, since writing on current events greatly minimizes the amount of material available to a student. I was really interested to learn this.

## Reflection Questions

### What are the dangers and what are the opportunities of open access research? What does open access mean for you as a student?

I think that the opportunities completely outweigh the dangers of open access research. One common worry surrounds someone scooping your idea before you can publish it, but this has been well-disputed in our readings because of the fact that open access research can provide proof than an idea was yours first. It provides a time-stamp so there is no uncertainty around who deserves credit. Furthermore, another worry is that, with everything out in the open, it will be difficult to find publishers who want to take your writing on. But, it has been pointed out that open access research has not, so far, hindered any scholars from being published. Another worry, as discussed by Sheila Brennan, is that publishers may not have guidelines for publishing works created through open access research, which could significantly delay the publishing process. While this is not as easily disputed, it is a matter of forcing publishers to adapt through the wide adoption of open access research. Once they see there is a need, they will have no choice but to work out publishing guidelines, eliminating this danger.

The opportunities of open access research are huge. Being able to collaborate with people around the world, with different specialties and perspectives, is invaluable to the advancement of ideas. Furthermore, it makes scholarship more accessible. The readings this week discussed how the humanities can sometimes seem prestigious. Conducting research is an expensive and time-consuming process, and is not a possibility for everyone, especially if they don't have funding. Having access to the research someone else already did, which is relevant to your own project, can save so much time and money. This is true for students as well, as I mentioned in Annotation 3. It's difficult for a student to get access to all of the material they want for a paper, and most students certainly can't afford to travel to an archive or pay for a subscription, so they must make do with what their institution offers. For this reason, open access research would make a big difference to students, as well.

All of the values of open access research have been stressed by most of the professors I've had so far in my studies. They require discussion so that we can interact with others' perspectives and begin thinking more broadly about historical concepts and events. I've learned a lot about how narrow my thinking can be sometimes and why working with others is so valuable, and I know that open access research matters because of this. I've also encountered professors who know that accessibility can be a big challenge, since many students can't even afford the textbook, let alone a trip to the archives, so they post as much of the textbook as they are legally allowed to. These are the two biggest values of open access research I've encountered in my studies, so they stand out the most to me.

## Comments/Concerns

I have replied to two people on Hypothesis but these replies aren't showing up on my Hypothesis page. I want it to be visible that I am interacting with the community, both on Slack and Hypothesis, so I will link my replies here. The [first](https://hyp.is/R6bwkndtEem2fsP48MI3cw/wcm1.web.rice.edu/open-notebook-history.html) is a conversation about plagiarism. In the [second](https://hyp.is/AS7n4nnTEemU2gfqui8b5g/workbook.craftingdigitalhistory.ca/module-1/Exercises/) I am helping a classmate. 

With regards to DHBox's tendency to freeze, Dr. Graham suggested in Slack that I try using it in Firefox instead of Chrome and see if anything changes. I will do this for the exercises in the next module, as I had already finished everything I had to do for this module by the time I remembered to ask about this issue.
