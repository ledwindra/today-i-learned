# About
A list of my daily lessons. I don't set high expectations here. My rationale is that building a good habit might not be easy. So let's just find out how this goes. I also haven't thought the best format for this repository so it will be just a simple markdown.

## Before 2020
Skipped.

## 2020: January 1 - July 26
It's been a rough year, hasn't it? Anyway, skipped

## July 27, 2020
Today I learned how to encode a string in Python using [`base64`](https://docs.python.org/3/library/base64.html) built-in module. This question posted on [`stackoverflow`](https://stackoverflow.com/questions/8908287/why-do-i-need-b-to-encode-a-string-with-base64) helps me through it. Following is my main usage:

```python
>>> import base64
>>> encode = 'but you have to decode it'.encode()
>>> base64.b64encode(encode)
b'YnV0IHlvdSBoYXZlIHRvIGRlY29kZSBpdA=='
```

[and then ...](https://twitter.com/ledwindra/status/1287697628268879877)

![i-have-an-encoded-joke](img/i-have-an-encoded-joke.png)

## July 28, 2020

### latest git version now allows us to get rid of `master` branch
Today I learned how to initiate `main` as a default branch on git! This article from [`GitHub`](https://github.blog/2020-07-27-highlights-from-git-2-28/#introducing-init-defaultbranch) helps me from updating git to version 2.28 to [creating a new repository](https://github.com/ledwindra/change-main-branch) with `main` branch, instead of `master`.

In addition, I managed to changed the default branch from existing project such as this repository  to `main`. [This article](https://www.hanselman.com/blog/EasilyRenameYourGitDefaultBranchFromMasterToMain.aspx) and [this StackOverflow post](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely) help me to make this happen. A small step worth doing indeed!

Following is the snippet from the command line:

```bash
ledwindra@R90SEMHV:~/today-i-learned$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
ledwindra@R90SEMHV:~/today-i-learned$ git add README.md 
ledwindra@R90SEMHV:~/today-i-learned$ git commit -m "Today I learned"
[main e1f5f04] Today I learned
 1 file changed, 25 insertions(+), 8 deletions(-)
ledwindra@R90SEMHV:~/today-i-learned$ git push origin main
Username for 'https://github.com': ledwindra
Password for 'https://ledwindra@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.42 KiB | 485.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ledwindra/today-i-learned.git
   d371988..e1f5f04  main -> main
```

### a conservative anarchist with a beautiful job description
Besides, today I learned about [Audrey Tang](https://en.wikipedia.org/wiki/Audrey_Tang), Taiwan's Digital Minister, who's also--according to her Wikipedia page--the first transgender official in the top executive cabinet. This afternoon while I was doing my work, I saw [this tweet](https://twitter.com/hardmaru/status/1288009848102113280), which basically tells Audrey is a well known hacker in the [Haskell](https://www.haskell.org/) and [Perl](https://www.perl.org/) communities.

Later I dig deeper about her, from [this article](https://www.wired.com/story/how-taiwans-unlikely-digital-minister-hacked-the-pandemic/) (also from that tweet). It's totally a worth read on how she and the Taiwanese government handled the COVID-19 pandemic so well. "She's really fantastic", my mind said. Then I surfed to her [talk](https://www.youtube.com/watch?v=LscTx6DHh9I) and [interview](https://www.youtube.com/watch?v=IZ2N3tF4W_k).

What's really fascinating about her is not only that she's technically savvy, but she also shows us that being a prodigy doesn't necessarily mean she loses her human touch. Basically she's not a typical brilliant asshole which is ubiquitous in the tech scene and also how popular culture depicts it (like Elon Musk or Mark Zuckerberg). As a closing remark for today's session, below I quote her job description, which is totally beautiful:

![audrey-tang-job-desc](img/audrey-tang-job-desc.png)

From today, I declare that I'm her fan. 🥰

## July 29, 2020
I don't think I learned something new today. Mostly I was just continue watching and reading stuffs about Audrey Tang (both related to his work as a minister and his effort in [Raku](https://raku.org/) development). Besides, I started reading [Break 'em Up](https://www.goodreads.com/book/show/51176626-break-em-up), which I find quite interesting. Nothing particular from the it that caught my attention so far, but will update a snippet here if it does.
