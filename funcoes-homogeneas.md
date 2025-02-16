---
description: Função homogénea, grau, exemplo.
---

# 🗃️ Funções homogéneas

## Definição.&#x20;

Uma função $$f:\mathbb{R}^n\to\mathbb{R}$$ chama-se **homogénea** de **grau** $$\mathbf{\alpha}$$ se satisfaz a seguinte equação

$$
f(t\bm{x})=t^\alpha f(\bm{x}),\qquad\forall\,t\in\mathbb{R},
$$

onde $$\alpha$$ é um inteiro positivo e $$f$$ tem derivadas parciais de segunda ordem contínuas. Se a expressão $$f(t\bm{x})$$ faz sentido para qualquer $$t$$ excepto $$t=0$$, podemos adaptar a definição de homogeneidade e dizer que $$f$$ é uma função homogénea de grau $$\alpha\in\mathbb{Z}$$, se satisfaz a equação

$$
f(t\bm{x}) = t^\alpha f(\bm{x}),\qquad \forall\,t\in\mathbb{R}\setminus\{0\}.
$$

<details>

<summary>Exemplo.</summary>

O polinómio $$f(x,y)=x^2y+2xy^2+5y^3$$ de grau $$3$$ é uma função homogénea de grau $$3$$, pois claramente

&#x20;                               $$f(tx,ty)=t^3f(x,y)$$

</details>
