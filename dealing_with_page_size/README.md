<div id=":1b3" class="ii gt m14b3b1af6261bdc3 adP adO"><div id=":1b4" class="a3s" style="overflow: hidden;"><div dir="ltr"><div class="adM"><br></div><h3>Custom Page Size<br></h3>
<hr>
<h4>Introduction</h4>
<p>Using @media screen you can set page size</p>
<br>
<h4>Table of Paper Sizes From 4A0 to A10</h4>
<table>
<tbody><tr><td class="tdbold">Size</td><td class="tdbold">Width x Height (mm)</td><td class="tdbold">Width x Height (in)</td></tr>
<tr><td class="tdbold">4A0</td><td>1682 x 2378 mm</td><td>66.2 x 93.6 in</td></tr>
<tr><td class="tdbold">2A0</td><td>1189 x 1682 mm</td><td>46.8 x 66.2 in</td></tr>
<tr><td class="tdbold">A0</td><td>841 x 1189 mm</td><td>33.1 x 46.8 in</td></tr>
<tr><td class="tdbold">A1</td><td>594 x 841 mm</td><td>23.4 x 33.1 in</td></tr>
<tr><td class="tdbold">A2</td><td>420 x 594 mm</td><td>16.5 x 23.4 in</td></tr>
<tr><td class="tdbold">A3</td><td>297 x 420 mm</td><td>11.7 x 16.5 in</td></tr>
<tr><td class="tdbold"><a href="/a4-size-factsheet.htm">A4</a></td><td>210 x 297 mm</td><td>8.3 x 11.7 in</td></tr>
<tr><td class="tdbold">A5</td><td>148 x 210 mm</td><td>5.8 x 8.3 in</td></tr>
<tr><td class="tdbold">A6</td><td>105 x 148 mm</td><td>4.1 x 5.8 in</td></tr>
<tr><td class="tdbold">A7</td><td>74 x 105 mm</td><td>2.9 x 4.1 in</td></tr>
<tr><td class="tdbold">A8</td><td>52 x 74 mm</td><td>2.0 x 2.9 in</td></tr>
<tr><td class="tdbold">A9</td><td>37 x 52 mm</td><td>1.5 x 2.0 in</td></tr>
<tr><td class="tdbold">A10</td><td>26 x 37 mm</td><td>1.0 x 1.5 in</td></tr>
</tbody>
</table>
<br>
<p>For styling, the Boostrap CSS framework is provided and you can enjoy the full range of classes.</p>

<hr>
<h4>References</h4>
<ol><li><a href="http://jinja.pocoo.org/docs/templates/" target="_blank">Jinja Tempalting Language: Reference</a></li><li><a href="http://getbootstrap.com" target="_blank">Bootstrap CSS Framework</a></li></ol>
<hr><h4>Other Notes:</h4><p>1) Fetching document object</p><pre><code>{{ doc.customer_name }}</code></pre><p>2) Date format</p><p>{{ doc.get_formatted("po_date") or ''}}<br></p><p>3) Currency Formate <br></p><p>{{ doc.get_formatted("date") }}</p><p>4) Avoiding None in Print Format:<br></p><p>Fetching Batch number if ordered item has batch. <br></p><p>Write if condition, otherwise it will print None<br></p><p>{%- if row.batch_no -%}<br>&lt;b&gt;Batch No: &lt;/b&gt;{{ row.batch_no or '' }} &lt;br&gt;<br>{%- endif -%}<br></p><p><br></p><p>If
 you find any bug in this repository or want any help for customizing 
ERPNext, Customise print formate you can contact me or drop email.</p><div> <b>Sambhaji Kolate</b><br> <span>Software Developer</span>, <span>Systematrix Solution</span> </div><div style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"> <span style="display:inline-block"><span style="color:rgb(69,102,142)">Mobile: </span><a href="tel:9850015051" style="color:rgb(141,141,141);text-decoration:none" target="_blank">9850015051</a></span>  | <span style="display:inline-block"><span style="color:rgb(69,102,142)">Email:</span><a href="mailto:kolate.sambhaji@gmail.com" target="_blank">kolate.sambhaji@gmail.<wbr>com</a></span><br><br></div><div style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"><br>
<hr>Thanks to <a href="http://erpnext.com/" target="_blank">ERPNext</a><a> Team</a> for Great Product</div><div class="yj6qo"></div><div class="adL" style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"><br><br><br><br></div></div><div class="adL">
</div></div></div>
