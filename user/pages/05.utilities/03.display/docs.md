---
title: Display
visible: true
---

<h4>Quickly and responsively toggle the display value of components and more with our display utilities. Includes support for some of the more common values, as well as some extras for controlling display when printing.</h4>




<h3>How it works</h3>
<p>Change the value of the display property with our responsive display utility classes. We purposely support only a subset of all possible values for display. Classes can be combined for various effects as you need.</p>

<h3>Notation</h3>
<p>Display utility classes that apply to all breakpoints, from xs to xl, have no breakpoint abbreviation in them. This is because those classes are applied from min-width: 0; and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.</p>



<div class="d-inline p-2 bg-primary text-white">d-inline</div>
<div class="d-inline p-2 bg-dark text-white">d-inline</div>

<div class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-inline p-2 bg-primary text-white"</span><span class="nt">&gt;</span>d-inline<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-inline p-2 bg-dark text-white"</span><span class="nt">&gt;</span>d-inline<span class="nt">&lt;/div&gt;</span></code></pre></div>


<span class="d-block p-2 bg-primary text-white">d-block</span>
<span class="d-block p-2 bg-dark text-white">d-block</span>

<div class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"d-block p-2 bg-primary text-white"</span><span class="nt">&gt;</span>d-block<span class="nt">&lt;/span&gt;</span>
<span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"d-block p-2 bg-dark text-white"</span><span class="nt">&gt;</span>d-block<span class="nt">&lt;/span&gt;</span></code></pre></div>


<h3>Hiding elements</h3>
<p>For faster mobile-friendly development, use responsive display classes for showing and hiding elements by device. Avoid creating entirely different versions of the same site, instead hide element responsively for each screen size.

To hide elements simply use the .d-none class or one of the .d-{sm,md,lg,xl}-none classes for any responsive screen variation.

To show an element only on a given interval of screen sizes you can combine one .d-*-none class with a .d-*-* class, for example .d-none .d-md-block .d-xl-none will hide the element for all screen sizes except on medium and large devices.</p>


<table>
  <thead>
    <tr>
      <th>Screen Size</th>
      <th>Class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Hidden on all</td>
      <td><code class="highlighter-rouge">.d-none</code></td>
    </tr>
    <tr>
      <td>Hidden only on xs</td>
      <td><code class="highlighter-rouge">.d-none .d-sm-block</code></td>
    </tr>
    <tr>
      <td>Hidden only on sm</td>
      <td><code class="highlighter-rouge">.d-sm-none .d-md-block</code></td>
    </tr>
    <tr>
      <td>Hidden only on md</td>
      <td><code class="highlighter-rouge">.d-md-none .d-lg-block</code></td>
    </tr>
    <tr>
      <td>Hidden only on lg</td>
      <td><code class="highlighter-rouge">.d-lg-none .d-xl-block</code></td>
    </tr>
    <tr>
      <td>Hidden only on xl</td>
      <td><code class="highlighter-rouge">.d-xl-none</code></td>
    </tr>
    <tr>
      <td>Visible on all</td>
      <td><code class="highlighter-rouge">.d-block</code></td>
    </tr>
    <tr>
      <td>Visible only on xs</td>
      <td><code class="highlighter-rouge">.d-block .d-sm-none</code></td>
    </tr>
    <tr>
      <td>Visible only on sm</td>
      <td><code class="highlighter-rouge">.d-none .d-sm-block .d-md-none</code></td>
    </tr>
    <tr>
      <td>Visible only on md</td>
      <td><code class="highlighter-rouge">.d-none .d-md-block .d-lg-none</code></td>
    </tr>
    <tr>
      <td>Visible only on lg</td>
      <td><code class="highlighter-rouge">.d-none .d-lg-block .d-xl-none</code></td>
    </tr>
    <tr>
      <td>Visible only on xl</td>
      <td><code class="highlighter-rouge">.d-none .d-xl-block</code></td>
    </tr>
  </tbody>
</table>



<div class="d-lg-none">hide on screens wider than lg</div>
<div class="d-none d-lg-block">hide on screens smaller than lg</div>


<div class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-lg-none"</span><span class="nt">&gt;</span>hide on screens wider than lg<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-none d-lg-block"</span><span class="nt">&gt;</span>hide on screens smaller than lg<span class="nt">&lt;/div&gt;</span></code></pre></div>



<h4>Display in print</h4>
<p>Change the <code class="highlighter-rouge">display</code> value of elements when printing with our print display utility classes. Includes support for the same <code class="highlighter-rouge">display</code> values as our responsive <code class="highlighter-rouge">.d-*</code> utilities.</p>

<ul>
  <li><code class="highlighter-rouge">.d-print-none</code></li>
  <li><code class="highlighter-rouge">.d-print-inline</code></li>
  <li><code class="highlighter-rouge">.d-print-inline-block</code></li>
  <li><code class="highlighter-rouge">.d-print-block</code></li>
  <li><code class="highlighter-rouge">.d-print-table</code></li>
  <li><code class="highlighter-rouge">.d-print-table-row</code></li>
  <li><code class="highlighter-rouge">.d-print-table-cell</code></li>
  <li><code class="highlighter-rouge">.d-print-flex</code></li>
  <li><code class="highlighter-rouge">.d-print-inline-flex</code></li>
</ul>

<p>The print and display classes can be combined.</p>

<div class="d-print-none">Screen Only (Hide on print only)</div>
<div class="d-none d-print-block">Print Only (Hide on screen only)</div>
<div class="d-none d-lg-block d-print-block">Hide up to large on screen, but always show on print</div>

<div class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-print-none"</span><span class="nt">&gt;</span>Screen Only (Hide on print only)<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-none d-print-block"</span><span class="nt">&gt;</span>Print Only (Hide on screen only)<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-none d-lg-block d-print-block"</span><span class="nt">&gt;</span>Hide up to large on screen, but always show on print<span class="nt">&lt;/div&gt;</span></code></pre></div>
