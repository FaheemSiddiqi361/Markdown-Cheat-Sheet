# Markdown-Cheat-Sheet
I have a completed a course for the Markdown language for VS code. the file shows that how to use this amazing langauge while writing your code.
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-type" content="text/html;charset=UTF-8">



<h1 id="1-heading">1-Heading</h1>
<p>How to give headings in markdown files?</p>
<h1 id="heading">Heading</h1>
<h2 id="heading-1">Heading 1</h2>
<h3 id="heading-3">Heading 3</h3>
<h4 id="heading-4">Heading 4</h4>
<h6 id="so-on">so on</h6>
<h1 id="2-block-of-words">2-Block of Words</h1>
<blockquote>
<p>This is a normal text in markdown</p>
<p>This  is another line of the same paragraph.</p>
</blockquote>
<h1 id="3-line-breaks">3-Line Breaks</h1>
<p>This is 40 days long course for python AKA Python ka chila with Dr Ammar.<br>
so that we could learn pyhn in desi style.</p>
<h1 id="4-combine-two-things">4-Combine Two Things</h1>
<p>Block of Words and Headings</p>
<blockquote>
<h2 id="heading-2">Heading 2</h2>
</blockquote>
<h1 id="5-face-of-text">5-Face of Text</h1>
<h3 id="using-asteric">Using Asteric (*)</h3>
<p><strong>Bold</strong></p>
<p><em>Italic</em></p>
<p><em><strong>Bold and Italic</strong></em></p>
<h3 id="using-underscore">Using Underscore(_)</h3>
<p><strong>Bold</strong></p>
<p><em>Italic</em></p>
<p><em><strong>Bold and Italic</strong></em></p>
<h1 id="6-bullet-points--lists">6-Bullet Points / Lists</h1>
<p>We use Dash(-) for making bullet points and use Tabs for making point within a point. e.g</p>
<p>What we have covered till now in Python:</p>
<ul>
<li>Day-1</li>
<li>Day 2</li>
<li>Day 3</li>
<li>Day 4</li>
<li>Day 5
<ul>
<li>Day 5a</li>
<li>Day 5b</li>
<li>Day 5c</li>
</ul>
</li>
<li>Day 6</li>
<li>Day 7</li>
</ul>
<blockquote>
<p>Also we can use * and + for the same purpose</p>
</blockquote>
<ul>
<li>One</li>
<li>Two</li>
</ul>
<ul>
<li>Three</li>
<li>Four</li>
</ul>
<blockquote>
<p>Numbering of Lists
(1 plus point and space)</p>
</blockquote>
<ol>
<li>Day 1</li>
<li>Day 2</li>
<li>Day 3
<ol>
<li>Day 3.1</li>
<li>Day 3.2</li>
</ol>
</li>
</ol>
<h1 id="7--line-breaks-or-page-breaks">7- Line Breaks or Page Breaks</h1>
<p>This is a Page</p>
<hr>
<hr>
<hr>
<p>This is a Page</p>
<h1 id="8--links-and-hyperlinks">8- Links and Hyperlinks</h1>
<h2 id="links">Links</h2>
<p>use Title in [] and the link in () e.g</p>
<p><a href="Link">Title</a></p>
<p><a href="https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/">Python Ka Chilla</a></p>
<h2 id="hyperlinks">Hyperlinks</h2>
<p>use &lt;&gt; and paste link in between. e.g</p>
<p><a href="https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/">https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/</a></p>
<h2 id="key-links">Key links</h2>
<p>The complete list is <a href="https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/">here</a>.</p>
<blockquote>
<p>To comment out in Markdown:</p>
</blockquote>
<!-- This is a commented out line in Markdown -->
<h1 id="9-online-picture">9-Online Picture</h1>
<p><img src="http://codanics.com/wp-content/uploads/2023/09/cropped-250x150-logo.png.webp" alt="Codanics"></p>
<p><strong>QR Code</strong></p>
<p><img src="fb.png" alt="QR"></p>
<h1 id="10-adding-code-or-code-block">10-Adding code or code Block</h1>
<p>we use (`) for this purpose</p>
<p>To print a string use <code>print(&quot;Codanics&quot;)</code></p>
<p>If we want a block of code then use three of (`)</p>
<pre class="hljs"><code><div>print(&quot;Hello Sir&quot;)
</div></code></pre>
<pre class="hljs"><code><div>x = 6
y = 9
z = x*y
print(z)
</div></code></pre>
<blockquote>
<p>Colors are changes when we use the name of the language</p>
</blockquote>
<pre class="hljs"><code><div>x = <span class="hljs-number">6</span>
y = <span class="hljs-number">9</span>
z = x*y
print(z)
</div></code></pre>
<pre class="hljs"><code><div>x = <span class="hljs-number">6</span>
y = <span class="hljs-number">9</span>
z = x*y
print(z)
</div></code></pre>
<pre class="hljs"><code><div>x = <span class="hljs-number">6</span>
y = <span class="hljs-number">9</span>
z = x*y
<span class="hljs-built_in">print</span>(z)
</div></code></pre>
<h1 id="11--adding-tables">11- Adding Tables</h1>
<p><strong>use pipe (|) for this purpose</strong></p>
<table>
<thead>
<tr>
<th>Specie</th>
<th>petal_length</th>
<th>petal_width</th>
</tr>
</thead>
<tbody>
<tr>
<td>Gulab</td>
<td>12.4</td>
<td>42.8</td>
</tr>
<tr>
<td>Motiya</td>
<td>32.4</td>
<td>62.8</td>
</tr>
<tr>
<td>Gobhi</td>
<td>16.4</td>
<td>12.8</td>
</tr>
</tbody>
</table>
<blockquote>
<p>for right and left align we use (<img class="emoji" alt="smiley" src="data:image/png;base64,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" /> before or the after dashes.use both for middle align</p>
</blockquote>
<table>
<thead>
<tr>
<th style="text-align:center">Specie</th>
<th style="text-align:left">petal_length</th>
<th style="text-align:right">petal_width</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Gulab</td>
<td style="text-align:left">12.4</td>
<td style="text-align:right">42.8</td>
</tr>
<tr>
<td style="text-align:center">Motiya</td>
<td style="text-align:left">32.4</td>
<td style="text-align:right">62.8</td>
</tr>
<tr>
<td style="text-align:center">Gobhi</td>
<td style="text-align:left">16.4</td>
<td style="text-align:right">12.8</td>
</tr>
</tbody>
</table>
<h1 id="12--cotents">12- Cotents</h1>
<p><a href="#1-heading">1- Headings</a><br>
<a href="#2-block-of-words">2- Block of words / Citations</a><br>
<a href="#3-line-breaks">3- Line breaks</a><br>
<a href="#4-combine-two-things">4- Combine two things</a><br>
<a href="#5-face-of-text">5- Face of text</a><br>
<a href="#6-bullet-points--lists">6- Bulletpints / lists</a><br>
<a href="#7--line-breaks-or-page-breaks">7- Line breaks or Page breaks</a><br>
<a href="#8--links-and-hyperlinks">8- Links and Hyperlink</a><br>
<a href="#9-online-picture">9- Online Picture / QR code</a><br>
<a href="#10-adding-code-or-code-block">10- Adding code or code blocks</a><br>
<a href="#11--adding-tables">11- Adding Tables</a><br>
<a href="#12--cotents">12- Cotents</a><br>
<a href="#13--adding-extensions">13- Extensions</a></p>
<h1 id="13--adding-extensions">13- Adding extensions</h1>
<p>markdown all in one extension</p>

</body>
</html>
