# Analyse2

## 18.02.2020

> Rappel : Le logarithme neturel $\ln(a)$ estl surface délimitée par y=$\frac1x$, y=0, x=1, x=a
>
> 

![](/home/valentin/Images/Screenshot from 2020-02-19 19-57-46.png)

> Le log est défini pour a > 0 
>
> Par 0 < a < 1  La surface est compté négativement
>
> Propriétés: 
>
> * $\ln(a\cdot b)$ = $\ln(a) + \ln(b)$
> * $\ln(\frac ab)= \ln(a) - \ln(b)$
> * $\ln(1) = 0$
> * $\ln(e) = 1$ , 2<e<3
> * $\ln: \mathbb{R}_+^* \Rightarrow\Longrightarrow \mathbb{R}$ (bijection)
> * $\ln $ est croissant et continue
>
> ![Screenshot from 2020-02-19 17-29-24](/home/valentin/Images/Screenshot from 2020-02-19 17-29-24.png)

> #### Définition :
>
>  Soit b $\in \mathbb{R}_+^*, b\ne1$, Le logarythme de base b est la fonction définie par 
> $$
> \log_b(x) = \frac{\ln(x)}{\ln(b)}
> $$
>
> * si ${\color{Red}b>e}$
> * si ${\color{Green}1 < b < e}$
> * si  $ {\color{Blue}\frac1e < b < e}$
> * si ${\color{Purple}0 < b < \frac1e}$

![Screenshot from 2020-02-19 18-02-30](/home/valentin/Images/Screenshot from 2020-02-19 18-02-30.png)

> Propriétés : 
>
> * $\log_b(1) = 0$
> * $\log_b(b)=1$
> * $\log_b(x*y) = \log_b(x) + \log_b(y)$
> * $\log_b(\frac xy) = \log_b(x) - \log_b(y)$
> * $\log_b :  \mathbb{R}_+^* \Rightarrow\Longrightarrow \mathbb{R}$ (bijection) continue, coissant si b > 1 décroissante si b < 1
> * si b=10, on écrit $\log(x)$



> ###  §2.2 Exponentielles
>
> #### définition : 
>
> Soit b $\in \mathbb{R}^*_+$\{1}. On définit $\exp_b(x)$ := ($\log_b⁻¹$)(x)
>
> #### Rappel :
>
> Si $f(x)$ est un bijection, $f⁻¹(x)$ $\ne \frac{1}{f(x)}$
>
> Par exemple $f$(x) = x², x $\geq$ 0
>
>  ![Screenshot from 2020-02-19 18-24-28](/home/valentin/Images/Screenshot from 2020-02-19 18-24-28.png)
>
> 
>
> $f$⁻¹(x) = $\sqrt{x} \ne \frac{1}{x²}$
>
> si  $f$'(x) est un fontion, l'image réciproque $f$ ⁻¹(x) existe toujours
>
> par exemple $g$(x) = x², x $\in \mathbb{R}$  
>
> fdsafsda

 ![Screenshot from 2020-02-19 18-29-55](/home/valentin/Images/Screenshot from 2020-02-19 18-29-55.png) 

> * $y$⁻¹{1} = {-1, 1}
> * $y$⁻¹{2} = {$-\sqrt{2},\sqrt{2}$}
> * $y$⁻¹[0,1] = [-1,1]
> * $y$⁻¹{-1} = $ \emptyset$ 
>
> #### Propriétés : 
>
> * $\exp_b(0) = 1$
> * $\exp_b(1) = b$
> * $exp_b : \mathbb{R} \Rightarrow \Longrightarrow \mathbb{R}_+^*$
> * si x,y $\in \mathbb{R}$, alors $\exp_b(x+y) = \exp_b(\log_b(x') + \log_b(y')) = \exp_b(\log_bx'*y') = x' * y' = \exp_b(x) * \exp_b(y)$, x est le $\log_b(x') $ $\Leftrightarrow x' = \exp_b(x)$
> * $\exp_b(x-y) = \frac{\exp_b(x)}{\exp_b(y)}$
>
> #### Notation :
>
> * $\exp_b(x) := b^x$
> * si b=e, $\exp_e(x) = e^x = \exp(x)$
>
> #### justitifaction :
>
> * si x = 0, $\exp_b(0)=1$
> * si x = 1, $\exp_b(1)=b$
> * si x = 2, $\exp_b(2) = \exp_b(1+1) = \exp_b(1) * \exp_b(1) = b * b = b^2$
> * si x = n+1, $\exp_b(n+1) = \exp_b(n)*\exp_b(1) = b * b^n = b^{n+1}$
> * Pour a,b,c $\in \mathbb{R}^*_+ $ \ {1} ${\color{Red} \log_a(b^c)} = \log_a(\exp(c)) = \frac{\ln(\exp_b(c))}{\ln(a)} = \frac{\ln(b)}{\ln(a)} * \frac{\ln(\exp_b(c))}{\ln(b)} = \frac{\ln(b)}{\ln(a)} * \log_b(\exp_b(c)) = {\color{Red}\log_b(b)*c}$
> *  ${\color {Blue}\exp_a(b*c)} = \exp_a(b*\log_a(\exp_a(c))) = \exp_a(\log_a(\exp_a(c)^b)) = {\color{blue}\exp_a(c)^b}$
> * Par exemple $e^{ab} = (e^{a)^b}$ 

![Screenshot from 2020-02-19 19-17-48](/home/valentin/Images/Screenshot from 2020-02-19 19-17-48.png)

> * ${\color{red}y = 10^x}$
> * ${\color{blue}y = e^x}$
> * ${\color{green}y = x}$
> * ${\color{purple}y = \ln(x)}$
> * ${\color{black}y = \log_{10}(x)}$
>
> #### Théorème de la valeur intermédiaire : 
>
> ##### (TVI) : 
>
> Soit $f$:[a,b] $\longrightarrow \mathbb{R}$ continue. Soir y $\in$ [$f$(a),$f$(b)].
>
> alors $\exist x \in [a,b] $ tel que y = $f$(x)
>
> #### Théorème : 
>
> Soit $f$: I $\Rightarrow \Longrightarrow$ J Une bijection continues des intervalles I,J $\subset \mathbb{R}$ alors $f$ est monotone.
>
> ##### Preuve : 
>
> Supposons que a,b,c $\in$ I avec a < b < c et $f$(a) < $f$(b) > $f$(c) 
>
> Soit y $\in$ [$f$(a),$f$(b)] $\cap$ [$f$(c), $f$(b)] et y $\ne$ $f$(b)
> Pour le T.V.I $\exist x \in [a,b] $ tel que $f$(x) = y et $\exist x' \in $[b,c] tel que $f$(x') = y 
>
> Ceci conredit l'hypothèse de bijectivité de $f$.
>
> Donc, soit $f$(a) < $f$(b) < $f$(c) ou $f$(a)>$f$(b)>$f$(c)
>
> donc$f$ est monotone sur tout l'intervalle
>
> ####  Théorème : 
>
> Soit $f$ : I $\Rightarrow \Longrightarrow$ J une bijection continu entre les intervalles I, J $\subset \mathbb{R}$. Alors $f^{-1}$ J $ \Rightarrow\Longrightarrow$ est continue aussi.
>
> ##### Preuve : 
>
> On va supposer $f$ monotone croissante.
>
> Soit y $\in$ J et $\epsilon$ > 0. Par bijectivité de $f$, $\exist$ x $\in$ I tel que $f$(x) = y
>
> Posons y = $f$(x+$\epsilon$)
>
> Posons $\varsigma \epsilon $ := min {$|y,y_-|,y,y_+$, } si $|y'-y| < \varsigma \epsilon \Rightarrow y' \in ]y_-, y_+[$
>
> Par monotonie : 
> $$
> \begin{split}
> f^{-1}(y') & \in [f^{-1}(y_-),f^{-1}(y_+] \\
>  & = [x-\epsilon, x + \epsilon] \\ 
>  & = [f^{-1}(y) - \epsilon, f^{-1}(y)+ \epsilon]\\ 
>  & \Rightarrow |f^{-1}(y') - f^{-1}(y)| < \epsilon
> \end{split}
> $$
> Conséquence : $\exp_b \R \Rightarrow \Longrightarrow \R^*_+$ continues , croissantes si b>1, décroissante si b<1
>
> 
>
> 
>
>  

