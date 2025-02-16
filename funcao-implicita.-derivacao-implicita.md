---
description: Teorema da função implícita.
---

# 🗃️ Função implícita. Derivação implícita

A equação da circunferência com centro em $$(0,0)$$ e raio $$r>0$$ é&#x20;

$$
x^2+y^2=r^2
$$

Podemos obter uma expressão para $$y$$ em termos de $$x$$ a partir da equação da circunferência; a saber,&#x20;

$$
y=\sqrt{r^2-x^2}\quad\textsf{ou}\quad y=-\sqrt{r^2-x^2} .
$$

desde que as expressões acima [**façam sentido**](#user-content-fn-1)[^1]. Ora bem, nem sempre é possível fazer isto; por exemplo, como escrevemos explicitamente $$y$$ como função de $$x$$ em $$\mathbb{R}$$, a partir da equação $$y^2+xy+x^2=0\,\, ?$$

Podem estar a pensar em usar a [**fórmula resolvente** ](https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%A3o_quadr%C3%A1tica)para $$y$$. Qual é o **problema**?)

O Teorema da Função Implícita que veremos logo dá condições sobre uma equação para que, pelo menos localmente, podamos afirmar que é possível escrever uma variável em termos das outras. O Teorema não dá uma fórmula explícita, só garante que tal fórmula existe na vizinhança de um ponto.

Portanto, digamos que&#x20;

$$
F(x,y)=0 ,
$$

é uma **equação geral** em duas variáveis e suponhamos que existe um ponto $$(a,b)\in\mathbb{R}^2$$ tal que $$F(a,b)=0$$; ou seja, $$(a,b)$$ é um **zero** de $$F$$. Assumamos por agora que é possível escrever $$y=f(x)$$ numa vizinhança de $$(a,b)$$ a partir da equação, ou seja

$$
F\big(x,f(x)\big)=0 .
$$

Que podemos fazer? Nesta altura do campeonato vemos derivadas por todos lados e portanto, é natural quer [**derivar a equação**](derivada-da-funcao-composta..md) em relação a $$x$$. Desta forma, obtemos

$$
\frac{\partial F}{\partial x}\cdot\frac{dx}{dx}+\frac{\partial F}{\partial y}\cdot\frac{dy}{dx} = 0 .
$$

Como $$\frac{dx}{dx}=1$$, e se $$\frac{\partial F}{\partial y}\neq 0$$, poderíamos resolver para $$\frac{dy}{dx}$$  e obter&#x20;

$$
\frac{dy}{dx}=-\frac{\frac{\partial F}{\partial x}}{\frac{\partial F}{\partial y}} .
$$

{% hint style="warning" %}
E se temos uma equação em três ou mais variáveis, é a mesma história? :thinking:
{% endhint %}

## Teorema da Função implícita.

Se $$F$$ está definida num [**disco aberto**](#user-content-fn-2)[^2] $$D$$ que contém o ponto $$(a,b)$$, onde $$F(a,b)=0$$, $$F_x$$ e $$F_y$$ são [**contínuas em**](#user-content-fn-3)[^3] $$\bm{D}$$, e $$F_y(a,b)\neq 0$$, então a equação $$F(x,y)=0$$ define $$y$$ como função de $$x$$, numa vizinhança do ponto $$(a,b)$$, e a derivada desta função em $$a$$ é&#x20;

$$
\frac{dy}{dx}\small(a)=-\frac{\frac{\partial F}{\partial x}\scriptsize(a,b)}{\frac{\partial F}{\partial y}\scriptsize(a,b)} .
$$

{% hint style="warning" %}
E se se quisermos ter a garantia que podemos escrever $$x=g(y)$$ numa vizinhança do ponto $$(a,b)$$, o que temos de verificar? :thinking:
{% endhint %}

<details>

<summary>Exercício 14, Ficha I.</summary>

Considere a equação $$xy^2-x^2y+2=0$$.

a) Verifique que a equação define $$x=f(y)$$ na vizinhança do ponto $$P(2,1)$$.

b) Calcule $$\frac{dx}{dy}{\scriptsize(1)}$$.

***

a, b) Definimos primeiro a função $$F(x,y)=xy^2-x^2y+2$$. Verificamos que o ponto $$P(2,1)$$ é um zero de $$F(x,y)$$. Com efeito, temos que $$F(2,1)=2(1)^2-(2)^21+2=0$$. Agora, como queremos saber se podemos escrever $$x$$ em termos de $$y$$ perto de $$P(2,1)$$, calculamos $$\frac{\partial F}{\partial x}\scriptsize(2,1)$$, atenção  que esta derivada parcial é em relação à variável que queremos que sea a variável **dependente.** Desta forma, temos

&#x20;                 $$\dfrac{\partial F}{\partial x}(x,y) = y^2-2xy\qquad\Rightarrow\qquad \dfrac{\partial F}{\partial x}(2,1) = 1^2-2(2)1=-3$$.

Isto é uma **boa notícia!** :clap:, pois sendo que $$F$$ é um polinómio (e portanto $$F_x$$ e $$F_y$$ são contínuas em qualquer disco aberto em $$\mathbb{R}^2$$), o ponto $$P(2,1)$$ é um zero de $$F$$, e, como acabamos de verificar, $$F_x(2,1)\neq 0$$; então temos **todas as condições** que garantem que podemos escrever $$x=f(y)$$ numa vizinhança de $$(2,1)$$, pelo [Teorema da Função Implícita](funcao-implicita.-derivacao-implicita.md#teorema-da-funcao-implicita). Por último, temos também que

&#x20;                  $$\dfrac{dx}{dy}(1) = -\dfrac{F_y(2,1)}{F_x(2,1)} = -\dfrac{2xy-x^2}{y^2-2xy}\Bigg|_{(2,1)} = -\dfrac{0}{-3} = 0 .$$

</details>

[^1]: isto acontece quando $$r^2-x^2\ge 0$$

[^2]: ![](<.gitbook/assets/Captura de ecrã 2024-02-22, às 13.22.06.png>)

[^3]: $$\forall\,\,(x,y)\in D$$
