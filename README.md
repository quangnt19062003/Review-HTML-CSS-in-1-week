# Review-HTML-CSS-in-1-week
Review html/css in 1 week

## HTML syntaxes to remember

### Thẻ meta
**Thẻ meta charset**
</br>
&lt;meta charset=”UTF-8”/&gt;
</br>
**Thẻ meta title**
</br>
&lt;title&gt; ///description &lt;/title&gt;
</br>
**Thẻ meta viewport**
</br>
&lt;meta name=”viewport” content=”width=device-width, initial-scale=1.0”/&gt;
</br>
**Thẻ meta Open Graph (*)**
</br>
&lt;meta property =””&gt;

### &lt;h1 - h6&gt; 
Heading - Tiêu đề, thông thường h1 được sử dụng cho tiêu đề chính của trang web, mỗi trang web **chỉ nên có một** thẻ h1, các thẻ h cấp sau sẽ là tiêu đề con cho các thẻ h cấp trên
### &lt;p&gt;
Paragraph - Văn bản, thể hiện một đoạn văn bản
### &lt;a&gt;
Anchor - Móc neo, thể hiện một liên kết
<br/> Các thuộc tính ở trong thẻ a
<ul>
  <li>href : đường dẫn cần chỉ đến, tel:, mailto:,...</li>
  <li>target : chỉ định nơi mở đường dẫn, _blank, _self,... </li>
</ul>

### &lt;b&gt; and &lt;strong&gt;
Bold - in đậm, cà 2 đều in đậm đoạn nội dung, tuy nhiên khác nhau về cách sử dụng, thẻ b được sử dụng khi muốn **in đậm gây sự chú ý** một đoạn nội dung, thẻ strong được sử dụng khi muốn **thể hiện sự quan trọng, nghiêm trọng,...**
### &lt;i&gt; and &lt;em&gt;
Italic - chữ nghiêng, cả 2 đều dùng để in nghiêng đoạn nội dung, tuy nhiên khác nhau về cách sử dụng, thẻ i được sử dụng khi **thể hiện các thuật ngữ chuyên ngành**, thẻ em được sử dụng để **nhấn mạnh**
### &lt;u&gt;
Underline - gạch dưới, thể hiện một đoạn nội dung với dòng gạch chân ở phía dưới
### &lt;img&gt;
Image - Hình ảnh, thể hiện một hình ảnh, có nhiều dạng hình ảnh như: JPG, JPEG, PNG, SVG, GIF,...
<br/> Các thuộc tính ở trong thẻ img
<ul>
  <li>src : đường dẫn của hình ảnh</li>
  <li>alt : nội dung hiển thị khi hình ảnh bị lỗi</li>
  <li>width, height : chỉ định độ rộng và độ dài cho hình ảnh </l>     
</ul>

### &lt;ul&gt; and &lt;ol&gt;
Unordered List - Danh sách không có thứ tự, Ordered List - Danh sách có thứ tự

<code>&lt;ul&gt;
      &lt;li&gt; Item &lt;li/&gt;
&lt;ul/&gt;
</code>
<br/> Các thuộc tính ở trong thẻ ol
<ul>
  <li>reserved : đảo ngược số thứ tự</li>
  <li>start = "?" : bắt đầu từ số thự tự ? </li>
  <li>type : đặt kiểu cho market, i, I, a, A, 1 </l>     
</ul>

### &lt;figure&gt; and &lt;figcaption&gt;
Sử dụng phần tử &lt;figure&gt; để đánh dấu ảnh trong tài liệu và phần tử &lt;figcaption&gt; để xác định chú thích cho ảnh
<code>&lt;figure&gt;
  &lt;img src=&quot;pic_trulli.jpg&quot; alt=&quot;Trulli&quot; style=&quot;width:100%&quot;&gt;
  &lt;figcaption&gt;Fig.1 - Trulli, Puglia, Italy.&lt;/figcaption&gt;
&lt;/figure&gt;
</code>

### Các trang web tham khảo
**Bên trên chỉ là một vài thẻ căn bản cần nhớ**
https://www.w3schools.com/html/default.asp
https://htmlreference.io/
