---
title: 'Tool Tip'
visible: true
taxonomy:
    category: docs
process:
    twig: true
---

<p>Documentation and examples for adding custom Bootstrap tooltips with CSS and JavaScript using CSS3 for animations and data-attributes for local title storage.</p>


<button type="button" class="btn btn-secondary" data-toggle="tooltip" data-placement="top" title="Tooltip on top">
  Tooltip on top
</button>
<button type="button" class="btn btn-secondary" data-toggle="tooltip" data-placement="right" title="Tooltip on right">
  Tooltip on right
</button>
<button type="button" class="btn btn-secondary" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">
  Tooltip on bottom
</button>
<button type="button" class="btn btn-secondary" data-toggle="tooltip" data-placement="left" title="Tooltip on left">
  Tooltip on left
</button>

<button type="button" class="btn btn-secondary" data-toggle="tooltip" data-html="true" title="<em>Tooltip</em> <u>with</u> <b>HTML</b>">
  Tooltip with HTML
</button>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;button</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">class=</span><span class="s">"btn btn-secondary"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">data-placement=</span><span class="s">"top"</span> <span class="na">title=</span><span class="s">"Tooltip on top"</span><span class="nt">&gt;</span>
  Tooltip on top
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">class=</span><span class="s">"btn btn-secondary"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">data-placement=</span><span class="s">"right"</span> <span class="na">title=</span><span class="s">"Tooltip on right"</span><span class="nt">&gt;</span>
  Tooltip on right
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">class=</span><span class="s">"btn btn-secondary"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">data-placement=</span><span class="s">"bottom"</span> <span class="na">title=</span><span class="s">"Tooltip on bottom"</span><span class="nt">&gt;</span>
  Tooltip on bottom
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">class=</span><span class="s">"btn btn-secondary"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">data-placement=</span><span class="s">"left"</span> <span class="na">title=</span><span class="s">"Tooltip on left"</span><span class="nt">&gt;</span>
  Tooltip on left
<span class="nt">&lt;/button&gt;</span></code></pre></figure>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;button</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">class=</span><span class="s">"btn btn-secondary"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">data-html=</span><span class="s">"true"</span> <span class="na">title=</span><span class="s">"&lt;em&gt;Tooltip&lt;/em&gt; &lt;u&gt;with&lt;/u&gt; &lt;b&gt;HTML&lt;/b&gt;"</span><span class="nt">&gt;</span>
  Tooltip with HTML
<span class="nt">&lt;/button&gt;</span></code></pre></figure>



<h3>Disabled elements</h3>

<span class="d-inline-block" tabindex="0" data-toggle="tooltip" title="Disabled tooltip">
  <button class="btn btn-primary" style="pointer-events: none;" type="button" disabled>Disabled button</button>
</span>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"d-inline-block"</span> <span class="na">tabindex=</span><span class="s">"0"</span> <span class="na">data-toggle=</span><span class="s">"tooltip"</span> <span class="na">title=</span><span class="s">"Disabled tooltip"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">style=</span><span class="s">"pointer-events: none;"</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">disabled</span><span class="nt">&gt;</span>Disabled button<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/span&gt;</span></code></pre></figure>






