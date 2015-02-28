# CSS grid system
Inspired by Harry Roberts' grids: https://github.com/csswizardry/csswizardry-grids

This CSS grid will give you the flexabilty to work with BEM syntax and achieve your required grid system.

Optional classes include:
<pre>.grid--gutter-{$gutter}</pre>
<pre>.grid--flex</pre>
<pre>.grid--tight</pre>
<pre>.grid--flush</pre>
<pre>.{$size}-clearfix</pre>

Sizes (variable example above being <code>$size</code>) are made up of three media queries with the prefixes:<br />
<code>l</code>: Large<br />
<code>m</code>: Medium<br />
<code>s</code>: Small

Gutter sizes (variable example above being <code>$gutter</code>) are available as follows:<br />
<code>5</code>, 
<code>10</code>, 
<code>15</code>, 
<code>20</code>, 
<code>25</code>, 
<code>30</code>, 
<code>35</code>, 
<code>40</code>, 
<code>45</code>, 
<code>50</code>

With the default gutter being <code>20px</code>

# Example
<pre>
&lt;div class="grid"&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
    &lt;div class="grid__item one-quarter l-one-quarter m-one-half s-full"&gt;&lt;/div&gt;
&lt;/div&gt;
</pre>
