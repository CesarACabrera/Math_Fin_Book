# 1.3 Tasas Equivalentes
Las tasas equivalente, son un instrumento para el analisis financiero, el 
objetivo de las mismas es permitirnos comprarar, trabajar y planificar; sobre tasas de interes con diferentes periodos de capitalizacion.
Una situacion muy común en el ambito financiero es la necesidad de comparar los rendimientos de varias opciones de inversion diferentes, pero entonces surge un dilema cuando uno encuentra algo similar a lo siguiente:

Bolivia 2030, ASFI declara una tasa de interes minima del 10% capitalizable anualmente en los DPFS bancarios, ante esta noticia los siguientes bancos anuncian las siguientes tasas de interes para el siguiente año:
        
* **Banco BNB:** 12% capitalizable mensualmente
* **Banco Fasil:** 6% semestral capitalizable bimestralmente 
* **Banco Morales:** 8% capitalizable trimestralmente

En este momento, usted se abra dado cuenta de que aunque podemos ver todas las tasas efectivas, es dificil dar un juicio sobre cual es mejor oferta y si todos ellos cumplen efectivamente las exigencias de la ASFI, entonces es cuando nos resultan utiles las tasas equivalentes. Para este propósito, es bueno utilizar la siguiente formula como guia para realizar estos calculos:

> $(1+i)^{t}=(1+i_e)^{t_e}$
>
> * **$i$**: Tasa de interes
> * **$i_e$**: Tasa equivalente
> * **$t$**: Periodo de tiempo
> * **$t_e$**: Periodo de tiempo equivalente

Es bueno hacer una aclariacion del siguiente topico, cuando decimos periodo de tiempo equivalente 
nos referimos a que si tenemos una tasa de interes del 10\% efectiva mensual, pero queremos su equivalente 
en capitalzacion anual, entonces nuestro periodo de tiempo seria 12 meses y su equivalente seria 1 año, 
es asi que reemplazando datos en nuestra formula tendriamos $(1+10\%)^{12}=(1+i_e)^1$ y lo unico que 
faltaria seria despejar la tasa equivalente puesto que es la unica incognita de la ecuacion.

## 1.3.1 Ejemplo ilustrativo
Jason Voorhees es un hombre simple que disfrute de vivir en su cabaña al lado del lago, pero justamente un dia un hombre lo atropella, gracias a una demanda y un buen abogado, el señor Voorhees se consigue hacer con una buena suma de dinero, ante lo cual le empiezan a llegar ofertas bancarias para que deposite su dinero con ellos, ante lo cual el señor Voorhees decide contratarlo a usted, el señor Voorhees le aclara que no quiere complicarce la existencia y solo quiere tomar algunos de los DPFs que le ofrecen los bancos, donde el banco Krueger le ofrece una tasa de 72\% trianual capitalizable mensualmente, el banco Predator le ofrece un 19\% efectivo anual, el banco DOOM le ofrece un 12\% semestral capitalizable bimestralmente, el señor Voorhees le dice que como acesor se llevara como comision el primer interes generado por el DPF en el cual se deposite el dinero, ¿En que DPF le conviene al señor Voorhees depositar su dinero? ¿En que DPF le conviene a usted que el señor Voorhees deposite su dinero?
### Pasos de la resolucion
1. Volvemos a leer el ejercicio con la intencion de responder la pregunta ¿Que clase de ejercicio es?
2. \textbf{Es un ejercicio de Tasas Equivalentes} || En este caso, es un ejercicio de tasas equivalentes puesto que necesitamos comparar diferentes tasas de interes, las cuales tienen distintos periodos de capitalizacion. Dicho asi sea, cada vez que deba comparar tasas efectivas de interes, debera referirse a las tasas equivalentes.
3. \item Definimos en que escala temporal queremos trabajar, usualmente puede decidir esto de forma arbitraria pero como en este caso tenemos una tasa efectiva anual, podemos ahorrarnos trabajo llevando todo a la escala temporal de esta tasa efectiva.\\
    \textbf{Anual}
    \item Se tienen que llevar todas las tasas de interes a tasas efectivas.
    \item Revisamos la ecuacion de tasas equivalentes $(1+i)^{t}=(1+i_e)^{t_e}$, necesitamos saber cuales son las tasas de interes efectivas y los periodos de capitalizacion de cada una de las ofertas que se le han dado al señor Voorhees.\\
    \text{ }\\
    \begin{center}
        \begin{tabular}{l c c}
            \toprule
            Banco&i&t\\
            \midrule
            Krueger&2\%&1 mes\\
            Predator&19\%&1 año\\
            DOOM&4\%&1 bimestre\\
            \bottomrule  
        \end{tabular}
    \end{center}
    \item Una vez que tenemos los datos, debemos de realizar la conversion correspondiente de los periodos de tiempo para hallar el valor del $t_e$ para cada uno de los bancos.\\
    \textbf{Krueger:}
    \begin{center}
        \Large{$1\text{ Mes} * \frac{1 \text{ Año}}{12 \text{ Meses}}=\frac{1}{12}\text{ Años}$}
    \end{center}
    \textbf{DOOM:}
    \begin{center}
        \Large{$1\text{ Bimestre} * \frac{1 \text{ Año}}{6 \text{ Bimestres}}=\frac{1}{6}\text{ Años}$}
    \end{center}
    \item Finalmente solamente hay que reemplazar los datos en la ecuacion de las tasas de interes equivalentes y despejar $i_e$ para poder realizar nuestra comparacion.\\
    \textbf{Krueger:}
    \begin{align*}
        (1+2\%)^{1}=(1+i_e)^{\frac{1}{12}}\\
        (1+2\%)^{12}=1+i_e\\
        i_e=(1+2\%)^{12}-1\approx26,8242\%
    \end{align*}
    \textbf{DOOM:}
    \begin{align*}
        (1+4\%)^{1}=(1+i_e)^{\frac{1}{6}}\\
        (1+4\%)^{6}=1+i_e\\
        i_e=(1+4\%)^{6}-1\approx26,5319\%
    \end{align*}
    \item Finalmente podemos observar la siguiente situacion cuando queremos comparar las tasas de todos los bancos.
    \text{ }\\
    \begin{center}
        \begin{tabular}{l c c}
            \toprule
            Banco&$i_e$\\
            \midrule
            Krueger&26,8242\%\\
            Predator&19\%\\
            DOOM&26,5319\%\\
            \bottomrule  
        \end{tabular}
    \text{ }\\
    \end{center}
    \textbf{Comparando todas las tasas, señor Voorhees ganaria mas en el banco Krueger, pero por el periodo de capitalizacion, a nosotros nos conviene que invierta en el banco Predator donde obtendremos intereses generados en un año en lugar de 1 mes.}
    

\end{enumerate}

\subsection{Ejercicios de Capitulo}
\subsection{Problemas para practicar}
\begin{enumerate}
    \item Se tienen las siguientes tasas de interes:
    \begin{itemize}
        \item 6.3\% trimestral capitalizable trimestralmente
        \item 9.7\% semestral capitalizable mensualmente
        \item 11.2\% anual capitalizable trimestralmente
        \item 7.8\% mensual capitalizable semestralmente
        \item 10.4\% bimestral capitalizable anualmente
        \item 8.6\% trimestral capitalizable bimestralmente
        \item 5.9\% mensual capitalizable mensualmente
        \item 12.1\% bimestral capitalizable semestralmente
        \item 9.9\% anual capitalizable mensualmente
        \item 7.2\% mensual capitalizable bimestralmente
    \end{itemize}
    Se pide las tasas equivalentes para:
        \begin{itemize}
            \item Capitalizacion anual
            \item Capitalizacion semestral
            \item Capitalizacion cuatrimestral
            \item Capitalizacion diaria (Suponga que cada mes tiene 30 dias)
        \end{itemize}

    \textbf{Repuestas para Capitalizacion Anual:}
    \begin{itemize}
        \item 27.68\%
        \item 21.22\%
        \item 11.68\%
        \item 115.5\%
        \item 62.4\%
        \item 39.72\%
        \item 98.95\%
        \item 85.78\%
        \item 10.36\%
        \item 124.16\%
    \end{itemize}
    \textbf{Repuestas para Capitalizacion Semestral:}
    \begin{itemize}
        \item 12.99\%
        \item 10.1\%
        \item 5.68\%
        \item 46.8\%
        \item 27.44\%
        \item 18.21\%
        \item 41.05\%
        \item 36.03\%
        \item 5.05\%
        \item 49.72\%
    \end{itemize}
    \textbf{Repuestas para Capitalizacion Cuatrimestral:}
    \begin{itemize}
        \item 8.49\%
        \item 10.1\%
        \item 5.68\%
        \item 46.8\%
        \item 27.44\%
        \item 18.2\%
        \item 41.05\%
        \item 36.3\%
        \item 5.05\%
        \item 49.72\%
    \end{itemize}
    \textbf{Repuestas para Capitalizacion Diaria:}
    \begin{itemize}
        \item 0.07\%
        \item 0.05\%
        \item 0.03\%
        \item 0.21\%
        \item 0.13\%
        \item 0.09\%
        \item 0.19\%
        \item 0.17\%
        \item 0.03\%
        \item 0.22\%
    \end{itemize}
    
    
    \item Se tiene una cuenta de inversion compuesta con una tasa de interes del 15\% capitalizable trimestralmente, si se realizan 2 depositos 
    cada año, uno a la mitad de año y otro al final, cuanto es el saldo final de la cuenta si:
    \begin{itemize}
        \item Se invierte por 3 años y se deposita Bs.200
        \item Se invierte por 1 año y se deposita Bs.500
        \item Se invierte por 2 años y se deposita Bs.300
    \end{itemize}
    \textbf{Respuestas:}
    \begin{itemize}
        \item \textbf{1037,85}
        \item \textbf{1009,29}
        \item \textbf{1233,85}
    \end{itemize}
    \item Si en el ejercicio anterior se realizan las tres opciones de forma descendente segun los depositos, en una misma cuenta, ¿cuanto es el saldo de la cuenta al cabo de los 6 años? y ¿si fuera ascendente?
    \textbf{3848,33}
    \textbf{3693,34}
\end{enumerate}
\subsection*{Problemas reto}
\begin{enumerate}
    \item {Bolivia 2030, ASFI declara una tasa de interes minima del 10\% capitalizable anualmente en los DPFS 
    bancarios, ante esta noticia los siguientes bancos anuncian las siguientes tasas de interes para el siguiente año:}
    \begin{itemize}
        \item \textit{Banco BNB:} 12\% capitalizable mensualmente
        \item \textit{Banco Fasil:} 6\% semestral capitalizable bimestralmente 
        \item \textit{Banco Morales:} 8\% capitalizable trimestralmente
    \end{itemize} 
    ¿Cuales bancos son los que cumplen las regulaciones de la ASFI y cual es el que ofrece la mejor opcion?
    \textbf{Los bancos BNB y Fassil cumplen las regulaciones, pero el banco Morales no.}
    \textbf{El banco BNB es la mejor opcion.}
    \item Una cuenta bancaria ofrece un interes del 12\% capitalizable mensualmente, Ernesto decide meter dinero a la cuenta, 
    pero como Ernesto es un trabajador informal, no consigue hacer pagos periodicos, por lo que acaba haciendo los siguiente movimientos:
    \begin{itemize}
        \item Al abrir la cuenta deposita Bs330
        \item 15 dias despues deposita Bs420 
        \item Mes y 3 dias despues deposita Bs345
        \item 3 semanas despues de abrir la cuenta deposita Bs231
        \item 4 semanas y 5 dias despues del deposito de Bs420, deposita Bs85
        \item Un mes antes antes del anterior deposito, ingresa Bs437 
    \end{itemize}
    Apenas Ernesto termina todos estos movimientos, Ernesto decide retirar todo el dinero de la cuenta para comprar una consola, 
    pero le falta el 14\% del costo, aunque lo subsanara con un prestamo de un amigo, ¿Cuanto costara la consola? y ¿Que tantos intereses genero la cuenta? (Considere que los meses duran 30 dias)
    \textbf{Bs1.896,85}
    \textbf{Bs14,28}
    \item Cada inicio de mes Juan Carlos Bodoque deposita Bs3000 a una cuenta bancara, ultimamente como el pais a estado pasando por una constante inestabilidad 
    las tasas de interes han estado cambiando constantemente, el ultimo año cambiaron de la siguiente forma:
    \begin{itemize}
        \item 8\% anual capitalizable mensualmente durante 2 meses
        \item 9.5\% semestral capitalizable trimestralmente durante 1 mes y 2 semanas
        \item 10.2\% trimestral capitalizable bimestralmente durante 5 meses
        \item 7.3\% mensual capitalizable diariamente durante 6 semanas
        \item 6.5\% anual capitalizable semestralmente por un mes
        \item 11.8\% bimestral capitalizable anualmente por el ultimo mes
    \end{itemize}
    Si al inicio del año pasado la cuenta habia empezado con un capital de Bs4567, ¿cuanto dinero tiene a dia de hoy la cuenta? 
    Juan Carlos decide invertir todo el dinero de la cuenta en un carrera de caballos, el apuesta por Tormenta China su caballo favorito, 
    pero gracias a esto Juan Carlos pierde la mitad de su dinero, si quiere volver a la cantidad anterior en 3 meses, cuanto debera invertir 
    sabiendo que las tasas de interes pronosticadas para los siguientes 3 meses son las siguientes:
    \begin{itemize}
        \item 8.5\% mensual capitalizable trimestralmente por 3 semanas
        \item 9.8\% semestral capitalizable bimestralmente 4 semanas
        \item 10.5\% anual capitalizable mensualmente 2 semanas
        \item 7.1\% mensual capitalizable semestralmente 3 semanas
    \end{itemize}
    Para su siguiente nota verde Juan Carlos Bodoque quiere hablar de una fundacion ecologista y quiere donar 
    una cantidad igual a todos los intereses generado por la cuenta bancaria en el ultimo año, ¿cuanto debera donar?  
    \textbf{Bs56.987,08}
    \textbf{Bs13.363,95}
    \textbf{Bs11.168,60}
\end{enumerate}~