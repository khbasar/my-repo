# Test Lagi Markdown
Paragraf biasa
Persamaan atau simbol inline 
$$ \alpha \beta \gamma \sin(x)$$

---
## Berikut ini jika kita ingin membuat slide presentasi

* Item 
* item

---
Sedang dicoba memanfaatkan fasilitas synchronize dengan folder di github. Dengan demikian tulisan yang dibuat melalui browser menggunakan [Stackedit](https://stackedit.io) akan langsung tersimpan di folder yang ada di [Github](github.com/khbasar).

---
### 06032024

> kutipan 
> kutipan berikutnya
>> sub kutipan

`kode` inline pada suatu teks.

``bagaimana dengan yang ini?``

```Kalau yang ini bagaimana? Apa bedanya menggunakan tiga tanda apostrof (?)``` 

---
## Bisakah menggunakan kode $\LaTeX{}$?

Simbol dan persamaan inline dalam suatu teks dituliskan di antara sepasang tanda _single dollar_. Tampilan $\LaTeX{}$, atau simbol huruf Yunani: $\alpha, \beta, \gamma,\epsilon,\xi$ dlsb. Juga persamaan inline: $E=mc^2$, $\vec{F}=\tfrac{d\vec{p}}{dt}$. 

Sedangkan untuk displayed equation dituliskan di antara tanda _double dollar_. Misalnya persamaan berikut ini:
$$
I=\frac{1}{2\pi\,i}\oint\limits_{\substack{\text{lintasan}\\ \text{khusus}}} \frac{e^{(-2i\theta)}}{\theta^2}\;d\theta
$$

### Bisakah menampilkan gambar yang dibuat menggunakan TikZ?

$$
\begin{tikzpicture}
\draw (0,0) rectangle ++(2,2);
\end{tikzpicture}
$$

Ternyata tidak bisa, karena jenis $\LaTeX{}$ yang digunakan di [Stackedit](stackedit.io) ini rupanya adalah $\KaTeX{}$ yang tidak mengenali paket TikZ. 

Berarti... yang paling menarik (paling tidak sampai saat ini) ya... [Upmath](upmath.me).


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc0Mjc0MjU1NywxMTkzMzQ3MzUzLC0xMz
czMzQxMTkwLC0zMDYwNzU4NjJdfQ==
-->