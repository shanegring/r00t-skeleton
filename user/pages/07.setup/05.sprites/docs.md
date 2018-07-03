---
title: 'Sprites'
visible: true
---

<h1>SVG Sprites</h1>


<p>is a Gulp plugin wrapping around svg-sprite which takes a bunch of SVG files, optimizes them and bakes them into SVG sprites of several types:</p>
<ul>
  <li>Traditional CSS sprites for use as background images,</li>
  <li>CSS sprites with pre-defined view elements, useful for foreground images as well,</li>
  <li>inline sprites using the defs element,</li>
  <li>inline sprites using the symbol element</li>
  <li>and SVG stacks.</li>
</ul>

<br />

<h5 style="margin-top: 50px">First, install <code>gulp-svg-sprite</code> as a development dependency:</h5>
<div class="highlight mt-4 p-3">
<h5><code>npm install --save-dev gulp-svg-sprite</code></h5>
</div>


<h5 style="margin-top: 50px">Then, add it to your <code>gulpfile.js</code>:</h5>
<div class="highlight mt-4 p-3">
<pre><code>
<span class="pl-k">var</span> gulp       <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>gulp<span class="pl-pds">'</span></span>),
svgSprite       <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>gulp-svg-sprite<span class="pl-pds">'</span></span>);

<span class="pl-smi">gulp</span>.<span class="pl-en">src</span>(<span class="pl-s"><span class="pl-pds">'</span>path/to/assets/*.svg<span class="pl-pds">'</span></span>)
  .<span class="pl-en">pipe</span>(<span class="pl-en">svgSprite</span>( <span class="pl-c"><span class="pl-c">/*</span> ... Insert your configuration here ... <span class="pl-c">*/</span></span> ))
  .<span class="pl-en">pipe</span>(<span class="pl-smi">gulp</span>.<span class="pl-en">dest</span>(<span class="pl-s"><span class="pl-pds">'</span>out<span class="pl-pds">'</span></span>));
</code></pre>
</div>


<button class="btn btn-primary mt-4" href="https://github.com/jkphl/gulp-svg-sprite">More documentation</button>
      