---
description: >-
  Máximos e mínimos relativos e absolutos. Ponto crítico. Matriz Hessiana.
  Critério da segunda derivada. Teoremas análogos aos teoremas de Fermat e
  Weierstrass.
---

# 🗃️ Extremos relativos e absolutos

## Pontos extremos.

Uma função real de $$n$$ variáveis reais tem um **máximo local** em $$\bm{(a_1,a_2,\ldots,a_n)}\in\operatorname{Dom}f$$, se $$f(x_1,x_2,\ldots,x_n)\le f(a_1,a_2,\ldots,a_n)$$ quando $$(x_1,x_2,\ldots,x_n)$$ está **próximo** de $$(a_1,a_2,\ldots,a_n)$$. O número $$\bm{f(a_1,a_2,\ldots,a_n)}$$ é chamado de **valor máximo local**.

Se $$f(x_1,x_2,\ldots,x_n)\ge f(a_1,a_2,\ldots,a_n)$$ quando $$(x_1,x_2,\ldots,x_n)$$ está próximo de $$(a_1,a_2,\ldots,a_n)$$, então $$\bm{(a_1,a_2,\ldots,a_n)}$$ é um **mínimo local** e $$\bm{f(a_1,a_2,\ldots,a_n)}$$ é um **valor mínimo local**.

{% hint style="info" %}
Se as desigualdades na Definição[^1] se mantiverem para todos os pontos no domínio de $$f$$, então $$f$$ tem um **máximo absoluto** (ou **mínimo absoluto**) em $$(a_1,a_2,\ldots,a_n)$$.
{% endhint %}

## Ponto crítico.

Um ponto $$(a_1,a_2,\ldots,a_n)$$ é chamado de **ponto crítico** de $$f$$ se

$$
\small f_{x_1}(a_1,a_2,\ldots,a_n)=0\quad,\quad f_{x_2}(a_1,a_2,\ldots,a_n)=0 \quad,\ldots,\quad f_{x_n}(a_1,a_2,\ldots,a_n)=0
$$

**ou** se alguma destas derivadas parciais **não existe**.

## Teorema (análogo ao do Fermat para funções numa variável).

Se $$f$$ **tem** um **máximo** ou **mínimo** local em $$(a_1,a_2,\ldots,a_n)$$ **e** as **derivadas** parciais de primeira ordem **existem** nesse ponto, **então** $$\nabla f(a_1,a_2,\ldots,a_n)=(0,0,\ldots,0)$$.

{% hint style="danger" %}
O [Teorema](extremos-relativos-e-absolutos.md#teorema) dá uma condição necessária para os pontos extremos de uma função, mas não suficiente, isto é,

&#x20;              $$(a_1,a_2,\ldots,a_n)$$ **ponto extremo** de $$f$$ $$\Large\,\Rightarrow\atop\nLeftarrow$$ $$(a_1,a_2,\ldots,a_n)$$ **ponto crítico** de $$f$$.
{% endhint %}

## Teorema (análogo ao do Weierstrass para funções numa variável).

Se $$f$$ é **contínua** num conjunto **fechado e limitado** (compacto) $$D$$, então $$f$$ atinge um valor **máximo absoluto** $$f(a_1​,a_2,\ldots,a_n​)$$ e um valor **mínimo absoluto** $$f(b_1,b_2,\ldots,b_n​)$$ nalguns pontos $$(a_1​,a_2,\ldots,a_n​)$$ e $$(b_1,b_2​,\ldots,b_n​)$$ em $$D$$.

{% hint style="danger" %}
Este Teorema é **relevante** como marco teórico no cálculo de [extremos condicionados](extremos-condicionados.md).
{% endhint %}

## Matriz [Hessiana](https://pt.wikipedia.org/wiki/Hessiano).

Suponhamos que $$f(x_1,x_2,\ldots,x_n)$$ seja uma função real diferenciável de $$n$$ variáveis cujas segundas derivadas parciais existem. A **matriz Hessiana** $$H_f$$ de $$f$$ é a matriz n × n das [**derivadas parciais**](derivadas-parciais.md) **de segunda ordem** de $$f$$; isto é

$$
\small H_f(x_1,x_2,\ldots,x_n)=\begin{bmatrix}f_{x_1x_1}(x_1,x_2,\ldots,x_n) & f_{x_1x_2}(x_1,x_2,\ldots,x_n) & \cdots & f_{x_1x_n}(x_1,x_2,\dots,x_n)\\[2ex] f_{x_2x_1}(x_1,x_2,\ldots,x_n) & f_{x_2x_2}(x_1,x_2,\ldots,x_n) & \cdots & f_{x_2x_n}(x_1,x_2,\ldots,x_n) \\[2ex] \vdots & \vdots & \ddots & \vdots \\[2ex] f_{x_nx_1}(x_1,x_2,\ldots,x_n) & f_{x_nx_2}(x_1,x_2,\ldots,x_n) & \cdots & f_{x_nx_n}(x_1,x_2,\ldots,x_n)\end{bmatrix} .
$$

{% hint style="info" %}
**Menores principais líderes.**

Os menores principais líderes de uma matriz $$A$$ de ordem $$n=3$$, são os determinantes das seguintes submatrizes de $$A$$, destacadas a vermelho:

&#x20;               <img src=".gitbook/assets/Captura de ecrã 2024-03-10, às 22.09.19.png" alt="" data-size="original">

Desta forma, temos

$$
\small A_1=\begin{vmatrix}a_{11}\end{vmatrix}\quad,\quad A_2=\begin{vmatrix}a_{11} & a_{12} \\ a_{21} & a_{22}\end{vmatrix}\quad,\quad A_3=\begin{vmatrix}a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23} \\ a_{31} & a_{32} & a_{33}\end{vmatrix}
$$

**Definição.** Seja $$A$$ uma matriz de ordem $$n$$. O **menor principal líder** $$\boldsymbol{A_r}$$ é o determinante da submatriz de ordem $$r$$, com $$1\le r\le n$$, que se obtém de $$A$$ ao eliminar as últimas $$n-r$$ linhas e colunas; isto é.
{% endhint %}

## Critério das Segundas derivadas.

Sejam $$(a_1,a_2,\ldots,a_n)$$ um ponto crítico de $$f$$ e $$H_k$$ o menor principal líder de ordem $$k$$ da matriz hessiana de $$f$$ em $$(a_1,a_2,\ldots,a_n)$$. Então &#x20;

1. Se $$\forall\,k\,\,,\,\,1\le k\le n$$ , $$H_k>0$$ $$\Longrightarrow$$ $$(a_1,a_2,\ldots,a_n)$$ é um **mínimo** local.
2. Se $$\forall\,k\,\,,\,\,1\le k\le n$$ ,  $$(-1)^kH_k>0$$  \[i.e., $$H_1, H_3,\ldots<0$$ e $$H_2, H_4,\ldots>0$$] $$\Longrightarrow$$ $$(a_1,a_2,\ldots,a_n)$$ é um **máximo** local.
3. Se $$\operatorname{det}H_f(a_1,a_2,\ldots,a_n)\neq 0$$, mas nem 1. nem 2. são satisfeitas, então $$(a_1,a_2,\ldots,a_n)$$ é um ponto sela de $$f$$.
4. Se $$\operatorname{det}H_f(a_1,a_2,\ldots,a_n)= 0$$, então **nada** se pode concluir acerca de $$(a_1,a_2,\ldots,a_n)$$.

[^1]: Pontos extremos de uma função
