---
title: Collapse
visible: true
taxonomy:
    category: docs
process:
    twig: true
---

<h4 class="mt-4">Example</h4>

<p>
<a class="btn btn-primary" data-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
Link with href
</a>
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
Button with data-target
</button>
</p>
<div class="collapse" id="collapseExample">
<div class="card card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">href=</span><span class="s">"#collapseExample"</span> <span class="na">role=</span><span class="s">"button"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"collapseExample"</span><span class="nt">&gt;</span>
Link with href
<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">"#collapseExample"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"collapseExample"</span><span class="nt">&gt;</span>
Button with data-target
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"collapse"</span> <span class="na">id=</span><span class="s">"collapseExample"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>



<hr />

<h4 class="mt-4">Multiple targets</h4>

<p>
<a class="btn btn-primary" data-toggle="collapse" href="#multiCollapseExample1" role="button" aria-expanded="false" aria-controls="multiCollapseExample1">Toggle first element</a>
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Toggle second element</button>
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target=".multi-collapse" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">Toggle both elements</button>
</p>
<div class="row">
<div class="col">
<div class="collapse multi-collapse" id="multiCollapseExample1">
<div class="card card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
</div>
</div>
</div>
<div class="col">
<div class="collapse multi-collapse" id="multiCollapseExample2">
<div class="card card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
</div>
</div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;p&gt;</span>
<span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">href=</span><span class="s">"#multiCollapseExample1"</span> <span class="na">role=</span><span class="s">"button"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"multiCollapseExample1"</span><span class="nt">&gt;</span>Toggle first element<span class="nt">&lt;/a&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">"#multiCollapseExample2"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"multiCollapseExample2"</span><span class="nt">&gt;</span>Toggle second element<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-primary"</span> <span class="na">type=</span><span class="s">"button"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">".multi-collapse"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"multiCollapseExample1 multiCollapseExample2"</span><span class="nt">&gt;</span>Toggle both elements<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/p&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"row"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"col"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"collapse multi-collapse"</span> <span class="na">id=</span><span class="s">"multiCollapseExample1"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"col"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"collapse multi-collapse"</span> <span class="na">id=</span><span class="s">"multiCollapseExample2"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>


<hr />

<h4 class="mt-4">Accordion</h4>

<div id="accordion">
<div class="card">
<div class="card-header" id="headingOne">
<h5 class="mb-0">
<button class="btn btn-link" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
  Collapsible Group Item #1
</button>
</h5>
</div>

<div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordion">
<div class="card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
</div>
</div>
</div>
<div class="card">
<div class="card-header" id="headingTwo">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
  Collapsible Group Item #2
</button>
</h5>
</div>
<div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordion">
<div class="card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
</div>
</div>
</div>
<div class="card">
<div class="card-header" id="headingThree">
<h5 class="mb-0">
<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
  Collapsible Group Item #3
</button>
</h5>
</div>
<div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordion">
<div class="card-body">
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
</div>
</div>
</div>
</div>

<div class="highlight mt-4">
<pre><code class="language-html" data-lang="html">
<span class="nt">&lt;div</span> <span class="na">id=</span><span class="s">"accordion"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span> <span class="na">id=</span><span class="s">"headingOne"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-link"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">"#collapseOne"</span> <span class="na">aria-expanded=</span><span class="s">"true"</span> <span class="na">aria-controls=</span><span class="s">"collapseOne"</span><span class="nt">&gt;</span>
  Collapsible Group Item #1
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;/div&gt;</span>

<span class="nt">&lt;div</span> <span class="na">id=</span><span class="s">"collapseOne"</span> <span class="na">class=</span><span class="s">"collapse show"</span> <span class="na">aria-labelledby=</span><span class="s">"headingOne"</span> <span class="na">data-parent=</span><span class="s">"#accordion"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span> <span class="na">id=</span><span class="s">"headingTwo"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-link collapsed"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">"#collapseTwo"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"collapseTwo"</span><span class="nt">&gt;</span>
  Collapsible Group Item #2
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">id=</span><span class="s">"collapseTwo"</span> <span class="na">class=</span><span class="s">"collapse"</span> <span class="na">aria-labelledby=</span><span class="s">"headingTwo"</span> <span class="na">data-parent=</span><span class="s">"#accordion"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-header"</span> <span class="na">id=</span><span class="s">"headingThree"</span><span class="nt">&gt;</span>
<span class="nt">&lt;h5</span> <span class="na">class=</span><span class="s">"mb-0"</span><span class="nt">&gt;</span>
<span class="nt">&lt;button</span> <span class="na">class=</span><span class="s">"btn btn-link collapsed"</span> <span class="na">data-toggle=</span><span class="s">"collapse"</span> <span class="na">data-target=</span><span class="s">"#collapseThree"</span> <span class="na">aria-expanded=</span><span class="s">"false"</span> <span class="na">aria-controls=</span><span class="s">"collapseThree"</span><span class="nt">&gt;</span>
  Collapsible Group Item #3
<span class="nt">&lt;/button&gt;</span>
<span class="nt">&lt;/h5&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;div</span> <span class="na">id=</span><span class="s">"collapseThree"</span> <span class="na">class=</span><span class="s">"collapse"</span> <span class="na">aria-labelledby=</span><span class="s">"headingThree"</span> <span class="na">data-parent=</span><span class="s">"#accordion"</span><span class="nt">&gt;</span>
<span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"card-body"</span><span class="nt">&gt;</span>
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</code></pre>
</div>