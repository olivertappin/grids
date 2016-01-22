# CSS grid system
Inspired by Harry Roberts' grids: https://github.com/csswizardry/csswizardry-grids

This CSS grid will give you the flexabilty to work with BEM syntax and achieve your required grid system. This is a simplified version of Harry's grid system to get you started without having to understand the full concept or read through pages of documentation to see how it works.

Optional classes include:
<pre>.grid--gutter-{$gutter}</pre>
<pre>.grid--tight</pre>
<pre>.grid--flush</pre>

Sizes (variable example above being <code>$size</code>) are made up of three media queries with the prefixes:<br />
<code>l</code>: Large<br />
<code>m</code>: Medium<br />
<code>s</code>: Small

Gutter sizes (variable example above being <code>$gutter</code>) are available as follows:<br />
<code>20</code>,
<code>40</code>,
<code>60</code>

With the default gutter being <code>20px</code>

# Setup
No setup needed. All the hard work is already done.

# Usage
Simply include the grids.css or _grids.scss file in your head tag or Sass project and you can start using the grid system in your HTML instantly.

The idea of this simple grid system is so you can apply it (and of course, edit it) to meet your needs. It's built to be extremely simple so you can understand how it works and change anything necessary to your requirements.

# Example
<pre>
&lt;div class="grid"&gt;
    &lt;div class="grid__item w-1/4 w-1/2-m w-1/1-s"&gt;&lt;/div&gt;
    &lt;div class="grid__item w-1/4 w-1/2-m w-1/1-s"&gt;&lt;/div&gt;
    &lt;div class="grid__item w-1/4 w-1/2-m w-1/1-s"&gt;&lt;/div&gt;
    &lt;div class="grid__item w-1/4 w-1/2-m w-1/1-s"&gt;&lt;/div&gt;
&lt;/div&gt;
</pre>
