---
layout: post
title: "Una demostración de la infinitud de los números primos"
date: 2025-11-24
---

<script type="text/javascript" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

Mientras escribía mi tesis encontré, según yo, una nueva demostración sobre la demostración de los números
primos. Esta nueva demostración consiste en encontrar todos los números que son coprimos a toda una colección
de números. De cierta manera es una generalización de la demostración de Euclides.

<a href="https://m1anm3.github.io/assets/DemoPrimos.pdf" target="_blank">Archivo PDF</a>

<iframe src="https://m1anm3.github.io/assets/DemoPrimos.pdf" width="100%" height="600px">
  Este navegador no soporta PDFs. Puedes descargarlo
  <a href="https://m1anm3.github.io/assets/DemoPrimos.pdf">aquí</a>.
</iframe>

Mi duda ahora es si esto de generalizar la demostración de Euclides es útil para demostrar que otros conjuntos
de números son infinitos. Por ejemplo, el conjunto de los números pares $$2\mathbb{Z}^{+}$$ satisface que

$$
\operatorname{Cop}_{*}(2\mathbb{Z}^{+}) = \{1\}.
$$

Lo anterior es trivial, pero su complemento $$\mathbb{Z}^{+}\setminus 2\mathbb{Z}^{+}$$, que es igual un
conjunto infinito, satisface que su imagen $$\operatorname{Cop}_{*}(\mathbb{Z}^{+}\setminus 2\mathbb{Z}^{+})$$
es infinita ya que 

$$
\{2^{n}\in\mathbb{Z}^{+}\mid n\in\mathbb{Z}^{+}\} \subseteq \operatorname{Cop}_{*}(\mathbb{Z}^{+}\setminus 2\mathbb{Z}^{+}).
$$

Esto nos dice que es posible que si $$X$$ infinito, entonces $$\operatorname{Cop}_{*}(X)$$ es infinito.