---
title: Fonts
visible: true
taxonomy:
    category: docs
process:
	twig: true
---

<h4 class="mt-4">Museo Slab</h4>
<div class="highlight mt-4 p-3">
<pre><code>
<span class="nt">h1</span>
<span class="s">{font-family: "museo-slab",sans-serif; }</span>
</code></pre>
</div>

<h4 class="mt-4">Museo Sans</h4>
<div class="highlight mt-4 p-3">
<pre><code>
<span class="nt">h2, h3, h4, h5, h6, th, td, select, option, legend, fieldset, button, optgroup, body, p, input, textarea  {</span>
<span class="s">{font-family: "museo-sans",sans-serif; }</span>
</code></pre>
</div>


<hr />

<h1>h1. Bootstrap heading</h1>
<h2>h2. Bootstrap heading</h2>
<h3>h3. Bootstrap heading</h3>
<h4>h4. Bootstrap heading</h4>
<h5>h5. Bootstrap heading</h5>
<h6>h6. Bootstrap heading</h6>


<figure class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;h1&gt;</span>h1. Bootstrap heading<span class="nt">&lt;/h1&gt;</span>
<span class="nt">&lt;h2&gt;</span>h2. Bootstrap heading<span class="nt">&lt;/h2&gt;</span>
<span class="nt">&lt;h3&gt;</span>h3. Bootstrap heading<span class="nt">&lt;/h3&gt;</span>
<span class="nt">&lt;h4&gt;</span>h4. Bootstrap heading<span class="nt">&lt;/h4&gt;</span>
<span class="nt">&lt;h5&gt;</span>h5. Bootstrap heading<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;h6&gt;</span>h6. Bootstrap heading<span class="nt">&lt;/h6&gt;</span>
</code></pre>
</figure>

<hr />

<h4 class="mt-4">Display</h4>
<h1 class="display-1 mt-4">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>

<figure class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;h1</span> <span class="na">class=</span><span class="s">"display-1"</span><span class="nt">&gt;</span>Display 1<span class="nt">&lt;/h1&gt;</span>
<span class="nt">&lt;h1</span> <span class="na">class=</span><span class="s">"display-2"</span><span class="nt">&gt;</span>Display 2<span class="nt">&lt;/h1&gt;</span>
<span class="nt">&lt;h1</span> <span class="na">class=</span><span class="s">"display-3"</span><span class="nt">&gt;</span>Display 3<span class="nt">&lt;/h1&gt;</span>
<span class="nt">&lt;h1</span> <span class="na">class=</span><span class="s">"display-4"</span><span class="nt">&gt;</span>Display 4<span class="nt">&lt;/h1&gt;</span>
</code></pre>
</figure>

<hr />

<h4 class="mt-4">Text Elements</h4>
<p class="mt-4">You can use the mark tag to <mark>highlight</mark> text.</p>
<p><del>This line of text is meant to be treated as deleted text.</del></p>
<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
<p><u>This line of text will render as underlined</u></p>
<p><small>This line of text is meant to be treated as fine print.</small></p>
<p><strong>This line rendered as bold text.</strong></p>
<p><em>This line rendered as italicized text.</em></p>

<div class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;p&gt;</span>You can use the mark tag to <span class="nt">&lt;mark&gt;</span>highlight<span class="nt">&lt;/mark&gt;</span> text.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;del&gt;</span>This line of text is meant to be treated as deleted text.<span class="nt">&lt;/del&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;s&gt;</span>This line of text is meant to be treated as no longer accurate.<span class="nt">&lt;/s&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;ins&gt;</span>This line of text is meant to be treated as an addition to the document.<span class="nt">&lt;/ins&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;u&gt;</span>This line of text will render as underlined<span class="nt">&lt;/u&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;small&gt;</span>This line of text is meant to be treated as fine print.<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;strong&gt;</span>This line rendered as bold text.<span class="nt">&lt;/strong&gt;&lt;/p&gt;</span>
<span class="nt">&lt;p&gt;&lt;em&gt;</span>This line rendered as italicized text.<span class="nt">&lt;/em&gt;&lt;/p&gt;</span>
</code></pre>
</div>

<hr />

<h4 class="mt-4">Quotes</h4>
<blockquote class="blockquote">
<p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
<footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>

<blockquote class="blockquote blockquote-reverse">
<p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
<footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>

<div class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"mb-0"</span><span class="nt">&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
</code></pre>

<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote blockquote-reverse"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"mb-0"</span><span class="nt">&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
</code></pre>

</div>



<hr />


<h4 class="mt-4">Lists</h4>
<ul class="list-unstyled">
<li>Lorem ipsum dolor sit amet</li>
<li>Consectetur adipiscing elit</li>
<li>Integer molestie lorem at massa</li>
<li>Facilisis in pretium nisl aliquet</li>
<li>Nulla volutpat aliquam velit
<ul>
  <li>Phasellus iaculis neque</li>
  <li>Purus sodales ultricies</li>
  <li>Vestibulum laoreet porttitor sem</li>
  <li>Ac tristique libero volutpat at</li>
</ul>
</li>
<li>Faucibus porta lacus fringilla vel</li>
<li>Aenean sit amet erat nunc</li>
<li>Eget porttitor lorem</li>
</ul>

<div class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-unstyled"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li&gt;</span>Lorem ipsum dolor sit amet<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Consectetur adipiscing elit<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Integer molestie lorem at massa<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Facilisis in pretium nisl aliquet<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Nulla volutpat aliquam velit
<span class="nt">&lt;ul&gt;</span>
<span class="nt">&lt;li&gt;</span>Phasellus iaculis neque<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Purus sodales ultricies<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Vestibulum laoreet porttitor sem<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Ac tristique libero volutpat at<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Faucibus porta lacus fringilla vel<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Aenean sit amet erat nunc<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li&gt;</span>Eget porttitor lorem<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
</code></pre>
</div>


<hr/>

<h4 class="mt-4">Code</h4>

<p>For example, <code>&lt;section&gt;</code> should be wrapped as inline.</p>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
For example, <span class="nt">&lt;code&gt;</span><span class="ni">&amp;lt;</span>section<span class="ni">&amp;gt;</span><span class="nt">&lt;/code&gt;</span> should be wrapped as inline.
</code></pre>
</div>


</div>
</div>
</div>
</div>
</div>