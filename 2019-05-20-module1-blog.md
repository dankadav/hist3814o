# Blog for Module 1

This week's exercises went smoothly, for the most part. However, there were some fails, outlined below. MORE

## Activities

### Exercise 1

This exercise went well. Steps 1-3 posed no challenges, but step 4 resulted in minimal confusion. Once I had identified which images I wanted to include, I had trouble finding the addresses for the actual pictures to put those links in Dillinger. Took some trial and error to realize that if I simply right clicked, "Copy Image Address" would give me what I needed. However, linking the 4 articles was not a challenge, nor were the last few steps. 

### Exercise 2

I had been working on setting up DHBox since May 10th, and, finally, on the 17th it worked! I had messaged Dr. Graham regularly during that period for advice on what I could try to make it work, but nothing seemed to make a difference. Each separate time I tried to make an account (I think there were 5 attempts before success), I used different usernames and passwords, but my email was always my Carleton email address. So, it occurred to me that maybe my email address was the problem? I then tried again, but listed a personal email, and it worked. I don't know enough about DHBox to say whether this was actually the reason it finally worked, or whether something behind-the-scenes clicked into place right when I decided to try a different email, but I'm just happy I don't have to worry about this anymore.

Once I had DHBox, I began the exercise Using the Command Line. At step 2, something went wrong and I did not get a copy of Pandoc after typing in the wget code. Thankfully, this issue was resolved quickly because my first instinct was to reread what I had typed, and I found that I had accidentally written "amd.64.deb" at the end, instead of "amd64.deb". I tried again and all was good! Everything else went as it was supposed to.

### Exercise 3

Nothing much to say for this exercise because I encountered no problems at all! I do want to mention, though, that I did the GitHub hello-world tutorial in the Getting Started week because it popped up when I first made my account. But in case you will be looking for it, I made it private at the time because I didn't think it mattered for the class, I just wanted a bit of practice. I don't know how to switch it to public (or if that's even possible) so if you would like proof, I can take a screenshot of my page or something.

### Exercise 4

There is much to say about this one, so I will break it down by sub-exercise. I am very surprised at how smoothly this exercise actually went for me, because I am not tech savvy. When the course first started, I assumed I'd probably start out only being able to get through half of the exercises in each module, so I thought 4 would stump me no doubt. It is very encouraging that it didn't. Also, for some reason, DHBox kept freezing on me. I checked that I was still connected to the VPN and I always was, so I had to refresh the page every time. Because of this, I didn't have any lists of my recent commands, BUT I am lucky because I kept a few notes on the side when things went wrong, about how I fixed them.

#### 4.1

Creating the repository went well. The only thing I had trouble with was answering the question "what do you (not) see?" in step 8. I turned to Slack for some help and Maggie Sherwin informed me that you could no longer see the /.git/ folder. Also, when I first got into Nano, I tried to type ctrl+X to exit, but instead typed command+X because I have a Mac and assumed it would be command not control for Macs. Instead, this disabled help mode, but I just typed the same command and re-enabled help mode, so this was not an issue. It will take some time for me to get used to using control instead of command, and also to get used to having to use the arrow keys to move around instead of my cursor.

#### 4.2

Clicking through the annotations provided some useful information about how to complete 4.2. A comment by jordenlee on step 2 informed me that the commands are case-sensitive, and a comment by arborlux on step 10 reminded me to stage my files before commiting. Having this information available made 4.2 go completely smoothly.

#### 4.3

In this sub-exercise, lots went wrong. One of the times DHBox froze was right when I started 4.3, and it confused me because I had thought it would remember what I had been doing so I was not aware I wasn't in the repository I made in 4.1 anymore. So, when I made a new file and tried to stage it, I got an error message about there being no git repository. I forgot about the command "cd first-repo" so I tried "git init" instead, and created /home/ddavidovic/.git/. I knew this didn't look right but I decided to push on and try to get myself onto the right track. 

I checked the status and every file I had made since first creating DHBox (minus the ones in first-repo) was listed as untracked, but I thought "git add -A" would single out the last file I made so I typed in that command. I checked the status again and all of the files were in green, so it was clear that I was not getting any closer to working this out. I decided to make another text file in Nano, stage and commit it, and then type git log to see if maybe that revealed what might have gone wrong. Git log showed only those 2 commits, so I decided to stop pushing on and go back and reread all of exercise 4. Doing this reminded me of "cd first-repo" and everything went perfectly from there.

#### 4.4

When I executed the merger and typed in my message, I did not have the option of saving before it exited. I typed ctrl+X (I did not accidentally type command this time) and it just exited immediately. To try to check if it worked, I typed git log and saw a merger recorded as the most recent event, so I believe everything worked well.

#### 4.5

There is nothing to say about 4.5. It went perfectly.

#### 4.6

In 4.6, I encountered more problems, which I still do not understand. Steps 1-4 went well, but upon doing step 5, I got a "permission denied" error message. I tried starting from the top and typing "cd .." and "pwd" and I learned I was in /home/. I tried a few more times to continue as instructed and kept getting the same error message. I then watched the instructional video and noticed that the instructor was in /home/demonstration, so I realized I probably need to be in /home/ddavidovic and not just /home/. I restarted DHBox because I didn't know how else to get out of /home/ and typed "cd .." and got /home/ddavidovic this time. I don't understand the difference between the two is or why it stopped showing /home/ after I refreshed DHBox, but everything worked smoothly after that.

#### 4.7

Sub-exercise 4.7 went perfectly.

#### 4.8

So far, I do not have any pull requests so I can't complete this step. Also, I can't create a document of recent commands because DHBox stopped working so many times.

## Annotations

### Annotation 1

