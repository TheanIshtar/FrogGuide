<template><div><h1 id="wrapper-classes-muc-luc" tabindex="-1"><a class="header-anchor" href="#wrapper-classes-muc-luc" aria-hidden="true">#</a> Wrapper Classes--------------------------------------------<a href="https://github.com/Zenfection/Java" target="_blank" rel="noopener noreferrer">Mục lục<ExternalLinkIcon/></a></h1>
<h2 id="_1-gioi-thieu" tabindex="-1"><a class="header-anchor" href="#_1-gioi-thieu" aria-hidden="true">#</a> 1. Giới thiệu</h2>
<p><code v-pre>Wrapper Classes</code> cho phép ta sử dụng các kiểu dữ liệu nguyên thuỷ (<em>int,boolean,float</em>) như một <code v-pre>Object</code></p>
<table>
<thead>
<tr>
<th>Kiễu dữ liệu nguyên thuỷ</th>
<th>Wrapper Class</th>
</tr>
</thead>
<tbody>
<tr>
<td>byte</td>
<td>Byte</td>
</tr>
<tr>
<td>short</td>
<td>Short</td>
</tr>
<tr>
<td>int</td>
<td>Integer</td>
</tr>
<tr>
<td>long</td>
<td>Long</td>
</tr>
<tr>
<td>float</td>
<td>Float</td>
</tr>
<tr>
<td>double</td>
<td>Double</td>
</tr>
<tr>
<td>boolean</td>
<td>Boolean</td>
</tr>
<tr>
<td>char</td>
<td>Character</td>
</tr>
</tbody>
</table>
<blockquote>
<p>🔥 Ngoài <code v-pre>int</code> ⇨ <code v-pre>Interger</code> và <code v-pre>char</code> ⇨ <code v-pre>Character</code> thì những kiểu còn lại chỉ cần viết hoa chữ cái đầu là ra <code v-pre>Wrapper Class</code></p>
</blockquote>
<p>Khi tạo các đối tượng<code v-pre>Collection</code>, ta phải sử dụng <code v-pre>Wrapper Class</code> chứ không thể kiểu dữ liệu nguyên thuỷ được :</p>
<div class="language-java line-numbers-mode" data-ext="java"><pre v-pre class="language-java"><code><span class="token class-name">ArrayList</span><span class="token generics"><span class="token punctuation">&lt;</span><span class="token keyword">int</span><span class="token punctuation">></span></span> myNumbers <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">ArrayList</span><span class="token generics"><span class="token punctuation">&lt;</span><span class="token keyword">int</span><span class="token punctuation">></span></span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">//  SAI</span>
<span class="token class-name">ArrayList</span><span class="token generics"><span class="token punctuation">&lt;</span><span class="token class-name">Integer</span><span class="token punctuation">></span></span> myNumbers <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">ArrayList</span><span class="token generics"><span class="token punctuation">&lt;</span><span class="token class-name">Integer</span><span class="token punctuation">></span></span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// ĐÚNG</span>
</code></pre><div class="line-numbers" aria-hidden="true"><div class="line-number"></div><div class="line-number"></div></div></div><hr>
<h2 id="_2-su-dung" tabindex="-1"><a class="header-anchor" href="#_2-su-dung" aria-hidden="true">#</a> 2. Sử dụng</h2>
<p>Để tạo một đối tượng <code v-pre>Wrapper</code> như sau :</p>
<div class="language-java line-numbers-mode" data-ext="java"><pre v-pre class="language-java"><code><span class="token keyword">public</span> <span class="token keyword">class</span> <span class="token class-name">Main</span> <span class="token punctuation">{</span>
  <span class="token keyword">public</span> <span class="token keyword">static</span> <span class="token keyword">void</span> <span class="token function">main</span><span class="token punctuation">(</span><span class="token class-name">String</span><span class="token punctuation">[</span><span class="token punctuation">]</span> args<span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token class-name">Integer</span> myInt <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>
    <span class="token class-name">Double</span> myDouble <span class="token operator">=</span> <span class="token number">5.99</span><span class="token punctuation">;</span>
    <span class="token class-name">Character</span> myChar <span class="token operator">=</span> <span class="token char">'A'</span><span class="token punctuation">;</span>
    <span class="token class-name">System</span><span class="token punctuation">.</span>out<span class="token punctuation">.</span><span class="token function">println</span><span class="token punctuation">(</span>myInt<span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token class-name">System</span><span class="token punctuation">.</span>out<span class="token punctuation">.</span><span class="token function">println</span><span class="token punctuation">(</span>myDouble<span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token class-name">System</span><span class="token punctuation">.</span>out<span class="token punctuation">.</span><span class="token function">println</span><span class="token punctuation">(</span>myChar<span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
<span class="token comment">/* Output : 5
            5.99
            A
*/</span>
</code></pre><div class="line-numbers" aria-hidden="true"><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div></div></div><blockquote>
<p>Debug như sau :</p>
<img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/02/16-16-08-52-Ảnh chụp Màn hình 2021-02-16 lúc 16.07.14.png" title="" alt="Ảnh chụp Màn hình 2021-02-16 lúc 16.07.14.png" width="283">
<p>Vì là <code v-pre>Object</code> nên bạn có thể sử dụng các <code v-pre>method</code> lên nó như <code v-pre>intValue()</code>, <code v-pre>byteValue()</code>, <code v-pre>shortValue()</code>, <code v-pre>longValue()</code>, <code v-pre>floatValue()</code>, <code v-pre>doubleValue()</code>, <code v-pre>charValue()</code>, <code v-pre>booleanValue()</code>..</p>
</blockquote>
<p>Bạn cũng có thể sử dụng <code v-pre>toString</code> để chuyển thành chuỗi, và <code v-pre>length()</code> để biết độ dài chuỗi như sau :</p>
<div class="language-java line-numbers-mode" data-ext="java"><pre v-pre class="language-java"><code><span class="token keyword">public</span> <span class="token keyword">class</span> <span class="token class-name">Main</span> <span class="token punctuation">{</span>
  <span class="token keyword">public</span> <span class="token keyword">static</span> <span class="token keyword">void</span> <span class="token function">main</span><span class="token punctuation">(</span><span class="token class-name">String</span><span class="token punctuation">[</span><span class="token punctuation">]</span> args<span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token class-name">Integer</span> myInt <span class="token operator">=</span> <span class="token number">100</span><span class="token punctuation">;</span>
    <span class="token class-name">String</span> myString <span class="token operator">=</span> myInt<span class="token punctuation">.</span><span class="token function">toString</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token class-name">System</span><span class="token punctuation">.</span>out<span class="token punctuation">.</span><span class="token function">println</span><span class="token punctuation">(</span>myString<span class="token punctuation">.</span><span class="token function">length</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
<span class="token comment">//Output : 3</span>
</code></pre><div class="line-numbers" aria-hidden="true"><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div></div></div><table>
<thead>
<tr>
<th>🔙  <a href="https://github.com/Zenfection/Java/blob/master/Java%20Advaced/8.Iterator.md" target="_blank" rel="noopener noreferrer">Bài 8.Iterator<ExternalLinkIcon/></a></th>
<th><a href="https://github.com/Zenfection/Java/blob/master/Java%20Advaced/10.Exceptions.md" target="_blank" rel="noopener noreferrer">Bài 10.Exceptions<ExternalLinkIcon/></a> 🔜</th>
</tr>
</thead>
</table>
</div></template>


