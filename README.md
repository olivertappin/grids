# CSS grid system
Inspired by Harry Roberts' grids: https://github.com/csswizardry/csswizardry-grids

This CSS grid will give you the flexabilty to work with BEM syntax and achieve your required grid system.

Optional classes include:
<code>.grid--gutter-{$gutter}</code>
<code>.grid--flex</code>
<code>.grid--tight</code>
<code>.grid--flush</code>
<code>.{$size}-clearfix</code>

Sizes are made up of three media queries with the prefixes:
l: Large
m: Medium
s: Small

Gutter sizes are available as follows:
5
10
15
20
25
30
35
40
45
50

With the default gutter being 20px

# Example
<pre>
&lt;div class="grid"&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
&lt;/div&gt;
</pre>
