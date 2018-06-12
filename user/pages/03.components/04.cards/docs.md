---
title: Cards
visible: true
taxonomy:
    category: docs
process:
    twig: true
---



<div class="card mt-4" style="width: 20rem;">
	<img class="card-img-top" src="http://via.placeholder.com/318x180" alt="Card image cap">
	<div class="card-block">
	<h4 class="card-title">Card title</h4>
	<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
	<a href="#" class="btn btn-primary">Go somewhere</a>
	</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 20rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h4</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h4&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>Some quick example text to build on the card title and make up the bulk of the card's content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>



<h3>Blocks</h3>
<div class="card">
<div class="card-block">
This is some text within a card block.
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
This is some text within a card block.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>


<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Titles, text, and links</h3>
<div class="card" style="width: 18rem;">
<div class="card-body">
<h5 class="card-title">Card title</h5>
<h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
<a href="#" class="card-link">Card link</a>
<a href="#" class="card-link">Another link</a>
</div>
</div>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;h6</span> <span class="na">class=</span><span class="s">"card-subtitle mb-2 text-muted"</span><span class="nt">&gt;</span>Card subtitle<span class="nt">&lt;/h6&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>Some quick example text to build on the card title and make up the bulk of the card's content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"card-link"</span><span class="nt">&gt;</span>Card link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"card-link"</span><span class="nt">&gt;</span>Another link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>

<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Images</h3>

<div class="card" style="width: 18rem;">
<img class="card-img-top" src="http://via.placeholder.com/180x100" alt="Card image cap">
<div class="card-block">
<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>Some quick example text to build on the card title and make up the bulk of the card's content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>


</div>
</div>


<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>List groups</h3>

<div class="card">
<ul class="list-group list-group-flush">
<li class="list-group-item">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group list-group-flush"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>


</div>
</div>

<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Kitchen Sink</h3>

<div class="card" style="width: 20rem;">
<img class="card-img-top" src="http://via.placeholder.com/350x150" alt="Card image cap">
<div class="card-block">
<h4 class="card-title">Card title</h4>
<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
</div>
<ul class="list-group list-group-flush">
<li class="list-group-item">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>
<div class="card-block">
<a href="#" class="card-link">Card link</a>
<a href="#" class="card-link">Another link</a>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>Some quick example text to build on the card title and make up the bulk of the card's content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group list-group-flush"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"card-link"</span><span class="nt">&gt;</span>Card link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"card-link"</span><span class="nt">&gt;</span>Another link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>


<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Header and footer</h3>

<div class="card">
<div class="card-header">
Featured
</div>
<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span><span class="nt">&gt;</span>
Featured
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>



<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Qoute</h3>

<div class="card">
<div class="card-header">
Quote
</div>
<div class="card-block">
<blockquote class="card-blockquote">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
<footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span><span class="nt">&gt;</span>
Quote
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>


<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Center</h3>

<div class="card text-center">
<div class="card-header">
Featured
</div>
<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
<div class="card-footer text-muted">
2 days ago
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span><span class="nt">&gt;</span>
Featured
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer text-muted"</span><span class="nt">&gt;</span>
2 days ago
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>




<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Sizing</h3>

<div class="row">
<div class="col-sm-6">
<div class="card">
<div class="card-block">
  <h3 class="card-title">Special title treatment</h3>
  <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
  <a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>
</div>
<div class="col-sm-6">
<div class="card">
<div class="card-block">
  <h3 class="card-title">Special title treatment</h3>
  <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
  <a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"row"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"col-sm-6"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"col-sm-6"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>





<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Sizing</h3>

<div class="card w-75">
<div class="card-block">
<h3 class="card-title">Card title</h3>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Button</a>
</div>
</div>

<div class="card w-50">
<div class="card-block">
<h3 class="card-title">Card title</h3>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Button</a>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card w-75"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Button<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>

<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card w-50"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Button<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>




<div class="row">
<div class="col-12" style="padding-top: 30px">
<h3>Text alignment</h3>

<div class="card" style="width: 20rem;">
<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>

<div class="card text-center" style="width: 20rem;">
<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>

<div class="card text-right" style="width: 20rem;">
<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>

<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-center"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>

<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-right"</span> <span class="na">style=</span><span class="s">"width: 18rem;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>

</div>
</div>








<h3>Navigation</h3>
<!--
<div class="card text-center">
<div class="card-header">
<ul class="nav nav-tabs card-header-tabs">
<li class="nav-item">
  <a class="nav-link active" href="#">Active</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#">Link</a>
</li>
<li class="nav-item">
  <a class="nav-link disabled" href="#">Disabled</a>
</li>
</ul>
</div>
</div>
-->

<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span><span class="nt">&gt;</span>
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"nav nav-tabs card-header-tabs"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link active"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Active<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link disabled"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Disabled<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h4</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h4&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Navigation Pills</h3>
<!--
<div class="card text-center">
<div class="card-header">
<ul class="nav nav-pills card-header-pills">
<li class="nav-item">
  <a class="nav-link active" href="#">Active</a>
</li>
<li class="nav-item">
  <a class="nav-link" href="#">Link</a>
</li>
<li class="nav-item">
  <a class="nav-link disabled" href="#">Disabled</a>
</li>
</ul>
</div>
</div>
-->

<div class="card-block">
<h4 class="card-title">Special title treatment</h4>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>


<div class="highlight">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span><span class="nt">&gt;</span>
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"nav nav-pills card-header-pills"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link active"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Active<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Link<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"nav-item"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"nav-link disabled"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Disabled<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h4</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h4&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Image caps</h3>

<div class="card mb-3">
<img class="card-img-top" src="http://via.placeholder.com/769x180" alt="Card image cap">
<div class="card-block">
<h4 class="card-title">Card title</h4>
<p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
<p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card mb-3"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>







<h3>Image overlays</h3>


<div class="card card-inverse">
<img class="card-img" src="http://via.placeholder.com/769x270" alt="Card image">
<div class="card-img-overlay">
<h4 class="card-title">Card title</h4>
<p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
<p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card bg-dark text-white"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-img-overlay"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Inverted text</h3>

<div class="card card-inverse" style="background-color: #333; border-color: #333;">
<div class="card-block">
<h3 class="card-title">Special title treatment</h3>
<p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
<a href="#" class="btn btn-primary">Go somewhere</a>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse"</span> <span class="na">style=</span><span class="s">"background-color: #333; border-color: #333;"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h3</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Special title treatment<span class="nt">&lt;/h3&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>With supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span><span class="nt">&gt;</span>Go somewhere<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>




<h3>Background variants</h3>

<div class="card card-inverse card-primary mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-inverse card-success mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-inverse card-info mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-inverse card-warning mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-inverse card-danger text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse card-primary mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse card-success mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse card-info mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse card-warning mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-inverse card-danger text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>






<h3>Outline Cards</h3>

<div class="card card-outline-primary mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-outline-secondary mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-outline-success mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-outline-info mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-outline-warning mb-3 text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>
<div class="card card-outline-danger text-center">
<div class="card-block">
<blockquote class="card-blockquote">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-primary mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-secondary mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-success mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-info mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-warning mb-3 text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-outline-danger text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-block"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"card-blockquote"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer&gt;</span>Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Card groups</h3>

<div class="card-group">
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Card groups with footer</h3>

<div class="card-group">
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/256x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>




<h3>Card deck</h3>

<div class="card-deck">
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x200" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x200" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x200" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
</div>
</div>
</div>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-deck"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>





<h3>Card deck with footers</h3>

<div class="card-deck">
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
<div class="card">
<img class="card-img-top" src="http://via.placeholder.com/235x180" alt="Card image cap">
<div class="card-block">
  <h4 class="card-title">Card title</h4>
  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
</div>
<div class="card-footer">
  <small class="text-muted">Last updated 3 mins ago</small>
</div>
</div>
</div>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-deck"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>


<h3>Card columns</h3>

<div class="card-columns">
<div class="card">
  <img class="card-img-top img-fluid" src="http://via.placeholder.com/242x160" alt="Card image cap">
  <div class="card-block">
    <h4 class="card-title">Card title that wraps to a new line</h4>
    <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
  </div>
</div>
<div class="card p-3">
  <blockquote class="card-block card-blockquote">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
    <footer>
      <small class="text-muted">
        Someone famous in <cite title="Source Title">Source Title</cite>
      </small>
    </footer>
  </blockquote>
</div>
<div class="card">
  <img class="card-img-top img-fluid" src="http://via.placeholder.com/242x160" alt="Card image cap">
  <div class="card-block">
    <h4 class="card-title">Card title</h4>
    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
  </div>
</div>
<div class="card card-inverse card-primary p-3 text-center">
  <blockquote class="card-blockquote">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat.</p>
    <footer>
      <small>
        Someone famous in <cite title="Source Title">Source Title</cite>
      </small>
    </footer>
  </blockquote>
</div>
<div class="card text-center">
  <div class="card-block">
    <h4 class="card-title">Card title</h4>
    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
  </div>
</div>
<div class="card">
  <img class="card-img img-fluid" src="http://via.placeholder.com/242x260" alt="Card image">
</div>
<div class="card p-3 text-right">
  <blockquote class="card-blockquote">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
    <footer>
      <small class="text-muted">
        Someone famous in <cite title="Source Title">Source Title</cite>
      </small>
    </footer>
  </blockquote>
</div>
<div class="card">
  <div class="card-block">
    <h4 class="card-title">Card title</h4>
    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
  </div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-columns"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title that wraps to a new line<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card p-3"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote mb-0 card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>
Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;</span>
<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img-top"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image cap"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card bg-primary text-white text-center p-3"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small&gt;</span>
Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;</span>
<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card text-center"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This card has supporting text below as a natural lead-in to additional content.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;img</span> <span class="na">class=</span><span class="s">"card-img"</span> <span class="na">src=</span><span class="s">"..."</span> <span class="na">alt=</span><span class="s">"Card image"</span><span class="nt">&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card p-3 text-right"</span><span class="nt">&gt;</span>
<span class="nt">&lt;blockquote</span> <span class="na">class=</span><span class="s">"blockquote mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;p&gt;</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;footer</span> <span class="na">class=</span><span class="s">"blockquote-footer"</span><span class="nt">&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>
Someone famous in <span class="nt">&lt;cite</span> <span class="na">title=</span><span class="s">"Source Title"</span><span class="nt">&gt;</span>Source Title<span class="nt">&lt;/cite&gt;</span>
<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/footer&gt;</span>
<span class="nt">&lt;/blockquote&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"card-title"</span><span class="nt">&gt;</span>Card title<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;</span>This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"card-text"</span><span class="nt">&gt;&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Last updated 3 mins ago<span class="nt">&lt;/small&gt;&lt;/p&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>