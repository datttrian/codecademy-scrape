## LANGUAGES FOR WEB DEVELOPMENT

### What is CSS?

Languages for Web Development

<span class="gamut-yj8jvy-Text e8i0p5k0" aria-hidden="true">What is
CSS?</span>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Using just HTML, Alejandra was able to build a website that contains all
of the content that she wants. But it doesn’t look very
impressive—Alejandra knows that a basic black and white website won’t
give her business the credibility she needs to find new customers.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
That’s where CSS comes in! <em>CSS</em> is the language that provides
<em>style</em> to the content of an HTML page. This includes colors,
fonts, positioning, layout, and more!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Why do we need a separate language for content and presentation? This is
an example of the computer science principle <em>separation of
concerns</em>. Large codebases are kept maintainable when each section
has clearly differentiated problems that it is trying to solve.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Since the styling rules are described separately from the content
itself, if Alejandra adds more paragraphs, images, or other forms of
content, she can expect them to be styled the same way as her existing
content. This will save Alejandra time in the long run, especially as
her website gets more and more complex.
</p>

<p class="p__1qg33Igem5pAgn4kPMirjw">
After you’ve reviewed the diagram to compare the uses of HTML and CSS,
continue to the next exercise.
</p>

## LANGUAGES FOR WEB DEVELOPMENT

### Applying CSS

Languages for Web Development

<span class="gamut-yj8jvy-Text e8i0p5k0" aria-hidden="true">Applying
CSS</span>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Alejandra has learned CSS and created the desired visual rules to make
her website look sleek and polished.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Navigate to the <strong>style.css</strong> file to take a look at the
CSS code that she’s written.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In this file, you will recognize many of the HTML tags that you have
been working with — and maybe a few that you haven’t seen yet! CSS
contains <em>selectors</em> that specify the HTML elements to which the
style should be applied as well as <em>visual rules</em> that specify
how that content should be displayed.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Now it’s time to use the HTML link element to apply the CSS file to her
existing website. This is done with an HTML link tag. An HTML link tag
is often used to create a connection between an HTML file and the CSS
file and tells the browser to apply the CSS styles to the HTML.
</p>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
On line 6 of <strong>index.html</strong>, copy and paste the code below
to apply the CSS file to the existing HTML.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Use your knowledge of HTML attributes to figure out what this code
specifies, and check out extra information in the hint if you want to
learn more.
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-html" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk4">&lt;link</span><span class="mtk1"> </span><span class="mtk7">rel</span><span class="mtk1">=</span><span class="mtk8">"stylesheet"</span><span class="mtk1"> </span><span class="mtk7">href</span><span class="mtk1">=</span><span class="mtk8">"style.css"</span><span class="mtk4">&gt;</span></span><br></div></code></pre></pre>

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
Awesome! Alejandra’s site is looking good! Just a little CSS can make
the difference between a website that looks like a skeleton and
portfolio-ready site.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Now let’s tweak the CSS just a little bit, to see how the visual rules
specified in CSS can change the way that a website is displayed.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Navigate to the <strong>style.css</strong> and scroll down to line 37
where you will see the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">h1</code> selector. This
section defines the styles for the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">h1</code> element on the
page, which is the most prominent heading.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Just for practice, change the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">color</code> property from
<code class="code__2rdF32qjRVp7mMVBHuPwDS">white</code> to
<code class="code__2rdF32qjRVp7mMVBHuPwDS">black</code> and press Run to
see what changes!
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">3.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Good job changing the color of the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">h1</code> text!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
If you look at the rendered browser, you’ll notice that the heading text
is no longer readable in-front of the image.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Let’s change the color property within the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">h1</code> selector back to
white.
</p>

<span aria-live="assertive">Checkpoint 4 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

## LANGUAGES FOR WEB DEVELOPMENT

### What is JavaScript?

Languages for Web Development

<span class="gamut-yj8jvy-Text e8i0p5k0" aria-hidden="true">What is
JavaScript?</span>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now that Alejandra has her website looking polished, she’s realized that
she wants the site to be more interactive. She would like to build a
shopping cart feature that allows her users to buy travel packages
directly from her website.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
To accomplish this, Alejandra is going to need to learn JavaScript. Any
website that provides more than just static information probably
utilizes JavaScript in some way. Here are some familiar examples of
website features most often built with JavaScript:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
popup ads
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
animated graphics (2D or 3D)
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
interactive audio and video
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
maps and other features access the user’s geographic location
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
and much more!
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
One of the defining features of JavaScript is its ability to respond to
browser events. These events happen in real time and can be triggered by
a wide variety of user interactions, including:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
the user clicking on a button
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
the user pressing enter on their keyboard
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
a video file finishing loading
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
the user re-sizing their window
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
the user hovering over text on the webpage
</li>
</ul>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
One of the classic browser events that JavaScript can respond to is the
position of the mouse. When a user puts the mouse near an HTML element,
the <code class="code__2rdF32qjRVp7mMVBHuPwDS">onmouseover</code> event
is fired.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Hover over the text in the browser to see how it responds to the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">onmouseover</code> event.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Once you have observed the effect of
<code class="code__2rdF32qjRVp7mMVBHuPwDS">onmouseover</code>, click the
<strong>Run</strong> button to move on to the next Checkpoint.
</p>

<span aria-live="assertive">Checkpoint 2 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">2.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
What else is happening here?
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
JavaScript uses functions, which are reusable blocks of code designed to
perform a specific task.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<code class="code__2rdF32qjRVp7mMVBHuPwDS">drawText</code> is a function
that is being run on line 2. Change the text that says
<code class="code__2rdF32qjRVp7mMVBHuPwDS">‘hello world’</code> to
<code class="code__2rdF32qjRVp7mMVBHuPwDS">‘JavaScript’</code> to pass a
different value into this function.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Check out the browser to see what changed! One of the benefits of
functions is that they are <em>reusable</em>. The
<code class="code__2rdF32qjRVp7mMVBHuPwDS">drawText</code> function
allows us to take advantage of the reusability of functions because it
can render any input text without us needing to rewrite the logic of the
function.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Confused? Don’t worry, we’ll cover functions more thoroughly in the next
exercise.
</p>

<span aria-live="assertive">Checkpoint 3 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

## LANGUAGES FOR WEB DEVELOPMENT

### JavaScript Functions

Languages for Web Development

<span class="gamut-yj8jvy-Text e8i0p5k0" aria-hidden="true">JavaScript
Functions</span>

<p class="p__1qg33Igem5pAgn4kPMirjw">
In the last exercise, you started to think about two key building blocks
of JavaScript: functions and events. Let’s review:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Functions allow us to write a chunk of code once that can be reused over
and over.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Events allow JavaScript to respond to user behaviors, like the user
hovering their mouse over an HTML element or resizing their window.
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Events and functions combine to give JavaScript the ability to create
interactive experiences. When an event is fired, a function is executed.
This pattern is used again and again in web development to create
interactive websites.
</p>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
First, let’s take a look at the JavaScript in the
<strong>index.html</strong> file.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The JavaScript code is between the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">\<script\></code> tags. This
tag alerts the browser that the page contains JavaScript and separates
the JavaScript code from the HTML.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Find the JavaScript function
<code class="code__2rdF32qjRVp7mMVBHuPwDS">changeColor()</code>. This
function chooses a color from a list of colors.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
How does that happen?
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
First, the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">getRandomColor()</code>
function generates a random series of numbers and letters to create a
new
<a target="_blank" rel="noopener" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.mathsisfun.com/hexadecimal-decimal-colors.html">hexadecimal
color code</a>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
It then saves the new color under the name
<code class="code__2rdF32qjRVp7mMVBHuPwDS">newColor</code>.
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-js" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk12">let newColor</span><span class="mtk1"> =&nbsp;</span><span class="mtk9">getRandomColor</span><span class="mtk1">();</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
On the next line, the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">document</code> keyword
accesses the page’s background color and sets it equal to the new color.
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-js" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk9">document</span><span class="mtk1">.</span><span class="mtk10">body</span><span class="mtk1">.</span><span class="mtk10">style</span><span class="mtk1">.</span><span class="mtk10">backgroundColor</span><span class="mtk1"> =&nbsp;</span><span class="mtk9">newColor</span><span class="mtk1">;</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the <strong>Run</strong> button to move on to the next checkpoint
to see how we can let a user change the color!
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
The next step is to connect the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">changeColor()</code>
JavaScript function with an event, so that when we click the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">Repaint!</code> button, it
changes the background color.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
An event is something that can happen in a browser, like clicking or
hovering with your mouse.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
HTML attributes can set events, where the <strong>name</strong> of the
attribute is the event and the <strong>value</strong> of the attribute
is the JavaScript function that we want to execute.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In this case, the name of the event is
<code class="code__2rdF32qjRVp7mMVBHuPwDS">onclick</code> and we can
invoke the function by calling
<code class="code__2rdF32qjRVp7mMVBHuPwDS">“changeColor()”</code>.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Paste this code into the opening tag of the button element:
<code class="code__2rdF32qjRVp7mMVBHuPwDS">onclick=“changeColor()”</code>.
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
Let’s test out the functionality of the code that we just added. When
you click the “Repaint!” button, the background color of the site should
be reset at random!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
When you’re ready, click <strong>Run</strong> again and move on to the
next exercise.
</p>

<span aria-live="assertive">Checkpoint 4 Passed</span>

<svg viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true" class="gamut-sd6ku5-Svg eol2zvm0">
<title>
Check Icon
</title>
<path fill-rule="evenodd" clip-rule="evenodd" d="M23.552 3.93a1.5 1.5 0 01.017 2.122l-13.778 14a1.5 1.5 0 01-2.056.077L.513 13.813a1.5 1.5 0 011.974-2.258l6.158 5.385L21.431 3.948a1.5 1.5 0 012.121-.017z" fill="currentColor"></path>
</svg>

## LANGUAGES FOR WEB DEVELOPMENT

### What is SQL?

Languages for Web Development

<span class="gamut-yj8jvy-Text e8i0p5k0" aria-hidden="true">What is
SQL?</span>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now that Alejandra has built out the user-facing checkout features of
her website, she’s realized that she needs to store all of this
information somewhere! She needs her application to be able to store,
retrieve, and modify data like usernames, shipping addresses, payment
information, and more.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In order to build out these features, Alejandra needs to learn some
<em>SQL</em>, which stands for <strong>s</strong>tructured
<strong>q</strong>uery <strong>l</strong>anguage. You might be familiar
with SQL as a language that Data Analysts and Data Scientists use to
query and analyze data.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
SQL stores information in tables, which is simply a collection of
information organized into rows and columns. If you’ve worked with a
spreadsheet like Microsoft Excel or Google Sheets, you might be familiar
with working with tables. To get the information, you would write a
<em>query</em>, or a program that would retrieve data from the table.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Here’s an example of a query that would select all of the columns —the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">\*</code> keyword is a
shorthand for “all”— from the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">page_views</code> table:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-sql" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk12">SELECT</span><span class="mtk1"> *&nbsp;</span><span class="mtk12">FROM</span><span class="mtk1"> page_views;</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Web developers and software engineers also use SQL to build apps that
can save, modify, and access data. There’s even a growing field of
<em>data engineering</em>, which is a specialized subset of software
engineers who ensure that the applications they are working with
accurately and efficiently record all of the required data.
</p>

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Now you try it! Add <code class="code__2rdF32qjRVp7mMVBHuPwDS">SELECT \*
FROM users;</code> to the text editor to select the entire
<code class="code__2rdF32qjRVp7mMVBHuPwDS">users</code> table from the
database.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Press run and take a look at the data that is returned. What kinds of
data is Alejandra’s app able to store and retrieve? Why is it important
for her to store this particular set of information?
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
