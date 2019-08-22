    Title: Creating my blog using Frog, a Racket library
    Date: 2019-08-22T15:58:41
    Tags: Racket, Programming, Frog

Being my first blog post with Frog, I thought it would be a good idea to talk about what Frog is and why I chose it to create this blog.

[Frog](https://github.com/greghendershott/frog) is a static blog generator implemented in Racket. If you haven't heard of Racket, it is a programming language similar to Scheme that is strong at programming language design. Racket is fun to work with, and surprising fast to develop with once you get the hang of it. You don't need to know much Racket (if any) to use Frog, but you can use Racket to help modify the website if desired. 

Blog posts are written purely in markdown, which I love. That gives me a lot of control with how the blog posts look, without putting in a lot of effort. It also supports Python3's Pygments libr
ary for syntax highlighting in code blocks, while not required, is a great addition for someone l
ike me.

<!-- more -->
## Why I chose Frog

Even though the author, Greg Hendershott, recently posted about how frog isn't lightweight enough for his own blog anymore, it is exactly the amount of weight that I need. It takes markdown files, turns them into blog posts, and renders a nice static webpage that I can easily push to github. It is easy to modify the site as needed, but comes out of the box doing its job extremely well.

I have tried creating blogs in the past, the most recent being one I wrote using Django, but they seemed to have too much overhead and didn't allow easy control over formatting my posts. 

## Why not use Wordpress or Blogger?

It is easier for me to open up my terminal, type `raco frog -n blog-title`, and write some markdown, than to have to log into a Blogger account or navigate to some site to create a post. I think the real reason is the hacker in me would rather just do it myself.

## What I plan for the future with Frog

I hope to write occational posts with updates on what I am working on, how-to's for anything programming related that I don't want to forget, as well as posts related to guitar and P4 tuning. I plan on adding some sort of tool to Frog that allows me to easily write and display guitar tab and/or music notation directly in my blog posts.
