---
title: Lint Rule jsx/useJSXFileExtension
layout: layouts/rule.liquid
description: MISSING DOCUMENTATION
eleventyNavigation:
	key: lint-rules/jsx/useJSXFileExtension
	parent: lint-rules
	title: jsx/useJSXFileExtension
---

# jsx/useJSXFileExtension

MISSING DOCUMENTATION

<!-- GENERATED:START(hash:da39a3ee5e6b4b0d3255bfef95601890afd80709,id:description) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules` to update. -->

<!-- GENERATED:END(id:description) -->

<!-- GENERATED:START(hash:735f5544ebc7c5e960ca7dd798d182aed08648c8,id:examples) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules-docs` to update. -->
## Examples

### Invalid

{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">div</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">div</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">test.js:2</span> <strong>lint/jsx/useJSXFileExtension</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Files with the </span><span style="color: Tomato;"><strong>.js</strong></span><span style="color: Tomato;"> extension cannot contain JSX elements.</span>

  <strong>  1</strong><strong> │ </strong><span class="token comment">// @jsx</span>
  <strong><span style="color: Tomato;">&gt;</span></strong><strong> 2</strong><strong> │ </strong>&lt;<span class="token variable">div</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">div</span>&gt;
     <strong> │ </strong><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Change the </span><span style="color: rgb(38, 148, 255);"><strong>test.js</strong></span><span style="color: rgb(38, 148, 255);"> file extension to </span><span style="color: rgb(38, 148, 255);"><strong>.jsx</strong></span><span style="color: rgb(38, 148, 255);"> or </span><span style="color: rgb(38, 148, 255);"><strong>.tsx</strong></span><span style="color: rgb(38, 148, 255);">.</span>

</code></pre>{% endraw %}

---

{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;&gt;&lt;<span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">test.js:2</span> <strong>lint/jsx/useJSXFileExtension</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Files with the </span><span style="color: Tomato;"><strong>.js</strong></span><span style="color: Tomato;"> extension cannot contain JSX elements.</span>

  <strong>  1</strong><strong> │ </strong><span class="token comment">// @jsx</span>
  <strong><span style="color: Tomato;">&gt;</span></strong><strong> 2</strong><strong> │ </strong>&lt;&gt;&lt;<span class="token operator">/</span>&gt;
     <strong> │ </strong><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Change the </span><span style="color: rgb(38, 148, 255);"><strong>test.js</strong></span><span style="color: rgb(38, 148, 255);"> file extension to </span><span style="color: rgb(38, 148, 255);"><strong>.jsx</strong></span><span style="color: rgb(38, 148, 255);"> or </span><span style="color: rgb(38, 148, 255);"><strong>.tsx</strong></span><span style="color: rgb(38, 148, 255);">.</span>

</code></pre>{% endraw %}

---

{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">Fragment</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">test.js:2</span> <strong>lint/jsx/useJSXFileExtension</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Files with the </span><span style="color: Tomato;"><strong>.js</strong></span><span style="color: Tomato;"> extension cannot contain JSX elements.</span>

  <strong>  1</strong><strong> │ </strong><span class="token comment">// @jsx</span>
  <strong><span style="color: Tomato;">&gt;</span></strong><strong> 2</strong><strong> │ </strong>&lt;<span class="token variable">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">Fragment</span>&gt;
     <strong> │ </strong><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Change the </span><span style="color: rgb(38, 148, 255);"><strong>test.js</strong></span><span style="color: rgb(38, 148, 255);"> file extension to </span><span style="color: rgb(38, 148, 255);"><strong>.jsx</strong></span><span style="color: rgb(38, 148, 255);"> or </span><span style="color: rgb(38, 148, 255);"><strong>.tsx</strong></span><span style="color: rgb(38, 148, 255);">.</span>

</code></pre>{% endraw %}

---

{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">test.js:2</span> <strong>lint/jsx/useJSXFileExtension</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Files with the </span><span style="color: Tomato;"><strong>.js</strong></span><span style="color: Tomato;"> extension cannot contain JSX elements.</span>

  <strong>  1</strong><strong> │ </strong><span class="token comment">// @jsx</span>
  <strong><span style="color: Tomato;">&gt;</span></strong><strong> 2</strong><strong> │ </strong>&lt;<span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;
     <strong> │ </strong><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Change the </span><span style="color: rgb(38, 148, 255);"><strong>test.js</strong></span><span style="color: rgb(38, 148, 255);"> file extension to </span><span style="color: rgb(38, 148, 255);"><strong>.jsx</strong></span><span style="color: rgb(38, 148, 255);"> or </span><span style="color: rgb(38, 148, 255);"><strong>.tsx</strong></span><span style="color: rgb(38, 148, 255);">.</span>

</code></pre>{% endraw %}

### Valid

{% raw %}<pre class="language-js"><code class="language-js"><span class="token string">&apos;&lt;div&gt;&lt;/div&gt;&apos;</span></code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">div</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">div</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;&gt;&lt;<span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">Fragment</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">div</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">div</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;&gt;&lt;<span class="token operator">/</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">Fragment</span>&gt;</code></pre>{% endraw %}
{% raw %}<pre class="language-js"><code class="language-js"><span class="token comment">// @jsx</span>
&lt;<span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;&lt;<span class="token operator">/</span><span class="token variable">React</span><span class="token punctuation">.</span><span class="token attr-name">Fragment</span>&gt;</code></pre>{% endraw %}
<!-- GENERATED:END(id:examples) -->
