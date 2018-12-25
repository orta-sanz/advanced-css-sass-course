# rem (CSS)

Le marcamos al elemento `html` un `font-size` de 10px
Entendemos que `1rem = 10px` ya que `1rem = font-size del elemento root (html)`

```
html {
	font-size: 62.5%; // Por accesibilidad, usamos percentajes. 100% = 16px así que 62.5% = 10px
}

.btn {
	padding: 1rem; // Serán 10px
}
```