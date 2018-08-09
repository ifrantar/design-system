---
layout: page
navigation : main
title: Pagination
permalink: /pagination/
---

<header class="main__header">
  <h1 class="main__header--header">Pagination</h1>
  <p>We use pagination to indicate large amounts of content and sectioning it into different pages as as dynamically loading content as required.</p>
</header>
<p>There are good reasons to use pagination or infinite scrolling. Without going to extensive on the explanation as to why would you choose one over there other,<a href="https://uxplanet.org/ux-infinite-scrolling-vs-pagination-1030d29376f1" target="_blank">there's this comprenhensive article</a> on the matter.</p>
<p>At the present time, it is sufficient to say that we support both approaches where they'll be used accordingly based on the best experience depending of the use case:</p>
<ul class="list__ul">
  <li>Pagination</li>
  <li>Infinite scrolling</li>
</ul>
<section class="main__block">
  <h2>Pagination</h2>
  <h3>Alignment</h3>
  <p><!-- react-text: 24 -->Pagination could be aligned left—which is the default behaviour—by using the clases<!-- /react-text --><code>pagination__align-left</code><!-- react-text: 26 -->, <!-- /react-text --><code>pagination__align-center</code><!-- react-text: 28 --> and <!-- /react-text --><code>pagination__align-right</code></p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-s pagination__align-left">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-s pagination__align-left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-s pagination__align-center">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-s pagination__align-center"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-s pagination__align-right">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-s pagination__align-right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <h3>Size</h3>
  <p><!-- react-text: 131 -->There are 3 sizes that can be used for pagination: <!-- /react-text --><code>pagination__size-s</code><!-- react-text: 133 -->,<!-- /react-text --><code>pagination__size-m</code><!-- react-text: 135 -->, <!-- /react-text --><code>pagination__size-l</code></p>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-s pagination__align-left">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-s pagination__align-left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-m pagination__align-left">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-m pagination__align-left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <nav class="pagination pagination__size-l pagination__align-left">
          <ul>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--previous" href="#"><i class="material-icons">keyboard_arrow_left</i></a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">1</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--active" href="#">2</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">3</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">4</a>
            </li>
            <li class="pagination__item pagination__item--hellip">…</li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">24</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link" href="#">28</a>
            </li>
            <li class="pagination__item">
              <a class="pagination__link pagination__link--next" href="#"><i class="material-icons">keyboard_arrow_right</i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination pagination__size-l pagination__align-left"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--previous"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_left<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>1<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--active"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>2<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>3<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>4<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item pagination__item--hellip"</span>&gt;</span>…<span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>24<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>28<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__item"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"pagination__link pagination__link--next"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>keyboard_arrow_right<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
</section>
<section class="main__block">
  <h2>Infinite scrolling</h2>
  <p>For the sake of illustration we are going to use what would be a use case if you wanted to scroll down on a table.</p>
  <h3>Load button</h3>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="panel">
          <div class="panel__header">
            <h3>Users</h3>
            <div class="panel__header--action-btn add__btn--user"></div>
          </div>
          <div class="panel__body panel__body--with-table">
            <table class="table table__easy table__inside-panel">
              <thead>
                <tr>
                  <th>Name</th>
                  <th>Email</th>
                  <th>Status</th>
                  <th class="table__align--right">Actions</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Ivan Frantar</td>
                  <td>ivan.frantar@stelltec.com</td>
                  <td><span class="badge badge__default">Enabled</span></td>
                  <td class="table__align--right">
                    <div class="actions">
                      <a class="context__menu--js" href="#"><i class="material-icons">more_horiz</i></a>
                    </div>
                  </td>
                </tr>
                <tr>
                  <td>Remo Hansen</td>
                  <td>remo.hansen@stelltec.com</td>
                  <td><span class="badge badge__information">Enabled</span></td>
                  <td class="table__align--right">
                    <div class="actions">
                      <a href="#"><i class="material-icons">more_horiz</i></a>
                    </div>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="panel__footer panel__footer--infinite">
            <nav class="infinite-scroll infinite-scroll__align-center">
              <button class="btn btn__primary btn__primary--flat btn__size-m">Load more</button>
            </nav>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__header"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">h3</span>&gt;</span>Users<span class="hljs-tag">&lt;/<span class="hljs-name">h3</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__header--action-btn add__btn--user"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__body panel__body--with-table"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">table</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table table__easy table__inside-panel"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">thead</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Name<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Email<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Status<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span>Actions<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">thead</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tbody</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>Ivan Frantar<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>ivan.frantar@stelltec.com<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"badge badge__default"</span>&gt;</span>Enabled<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"context__menu--js"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">className</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>more_horiz<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>Remo Hansen<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>remo.hansen@stelltec.com<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"badge badge__information"</span>&gt;</span>Enabled<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>more_horiz<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tbody</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">table</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__footer panel__footer--infinite"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"infinite-scroll infinite-scroll__align-center"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">button</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"btn btn__primary btn__primary--flat btn__size-m"</span>&gt;</span>Load more<span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <h3>Loading spinner</h3>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="panel">
          <div class="panel__header">
            <h3>Users</h3>
            <div class="panel__header--action-btn add__btn--user"></div>
          </div>
          <div class="panel__body panel__body--with-table">
            <table class="table table__easy table__inside-panel">
              <thead>
                <tr>
                  <th>Name</th>
                  <th>Email</th>
                  <th>Status</th>
                  <th class="table__align--right">Actions</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Ivan Frantar</td>
                  <td>ivan.frantar@stelltec.com</td>
                  <td><span class="badge badge__default">Enabled</span></td>
                  <td class="table__align--right">
                    <div class="actions">
                      <a class="context__menu--js" href="#"><i class="material-icons">more_horiz</i></a>
                    </div>
                  </td>
                </tr>
                <tr>
                  <td>Remo Hansen</td>
                  <td>remo.hansen@stelltec.com</td>
                  <td><span class="badge badge__information">Enabled</span></td>
                  <td class="table__align--right">
                    <div class="actions">
                      <a href="#"><i class="material-icons">more_horiz</i></a>
                    </div>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="panel__footer panel__footer--infinite">
            <nav class="infinite-scroll infinite-scroll__align-center">
              <button class="btn btn__secondary btn__secondary--flat btn__size-m"><span class="spinner spinner__small spinner__small--default"></span></button>
            </nav>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__header"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">h3</span>&gt;</span>Users<span class="hljs-tag">&lt;/<span class="hljs-name">h3</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__header--action-btn add__btn--user"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__body panel__body--with-table"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">table</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table table__easy table__inside-panel"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">thead</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Name<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Email<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span>&gt;</span>Status<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">th</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span>Actions<span class="hljs-tag">&lt;/<span class="hljs-name">th</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">thead</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tbody</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>Ivan Frantar<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>ivan.frantar@stelltec.com<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"badge badge__default"</span>&gt;</span>Enabled<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"context__menu--js"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>more_horiz<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>Remo Hansen<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span>remo.hansen@stelltec.com<span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"badge badge__information"</span>&gt;</span>Enabled<span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">td</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"table__align--right"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">i</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"material-icons"</span>&gt;</span>more_horiz<span class="hljs-tag">&lt;/<span class="hljs-name">i</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">tbody</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">table</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"panel__footer panel__footer--infinite"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"infinite-scroll infinite-scroll__align-center"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">button</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"btn btn__secondary btn__secondary--flat btn__size-m"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"spinner spinner__small spinner__small--default"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
</section>
