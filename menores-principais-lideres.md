# Menores principais líderes

**Exemplo.**

Os menores principais líderes de uma matriz $$A$$ de ordem $$n=3$$, são os determinantes das seguintes submatrizes de $$A$$, destacadas a vermelho:

<figure><img src=".gitbook/assets/Captura de ecrã 2024-03-10, às 22.09.19.png" alt=""><figcaption><p>Menores principais líderes de uma matriz de ordem 3.</p></figcaption></figure>

Desta forma, temos

$$
A_1=\begin{vmatrix}a_{11}\end{vmatrix}\quad,\quad A_2=\begin{vmatrix}a_{11} & a_{12} \\ a_{21} & a_{22}\end{vmatrix}\quad,\quad A_3=\begin{vmatrix}a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23} \\ a_{31} & a_{32} & a_{33}\end{vmatrix}
$$

**Definição.** Seja $$A$$ uma matriz de ordem $$n$$. O **menor principal líder** $$\boldsymbol{A_r}$$ é o determinante da submatriz de ordem $$r$$, com $$1\le r\le n$$, que se obtém de $$A$$ ao eliminar as últimas $$n-r$$ linhas e colunas; isto é

$$
\large\colorbox{yellow}{$A_{\boldsymbol{r}}=\begin{vmatrix}a_{ij}\end{vmatrix}_{\substack{\scriptsize 1\le i\le \boldsymbol{r} \\[1ex] \scriptsize 1\le j\le\boldsymbol{r}}}$}
$$
