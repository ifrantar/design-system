---
layout: page
navigation : main
title: Toasts
permalink: /toasts/
---

<header class="main__header">
  <h1 class="main__header--header">Toasts</h1>
  <p>These messages provide a brief message after the user has perform a task. They might simply inform you or come with an option action.</p>
</header>
<section class="main__block">
  <h2>Default</h2>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="toast" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div><br>
        <div class="toast" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Message hasn't been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Retry</a>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Dismiss<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Message hasn't been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Retry<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <p>Message should not be more than one line of text. These messages are not meant to explain but rather give some feedback and quick actionable items if needs be.</p>
  <p>Also, this messages are meant to exist for a short lapsus of time i.e., around 10 seconds.</p>
</section>
<section class="main__block">
  <h2>Color alternatives</h2>
  <p>The color alternatives follow the same pattern as on banners:</p>
  <ul class="list__ul">
    <li><code>default</code></li>
    <li><code>information</code></li>
    <li><code>success</code></li>
    <li><code>warning</code></li>
    <li><code>danger</code></li>
  </ul>
  <section class="demos">
    <div class="demos__header">
      <h4>Example</h4><a class="code__action"><span class="icon icon__size--medium icon__color--action"><svg height="24px" viewbox="0 0 24 24" width="24px">
      <g fill="inherit">
        <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
      </g></svg></span></a>
    </div>
    <div class="demos__body">
      <div>
        <div class="toast toast__default" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div><br>
        <div class="toast toast__information" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div><br>
        <div class="toast toast__success" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div><br>
        <div class="toast toast__warning" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div><br>
        <div class="toast toast__danger" style="position: static; transform: none;">
          <div class="toast__content">
            <p>Your email has been sent</p>
          </div>
          <div class="toast__actions">
            <a class="toast__action" href="#">Undo</a>
          </div>
        </div>
      </div>
    </div>
    <div class="demos__code">
      <div class="code__samples">
        <pre><code class="html hljs xml"></code></pre>
        <div>
          <code class="html hljs xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast toast__default"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast toast__information"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast toast__success"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast toast__warning"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast toast__danger"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__content"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Your email has been sent<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__actions"</span>&gt;</span> <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"toast__action"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"#"</span>&gt;</span>Undo<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span> <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></code>
        </div>
        <pre></pre>
      </div>
    </div>
  </section>
  <p>Message should not be more than one line of text. These messages are not meant to explain but rather give some feedback and quick actionable items if needs be.</p>
  <p>Also, this messages are meant to exist for a short lapsus of time i.e., around 10 seconds.</p>
</section>
