---
title: Pagination
visible: true
taxonomy:
    category: docs
process:
    twig: true
---

Documentation and examples for showing pagination to indicate a series of related content exists across multiple pages.

<nav aria-label="Page navigation example">
  <ul class="pagination">
    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item"><a class="page-link" href="#">Next</a></li>
  </ul>
</nav>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"Page navigation example"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Previous<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Next<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>





<nav aria-label="Page navigation example">
  <ul class="pagination">
    <li class="page-item">
      <a class="page-link" href="#" aria-label="Previous">
        <span aria-hidden="true">&laquo;</span>
        <span class="sr-only">Previous</span>
      </a>
    </li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item">
      <a class="page-link" href="#" aria-label="Next">
        <span aria-hidden="true">&raquo;</span>
        <span class="sr-only">Next</span>
      </a>
    </li>
  </ul>
</nav>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"Page navigation example"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">aria-label=</span><span class="s">"Previous"</span><span class="nt">&gt;</span>
        <span class="nt">&lt;span</span> <span class="na">aria-hidden=</span><span class="s">"true"</span><span class="nt">&gt;</span><span class="ni">&amp;laquo;</span><span class="nt">&lt;/span&gt;</span>
        <span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"sr-only"</span><span class="nt">&gt;</span>Previous<span class="nt">&lt;/span&gt;</span>
      <span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">aria-label=</span><span class="s">"Next"</span><span class="nt">&gt;</span>
        <span class="nt">&lt;span</span> <span class="na">aria-hidden=</span><span class="s">"true"</span><span class="nt">&gt;</span><span class="ni">&amp;raquo;</span><span class="nt">&lt;/span&gt;</span>
        <span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"sr-only"</span><span class="nt">&gt;</span>Next<span class="nt">&lt;/span&gt;</span>
      <span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>


<h3>Disabled and active states</h3>


<nav aria-label="...">
  <ul class="pagination">
    <li class="page-item disabled">
      <a class="page-link" href="#" tabindex="-1">Previous</a>
    </li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item active">
      <a class="page-link" href="#">2 <span class="sr-only">(current)</span></a>
    </li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item">
      <a class="page-link" href="#">Next</a>
    </li>
  </ul>
</nav>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"..."</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item disabled"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">tabindex=</span><span class="s">"-1"</span><span class="nt">&gt;</span>Previous<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item active"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2 <span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"sr-only"</span><span class="nt">&gt;</span>(current)<span class="nt">&lt;/span&gt;&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Next<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>



<h3>Sizing</h3>

<nav aria-label="...">
  <ul class="pagination pagination-lg">
    <li class="page-item disabled">
      <a class="page-link" href="#" tabindex="-1">1</a>
    </li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
  </ul>
</nav>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"..."</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination pagination-lg"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item disabled"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">tabindex=</span><span class="s">"-1"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>


<nav aria-label="...">
  <ul class="pagination pagination-sm">
    <li class="page-item disabled">
      <a class="page-link" href="#" tabindex="-1">1</a>
    </li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
  </ul>
</nav>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"..."</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination pagination-sm"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item disabled"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">tabindex=</span><span class="s">"-1"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>


<h3>Alignment</h3>

<nav aria-label="Page navigation example">
  <ul class="pagination justify-content-center">
    <li class="page-item disabled">
      <a class="page-link" href="#" tabindex="-1">Previous</a>
    </li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item">
      <a class="page-link" href="#">Next</a>
    </li>
  </ul>
</nav>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"Page navigation example"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination justify-content-center"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item disabled"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">tabindex=</span><span class="s">"-1"</span><span class="nt">&gt;</span>Previous<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Next<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>


<nav aria-label="Page navigation example">
  <ul class="pagination justify-content-end">
    <li class="page-item disabled">
      <a class="page-link" href="#" tabindex="-1">Previous</a>
    </li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item">
      <a class="page-link" href="#">Next</a>
    </li>
  </ul>
</nav>


<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;nav</span> <span class="na">aria-label=</span><span class="s">"Page navigation example"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;ul</span> <span class="na">class=</span><span class="s">"pagination justify-content-end"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item disabled"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span> <span class="na">tabindex=</span><span class="s">"-1"</span><span class="nt">&gt;</span>Previous<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>1<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>2<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>3<span class="nt">&lt;/a&gt;&lt;/li&gt;</span>
    <span class="nt">&lt;li</span> <span class="na">class=</span><span class="s">"page-item"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;a</span> <span class="na">class=</span><span class="s">"page-link"</span> <span class="na">href=</span><span class="s">"#"</span><span class="nt">&gt;</span>Next<span class="nt">&lt;/a&gt;</span>
    <span class="nt">&lt;/li&gt;</span>
  <span class="nt">&lt;/ul&gt;</span>
<span class="nt">&lt;/nav&gt;</span></code></pre></figure>









