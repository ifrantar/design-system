---
layout: page
navigation : main
title: Form elements
permalink: /form-elements/
---

<header class="main__header">
	<h1 class="main__header--header">Form elements</h1>
</header>
<section class="main__block">
	<h2 id="textfields">Textfields</h2>
	<p>Textfields and their respective states.</p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<ul>
					<li class="u__margin-bottom--medium"><label class="f__label">Default input label</label>
						<div class="form__textfield"><input class="f__textfield f__textfield--size-m" type="text" /></div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Default input label with placeholder</label>
						<div class="form__textfield"><input class="f__textfield f__textfield--size-m" type="text" placeholder="I'm a placeholder" /></div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Success input label</label>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-m f__textfield--success" type="text" />
							<div class="f__textfield--status f__textfield--status-m"><em class="material-icons f__mi--success">check</em></div>
						</div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Input with spinner</label>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-m f__textfield--spinner" type="text" />
							<div class="f__textfield--status f__textfield--status-m">&nbsp;</div>
						</div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Error input label</label>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-m f__textfield--error" type="text" />
							<div class="f__textfield--status f__textfield--status-m"><em class="material-icons f__mi--error">close</em></div>
							<span class="f__message f__message--error">This input field has an error</span></div>
					</li>
					<li><label class="f__label">Error input with tooltip message</label>
						<div class="form__textfield form__textfield--has-status form__textfield--error-tooltip"><input class="f__textfield f__textfield--size-m f__textfield--error" type="text" />
							<div class="f__textfield--status f__textfield--status-m"><em class="material-icons f__mi--error">close</em></div>
							<span class="f__message f__message--error">This input field has an error</span></div>
					</li>
				</ul>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;label class=&quot;f__label&quot;&gt;Default input label&lt;/label&gt;
&lt;div class=&quot;form__textfield&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m&quot; type=&quot;text&quot; /&gt;&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Default input label with placeholder&lt;/label&gt;
&lt;div class=&quot;form__textfield&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m&quot; type=&quot;text&quot; placeholder=&quot;I&#39;m a placeholder&quot; /&gt;&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Success input label&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--success&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Input with spinner&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--spinner&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&amp;nbsp;&lt;/div&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Error input label&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;span class=&quot;f__message f__message--error&quot;&gt;This input field has an error&lt;/span&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Error input with tooltip message&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status form__textfield--error-tooltip&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;span class=&quot;f__message f__message--error&quot;&gt;This input field has an error&lt;/span&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
	<h3>Sizes</h3>
	<p><!-- react-text: 63 -->Textfields can have 3 sizes: medium <!-- /react-text --><code>f__textfield--size-m</code><!-- react-text: 65 --> being the default size; small <!-- /react-text --><code>f__textfield--size-s</code><!-- react-text: 67 --> and large <!-- /react-text --><code>f__textfield--size-l</code></p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<ul class="u__margin-bottom--0">
					<li class="u__margin-bottom--medium">
						<h4>Large size</h4>
						<div class="form__textfield u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-l" type="text" /></div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-l f__textfield--success" type="text" />
							<div class="f__textfield--status f__textfield--status-l"><em class="material-icons f__mi--success">check</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-l f__textfield--error" type="text" />
							<div class="f__textfield--status f__textfield--status-l"><em class="material-icons f__mi--error">close</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-l f__textfield--spinner" type="text" />
							<div class="f__textfield--status f__textfield--status-l">&nbsp;</div>
						</div>
					</li>
					<li class="u__margin-bottom--medium">
						<h4>Medium size</h4>
						<div class="form__textfield u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-m" type="text" /></div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-m f__textfield--success" type="text" />
							<div class="f__textfield--status f__textfield--status-m"><em class="material-icons f__mi--success">check</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-m f__textfield--error" type="text" />
							<div class="f__textfield--status f__textfield--status-m"><em class="material-icons f__mi--error">close</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-m f__textfield--spinner" type="text" />
							<div class="f__textfield--status f__textfield--status-m">&nbsp;</div>
						</div>
					</li>
					<li>
						<h4>Small size</h4>
						<div class="form__textfield u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-s" type="text" /></div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-s f__textfield--success" type="text" />
							<div class="f__textfield--status f__textfield--status-s"><em class="material-icons f__mi--success">check</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status u__margin-bottom--x-small"><input class="f__textfield f__textfield--size-s f__textfield--error" type="text" />
							<div class="f__textfield--status f__textfield--status-s"><em class="material-icons f__mi--error">close</em></div>
						</div>
						<div class="form__textfield form__textfield--has-status"><input class="f__textfield f__textfield--size-s f__textfield--spinner" type="text" />
							<div class="f__textfield--status f__textfield--status-s">&nbsp;</div>
						</div>
					</li>
				</ul>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;!-- Large size --&gt;
&lt;div class=&quot;form__textfield&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-l&quot; type=&quot;text&quot; /&gt;&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-l f__textfield--success&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-l&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-l f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-l&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-l f__textfield--spinner&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-l&quot;&gt;&amp;nbsp;&lt;/div&gt;
&lt;/div&gt;

&lt;!-- Medium size --&gt;
&lt;div class=&quot;form__textfield&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m&quot; type=&quot;text&quot; /&gt;&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--success&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--spinner&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&amp;nbsp;&lt;/div&gt;
&lt;/div&gt;

&lt;!-- Small size --&gt;
&lt;div class=&quot;form__textfield&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-s&quot; type=&quot;text&quot; /&gt;&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-s f__textfield--success&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-s&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status u__margin-bottom--x-small&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-s f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-s&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-s f__textfield--spinner&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-s&quot;&gt;&amp;nbsp;&lt;/div&gt;
&lt;/div&gt;
&lt;label class=&quot;f__label&quot;&gt;Input with spinner&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--spinner&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&amp;nbsp;&lt;/div&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Error input label&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;span class=&quot;f__message f__message--error&quot;&gt;This input field has an error&lt;/span&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Error input with tooltip message&lt;/label&gt;
&lt;div class=&quot;form__textfield form__textfield--has-status form__textfield--error-tooltip&quot;&gt;&lt;input class=&quot;f__textfield f__textfield--size-m f__textfield--error&quot; type=&quot;text&quot; /&gt;
	&lt;div class=&quot;f__textfield--status f__textfield--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;span class=&quot;f__message f__message--error&quot;&gt;This input field has an error&lt;/span&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2 id="textareas">Textarea field</h2>
	<p>This is the textfield where users can type extensive amounts of text.</p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<ul>
					<li class="u__margin-bottom--medium"><label class="f__label">Textarea field</label>
						<div class="form__textarea"><textarea class="f__textarea" name="textarea"></textarea></div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Default input label with placeholder</label>
						<div class="form__textarea">&nbsp;</div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Error input label</label>
						<div class="form__textarea form__textarea--error"><textarea class="f__textarea f__textarea--error" placeholder="Write something here"></textarea><span class="f__message f__message--error">This input field has an error</span></div>
					</li>
				</ul>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;label class=&quot;f__label&quot;&gt;Textarea field&lt;/label&gt;
&lt;div class=&quot;form__textarea&quot;&gt;&lt;textarea class=&quot;f__textarea&quot; name=&quot;textarea&quot;&gt;&lt;/textarea&gt;&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Default input label with placeholder&lt;/label&gt;
&lt;div class=&quot;form__textarea&quot;&gt;&amp;nbsp;&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Error input label&lt;/label&gt;
&lt;div class=&quot;form__textarea form__textarea--error&quot;&gt;&lt;textarea class=&quot;f__textarea f__textarea--error&quot; placeholder=&quot;Write something here&quot;&gt;&lt;/textarea&gt;
   &lt;span class=&quot;f__message f__message--error&quot;&gt;This input field has an error&lt;/span&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2 id="dropdowns">Dropdowns</h2>
	<p>Some dropdowns alternatives being used at Stelltec.</p>
	<h3><!-- react-text: 163 -->Standard <!-- /react-text --><code>select</code><!-- react-text: 165 --> dropdown<!-- /react-text --></h3>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<ul>
					<li class="u__margin-bottom--medium"><label class="f__label">Select label</label>
						<div class="form__select"><select class="f__select f__select--size-m" name="select">
								<option value="value1">Value 1</option>
								<option value="value2">Value 2</option>
								<option value="value3">Value 3</option>
							</select>
							<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
						</div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Select label success</label>
						<div class="form__select form__select--has-status"><select class="f__select f__select--size-m f__select--success" name="select">
								<option value="value1">Value 1</option>
								<option value="value2">Value 2</option>
								<option value="value3">Value 3</option>
							</select>
							<div class="f__select--status f__select--status-m"><em class="material-icons f__mi--success">check</em></div>
							<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
						</div>
					</li>
					<li class="u__margin-bottom--medium"><label class="f__label">Select label error</label>
						<div class="form__select form__select--has-status"><select class="f__select f__select--size-m f__select--error" name="select">
								<option value="value1">Value 1</option>
								<option value="value2">Value 2</option>
								<option value="value3">Value 3</option>
							</select>
							<div class="f__select--status f__select--status-m"><em class="material-icons f__mi--error">close</em></div>
							<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
						</div>
					</li>
				</ul>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;label class=&quot;f__label&quot;&gt;Select label&lt;/label&gt;
&lt;div class=&quot;form__select&quot;&gt;&lt;select class=&quot;f__select f__select--size-m&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Select label success&lt;/label&gt;
&lt;div class=&quot;form__select form__select--has-status&quot;&gt;&lt;select class=&quot;f__select f__select--size-m f__select--success&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;label class=&quot;f__label&quot;&gt;Select label error&lt;/label&gt;
&lt;div class=&quot;form__select form__select--has-status&quot;&gt;&lt;select class=&quot;f__select f__select--size-m f__select--error&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
        </code></pre>
			</div>
		</div>
	</section>

	<section>
		<h3>Sizes</h3>
		<p><!-- react-text: 250 -->Dropdowns can have 3 sizes: medium <!-- /react-text --><code>f__select--size-m</code><!-- react-text: 252 --> being the default size; small <!-- /react-text --><code>f__select--size-s</code><!-- react-text: 254 --> and large <!-- /react-text --><code>f__select--size-l</code></p>
		<section class="demos">
      <div class="demos__header">
        <h4>Example</h4>
        <a class="code__action">
          <span class="icon icon__size--medium icon__color--action">
            <svg width="24px" height="24px" viewBox="0 0 24 24">
              <g fill="inherit">
                  <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
              </g>
            </svg>
          </span>
        </a>
      </div>
			<div class="demos__body">
				<div>
					<ul>
						<li class="u__margin-bottom--medium">
							<h4>Large size</h4>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-l" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--arrow f__select--arrow-l"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select form__select--has-status u__margin-bottom--x-small"><select class="f__select f__select--size-l f__select--success" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-l"><em class="material-icons f__mi--success">check</em></div>
								<div class="f__select--arrow f__select--arrow-l"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select form__select--has-status u__margin-bottom--x-small"><select class="f__select f__select--size-l f__select--error" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-l"><em class="material-icons f__mi--error">close</em></div>
								<div class="f__select--arrow f__select--arrow-l"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select form__select--has-status"><select class="f__select f__select--size-l" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-l">&nbsp;</div>
								<div class="f__select--arrow f__select--arrow-l"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
						</li>
						<li class="u__margin-bottom--medium">
							<h4>Medium size</h4>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-m" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-m f__select--success" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-m"><em class="material-icons f__mi--success">check</em></div>
								<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-m f__select--error" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-m"><em class="material-icons f__mi--error">close</em></div>
								<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-m" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-m">&nbsp;</div>
								<div class="f__select--arrow f__select--arrow-m"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
						</li>
						<li class="u__margin-bottom--0">
							<h4>Small size</h4>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-s" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--arrow f__select--arrow-s"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select form__select--has-status u__margin-bottom--x-small"><select class="f__select f__select--size-s f__select--success" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-s"><em class="material-icons f__mi--success">check</em></div>
								<div class="f__select--arrow f__select--arrow-s"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select form__select--has-status u__margin-bottom--x-small"><select class="f__select f__select--size-s f__select--error" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-s"><em class="material-icons f__mi--error">close</em></div>
								<div class="f__select--arrow f__select--arrow-s"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
							<div class="form__select u__margin-bottom--x-small"><select class="f__select f__select--size-s" name="select">
									<option value="value1">Value 1</option>
									<option value="value2">Value 2</option>
									<option value="value3">Value 3</option>
								</select>
								<div class="f__select--status f__select--status-s">&nbsp;</div>
								<div class="f__select--arrow f__select--arrow-s"><em class="material-icons">keyboard_arrow_down</em></div>
							</div>
						</li>
					</ul>
				</div>
			</div>
			<div class="demos__code">
				<div class="code__samples">
					<pre><code class="html">
&lt;!-- Large size --&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-l&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-l&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select form__select--has-status u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-l f__select--success&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-l&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-l&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select form__select--has-status u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-l f__select--error&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-l&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-l&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select form__select--has-status&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-l&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-l&quot;&gt;&amp;nbsp;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-l&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;!-- Medium size --&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-m&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-m f__select--success&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-m f__select--error&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-m&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-m&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-m&quot;&gt;&amp;nbsp;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-m&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;

&lt;!-- Small size --&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-s&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-s&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select form__select--has-status u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-s f__select--success&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-s&quot;&gt;&lt;em class=&quot;material-icons f__mi--success&quot;&gt;check&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-s&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select form__select--has-status u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-s f__select--error&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-s&quot;&gt;&lt;em class=&quot;material-icons f__mi--error&quot;&gt;close&lt;/em&gt;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-s&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;form__select u__margin-bottom--x-small&quot;&gt;
  &lt;select class=&quot;f__select f__select--size-s&quot; name=&quot;select&quot;&gt;
		&lt;option value=&quot;value1&quot;&gt;Value 1&lt;/option&gt;
		&lt;option value=&quot;value2&quot;&gt;Value 2&lt;/option&gt;
		&lt;option value=&quot;value3&quot;&gt;Value 3&lt;/option&gt;
	&lt;/select&gt;
	&lt;div class=&quot;f__select--status f__select--status-s&quot;&gt;&amp;nbsp;&lt;/div&gt;
	&lt;div class=&quot;f__select--arrow f__select--arrow-s&quot;&gt;&lt;em class=&quot;material-icons&quot;&gt;keyboard_arrow_down&lt;/em&gt;&lt;/div&gt;
&lt;/div&gt;
          </code></pre>
				</div>
			</div>
		</section>
	</section>
</section>
<section class="main__block">
	<h2 id="radio">Radio buttons</h2>
	<p>Collection of Radio buttons</p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">

				<ul class="u__margin-bottom--0">
					<li class="u__margin-bottom--small"><label><input name="test" type="radio" value="on" />Item 1</label></li> <!-- f__radio class on label -->
					<li class="u__margin-bottom--small"><label><input name="test" type="radio" value="on" />Item 2</label></li>
					<li class="u__margin-bottom--small"><label><input name="test" type="radio" value="on" />Item 3</label></li>
					<li class="u__margin-bottom--0"><label><input name="test" type="radio" value="on" />Item 4</label></li>
				</ul>

		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;label&gt;&lt;input name=&quot;test&quot; type=&quot;radio&quot; value=&quot;on&quot; /&gt;Item 1&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test&quot; type=&quot;radio&quot; value=&quot;on&quot; /&gt;Item 2&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test&quot; type=&quot;radio&quot; value=&quot;on&quot; /&gt;Item 3&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test&quot; type=&quot;radio&quot; value=&quot;on&quot; /&gt;Item 4&lt;/label&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
<section class="main__block">
	<h2 id="checkbox">Check boxes</h2>
	<p>Collection of Checkboxes</p>
	<section class="demos">
    <div class="demos__header">
      <h4>Example</h4>
      <a class="code__action">
        <span class="icon icon__size--medium icon__color--action">
          <svg width="24px" height="24px" viewBox="0 0 24 24">
            <g fill="inherit">
                <path d="M9.32923367,16.8036682 C9.71565227,17.1644938 9.71565227,17.7495076 9.32923367,18.1103332 C8.94281508,18.4711588 8.31630675,18.4711588 7.92988816,18.1103332 L2.28981395,12.8438087 C1.90339535,12.4829831 1.90339535,11.8979693 2.28981395,11.5371437 L7.92988816,6.27061918 C8.31630675,5.90979361 8.94281508,5.90979361 9.32923367,6.27061918 C9.71565227,6.63144475 9.71565227,7.21645859 9.32923367,7.57728416 L4.38883222,12.1904762 L9.32923367,16.8036682 Z M14.6707663,7.57728416 C14.2843477,7.21645859 14.2843477,6.63144475 14.6707663,6.27061918 C15.0571849,5.90979361 15.6836932,5.90979361 16.0701118,6.27061918 L21.7101861,11.5371437 C22.0966046,11.8979693 22.0966046,12.4829831 21.7101861,12.8438087 L16.0701118,18.1103332 C15.6836932,18.4711588 15.0571849,18.4711588 14.6707663,18.1103332 C14.2843477,17.7495076 14.2843477,17.1644938 14.6707663,16.8036682 L19.6111678,12.1904762 L14.6707663,7.57728416 Z"></path>
            </g>
          </svg>
        </span>
      </a>
    </div>
		<div class="demos__body">
			<div>
				<ul class="u__margin-bottom--0">
					<li class="u__margin-bottom--small"><label><input name="test-checkbox" type="checkbox" value="on" />Item 1</label></li>
					<li class="u__margin-bottom--small"><label><input name="test-checkbox" type="checkbox" value="on" />Item 2</label></li>
					<li class="u__margin-bottom--small"><label><input name="test-checkbox" type="checkbox" value="on" />Item 3</label></li>
					<li><label><input name="test-checkbox" type="checkbox" value="on" />Item 4</label></li>
				</ul>
			</div>
		</div>
		<div class="demos__code">
			<div class="code__samples">
				<pre><code class="html">
&lt;label&gt;&lt;input name=&quot;test-checkbox&quot; type=&quot;checkbox&quot; value=&quot;on&quot; /&gt;Item 1&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test-checkbox&quot; type=&quot;checkbox&quot; value=&quot;on&quot; /&gt;Item 2&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test-checkbox&quot; type=&quot;checkbox&quot; value=&quot;on&quot; /&gt;Item 3&lt;/label&gt;
&lt;label&gt;&lt;input name=&quot;test-checkbox&quot; type=&quot;checkbox&quot; value=&quot;on&quot; /&gt;Item 4&lt;/label&gt;
        </code></pre>
			</div>
		</div>
	</section>
</section>
