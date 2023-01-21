## Introduction: Fundamentals of CSS

<p class="p__1qg33Igem5pAgn4kPMirjw">
The goal of this unit is to introduce you to CSS, one of the languages
essential to developing websites. You will learn how to apply styles to
HTML documents using CSS.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
After this unit, you will be able to:
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Understand how CSS is used for web development
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Use CSS to add initial styling to your website
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Understand the Box Model in CSS
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Add positioning using CSS
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
Read CSS documentation
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

## SETUP AND SYNTAX

### Intro to CSS

<p class="p__1qg33Igem5pAgn4kPMirjw">
While
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/learn/learn-html">HTML</a>
is the fundamental structure of every web page, it can be visually
unappealing on its own. Cascading Style Sheets or <em>CSS</em> is a
language web developers use to style the HTML content on a web page. If
you’re interested in modifying colors, font types, font sizes, images,
element positioning, and more, CSS is the tool for the job!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
In this lesson, you’ll learn how to set up your CSS file structure and
select which HTML elements you wish to style.
</p>

#### Instructions

<b class="checkpointNumber__P9kFWzdu5a6M0jcG_LgjT">1.</b>

<p class="p__1qg33Igem5pAgn4kPMirjw">
Take a look at the code in
<code class="code__2rdF32qjRVp7mMVBHuPwDS">index.html</code> and observe
how it displays in the browser to the right. This is plain HTML without
any styling. Let’s take a quick look at the power of CSS.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Copy and paste the following line of code onto line 5:
</p>
<pre class="pre__3_SOs7YT7NaHjnNunEArSM"><pre><code><div data-lang="codecademy-html" class="gamut-1oq8wcb-ColorizedContainer e1hgti5c0"><span><span class="mtk4">&lt;link</span><span class="mtk1"> </span><span class="mtk7">href</span><span class="mtk1">=</span><span class="mtk8">"style.css"</span><span class="mtk1"> </span><span class="mtk7">rel</span><span class="mtk1">=</span><span class="mtk8">"stylesheet"</span><span class="mtk4">&gt;</span></span><br></div></code></pre></pre>
<p class="p__1qg33Igem5pAgn4kPMirjw">
What happens when you press the Run button?
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Take some time to explore and experiment with the code in the
<code class="code__2rdF32qjRVp7mMVBHuPwDS">style.css</code> file.
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

#### Solutions

``` html
```

## SETUP AND SYNTAX

### CSS Anatomy

<p class="p__1qg33Igem5pAgn4kPMirjw">
The diagram on the right shows two different methods, or
<em>syntaxes</em>, for writing CSS code. The first syntax shows CSS
applies as a <em>ruleset</em>, while the second shows it written as an
<em>inline style</em>. Two different methods of writing CSS may seem a
bit intimidating at first, but it’s not as bad as it looks!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/css/anatomy?page_req=catalog">anatomy</a>
of both methods does share common features. Notice how both syntaxes
contain a <em>declaration</em>. Declarations are the core of CSS. They
apply a style to the selected element. Here, the
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/paragraphs?page_req=catalog"><code class="code__2rdF32qjRVp7mMVBHuPwDS">\<p\></code></a>
element has been selected in both syntaxes and will be styled to display
the text in blue.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Understanding that a declaration is used to style a selected element is
key to learning how to style HTML documents with CSS! The terms below
explain each of the labels in the diagram on the right.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<strong>Ruleset Terms:</strong>
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Selector</em>—The beginning of the ruleset used to target the
element that will be styled.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration Block</em>—The code in-between (and including) the curly
braces (<code class="code__2rdF32qjRVp7mMVBHuPwDS">{ }</code>) that
contains the CSS declaration(s).
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration</em>—The group name for a property and value pair that
applies a style to the selected element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Property</em>—The first part of the declaration that signifies what
visual characteristic of the element is to be modified.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Value</em>—The second part of the declaration that signifies the
value of the property.
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<strong>Inline Style Terms:</strong>
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Opening Tag</em>—The start of an
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/elements?page_req=catalog">HTML
element</a>. This is the element that will be styled.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Attribute</em>—The style
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/attributes?page_req=catalog">attribute</a>
is used to add CSS inline styles to an HTML element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration</em>—The group name for a property and value pair that
applies a style to the selected element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Property</em>—The first part of the declaration that signifies what
visual characteristic of the element is to be modified.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Value</em>—The second part of the declaration that signifies the
value of the property.
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Don’t worry about memorizing all of these—you will get acquainted with
them more and more as the course progresses! Feel free to come back and
use this exercise as a reference later on.
</p>

#### Instructions

<p class="p__1qg33Igem5pAgn4kPMirjw">
Study the diagrams to become familiar with the CSS syntax and the new
terms that will be used throughout the course.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the “Next” button when you are ready to write some code!
</p>

#### Solutions

``` html
```

## SETUP AND SYNTAX

### CSS Anatomy

<p class="p__1qg33Igem5pAgn4kPMirjw">
The diagram on the right shows two different methods, or
<em>syntaxes</em>, for writing CSS code. The first syntax shows CSS
applies as a <em>ruleset</em>, while the second shows it written as an
<em>inline style</em>. Two different methods of writing CSS may seem a
bit intimidating at first, but it’s not as bad as it looks!
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
The
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/css/anatomy?page_req=catalog">anatomy</a>
of both methods does share common features. Notice how both syntaxes
contain a <em>declaration</em>. Declarations are the core of CSS. They
apply a style to the selected element. Here, the
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/paragraphs?page_req=catalog"><code class="code__2rdF32qjRVp7mMVBHuPwDS">\<p\></code></a>
element has been selected in both syntaxes and will be styled to display
the text in blue.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Understanding that a declaration is used to style a selected element is
key to learning how to style HTML documents with CSS! The terms below
explain each of the labels in the diagram on the right.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<strong>Ruleset Terms:</strong>
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Selector</em>—The beginning of the ruleset used to target the
element that will be styled.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration Block</em>—The code in-between (and including) the curly
braces (<code class="code__2rdF32qjRVp7mMVBHuPwDS">{ }</code>) that
contains the CSS declaration(s).
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration</em>—The group name for a property and value pair that
applies a style to the selected element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Property</em>—The first part of the declaration that signifies what
visual characteristic of the element is to be modified.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Value</em>—The second part of the declaration that signifies the
value of the property.
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
<strong>Inline Style Terms:</strong>
</p>
<ul class="ul__11icM1EC_0uPj3OY0Skp4r">
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Opening Tag</em>—The start of an
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/elements?page_req=catalog">HTML
element</a>. This is the element that will be styled.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Attribute</em>—The style
<a target="_blank" class="e14vpv2g1 gamut-xro1w8-ResetElement-Anchor-AnchorBase e1bhhzie0" href="https://www.codecademy.com/resources/docs/html/attributes?page_req=catalog">attribute</a>
is used to add CSS inline styles to an HTML element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Declaration</em>—The group name for a property and value pair that
applies a style to the selected element.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Property</em>—The first part of the declaration that signifies what
visual characteristic of the element is to be modified.
</li>
<li class="li__1KqBjwbWA3ze6V0BvXq9Rx">
<em>Value</em>—The second part of the declaration that signifies the
value of the property.
</li>
</ul>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Don’t worry about memorizing all of these—you will get acquainted with
them more and more as the course progresses! Feel free to come back and
use this exercise as a reference later on.
</p>

#### Instructions

<p class="p__1qg33Igem5pAgn4kPMirjw">
Study the diagrams to become familiar with the CSS syntax and the new
terms that will be used throughout the course.
</p>
<p class="p__1qg33Igem5pAgn4kPMirjw">
Click the “Next” button when you are ready to write some code!
</p>

#### Solutions

``` html
```
