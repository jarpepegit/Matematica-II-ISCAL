---
description: Definição do vetor gradiente, interpretação geométrica.
---

# 🗃️ Vetor gradiente

A partir das derivadas parciais, construimos um vetor que chamaremos de vetor gradiente.

## Definição.

Seja $$f\colon\mathbb{R}^2\to\mathbb{R}$$ e $$p\in\operatorname{Dom}f$$, o **vetor gradiente** de $$f$$ no ponto $$p\in\operatorname{Dom}f$$ é o vetor cujas coordenadas são dadas pelas derivadas parciais de $$f$$ em $$p$$.

$$
\nabla f (p) = \left(\dfrac{\partial f}{\partial x}(p),\dfrac{\partial f}{\partial y}(p)\right) .
$$

{% hint style="warning" %}
O vetor gradiente ilustra-se no plano **XY** para uma função em duas variáveis. E para uma função em três variáveis?
{% endhint %}

## Interpretação geométrica.

{% embed url="https://www.geogebra.org/classic/n2p2dcuh" %}
Ilustração do vetor gradiente da função $$\small f(x,y)=x^2+y^2$$ no ponto $$\small p$$.
{% endembed %}



{% hint style="warning" %}
O vetor gradiente é **perpendicular** às curvas de nível de $$f$$. A prova deste resultado vimos nas aulas. Para o exemplo acima vimos que a reta tangente à $$C$$ que passa pelo ponto $$p=(x_p,y_p)$$, tem direção $$\vec{v}=(y_p,-x_p)$$. Dado que $$\nabla f(p)=2(x_p,y_p)$$, temos que

&#x20;               $$\nabla f(p) \cdot \vec{v} = 2(x_p,y_p) \cdot (y_p,-x_p) = 0 .$$
{% endhint %}

## Vídeo elucidativo

{% embed url="https://www.youtube.com/watch?t=42s&v=tIpKfDc295M" %}
Vídeo criado por Grant Sanderson
{% endembed %}
