## Introduction: Deploying Websites

<p class="p__1qg33Igem5pAgn4kPMirjw">
The goal of this unit is to introduce you to web hosting and deploying
websites with GitHub Pages. You will also learn how to use the command
line to navigate file structures.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
After this unit, you will be able to:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Understand web hosting
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Deploy a simple website using GitHub pages
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Navigate file structures
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You will put all of this knowledge into practice with an upcoming
Portfolio Project. You can complete the Portfolio Project either in
parallel with or after taking the prerequisite content—it’s up to you!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Learning is social. Whatever you’re working on, be sure to connect with
the Codecademy community in the
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://discuss.codecademy.com/">forums</a>.
Remember to check in with the community regularly, including for things
like asking for code reviews on your project work and providing code
reviews to others in the
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://discuss.codecademy.com/c/project/1833">projects
category</a>, which can help to reinforce what you’ve learned.
</p>

## What is Hosting?

<iframe frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="What Is Web Hosting? Different Types of Hosting Providers Explained" width="100%" height="100%" src="https://www.youtube.com/embed/EOJxpgRmtxA?autoplay=0&amp;mute=0&amp;controls=1&amp;origin=https%3A%2F%2Fwww.codecademy.com&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;enablejsapi=1&amp;widgetid=1" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" id="widget2" data-gtm-yt-inspected-76="true">
</iframe>

## What is a Domain Name?

<iframe frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="What Is a Domain Name? Domain vs. Web Hosting" width="100%" height="100%" src="https://www.youtube.com/embed/se3ujLcBsAE?autoplay=0&amp;mute=0&amp;controls=1&amp;origin=https%3A%2F%2Fwww.codecademy.com&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;enablejsapi=1&amp;widgetid=1" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" id="widget2" data-gtm-yt-inspected-76="true">
</iframe>

## What is a Domain Name?

<iframe frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="What Is a Domain Name? Domain vs. Web Hosting" width="100%" height="100%" src="https://www.youtube.com/embed/se3ujLcBsAE?autoplay=0&amp;mute=0&amp;controls=1&amp;origin=https%3A%2F%2Fwww.codecademy.com&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;enablejsapi=1&amp;widgetid=1" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" id="widget2" data-gtm-yt-inspected-76="true">
</iframe>

## Creating a Website on GitHub Pages

<p class="p__1qg33Igem5pAgn4kPMirjw">
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://pages.github.com/">GitHub
Pages</a>, a tool provided by
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://github.com/">GitHub</a>,
lets you easily create and deploy a website online. GitHub allows you to
store all the files and code for your website in a repository. You can
then use GitHub Pages to generate a personal URL and share your site
with friends, family, and the world!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
For this tutorial, you need a GitHub account and basic HTML knowledge.
You don’t need to know Git or the command line. (But if you do want to
learn how to use these tools, check out our
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/learn/learn-git">Learn
Git & GitHub</a> and
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/learn/learn-the-command-line">Learn
the Command Line</a> courses.)
</p>
<h2 id="heading-github-vs-github-pages" class="h2__1Ly_Sza5xVS3yZl46_StcN">
GitHub vs. GitHub Pages
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In GitHub, code is stored in a <em>repository</em>, or repo. You can
think of it as a special folder that lives online. GitHub hosts that
folder so that it is accessible to you and your teammates from anywhere
in the world.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In our case, our repository will contain HTML and CSS code that defines
a website. But you can’t SEE the website anywhere. GitHub just displays
the code like any other text. GitHub Pages essentially connects your
repository to a unique URL so that, when you go to that URL – say
<code class="code__2rdF32qjRVp7mMVBHuPwDS">username.github.io</code> –
in your browser, you’ll find your website displayed.
</p>
<h2 id="heading-create-a-repository" class="h2__1Ly_Sza5xVS3yZl46_StcN">
Create a Repository
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Let’s get started!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://github.com/new">Create
a new repository</a> named
<code class="code__2rdF32qjRVp7mMVBHuPwDS">username.github.io</code>,
where <code class="code__2rdF32qjRVp7mMVBHuPwDS">username</code> is your
GitHub username.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<img src="https://content.codecademy.com/articles/github-pages-via-web-app/create-a-new-repository.png" alt="Screenshot of the create a new repository page" class="img__1JGFO2nlisObc3KeOSGPRp">
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You have the option here to use a template, add a description, make your
repository private, and initialize some additional files. These items
make it easy for other developers to learn about your repository: what
it’s about, who can access it, who can use the code, etc. For
simplicity, we’re going to skip those items for now. Your site will work
without them.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click “Create Repository”.
</p>
<h2 id="heading-creating-your-first-page" class="h2__1Ly_Sza5xVS3yZl46_StcN">
Creating Your First Page
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You should be redirected to the repository page, which shows an empty
repository. It’s time to add a file! On that page, click the “creating a
new file” link.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<img src="https://content.codecademy.com/articles/github-pages-via-web-app/creating-a-new-file-link.png" alt="Screenshot of the repository page with a rectangle around the creating a new file link" class="img__1JGFO2nlisObc3KeOSGPRp">
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Name your file <strong>index.html</strong>. Now copy and paste the
following code into the file.
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-html" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk4">&lt;html&gt;</span></span><br><span><span> </span></span><br><span><span class="mtk4">&lt;body&gt;</span></span><br><span><span class="mtk1">&nbsp;&nbsp;</span><span class="mtk4">&lt;h1&gt;</span><span class="mtk1">YOUR NAME</span><span class="mtk4">&lt;/h1&gt;</span></span><br><span><span class="mtk1">&nbsp;&nbsp;</span><span class="mtk4">&lt;p&gt;</span><span class="mtk1">Welcome to my website!</span><span class="mtk4">&lt;/p&gt;</span></span><br><span><span class="mtk1">&nbsp;&nbsp;</span><span class="mtk4">&lt;img</span><span class="mtk1"> </span><span class="mtk7">src</span><span class="mtk1">=</span><span class="mtk8">"https://content.codecademy.com/articles/github-pa</span><span class="mtk8">ges-via-web-app/happy-ice-cream.gif"</span><span class="mtk1"> </span><span class="mtk4">/&gt;</span></span><br><span><span class="mtk4">&lt;/body&gt;</span></span><br><span><span> </span></span><br><span><span class="mtk4">&lt;/html&gt;</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You can customize the text that says
<code class="code__2rdF32qjRVp7mMVBHuPwDS">YOUR NAME</code> and
<code class="code__2rdF32qjRVp7mMVBHuPwDS">Welcome to my
website!</code>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<img src="https://content.codecademy.com/articles/github-pages-via-web-app/commit-index-html.png" alt="Screenshot of the create index.html page after everything is filled out" class="img__1JGFO2nlisObc3KeOSGPRp">
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Changes to your repository are called <em>commits</em>. You can imagine
each commit as a snapshot of your repository at different times.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Time to create our first commit! In the first textbox, name your commit
“Create index.html”. Commits usually start with a verb describing
changes made to the repository.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Press the “Commit new file” button.
</p>
<h2 id="heading-viewing-your-website" class="h2__1Ly_Sza5xVS3yZl46_StcN">
Viewing Your Website
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Your website is now accessible at
<code class="code__2rdF32qjRVp7mMVBHuPwDS"><https://username.github.io></code>!
(Remember to replace
<code class="code__2rdF32qjRVp7mMVBHuPwDS">username</code> with your
GitHub username.)
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<img src="https://content.codecademy.com/articles/github-pages-via-web-app/deployed-website.gif" alt="An animated gif of the website you created" class="img__1JGFO2nlisObc3KeOSGPRp">
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
If you’d like, you can develop your website by adding more HTML and CSS!
Your site should update a few minutes after each commit.
</p>
<h2 id="heading-troubleshooting" class="h2__1Ly_Sza5xVS3yZl46_StcN">
Troubleshooting
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
If your site isn’t appearing after 10 minutes, try these additional
steps:
</p>
<ol class="ol__1XI8Ausmo9cwwog3NvDzWF">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<p class="p__1qg33Igem5pAgn4kPMirjw">
Within your
<code class="code__2rdF32qjRVp7mMVBHuPwDS">username.github.io</code>
repo, go to Settings and scroll down to GitHub Pages. Under Source, make
sure that your repo is linked to your web page. If you see
<code class="code__2rdF32qjRVp7mMVBHuPwDS">None</code>, then select the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">main</code> branch.
</p>
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<p class="p__1qg33Igem5pAgn4kPMirjw">
Within the same GitHub Pages section, go to Theme Chooser and select any
theme.
</p>
</li>
</ol>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<img src="https://static-assets.codecademy.com/Paths/front-end-career-path/github-pages/github-pages-settings-ii.png" alt="Repo Settings, GitHub Pages section" class="img__1JGFO2nlisObc3KeOSGPRp">
</p>

## NAVIGATION

### Introduction

<p class="p__1qg33Igem5pAgn4kPMirjw">
The <strong>command line</strong> is a text interface for your computer.
It’s a program that takes in commands and passes them on to the
computer’s operating system to run.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
From the command line, you can navigate through files and folders on
your computer, just as you would with Finder on Mac OS or Windows
Explorer on Windows. The difference is that the command line is fully
text-based.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The advantage of using the command line is its power. You can run
programs, write scripts to automate common tasks, and combine simple
commands to handle difficult tasks. All of these traits come together to
make it an important programming tool.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
This course is for unix-based systems such as Linux and Mac OS X. You
can also download programs on Windows that will allow you to use the
same commands. An appendix of all commands taught in this course is
available
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/articles/command-line-commands">here</a>.
</p>

**Instructions**

<p class="p__1qg33Igem5pAgn4kPMirjw">
When using the command line, we refer to folders as
<em>directories</em>. Files and directories on your computer are
organized into a <em>filesystem</em>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Move on to the next exercise to find out how the filesystem works.
</p>

**Solutions**

``` html
```

## NAVIGATION

### Filesystem

<p class="p__1qg33Igem5pAgn4kPMirjw">
A filesystem organizes a computer’s files and directories into a tree
structure:
</p>
<ol class="ol__1XI8Ausmo9cwwog3NvDzWF">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
The first directory in the filesystem is the <em>root directory</em>. It
is the parent of all other directories and files in the filesystem.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Each parent directory can contain more child directories and files. In
the filesystem on the right, <strong>blog/</strong> is the parent of
<strong>2014/</strong>, <strong>2015/</strong>, and
<strong>hardware.txt</strong>.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Each directory can contain more files and child directories. The
parent-child relationship continues as long as directories and files are
nested.
</li>
</ol>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You’re probably already familiar with this tree structure - Mac Finder
and Windows Explorer represent the filesystem as trees as well.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
We are going to use the pictured filesystem for the rest of the lesson.
You can reference it at anypoint
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://content.codecademy.com/courses/learn-command-line/img/LCL-fileTrees-01.png">here</a>.
</p>

**Instructions**

<p class="p__1qg33Igem5pAgn4kPMirjw">
Move on to the next exercise to start learning about the different
commands!
</p>

**Solutions**

``` html
```

## NAVIGATION

### ls

<div data-testid="markdown" class="spacing-tight__2Gp7GTqG0TykPQ18OnUOVt markdown__1eeYJ4WPKUcvX_LDDGJR12">
<p class="p__1qg33Igem5pAgn4kPMirjw">
The first command we’re going to look at is
<code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code>. A <em>command</em>
is a directive to the computer to perform a specific task. When you type
<code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code>, the command line
looks at the directory you are in, and then “lists” all the files and
directories inside of it. Be sure to type the letter
<code class="code__2rdF32qjRVp7mMVBHuPwDS">l</code> as in “List” and not
the number 1.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In the terminal, the first thing you see is
<code class="code__2rdF32qjRVp7mMVBHuPwDS">$\</code\>. This is called a \<em\>shell prompt\</em\>. It appears when the terminal is ready to accept a command.\</p\> \<p class="p\_\_1qg33Igem5pAgn4kPMirjw"\>If we typed:\</p\> \<pre class="pre\_\_3_SOs7YT7NaHjnNunEArSM"\>\<pre\>\<code\>\<div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"\>\<span\>\<span class="mtk1"\>$
ls</span></span><br>
</div>
</code>
</pre>
</pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
the terminal would display our current directory’s files and
directories:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">2014&nbsp;&nbsp;2015&nbsp;&nbsp;hardware.txt</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The directories <strong>2014/</strong>, <strong>2015/</strong>, and the
file <strong>hardware.txt</strong> are the contents of the current
directory.
</p>
</div>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
The exercises in this lesson use the <kbd>Check Work</kbd> button with
the terminal. To move through the instructions, perform the tasks and
click the <kbd>Check Work</kbd> button. If you accomplish the task
correctly, you can move to the next task or exercise.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
To start, after the <code class="code__2rdF32qjRVp7mMVBHuPwDS">$</code>
in the terminal, type:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">ls </span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
and press <kbd>enter</kbd>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
You should see the three items print out below the command.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click <kbd>Check Work</kbd> to see how you did.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### pwd

<p class="p__1qg33Igem5pAgn4kPMirjw">
The next command we’re going to look at is
<code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code>, which stands for
“print working directory.” It outputs the name of the directory you are
currently in, called the <em>working directory</em>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Here the working directory is <strong>blog/</strong>. In Codecademy
courses, your working directory is usually inside the
<strong>/home/ccuser/workspace/</strong> directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Together with <code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code>, the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code> command is useful
to show where you are in the filesystem.
</p>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Let’s continue with more commands. In the terminal, print the working
directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure to click the <kbd>Check Work</kbd> button once you’ve
completed each checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
List all files and directories in the working directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the “Check Work” button when you are done.
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### cd I

<p class="p__1qg33Igem5pAgn4kPMirjw">
Our next command is
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code>, which stands for
“change directory.” Just as you would click on a folder in Windows
Explorer or Finder, <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code>
switches you into the directory you specify. In other words,
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> changes the working
directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Let’s say the directory we change into is <strong>2015/</strong>:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ cd 2015</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
When a file, directory, or program is passed into a command, it is
called an <em>argument</em>. Here the <strong>2015/</strong> directory
is an argument for the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> command.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> command takes a
directory name as an argument and switches into that directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
It is also important to move up one directory. For this, we use:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ cd ..</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The argument <code class="code__2rdF32qjRVp7mMVBHuPwDS">..</code> stands
for the directory above the current working directory. Assuming we are
in <strong>/home/ccuser/workspace/blog/2015</strong>:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog/2015</span></span><br><span><span class="mtk1">$ cd ..</span></span><br><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The above example uses the command
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd ..</code> to navigate up
to the <strong>/home/ccuser/workspace/blog/</strong> directory.
</p>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Our current working directory is
<strong>/home/ccuser/workspace/blog/</strong>. Change into the
<strong>2015/</strong> directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Confirm you are in the <strong>2015/</strong> directory using
<code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure to click the <kbd>Check Work</kbd> button once you’ve
completed each checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now move back up to the <strong>blog/</strong> directory using the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">..</code> notation.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Confirm your location again with
<code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code> and click the
<kbd>Check Work</kbd> button?
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">3.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Let’s move further into the filesystem. We are currently in the
<strong>blog/</strong> directory. From here we want to move into the
<strong>2015/</strong> directory, then into a directory named
<strong>jan/</strong> and lastly, a directory named
<strong>memory/</strong>. (You can reference the filesystem for this
lesson
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://content.codecademy.com/courses/learn-command-line/img/LCL-fileTrees-01.png">here</a>.)
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Move down the filesystem into the <strong>memory/</strong> directory and
print the working directory again to see the new location.
</p>

<span aria-live="assertive">Checkpoint 4 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### cd II

<p class="p__1qg33Igem5pAgn4kPMirjw">
In the previous exercise, we used
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> multiple times to
go from the <strong>blog/</strong> directory to the
<strong>memory/</strong> directory. You can reference the file system
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://s3.amazonaws.com/codecademy-content/courses/learn-command-line/img/LCL-fileTrees-01.png">here</a>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
To move across multiple directories with a single command, we can
provide <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> a relative
path to the <strong>memory/</strong> directory as an argument. From the
<strong>blog/</strong> directory use:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ cd 2015/jan/memory</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The relative path is a forward slash (/) separated list of all the
directories leading to the goal directory. In the above example, we
navigate directly to <strong>memory/</strong> from
<strong>blog/</strong> using
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> with the relative
path <code class="code__2rdF32qjRVp7mMVBHuPwDS">2015/jan/memory</code>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
We can also move up multiple directories using the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">..</code> argument. To go
from <strong>memory</strong> up 2 directories to <strong>2015</strong>,
we use \`../..:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog/2015/jan/memory</span></span><br><span><span class="mtk1">$ cd ../..</span></span><br><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog/2015</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The relative path
<code class="code__2rdF32qjRVp7mMVBHuPwDS">../..</code> can be read: the
directory above and the directory above that.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Lastly, we can move to an adjacent directory using
<code class="code__2rdF32qjRVp7mMVBHuPwDS">..</code> and then a
directory name. If we are in the <strong>2015/</strong> directory and we
want to go into the <strong>2014/</strong> directory, we go up one
directory then into the <strong>2014/</strong> directory:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ ls</span></span><br><span><span class="mtk1">2014&nbsp;&nbsp;2015&nbsp;&nbsp;hardware.txt</span></span><br><span><span class="mtk1">$ cd 2015</span></span><br><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog/2015</span></span><br><span><span class="mtk1">$ cd ../2014</span></span><br><span><span class="mtk1">$ pwd</span></span><br><span><span class="mtk1">/home/ccuser/workspace/blog/2014</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The relative path is the directory above <strong>2015/</strong> (which
is <strong>blog/</strong>) and then the <strong>2014/</strong>.
</p>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
For this exercise, we want to start in the <strong>blog/2015/</strong>
directory. Check your location and navigate to this directory. Remember,
you can always use <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code>
with the absolute path,
<strong>/home/ccuser/workspace/blog/2015/</strong>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Once in the <strong>blog/2015/</strong> directory, change the directory
to the <strong>feb/</strong> directory using a single command.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
When in the <strong>feb/</strong> directory, check the working
directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure to click the <kbd>Check Work</kbd> button once you’ve
completed each checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now we’re in <strong>2015/feb/</strong>, but what if we want to move to
the adjacent directory <strong>2015/jan/</strong>? (You can reference
the filesystem for this lesson
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://s3.amazonaws.com/codecademy-content/courses/learn-command-line/img/LCL-fileTrees-01.png">here</a>.)
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Using a single <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code>
command, navigate from <strong>2015/feb/</strong> to
<strong>2015/jan/</strong> and confirm your working directory.
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">3.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Navigate back to <strong>/home/ccuser/workspace/blog</strong> using a
single <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> command and
then use <code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code> to
confirm your working directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the <kbd>Check Work</kbd> button when you are done.
</p>

<span aria-live="assertive">Checkpoint 4 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### mkdir

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now that we can traverse the existing filesystem, let’s try editing it
by making directories (folders) through the command line. The command
for that is <code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code>:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ mkdir media</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The <code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code> command
stands for “make directory”. It takes in a directory name as an argument
and then creates a new directory in the current working directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Here we used <code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code> to
create a new directory named <strong>media/</strong> inside our working
directory.
</p>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Navigate to the <strong>/home/ccuser/workspace/blog/2014/dec/</strong>
directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Then list all files and directories in the working directory to see
what’s currently in there.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure to click the <kbd>Check Work</kbd> button once you’ve
completed each checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Create a new directory named <strong>media</strong>. If you list the
contents of the working directory again, you should see your new
directory.
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">3.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Within our new <strong>media/</strong> directory we would like to create
another directory name <strong>tv/</strong>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
To do this we could:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> into
<strong>media/</strong> and then use
<code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code>
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
use <code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code> from our
current position by using the relative path
<code class="code__2rdF32qjRVp7mMVBHuPwDS">media/tv</code> as an
argument
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Create a new directory named <strong>tv/</strong> inside
<strong>media/</strong> using either of the above approaches.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the <kbd>Check Work</kbd> button when you are done.
</p>

<span aria-live="assertive">Checkpoint 4 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### touch

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now we know how to create directories through the command line, but how
do we create new files?
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
We can do this using the command
<code class="code__2rdF32qjRVp7mMVBHuPwDS">touch</code>:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="shell" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ touch keyboard.txt</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The <code class="code__2rdF32qjRVp7mMVBHuPwDS">touch</code> command
creates a new file inside the working directory. It takes in a filename
as an argument and then creates an empty file with that name in the
current working directory.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Here we used <code class="code__2rdF32qjRVp7mMVBHuPwDS">touch</code> to
create a new file named <strong>keyboard.txt</strong>.
</p>

**Instructions**

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure you are in the <strong>/home/ccuser/workspace/blog/</strong>
directory. List your working directory’s current contents.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Make sure to click the <kbd>Check Work</kbd> button once you’ve
completed each checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Create a new file named <strong>keyboard.txt</strong> inside the working
directory. If you list its contents again, you should now see your file
listed.
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<button aria-expanded="false" class="basicBtn__2_xxdSYwVIY18Fd5pq9JgS accordionButton__3LbMIquV93ec6TYv2l6mjX yellow__2olEZaNZdnw4sc3pSwo39e" data-btn="true">
<span class="children__3aFTNwOnkG0i7uCSFwvYT5">

Stuck? Get a hint

</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" role="img" aria-hidden="true" class="expansionIcon__3EAlubPR6T3-MPaeVEwyjl gamut-sd6ku5-Svg eol2zvm0">
<title>
Arrow Chevron Down Icon
</title>
<path d="M23.25 7.311L12.53 18.03a.749.749 0 01-1.06 0L.75 7.311" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"></path></svg>
</button>

**Solutions**

``` html
```

## NAVIGATION

### Helper Commands

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now that we’ve covered the basics of navigating your filesystem from the
command line, let’s look at some helpful commands that will make using
it easier!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<kbd>tab</kbd> can be used to autocomplete your command. When you are
typing the name of an existing file or directory, you can use
<kbd>tab</kbd> to finish the rest of the name.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The up and down arrows (<kbd>↑</kbd> and <kbd>↓</kbd>) can be used to
cycle through your previous commands. <kbd>↑</kbd> will take you up
through your most recent commands, and <kbd>↓</kbd> will take you back
through to the most recent one.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">clear</code> is used to clear
your terminal, which is useful when it’s full of previous commands and
outputs. It doesn’t change or undo your previous commands, it just
clears them from view. As mentioned above, you can use the up and down
arrow keys to review your command history anytime.
</p>

**Instructions**

<p class="p__1qg33Igem5pAgn4kPMirjw">
Experiment with the helper commands! Some things you could try are:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
When your working directory is
<strong>home/ccuser/workspace/blog</strong>, type
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd 2</code> and then use
<kbd>tab</kbd> - it should autocomplete upto
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd 201</code>. This is
because both possible directories (<strong>2014</strong> and
<strong>2015</strong>) start with
<code class="code__2rdF32qjRVp7mMVBHuPwDS">201</code>.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Use <code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code> to see what
contents are in your working directory. Then use
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> with the first
letter of one of the files or directories and use <kbd>tab</kbd> to
autocomplete.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Use the up and down arrows to cycle through your previous commands.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Use <code class="code__2rdF32qjRVp7mMVBHuPwDS">clear</code> to clear
your previous commands and output from the terminal.
</li>
</ul>

**Solutions**

``` html
```

## NAVIGATION

### Review

<p class="p__1qg33Igem5pAgn4kPMirjw">
Congratulations! You’ve learned five commands commonly used to navigate
the filesystem from the command line. What can we generalize so far?
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
The <em>command line</em> is a text interface for the computer’s
operating system. To access the command line, we use the terminal.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
A <em>filesystem</em> organizes a computer’s files and directories into
a tree structure. It starts with the <em>root directory</em>. Each
parent directory can contain more child directories and files.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
From the command line, you can navigate through files and folders on
your computer:
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">pwd</code> outputs the name
of the current working directory.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code> lists all files and
directories in the working directory.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">cd</code> switches you into
the directory you specify.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir</code> creates a new
directory in the working directory.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">touch</code> creates a new
file inside the working directory.
</li>
</ul>
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
You can use helper commands to make navigation easier:
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">clear</code> clears the
terminal
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<kbd>tab</kbd> autocompletes the name of a file or directory
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<kbd>↑</kbd> and <kbd>↓</kbd> allow you to cycle through previous
commands
</li>
</ul>
</li>
</ul>

**Instructions**

<p class="p__1qg33Igem5pAgn4kPMirjw">
Move on when you’re ready!
</p>

**Solutions**

``` html
```

## Setting Up Command Line

<div data-testid="markdown" class="spacing-loose__3_R8mSIQ2cspwhDGkCOXTu markdown__1eeYJ4WPKUcvX_LDDGJR12 darkTheme__2i0sjr_RjoITRh35Ld2GzM gamut-gk1onf-ArticleMarkdown e1xfx7rd0">
<h1 id="heading-setting-up-your-command-line" class="h1__3BU3KLGw2QEVAGn0rGpP21">
Setting Up Your Command Line
</h1>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The command line is a powerful tool used by developers to find, create,
and manipulate files and folders. This short tutorial will walk you
through the steps for setting up the command line application on your
computer.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Command Line Interfaces (CLIs) come in many forms. The CLI we’ll use is
called Bash.
</p>
<h2 id="heading-what-is-bash" class="h2__1Ly_Sza5xVS3yZl46_StcN">
What is Bash?
</h2>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<strong>Bash</strong>, or the
<strong>B</strong>ourne-<strong>A</strong>gain <strong>SH</strong>ell,
is a CLI that was created over twenty-seven years ago by Brian Fox as a
free software replacement for the Bourne Shell. A <strong>shell</strong>
is a specific kind of CLI. Bash is “open source” which means that anyone
can read the code and suggest changes. Since its beginning, it has been
supported by a large community of engineers who have worked to make it
an incredible tool. Bash is the default shell for Linux and Mac. For
these reasons, Bash is the most used and widely distributed shell. If
you want to learn more about Bash,
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://en.wikipedia.org/wiki/Bash_(Unix_shell)">this
Wikipedia article</a> is a good place to start.
</p>
<h2 id="heading-bash-setup-for-mac-and-windows" class="h2__1Ly_Sza5xVS3yZl46_StcN">
Bash Setup for Mac and Windows
</h2>
<h3 id="heading-mac-users" class="h3__3B1DSzXTW-ux1viDSStOux">
Mac users:
</h3>
<p class="p__1qg33Igem5pAgn4kPMirjw">
As mentioned before, Bash is the default shell on Linux and Mac OS X, so
good news, you don’t have to install anything!
</p>

<iframe frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Lesson Supplement How to setup the command line terminal Mac OS" width="100%" height="100%" src="https://www.youtube.com/embed/-zu_4QWHyF8?autoplay=0&amp;mute=0&amp;controls=1&amp;origin=https%3A%2F%2Fwww.codecademy.com&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;enablejsapi=1&amp;widgetid=1" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" id="widget2" data-gtm-yt-inspected-76="true">
</iframe>

<p class="p__1qg33Igem5pAgn4kPMirjw">
To access Bash in OS X, you can use an application called
<strong><em>Terminal</em></strong>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">

1.  First open the <strong>Applications</strong> folder, then open the
    <strong>Utilities</strong> folder.
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">

    1.  Once you’re in the <strong>Utilities folder</strong> you will
        see the application <strong>Terminal</strong>. Open the
        <strong>Terminal</strong> application and you’re ready to go!
        </p>
        <p class="p__1qg33Igem5pAgn4kPMirjw">

        1.  For ease of access later, you can keep Terminal in your
            Dock. Simply right click (alt-click) the Terminal icon in
            your dock, then select “Options”, then “Keep In Dock.”
            </p>
            <p class="p__1qg33Igem5pAgn4kPMirjw">
            Continue to the “Try it Out!” section below for some simple
            first steps with your new tool.
            </p>
            <h3 id="heading-windows-users" class="h3__3B1DSzXTW-ux1viDSStOux">
            Windows users:
            </h3>
            <p class="p__1qg33Igem5pAgn4kPMirjw">
            Windows has a different CLI, called <strong>Command
            Prompt</strong>. While this has many of the same features as
            Bash, Bash is much more popular. Because of the strength of
            the open source community and the tools they provide,
            mastering Bash is a better investment than mastering Command
            Prompt.
            </p>
            <p class="p__1qg33Igem5pAgn4kPMirjw">
            To use Bash on a Windows computer, we will download and
            install a program called <strong>Git Bash</strong>. Git Bash
            allows us to easily access Bash as well as another tool
            we’ll be using later called Git, inside the Windows
            environment.
            </p>
            <p class="p__1qg33Igem5pAgn4kPMirjw">
            You can either watch the following video, or read the rest
            of this article.
            </p>

            <iframe frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Lesson Supplement How to Setup the Command Line Using Git Bash on Windows OS" width="100%" height="100%" src="https://www.youtube.com/embed/sQY0g7s2hac?autoplay=0&amp;mute=0&amp;controls=1&amp;origin=https%3A%2F%2Fwww.codecademy.com&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;enablejsapi=1&amp;widgetid=3" sandbox="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox" id="widget4" data-gtm-yt-inspected-76="true">
            </iframe>

<h4 id="heading-how-to-install-git-bash" class="h4__1cJx3E4QhkKjfWj3jLsTFU">
How to install Git Bash:
</h4>
<p class="p__1qg33Igem5pAgn4kPMirjw">

1.  Navigate to the
    <a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://git-for-windows.github.io/">Git
    Bash installation page</a> and click the Download button.
    <img src="https://content.codecademy.com/courses/freelance-1/unit-3/git%20bash%20setup/annotated_gitbash_dl.png" alt="download" class="img__1JGFO2nlisObc3KeOSGPRp">
2.  Once Git Bash is downloaded, run the downloaded
    <strong>.exe</strong> file and allow the application to make changes
    to your PC. You will get a prompt that says “Do you want to allow
    this app to make changes to your device?” Click
    <strong>Yes</strong>. <br> <br>
3.  To keep things simple, we will use the default settings for
    everything in this installation, so all you need to do now is keep
    clicking <strong>Next</strong>, and finally <strong>Finish</strong>.
    <img src="https://content.codecademy.com/courses/freelance-1/unit-3/git%20bash%20setup/annotated_gitbash_installer.png" alt="setup" class="img__1JGFO2nlisObc3KeOSGPRp">
4.  Open the Start menu by clicking on the Windows icon and typing “Git
    Bash” into the search bar. The icon for Git Bash and the words “Git
    Bash Desktop App” will appear. Click on the icon or the words “Git
    Bash Desktop App” to open Git Bash.
    <img src="https://content.codecademy.com/courses/freelance-1/unit-3/git%20bash%20setup/annotated_gitbash_start.png" alt="openGitBash" class="img__1JGFO2nlisObc3KeOSGPRp">
5.  A new window will open. This is the Git Bash CLI where we will run
    Bash commands. Whenever a new window of the Git Bash app is opened,
    you will always be placed in the same directory, your <strong>home
    directory</strong>.
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    The home directory is represented by the tilde sign,
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">\~</code>, in the CLI
    after <code class="code__2rdF32qjRVp7mMVBHuPwDS">MINGW64</code>. The
    tilde is another way to say
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">/c/Users/username</code>
    in Git Bash or <code class="code__2rdF32qjRVp7mMVBHuPwDS">C:</code>
    in Windows’ Command Prompt.
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    The absolute path of your current working directory, how you got
    from the root directory to the directory you are currently in, will
    always be noted at the top of the window:
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    <img src="https://content.codecademy.com/courses/freelance-1/unit-3/git%20bash%20setup/annotated_gitbash_shell_edited.png" alt="homeDirectory" class="img__1JGFO2nlisObc3KeOSGPRp">
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    Git Bash works by giving you a CLI that acts like a Bash CLI. That
    means you can now work with your files and folders using Bash
    commands instead of Windows commands.
    </p>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    Congratulations, you now have Bash installed on your computer, ready
    to use!
    </p>
    <h2 id="heading-try-it-out" class="h2__1Ly_Sza5xVS3yZl46_StcN">
    Try it out!
    </h2>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    Now that you have your Command Line Interface open on your desktop,
    you are ready to use it. Go ahead and try some of the commands on
    your personal computer. Here are some good commands for practice:
    </p>
    <ol class="ol__1XI8Ausmo9cwwog3NvDzWF">
    <li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code> to list the
    contents of the current directory. It may look something like this:
    <pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ ls</span></span><br><span><span class="mtk1">Applications&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pictures</span></span><br><span><span class="mtk1">Codecademy&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Public</span></span><br><span><span class="mtk1">Desktop&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Downloads</span></span><br><span><span class="mtk1">Documents&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Library</span></span><br></div></code></pre></pre>
    </li>
    <li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">mkdir test</code> to make
    a new directory named <strong>test</strong>. Now, when you type
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code> you should see
    a folder called
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">test</code>:
    <pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ ls</span></span><br><span><span class="mtk1">Applications&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pictures</span></span><br><span><span class="mtk1">Codecademy&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Public</span></span><br><span><span class="mtk1">Desktop&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Downloads</span></span><br><span><span class="mtk1">Documents&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Library</span></span><br><span><span class="mtk1">test</span></span><br></div></code></pre></pre>
    </li>
    <li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">cd test</code> to
    navigate into the new directory. You won’t see an output when you do
    this.
    </li>
    <li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">echo “Hello Command Line”
    \>\> hello_cli.txt</code> to create a new file named
    <strong>hello_cli.txt</strong> and add
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">Hello Command Line</code>
    to that file. When you type
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">ls</code>, you should see
    the following:
    <pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ ls</span></span><br><span><span class="mtk1">hello_cli.txt</span></span><br></div></code></pre></pre>
    </li>
    <li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
    <code class="code__2rdF32qjRVp7mMVBHuPwDS">cat hello_cli.txt</code>
    to print the contents of the <strong>hello_cli.txt</strong> file to
    the terminal. You should see something like:
    <pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">$ cat hello_cli.txt</span></span><br><span><span class="mtk1">Hello Command Line</span></span><br></div></code></pre></pre>
    </li>
    </ol>
    <p class="p__1qg33Igem5pAgn4kPMirjw">
    Good job! You’re ready to explore the world of the Command Line
    Interface on your own computer.
    </p>
    </div>

## WEB DEVELOPMENT FOUNDATIONS

### Bicycle World

<p class="p__1qg33Igem5pAgn4kPMirjw">
Welcome to Bicycle World, the premier text-based bicycle shop! This shop
is only accessible to programmers like you, who are familiar with the
command line.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In this project, you’ll use the commands you learned to navigate and
edit the filesystem of this special shop.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The starting filesystem is shown below. (Bicycle World recently changed
owners, who named the main directory
<code class="code__2rdF32qjRVp7mMVBHuPwDS">bicycle-world-ii</code>.)
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="plaintext" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk1">bicycle-world-ii</span></span><br><span><span class="mtk1">|—— brands.txt</span></span><br><span><span class="mtk1">|—— freight/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|—— messenger/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|—— porteur/</span></span><br><span><span class="mtk1">|—— mountain/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|—— downhill/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;|—— heavyweight/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;|—— lightweight/</span></span><br><span><span class="mtk1">|&nbsp;&nbsp;&nbsp;|—— hardtail/</span></span><br><span><span class="mtk1">|—— racing/</span></span><br><span><span class="mtk1">&nbsp;&nbsp;&nbsp;&nbsp;|—— road/</span></span><br><span><span class="mtk1">&nbsp;&nbsp;&nbsp;&nbsp;|—— track/</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
If you get stuck during this project or would like to see an experienced
developer work through it, click “<strong>Get Unstuck</strong>“ to see a
<strong>project walkthrough video</strong>.
</p>

## WEB DEVELOPMENT FOUNDATIONS

### Daily Buzz

<p class="p__1qg33Igem5pAgn4kPMirjw">
In this project, you’ll use the commands you just learned to navigate
through the files and directories of Daily Buzz, a national newspaper.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
If you get stuck during this project or would like to see an experienced
developer work through it, click “<strong>Get Unstuck</strong>“ to see a
<strong>project walkthrough video</strong>.
</p>

## Review: Deploying Websites

<p class="p__1qg33Igem5pAgn4kPMirjw">
Congratulations! The goal of this unit was to get an introduction to web
hosting and deploying websites with GitHub Pages. You also learned how
to use the command line to navigate file structures.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Having completed this unit, you are now able to:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Understand web hosting
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Deploy a simple website using GitHub pages
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Navigate file structures
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Learning is social. Whatever you’re working on, be sure to connect with
the Codecademy community in the
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://discuss.codecademy.com/">forums</a>.
Remember to check in with the community regularly, including for things
like asking for code reviews on your project work and providing code
reviews to others in the
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://discuss.codecademy.com/c/project/1833">projects
category</a>, which can help to reinforce what you’ve learned.
</p>
