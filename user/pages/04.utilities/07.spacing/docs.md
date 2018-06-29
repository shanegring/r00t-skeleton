---
title: Spacing
visible: true
---

Your page content goes here.



Spacing utilities that apply to all breakpoints, from xs to xl, have no breakpoint abbreviation in them. This is because those classes are applied from min-width: 0 and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.

The classes are named using the format {property}{sides}-{size} for xs and {property}{sides}-{breakpoint}-{size} for sm, md, lg, and xl.

Where property is one of:



<p>Spacing utilities that apply to all breakpoints, from <code class="highlighter-rouge">xs</code> to <code class="highlighter-rouge">xl</code>, have no breakpoint abbreviation in them. This is because those classes are applied from <code class="highlighter-rouge">min-width: 0</code> and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.</p>

<p>The classes are named using the format <code class="highlighter-rouge">{property}{sides}-{size}</code> for <code class="highlighter-rouge">xs</code> and <code class="highlighter-rouge">{property}{sides}-{breakpoint}-{size}</code> for <code class="highlighter-rouge">sm</code>, <code class="highlighter-rouge">md</code>, <code class="highlighter-rouge">lg</code>, and <code class="highlighter-rouge">xl</code>.</p>

<p>Where property is one of:</p>

<ul>
  <li><code class="highlighter-rouge">m</code> - for classes that set <code class="highlighter-rouge">margin</code></li>
  <li><code class="highlighter-rouge">p</code> - for classes that set <code class="highlighter-rouge">padding</code></li>
</ul>

<p>Where sides is one of:</p>

<ul>
  <li><code class="highlighter-rouge">t</code> - for classes that set <code class="highlighter-rouge">margin-top</code> or <code class="highlighter-rouge">padding-top</code></li>
  <li><code class="highlighter-rouge">b</code> - for classes that set <code class="highlighter-rouge">margin-bottom</code> or <code class="highlighter-rouge">padding-bottom</code></li>
  <li><code class="highlighter-rouge">l</code> - for classes that set <code class="highlighter-rouge">margin-left</code> or <code class="highlighter-rouge">padding-left</code></li>
  <li><code class="highlighter-rouge">r</code> - for classes that set <code class="highlighter-rouge">margin-right</code> or <code class="highlighter-rouge">padding-right</code></li>
  <li><code class="highlighter-rouge">x</code> - for classes that set both <code class="highlighter-rouge">*-left</code> and <code class="highlighter-rouge">*-right</code></li>
  <li><code class="highlighter-rouge">y</code> - for classes that set both <code class="highlighter-rouge">*-top</code> and <code class="highlighter-rouge">*-bottom</code></li>
  <li>blank - for classes that set a <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> on all 4 sides of the element</li>
</ul>

<p>Where size is one of:</p>

<ul>
  <li><code class="highlighter-rouge">0</code> - for classes that eliminate the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> by setting it to <code class="highlighter-rouge">0</code></li>
  <li><code class="highlighter-rouge">1</code> - (by default) for classes that set the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> to <code class="highlighter-rouge">$spacer * .25</code></li>
  <li><code class="highlighter-rouge">2</code> - (by default) for classes that set the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> to <code class="highlighter-rouge">$spacer * .5</code></li>
  <li><code class="highlighter-rouge">3</code> - (by default) for classes that set the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> to <code class="highlighter-rouge">$spacer</code></li>
  <li><code class="highlighter-rouge">4</code> - (by default) for classes that set the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> to <code class="highlighter-rouge">$spacer * 1.5</code></li>
  <li><code class="highlighter-rouge">5</code> - (by default) for classes that set the <code class="highlighter-rouge">margin</code> or <code class="highlighter-rouge">padding</code> to <code class="highlighter-rouge">$spacer * 3</code></li>
  <li><code class="highlighter-rouge">auto</code> - for classes that set the <code class="highlighter-rouge">margin</code> to auto</li>
</ul>



<h2>Examples</h2>

<figure class="highlight p-3"><pre><code class="language-scss" data-lang="scss"><span class="nc">.mt-0</span> <span class="p">{</span>
  <span class="nl">margin-top</span><span class="p">:</span> <span class="m">0</span> <span class="o">!</span><span class="n">important</span><span class="p">;</span>
<span class="p">}</span>

<span class="nc">.ml-1</span> <span class="p">{</span>
  <span class="nl">margin-left</span><span class="p">:</span> <span class="p">(</span><span class="nv">$spacer</span> <span class="o">*</span> <span class="mi">.25</span><span class="p">)</span> <span class="o">!</span><span class="n">important</span><span class="p">;</span>
<span class="p">}</span>

<span class="nc">.px-2</span> <span class="p">{</span>
  <span class="nl">padding-left</span><span class="p">:</span> <span class="p">(</span><span class="nv">$spacer</span> <span class="o">*</span> <span class="mi">.5</span><span class="p">)</span> <span class="o">!</span><span class="n">important</span><span class="p">;</span>
  <span class="nl">padding-right</span><span class="p">:</span> <span class="p">(</span><span class="nv">$spacer</span> <span class="o">*</span> <span class="mi">.5</span><span class="p">)</span> <span class="o">!</span><span class="n">important</span><span class="p">;</span>
<span class="p">}</span>

<span class="nc">.p-3</span> <span class="p">{</span>
  <span class="nl">padding</span><span class="p">:</span> <span class="nv">$spacer</span> <span class="o">!</span><span class="n">important</span><span class="p">;</span>
<span class="p">}</span></code></pre></figure>




Horizontal centering
Additionally, Bootstrap also includes an .mx-auto class for horizontally centering fixed-width block level content—that is, content that has display: block and a width set—by setting the horizontal margins to auto.



<div class="mx-auto" style="width: 200px; background-color: rgba(86,61,124,.15)">
  Centered element
</div>


<figure class="highlight p-3 mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"mx-auto"</span> <span class="na">style=</span><span class="s">"width: 200px;"</span><span class="nt">&gt;</span>
  Centered element
<span class="nt">&lt;/div&gt;</span></code></pre></figure>