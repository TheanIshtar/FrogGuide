<template><div><h1 id="toan-tu-muc-luc" tabindex="-1"><a class="header-anchor" href="#toan-tu-muc-luc" aria-hidden="true">#</a> Toán tử---------------------------------------<a href="https://github.com/Zenfection/Java" target="_blank" rel="noopener noreferrer">Mục lục<ExternalLinkIcon/></a></h1>
<p>Được sử dụng để thực hiện trên phép tính của các biến với nhau, có <strong>5</strong> nhóm sau :</p>
<ul>
<li><code v-pre>Arithmetic</code> : <em>Toán tử số học</em></li>
<li><code v-pre>Assignment</code> : <em>Toán tử gán</em></li>
<li><code v-pre>Comparsion</code> : <em>Toán tử so sánh</em></li>
<li><code v-pre>Logical</code> : <em>Toán tử logic</em></li>
<li><code v-pre>Bitwise</code> : <em>Toán tử thao tác bit</em></li>
</ul>
<hr>
<h2 id="_1-toan-tu-so-hoc-arithmetic" tabindex="-1"><a class="header-anchor" href="#_1-toan-tu-so-hoc-arithmetic" aria-hidden="true">#</a> 1. Toán tử số học (<code v-pre>Arithmetic</code>)</h2>
<p>Có các loại toán tử sau đây :</p>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Miêu tả</th>
<th>Ví dụ</th>
</tr>
</thead>
<tbody>
<tr>
<td>+</td>
<td>Phép cộng</td>
<td>2 + 3 ⇨ 5</td>
</tr>
<tr>
<td>-</td>
<td>Phép trừ</td>
<td>2 - 3 ⇨ -1</td>
</tr>
<tr>
<td>*</td>
<td>Phép nhân</td>
<td>2 * 3 ⇨ 6</td>
</tr>
<tr>
<td>/</td>
<td>Phép chia</td>
<td>2 / 3 ⇨ 0</td>
</tr>
<tr>
<td>%</td>
<td>Phép chia lấy dư</td>
<td>2 % 3 ⇨ 2</td>
</tr>
<tr>
<td>++</td>
<td>tăng thêm 1</td>
<td>2++ ⇨ 3</td>
</tr>
<tr>
<td>--</td>
<td>giảm lại 1</td>
<td>2-- ⇨ 1</td>
</tr>
</tbody>
</table>
<blockquote>
<p>🤔 Bạn chỉ cần nhớ toán tử số học là <code v-pre>cộng, trừ, nhân, chia</code></p>
</blockquote>
<hr>
<h2 id="_2-toan-tu-gan-assignment" tabindex="-1"><a class="header-anchor" href="#_2-toan-tu-gan-assignment" aria-hidden="true">#</a> 2. Toán tử gán (<code v-pre>Assignment</code>)</h2>
<p>Có các loại toán tử sau :</p>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Miêu tả</th>
<th>Ví dụ (<em>a = 2</em>)</th>
</tr>
</thead>
<tbody>
<tr>
<td>=</td>
<td>phép gán</td>
<td>a = 2</td>
</tr>
<tr>
<td>+=<br>-=<br>*=<br>/=<br>%=</td>
<td>phép cộng và gán<br>phép trừ và gán<br>phép nhân và gán<br>phép chia và gán<br>phép chia lấy dư vá gán</td>
<td>a <strong>+=</strong> 3  ⇨ <strong>a = 5</strong><br>a -= 3   ⇨ <strong>a = -1</strong><br>a *<strong>=</strong> 3  ⇨ <strong>a = 6</strong><br>a <strong>/=</strong> 3   ⇨ <strong>a = 0</strong><br>a <strong>%=</strong> 3 ⇨ <strong>a = 2</strong><br></td>
</tr>
</tbody>
</table>
<hr>
<h2 id="_3-toan-tu-so-sanh-comparision" tabindex="-1"><a class="header-anchor" href="#_3-toan-tu-so-sanh-comparision" aria-hidden="true">#</a> 3. Toán tử so sánh (<code v-pre>Comparision</code>)</h2>
<p>Có các loại toán tử sau :</p>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Miêu tả</th>
<th>Ví dụ (<em>a = 2</em>)</th>
</tr>
</thead>
<tbody>
<tr>
<td>==<br>!=</td>
<td>bằng<br>không bằng</td>
<td>a <strong>==</strong> 2<br>a <strong>!=</strong> 3</td>
</tr>
<tr>
<td>&gt;<br>&lt;</td>
<td>lớn hơn<br>nhỏ hơn</td>
<td>a <strong>&gt;</strong> 1<br>a <strong>&lt;</strong> 3</td>
</tr>
<tr>
<td>&gt;=<br>&lt;=</td>
<td>lớn hơn hoặc bằng<br>nhỏ hơn hoặc bằng</td>
<td>a <strong>&gt;=</strong> 2<br>a <strong>&lt;=</strong> 2</td>
</tr>
</tbody>
</table>
<hr>
<h2 id="_4-toan-tu-logic-logical" tabindex="-1"><a class="header-anchor" href="#_4-toan-tu-logic-logical" aria-hidden="true">#</a> 4.Toán tử logic (<code v-pre>Logical</code>)</h2>
<p>Có các loại toán tử sau :</p>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Miêu tả</th>
<th>Ví dụ (<em>a = 2</em>)</th>
</tr>
</thead>
<tbody>
<tr>
<td>&amp;&amp;</td>
<td>Phép <strong>và</strong> : <em>nếu cả hai true thì true</em> <br><em>một trong hai false thì false</em></td>
<td>a <strong>&gt;</strong> 1 <strong>&amp;&amp;</strong> a <strong>==</strong> 2</td>
</tr>
<tr>
<td>||</td>
<td>Phép <strong>hoặc</strong> : <em>nếu cả 2 false thì false</em><br><em>một trong hai true thì true</em></td>
<td>a <strong>&lt;</strong> 1 <strong>||</strong> a <strong>==</strong> 2</td>
</tr>
<tr>
<td>!</td>
<td>Phép <strong>phủ</strong> : <em>true thành false</em> và <em>false thành true</em></td>
<td><strong>!a</strong></td>
</tr>
</tbody>
</table>
<blockquote>
<p>🔥 Phép phủ tức là ngược lại : <code v-pre>true</code> ⇨ <code v-pre>false</code> và <code v-pre>false</code> ⇨ <code v-pre>true</code></p>
</blockquote>
<hr>
<h2 id="_5-toan-tu-bit-bitwise" tabindex="-1"><a class="header-anchor" href="#_5-toan-tu-bit-bitwise" aria-hidden="true">#</a> 5. Toán tử Bit (<code v-pre>Bitwise</code>)</h2>
<p>Đây là thao tác trên <code v-pre>Bit</code>, các bạn không cần phải hiểu nó quá kỹ, biết là có là được.</p>
<table>
<thead>
<tr>
<th>Toán tử</th>
<th>Miêu tả</th>
<th>Ví dụ (<em>A = 2 và B = 3</em>)</th>
</tr>
</thead>
<tbody>
<tr>
<td>&amp;</td>
<td>Phép <strong>And bit</strong></td>
<td>A <strong>&amp;</strong> B ⇨ 2</td>
</tr>
<tr>
<td>!</td>
<td>Phép <strong>OR bit</strong></td>
<td>A <strong>|</strong> B ⇨ 3</td>
</tr>
<tr>
<td>^</td>
<td>Phép <strong>XOR bit</strong></td>
<td>A <strong>^</strong> B ⇨ 1</td>
</tr>
<tr>
<td>~</td>
<td>Phép <strong>phủ bit</strong></td>
<td>~B  ⇨ -4</td>
</tr>
<tr>
<td>&lt;&lt;</td>
<td>Phép <strong>dịch trái</strong></td>
<td>A <strong>&lt;&lt;</strong> 1 ⇨ 4</td>
</tr>
<tr>
<td>&gt;&gt;</td>
<td>Phép <strong>dịch phải</strong></td>
<td>A <strong>&gt;&gt;</strong> 1 ⇨ 1</td>
</tr>
<tr>
<td>&gt;&gt;&gt;</td>
<td>Phép <strong>dịch phải với Zero</strong></td>
<td>A <strong>&gt;&gt;&gt;</strong> 1 ⇨ 1</td>
</tr>
</tbody>
</table>
<blockquote>
<p>🔥 Nếu bạn muốn tìm hiểu, hãy xem <a href="https://openplanning.net/12281/cac-toan-tu-bitwise" target="_blank" rel="noopener noreferrer">tại đây<ExternalLinkIcon/></a></p>
<p>💡 Bạn không cần phải hiểu quá nhiều về vấn đề này</p>
</blockquote>
<table>
<thead>
<tr>
<th>🔙  <a href="https://github.com/Zenfection/Java/blob/master/Java%20Basic/5.Kieudulieu.md" target="_blank" rel="noopener noreferrer">Bài 5. Kiểu dữ liệu<ExternalLinkIcon/></a></th>
<th><a href="https://github.com/Zenfection/Java/blob/master/Java%20Basic/7.Dieukien.md" target="_blank" rel="noopener noreferrer">Bài 7. Điều kiện<ExternalLinkIcon/></a> 🔜</th>
</tr>
</thead>
</table>
</div></template>


