---
description: >-
  Derivadas de ordem 2 ou mais. Teorema de Schwarz. Equações em derivadas
  parciais.
---

# 🗃️ Derivadas de ordem superior

Seja $$f:\mathbb{R}^2\to\mathbb{R}$$. Se considerarmos as derivadas parciais de primeira ordem, $$f_x$$ e $$f_y$$  de $$f$$,  como funções em $$\mathbb{R}^2$$, podemos também derivá-las em ordem a $$x$$ e $$y$$. Desta forma, as derivadas parciais de $$f_x$$e $$f_y$$, em relação a $$x$$ e $$y$$, são as derivadas de segunda ordem de $$f$$, e assim sucessivamente.&#x20;

## Diagrama de árvore ilustrativo

<figure><img src=".gitbook/assets/Captura de ecrã 2024-02-20, às 04.42.27.png" alt="" width="375"><figcaption><p>Derivadas parciais de segunda ordem</p></figcaption></figure>

{% hint style="info" %}
**Notação:**  $$f_{xx}(x,y) = \frac{\partial^2}{\partial x^2}f(x,y)=\partial x\big(\partial x f(x,y)\big)$$ ,&#x20;

$$f_{yy}(x,y) = \frac{\partial^2}{\partial y^2}f(x,y)=\partial y\big(\partial y f(x,y)\big)$$,&#x20;

$$f_{xy}(x,y) = \frac{\partial^2}{\partial y \partial x}f(x,y)=\partial y\big(\partial x f(x,y)\big)$$,&#x20;

$$f_{yx}(x,y) = \frac{\partial^2}{\partial x\partial y}f(x,y)=\partial x\big(\partial y f(x,y)\big)$$.

As derivadas parciais $$f_{xy}$$ e $$f_{yx}$$ são chamadas de **derivadas mistas**.
{% endhint %}

## Definição.&#x20;

Seja $$f:\mathbb{R}^2\to\mathbb{R}$$ e $$p\in U\subset\operatorname{Dom}f$$, onde $$U$$ é um [**disco aberto**](#user-content-fn-1)[^1] que contém o ponto $$p$$. Diz-se que $$f$$ é de **classe** $$C^2$$ em $$U$$, se todas as derivadas parciais de segunda ordem de $$f$$ são contínuas em $$U$$.

## Teorema de Schwarz.&#x20;

Se $$f$$ é uma função de classe $$C^2$$ num ponto $$p$$, então as derivadas parciais mistas são iguais.

{% hint style="info" %}
Os polinómios em várias variáveis são funções de classe $$C^2$$ em $$\mathbb{R}^n$$.&#x20;
{% endhint %}

<details>

<summary>Exercício 4e) , Ficha I.</summary>

Calcule as derivadas parciais de segunda ordem de $$f(x,y)=\ln(x^2y^2)$$.

***

Note-se que $$x\neq 0$$ e $$y\neq 0$$ para que $$f$$ esteja bem definida. Dito isto, temos que

$$\partial_xf=\frac{2xy^2}{x^2y^2}=\frac{2}{x}$$   ,   $$\partial_yf(x,y)=\frac{2x^2y}{x^2y^2}=\frac{2}{y}$$.

$$\partial_x\partial_xf(x,y)=-\frac{2}{x^2}$$   ,   $$\partial_y\partial_yf(x,y)=-\frac{2}{y^2}$$.

$$\partial_y\partial_xf(x,y)=0$$   ,   $$\partial_x\partial_yf(x,y)=0$$.

</details>

[^1]: $$U=\big\{(x,y)\in\mathbb{R}^2: (x-c_1)^2)+(y-c_2)^2<r^2\big\}$$

    para algum $$r>0$$, com $$c_1, c_2\in\mathbb{R}.$$
