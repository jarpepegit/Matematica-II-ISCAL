---
description: >-
  Definição, um exemplo de cálculo de derivadas parciais, e um vídeo
  ilustrativo.
cover: .gitbook/assets/file.excalidraw.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🗃️ Derivadas parciais

Recordemos que para uma função real numa variável real, $$f\colon\mathbb{R}\to\mathbb{R}$$, a derivada de $$f$$ no ponto $$a\in\operatorname{Dom}f$$, interpreta-se como o **declive** da reta tangente ao gráfico de $$f$$ que passa por $$a$$. Ela é obtida da seguinte forma,

$$
\dfrac{df}{dx}(a)=\displaystyle\lim_{h\to 0}\dfrac{f(a+h)-f(a)}{h} .
$$

Queremos extender a definição dada acima para funções reais em várias variáveis. Para fixar ideias, consideremos funções $$f\colon\mathbb{R}^2\to\mathbb{R}.$$

## **Definição**.

As derivadas parciais de $$f$$no ponto $$(a,b)\in\operatorname{Dom}f$$, em relação a $$x$$ e $$y$$, são dadas por

$$
\begin{matrix}\dfrac{\partial f}{\partial x}(a,b)=\displaystyle\lim_{h\to 0}\dfrac{f(a+h,b)-f(a,b)}{h} .\\[5ex] \dfrac{\partial f}{\partial y}(a,b)=\displaystyle\lim_{h\to 0}\dfrac{f(a,b+y)-f(a,b)}{h} . \end{matrix}
$$

{% hint style="info" %}
**Notação:**  $$\dfrac{\partial f}{\partial x} , \,\,\partial_x f,\,\, f_x, \,\,D_1f  .$$ Similarmente, se a variável de derivação é $$y$$, temos $$\dfrac{\partial f}{\partial y} , \,\,\partial_y f,\,\, f_y, \,\,D_2f  .$$ A notação mais usual é a primeira.
{% endhint %}

<details>

<summary><strong>Exemplo</strong>. </summary>

$$f(x,y)=x^2y+\sin y .$$

$$\dfrac{\partial f}{\partial x}(a,b) = \partial_x\Big(x^2y+\sin y\Big)\Bigg|_{x=a \atop y=b}=2xy\Bigg|_{x=a \atop y=b}=2ab$$.

$$\dfrac{\partial f}{\partial y}(a,b) = \partial_y\Big(x^2y+\sin y\Big)\Bigg|_{x=a \atop y=b}=\Big(x^2+\cos y\Big)\Bigg|_{x=a \atop y=b}=a^2+\cos b$$

</details>

## Vídeo elucidativo

{% embed url="https://www.youtube.com/watch?v=kdMep5GUOBw" %}
Vídeo criado por Grant Sanderson
{% endembed %}
