---
description: Diagramas de árvore. Regra da cadeia.
---

# 🗃️ Derivada da função composta.

## Regra da Cadeia

<figure><img src=".gitbook/assets/Captura de ecrã 2024-02-22, às 02.08.23.png" alt="" width="375"><figcaption><p>Contando os caminhos que levam de <span class="math">f</span>a uma variável</p></figcaption></figure>

Suponhamos que queremos calcular $$\frac{\partial f}{\partial s}$$. No diagrama mostrado seguimos todos os caminos que levam de $$f$$ para $$s$$. Assim, temos que

$$
\frac{\partial f}{\partial s} = \frac{\partial f}{\partial x}\cdot\frac{\partial x}{\partial s} + \frac{\partial f}{\partial y}\cdot\frac{\partial y}{\partial s}
$$

<details>

<summary>Exercício 10 a), Ficha I. </summary>

Calcule $$\frac{\partial z}{\partial x}$$ e $$\frac{\partial z}{\partial y}$$ , sendo $$z=u^2v^3$$ com $$u=x+y$$ e $$v=x^2-y^2$$.

***

Utilizamos o diagrama acima, substituimos $$f$$ por $$z$$, $$x$$ por $$u$$ , $$y$$ por $$v$$, $$s$$ por $$x$$ , e $$t$$ por $$y$$. Assim, temos que

$$\frac{\partial z}{\partial x} = \frac{\partial z}{\partial u}\cdot\frac{\partial u}{\partial x} + \frac{\partial z}{\partial v}\cdot\frac{\partial v}{\partial x}$$ e $$\frac{\partial z}{\partial y} = \frac{\partial z}{\partial u}\cdot\frac{\partial u}{\partial y} + \frac{\partial z}{\partial v}\cdot\frac{\partial v}{\partial y}$$

de modo que:

$$\begin{array}{lcl}\frac{\partial z}{\partial x} &=& \small 2uv^3\cdot 1 + 3u^2v^2\cdot 2x  \\[1ex] &=& \small 2(x+y)(x^2-y^2)^3 + 3(x+y)^2(x^2-y^2)^2 2x\end{array} .$$

e

$$\begin{array}{lcl}\frac{\partial z}{\partial y} &=& \small 2uv^3\cdot 1 + 3u^2v^2\cdot (-2y) \\[1ex] &=& \small 2(x+y)(x^2-y^2)^3 + 3(x+y)^2(x^2-y^2)^2 (-2y)\end{array}.$$





</details>
