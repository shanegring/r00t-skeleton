---
title: 'List groups'
visible: true
taxonomy:
    category: docs
process:
    twig: true
---

<ul class="list-group">
<li class="list-group-item">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Morbi leo risus</li>
<li class="list-group-item">Porta ac consectetur ac</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>


<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Morbi leo risus<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Porta ac consectetur ac<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span>
</code></pre>
</div>


<hr />

<h4>Active Items</h4>


<ul class="list-group">
<li class="list-group-item active">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Morbi leo risus</li>
<li class="list-group-item">Porta ac consectetur ac</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item active"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Morbi leo risus<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Porta ac consectetur ac<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span></code></pre></div>

<hr />

<h4>Active Items</h4>


<ul class="list-group">
<li class="list-group-item disabled">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Morbi leo risus</li>
<li class="list-group-item">Porta ac consectetur ac</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item disabled"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Morbi leo risus<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Porta ac consectetur ac<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span></code></pre></div>


<hr />

<h4>Flush</h4>

<ul class="list-group list-group-flush">
<li class="list-group-item">Cras justo odio</li>
<li class="list-group-item">Dapibus ac facilisis in</li>
<li class="list-group-item">Morbi leo risus</li>
<li class="list-group-item">Porta ac consectetur ac</li>
<li class="list-group-item">Vestibulum at eros</li>
</ul>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group list-group-flush"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Cras justo odio<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Morbi leo risus<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Porta ac consectetur ac<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Vestibulum at eros<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span></code></pre></div>

<hr />

<ul class="list-group">
<li class="list-group-item">Dapibus ac facilisis in</li>


<li class="list-group-item list-group-item-primary">This is a primary list group item</li>
<li class="list-group-item list-group-item-secondary">This is a secondary list group item</li>
<li class="list-group-item list-group-item-success">This is a success list group item</li>
<li class="list-group-item list-group-item-danger">This is a danger list group item</li>
<li class="list-group-item list-group-item-warning">This is a warning list group item</li>
<li class="list-group-item list-group-item-info">This is a info list group item</li>
<li class="list-group-item list-group-item-light">This is a light list group item</li>
<li class="list-group-item list-group-item-dark">This is a dark list group item</li>
</ul>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item"</span><span class="nt">&gt;</span>Dapibus ac facilisis in<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-primary"</span><span class="nt">&gt;</span>This is a primary list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-secondary"</span><span class="nt">&gt;</span>This is a secondary list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-success"</span><span class="nt">&gt;</span>This is a success list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-danger"</span><span class="nt">&gt;</span>This is a danger list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-warning"</span><span class="nt">&gt;</span>This is a warning list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-info"</span><span class="nt">&gt;</span>This is a info list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-light"</span><span class="nt">&gt;</span>This is a light list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-dark"</span><span class="nt">&gt;</span>This is a dark list group item<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span></code></pre></div>

<hr />

<ul class="list-group">
<li class="list-group-item d-flex justify-content-between align-items-center">
Cras justo odio
<span class="badge badge-primary badge-pill">14</span>
</li>
<li class="list-group-item d-flex justify-content-between align-items-center">
Dapibus ac facilisis in
<span class="badge badge-primary badge-pill">2</span>
</li>
<li class="list-group-item d-flex justify-content-between align-items-center">
Morbi leo risus
<span class="badge badge-primary badge-pill">1</span>
</li>
</ul>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item d-flex justify-content-between align-items-center"</span><span class="nt">&gt;</span>
Cras justo odio
<span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"badge badge-primary badge-pill"</span><span class="nt">&gt;</span>14<span class="nt">&lt;/span&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item d-flex justify-content-between align-items-center"</span><span class="nt">&gt;</span>
Dapibus ac facilisis in
<span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"badge badge-primary badge-pill"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/span&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"list-group-item d-flex justify-content-between align-items-center"</span><span class="nt">&gt;</span>
Morbi leo risus
<span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"badge badge-primary badge-pill"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/span&gt;</span>
<span class="nt">&lt;/li&gt;</span>
<span class="nt">&lt;/ul&gt;</span></code></pre></div>

<hr />

<h4>Custom content</h4>

<div class="list-group" style="max-width: 400px">
<a href="#" class="list-group-item list-group-item-action flex-column align-items-start active">
<div class="d-flex w-100 justify-content-between">
<h5 class="mb-1">List group item heading</h5>
<small>3 days ago</small>
</div>
<p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
<small>Donec id elit non mi porta.</small>
</a>
<a href="#" class="list-group-item list-group-item-action flex-column align-items-start">
<div class="d-flex w-100 justify-content-between">
<h5 class="mb-1">List group item heading</h5>
<small class="text-muted">3 days ago</small>
</div>
<p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
<small class="text-muted">Donec id elit non mi porta.</small>
</a>
<a href="#" class="list-group-item list-group-item-action flex-column align-items-start">
<div class="d-flex w-100 justify-content-between">
<h5 class="mb-1">List group item heading</h5>
<small class="text-muted">3 days ago</small>
</div>
<p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
<small class="text-muted">Donec id elit non mi porta.</small>
</a>
</div>

<div class="highlight mt-4"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"list-group"</span><span class="nt">&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-action flex-column align-items-start active"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-flex w-100 justify-content-between"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>List group item heading<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;small&gt;</span>3 days ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;small&gt;</span>Donec id elit non mi porta.<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-action flex-column align-items-start"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-flex w-100 justify-content-between"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>List group item heading<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>3 days ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Donec id elit non mi porta.<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;a</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">class=</span><span class="s">"list-group-item list-group-item-action flex-column align-items-start"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-flex w-100 justify-content-between"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>List group item heading<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>3 days ago<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"mb-1"</span><span class="nt">&gt;</span>Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;small</span> <span class="na">class=</span><span class="s">"text-muted"</span><span class="nt">&gt;</span>Donec id elit non mi porta.<span class="nt">&lt;/small&gt;</span>
<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;/div&gt;</span></code></pre></div>