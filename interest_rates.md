# Tasas de interés

Imagina que Félix, un joven emprendedor con grandes ideas, está a punto de adquirir una herramienta esencial para su nuevo proyecto. Sin embargo, al revisar sus bolsillos, nota que el capital disponible no es suficiente. Decide acudir a su amigo de confianza, Bruno, quien trabaja en el sector financiero, para pedirle un préstamo que cubra la diferencia. Aunque Bruno aprecia la iniciativa de su amigo, le pide dos semanas para evaluar la propuesta.

Durante ese tiempo, la mente de Bruno no descansa. Como experto en finanzas, empieza a cuantificar la incertidumbre: ``¿Qué pasa si el proyecto de Félix no despega? ¿Y si surge una emergencia y necesito ese dinero antes? ¿Cómo me aseguro de que el valor de mi dinero no se pierda en el tiempo?'' Estas interrogantes son la esencia del riesgo. Finalmente, Bruno comprende que prestar dinero no es solo un acto de confianza, sino un sacrificio de su propia liquidez y seguridad.

Para equilibrar la balanza, Félix le propone un trato justo: no solo le devolverá el capital original, sino que añadirá un monto adicional como reconocimiento por el riesgo asumido y el tiempo transcurrido. Así es como cobran vida los intereses: como el precio del tiempo y la recompensa por enfrentar la incertidumbre.
    
## 1. Interés Simple

> $$S_t = K_0 + K_0 \cdot i \cdot t$$
> 
> * **$S_t$** : Saldo en el tiempo $t$
> * **$K_0$** : Capital inicial
> * **$i$** : Tasa de interés
> * **$t$** : Tiempo

Tras una breve negociación, Bruno acepta el trato bajo la modalidad de interés simple. En este esquema, el ``extra'' que Félix pagará se calcula exclusivamente sobre el monto original prestado, sin acumularse sobre sí mismo en periodos siguientes. Es una forma lineal y transparente de entender el crecimiento de una deuda o inversión. Por ejemplo, si Félix recibe 100 dólares con un interés simple del 5\% anual, al cabo de un año el agradecimiento se traduce en 5 dólares adicionales. El interés simple es la base fundamental de las finanzas porque nos permite modelar el crecimiento del capital de manera constante.

Para dominar estas decisiones financieras, debemos traducir la realidad al lenguaje de las ecuaciones. La fórmula maestra que utilizaremos es: $S_t = K_0 + K_0 \cdot i \cdot t$, donde cada variable cuenta una parte de la historia: el inicio ($K_0$), el costo del tiempo ($i$), la duración ($t$) y el desenlace final ($S_t$).

### Ejemplo ilustrativo:

Michael Mayers está cansado de caminar al trabajo todos los días y desea comprar una motocicleta para mejorar su puntualidad. El banco ``Jack Esqueleton'', donde Bruno es consultor, le ofrece una cuenta de ahorro especial con un interés simple del 20\% anual. Si Michael deposita $15,000$ USD al inicio del año y la motocicleta que desea cuesta $30,000$ USD, ¿cuántos años deberá dejar su dinero creciendo para alcanzar su meta?

### Pasos a seguir
1. **Análisis del escenario:** Leemos el problema con una visión estratégica. Debemos identificar qué meta persigue el personaje (en este caso, Michael), qué herramientas matemáticas tenemos a nuestra disposición y qué datos nos ofrece el contexto.
                
2. **Identificación y extracción de variables:** Recurrimos a la ecuación de interés simple que vimos antes $S_t = K_0 + K_0 \cdot i \cdot t$ y asignamos los valores correspondientes extrayéndolos del enunciado:

    * **Incógnita ($t$):** La pregunta clave es el tiempo necesario para alcanzar la meta.
    * **Valor Futuro ($S_t$):** Es el objetivo final o el costo de la motocicleta: $S_t = 30,000$ USD.
    * **Capital Inicial ($K_0$):** El monto con el que Michael abre su cuenta: $K_0 = 15,000$ USD.
    * **Tasa de interés ($i$):** La rentabilidad anual que ofrece el banco ``Jack Esqueleton'': $i =$ 0.2 (que representa el 20\% anual).

3. **Modelación y resolución matemática:** Reemplazamos los datos conocidos en nuestra ecuación de equilibrio financiero y despejamos la variable $t$: 
$$S_t = K_0 + K_0 \cdot i \cdot t$$
Sustituyendo los valores: 
$$30,000 = 15,000 + 15,000(\text{0.2})t$$
Despejando el término con $t$:
$$\begin{align*}
    30,000 - 15,000 &= 3,000t \\
    15,000 &= 3,000t \\
    t &= \frac{15,000}{3,000} \\
    t &= 5
\end{align*}$$

4. **Interpretación de resultados:** Finalmente, traducimos el valor matemático a una respuesta tangible: Michael Mayers deberá mantener su inversión durante 5 años para que el interés generado, sumado a su capital, le permita adquirir la motocicleta.

### Problemas para practicar
1. Juan invirtió $2,000$ USD a una tasa de interés simple del 8\% anual. ¿Cuánto interés ganará después de 3 años?\
**Respuesta:** 480 USD.
2. Calcular el tiempo necesario para que $5,000$ USD a una tasa de interés simple del 4\% anual genere 800 USD de interés.\
**Respuesta:** 4 años.           
3. ¿Cuánto es el interés simple acumulado en un préstamo de $3,000$ USD con una tasa de interés del 4\% anual durante 2 años?\
**Respuesta:** 240 USD.
4. María tomó un préstamo de $4,000$ USD con una tasa de interés simple del 10\% anual. Cuando decidió pagar la deuda terminó pagando $800$ USD de interés, ¿cuánto tiempo se prestó el dinero?\
**Respuesta:** 2 años.
5. Si un préstamo de $6,000$ USD con una tasa de interés del 5\% anual se pagó en su totalidad después de 2 años, ¿cuál es el monto total a pagar?\    
**Respuesta:** $6,600$ USD.
6. Una persona invirtió $800$ USD con la promesa de recibir intereses simples a una tasa del 12\% anual. Si ganó $192$ USD de interés, ¿cuánto tiempo mantuvo la inversión?\
**Respuesta:** 2 años.
7. ¿Cuánto será el interés simple generado con un préstamo de $2,500$ BOB con una tasa de interés del 7\% anual durante 4 años?\
**Respuesta:** $700$ BOB.            
8. Si se invierten $3,000$ BOB con una tasa de interés simple del 4\% anual, ¿cuánto tiempo tomará para que el monto se duplique?\
**Respuesta:** 25 años.            
9. Pedro invirtió $1,200$ BOB con una tasa de interés simple del 3\% anual. Si ganó 108 BOB de interés, ¿cuánto tiempo mantuvo la inversión?\
**Respuesta:** 3 años.    
### Problemas reto
10. Alberto apertura una cuenta con $30,000$ BOB que paga un 12\% de interés anual simple a partir de hoy. Luego de 6 meses realiza un nuevo depósito de $5,000$ BOB, $10,000$ BOB dentro de 1 año y un retiro de $2,500$ BOB después de 18 meses ¿En cuánto tiempo a partir de la apertura se tendrá el monto de $55,000$ BOB tomando en cuenta todas las operaciones mencionadas? ¿Cuánto interés fue generado durante todo este periodo?\    
**Respuesta:** Aproximadamente 2 años, 7 meses y 24 dias. $12,500$ BOB.
11. Alberto apertura una cuenta con $K_0$ BOB que paga un $r$\% de interés simple mensual a partir de hoy. Luego de $t_0$ meses realiza un nuevo depósito de $K_1$ BOB, $K_2$ BOB dentro de $t_1>t_0$ meses y un retiro de $K_3$ BOB después de $t_2>t_1$ meses ¿En cuánto tiempo a partir de la apertura se tendrá el monto de $K_4$ BOB tomando en cuenta todas las operaciones mencionadas? ¿Cuánto interés fue generado durante todo este periodo?\
**Respuesta:** Para resolver este problema, primero calculamos el saldo después de cada operación y el interés generado en cada periodo.
    1. Saldo inicial: $K_0$
    2. Después de $t_0$ meses: $S_{t_0} = K_0\left(1 + \displaystyle\frac{r}{100} \cdot t_0\right) + K_1$
    3. Después de $t_1$ meses: $S_{t_1} = \left[K_0\left(1 + \displaystyle\frac{r}{100} \cdot t_0\right) + K_1\right]\left(1 + \displaystyle\frac{r}{100}(t_1 - t_0)\right) + K_2$
    4. Después de $t_2$ meses: $$S_{t_2} = \left[\left[K_0 \left(1 + \frac{r}{100} \cdot t_0\right) + K_1\right]\times\left(1 + \frac{r}{100}(t_1 - t_0)\right) + K_2\right]\times\left(1 + \frac{r}{100}(t_2 - t_1)\right) - K_3$$
    5. Para alcanzar $K_4$ BOB, despejamos $t$: $t = t_2 + \displaystyle\frac{100}{r}\left(\frac{K_4}{S_{t_2}} - 1\right)$
    6. Interés total generado: $$I_{\text{total}} = S_t - (K_0 + K_1 + K_2 - K_3)$$

Por lo tanto, el tiempo total $t$ y el interés generado $I_{\text{total}}$ se pueden calcular usando las fórmulas anteriores.    


## 2. Interés Compuesto
> $$S_t=K_0(1+i)^t$$
>
>* **$S_t$**: Saldo en el tiempo $t$
>* **$K_0$**: Capital inicial
>* **$i$**: Tasa de interés efectiva
>* **$t$**: Tiempo

Pero la historia no termina ahí. Bruno, con su mentalidad de estratega financiero, sabe que el tiempo no solo transcurre, sino que se acumula. Por ello, le propone a Félix un esquema más sofisticado: el interés compuesto.

A diferencia del modelo lineal, aquí el interés se convierte en capital al final de cada periodo. Es lo que en el mundo financiero conocemos como ``el efecto bola de nieve'': el interés generado empieza, a su vez, a generar sus propios intereses. Imaginemos que Félix recibe los mismos 100 dólares con un interés del 5\% anual capitalizable anualmente. Al cierre del primer año, la deuda es de 105 dólares. Sin embargo, para el segundo año, la tasa del 5\% no se aplica sobre los 100 iniciales, sino sobre el nuevo saldo de 105 dólares. Así, al finalizar el segundo año, la deuda asciende a 110.25 dólares. Aunque esos 0.25 adicionales parezcan insignificantes hoy, el interés compuesto es la fuerza más poderosa de las finanzas: en el largo plazo, puede convertir una pequeña inversión en una fortuna o una deuda pequeña en una carga inmanejable.

Para dominar esta ``fuerza'', debemos entender que toda tasa compuesta se define por dos componentes críticos: la frecuencia de capitalización (cada cuánto tiempo se suman los intereses al capital) y el periodo de referencia (el tiempo total que abarca la tasa). La interacción entre estos dos factores nos permite clasificar las tasas en dos grandes categorías:

* **Tasas Nominales:** Son aquellas donde el periodo de la tasa y su frecuencia de capitalización no coinciden (por ejemplo, una tasa anual que capitaliza mensualmente). Son tasas ''de etiqueta'', que sirven de referencia pero no reflejan el costo real.
* ***Tasas Efectivas:** Son las tasas ``reales'', donde el periodo y la frecuencia de capitalización están en perfecta sintonía. Es la tasa que efectivamente afecta el bolsillo de Félix al final del día.

            % \begin{figure}[h]
            %     \centering
            %     \shorthandoff{>}
            %     \begin{tikzpicture}[scale=1.3, >=Stealth]
            %         % Colores narrativos
            %         \definecolor{NominalColor}{RGB}{150, 150, 150} % Gris para lo teórico/nominal
            %         \definecolor{EfectivaColor}{RGB}{0, 153, 76}    % Verde para la ganancia real/efectiva
            %         \definecolor{FelixColor}{RGB}{204, 0, 0}       % Rojo para los saltos de capitalización

            %         % Ejes
            %         \draw[->, thick] (0,0) -- (9,0) node[right] {Tiempo ($t$)};
            %         \draw[->, thick] (0,0) -- (0,5.5) node[above] {Valor Final ($S_t$)};

            %         % --- ESCENARIO 1: TASA NOMINAL (Referencia lineal) ---
            %         % Dibujamos una línea punteada que representa el 20% simple/nominal
            %         \draw[NominalColor, dashed, thick] (0,0) -- (8,3.5) node[right, font=\footnotesize] {Crecimiento Nominal (Lineal)};

            %         % --- ESCENARIO 2: TASA EFECTIVA (Capitalización) ---
            %         % Dibujamos la curva exponencial (escalonada)
            %         \draw[EfectivaColor, ultra thick] (0,0) 
            %             \foreach \x in {1,2,...,8} {
            %                 -- ({\x}, {0.15*exp(0.45*\x)}) % Curva exponencial
            %             } node[above right, font=\bfseries] {Rendimiento Efectivo};

            %         % Puntos de capitalización (Los momentos donde Félix gana interés)
            %         \foreach \x in {1,2,...,8} {
            %             \pgfmathsetmacro{\y}{0.15*exp(0.45*\x)}
            %             \filldraw[FelixColor] (\x, \y) circle (1.8pt);
            %             \draw[gray, ultra thin] (\x, 0) -- (\x, -0.1) node[below, font=\tiny] {m \x};
            %         }

            %         % --- DIFERENCIA (El Spread) ---
            %         % Sombreado o flecha que muestra la diferencia al final del periodo
            %         \draw[<->, blue, thick] (8, 3.55) -- (8, 5.4) 
            %             node[midway, right, align=left, font=\scriptsize] {Interés sobre\\interés (Anual)};

            %         % Etiquetas de conceptos
            %         \node[align=left, font=\small, draw, rounded corners, bg=white] at (3, 4.5) {
            %             \textbf{Diferencia Clave:}\\
            %             \textcolor{NominalColor}{Nominal:} Lo que se pacta ($j$).\\
            %             \textcolor{EfectivaColor}{Efectiva:} Lo que realmente sucede ($i_{ef}$).
            %         };

            %         % Periodo de Bruno
            %         \draw[thick] (0,-0.8) -- (8,-0.8) node[midway, fill=white, font=\small] {1 Año (Periodo de Bruno)};
            %         \draw (0,-0.7) -- (0,-0.9);
            %         \draw (8,-0.7) -- (8,-0.9);

            %     \end{tikzpicture}
            %     \shorthandon{>}
            %     \caption{Diferencia entre el crecimiento nominal (lineal) y el efectivo (exponencial). Los puntos rojos muestran cómo la capitalización mensual impulsa el valor por encima de la tasa nominal.}
            % \end{figure}

### Ejemplo ilustrativo:
Freddy K. siempre ha sido considerado un hombre metódico y peculiar por sus colegas. Mientras otros gastaban sus bonos, él seguía el consejo de su consultor, Bruno, manteniendo una disciplina inquebrantable. Durante los últimos 25 años, realizó depósitos constantes en una cuenta que le ofrecía un interés compuesto del 12\% anual, con capitalización mensual. Hoy, Freddy sonríe al ver su saldo: ha logrado acumular la impresionante cifra de $1,000,000$ USD. Sin embargo, la curiosidad lo asalta. Recuerda que hace 30 años ganó un premio de lotería de $25,000$ USD que gastó en viajes y lujos. Llama a Bruno con una duda existencial: Si en lugar de gastar ese premio, lo hubiera depositado en esa misma cuenta hace 30 años y me hubiera olvidado de él, ¿tendría hoy más o menos dinero que con mi plan de ahorro actual?'' Además, se pregunta: ¿Y si hubiera tenido la paciencia de esperar 10 años más (40 años en total)?''
            \subsection*{Pasos a seguir}
            \begin{enumerate}
                \item \textbf{Análisis del escenario:}Debemos contrastar el ahorro actual de Freddy ($1,000,000$ USD) contra el valor futuro ($S_t$) de un capital único invertido bajo el efecto del interés compuesto.
                \item \textbf{Identificación de variables y herramientas:} Utilizaremos la ecuación fundamental del interés compuesto: $S_t = K_0(1+i)^n$. Del enunciado de Freddy extraemos:
                \begin{itemize}
                    \item \textbf{Capital inicial ($K_0$):} $25,000$ USD (el premio de lotería).
                    \item \textbf{Tasa Nominal ($j$):} 12\% anual capitalizable mensualmente.
                    \item \textbf{Tiempo ($t$):} Escenario A: 30 años. Escenario B: 40 años.
                \end{itemize}

                \item \textbf{Sincronización de la Tasa (Conversión a Efectiva):} Como nos enfrentamos a una tasa nominal (el periodo anual no coincide con la frecuencia mensual), debemos encontrar la tasa efectiva mensual ($i$) que realmente hará crecer el dinero:
                \begin{equation*}
                    i = \frac{j}{m} = \frac{12\% \text{ anual}}{12 \text{ meses}} = 1\% \text{ mensual efectiva} = 0{.}01
                \end{equation*}

                \item \textbf{Sincronización del Tiempo ($n$):} 
                Para que la fórmula funcione, el tiempo debe hablar el mismo ``idioma'' que la tasa (meses):
                \begin{itemize}
                    \item Para 30 años: $n = 30 \times 12 = 360$ meses.
                    \item Para 40 años: $n = 40 \times 12 = 480$ meses.
                \end{itemize}

                \item \textbf{Resolución Matemática:} 
                Sustituimos en la ecuación para ambos escenarios:

                \textbf{Escenario A (30 años):}
                \begin{align*}
                    S_{360} &= 25.000 \cdot (1 + 0{.}01)^{360} \\
                    S_{360} &\approx 898.741,03 \text{ USD}
                \end{align*}
                \textit{Conclusión 1:} Freddy habría obtenido menos dinero que con su plan actual. La disciplina de ahorrar mes a mes durante 25 años superó el efecto de un capital único de 30 años.

                \textbf{Escenario B (40 años):}
                \begin{align*}
                    S_{480} &= 25.000 \cdot (1 + 0{.}01)^{480} \\
                    S_{480} &\approx 2,966,193{.}13 \text{ USD}
                \end{align*}
                \textit{Conclusión 2:} Aquí vemos el verdadero poder del tiempo. Al esperar solo 10 años más, el saldo casi se triplica, superando por mucho el millón de dólares actual.

                \item \textbf{Interpretación para la toma de decisiones:} 
                Como le explicaría Bruno a Freddy: ``El interés compuesto no es una carrera de velocidad, sino de resistencia''. 10 años adicionales de capitalización sobre una base ya crecida generan un efecto exponencial masivo.
            \end{enumerate}

            \subsection{Problemas para practicar}
            \begin{enumerate}
                \item \textbf{Conversión de Tasas:} Lleva las siguientes tasas de interés nominales a sus correspondientes tasas efectivas por periodo de capitalización:
                
                \begin{tasks}(2)
                    \task 12\% anual cap. bimestralmente
                    \task 8\% semestral cap. mensualmente
                    \task 10,5\% anual cap. trimestralmente
                    \task 12\% trimestral cap. bimestralmente
                    \task 9,25\% mensual cap. diariamente
                    \task 7,75\% anual cap. semestralmente
                    \task 11,8\% bimestral cap. anualmente
                    \task 6,9\% trimestral cap. mensualmente
                    \task 9,3\% semestral cap. trimestralmente
                    \task 5,5\% mensual cap. bimestralmente
                    \task 8,2\% bimestral cap. semestralmente
                    \task 10,75\% anual cap. mensualmente
                    \task 7,1\% mensual cap. trimestralmente
                    \task 11,9\% bimestral cap. mensualmente
                    \task 6,8\% trimestral cap. anualmente
                    \task 9,6\% semestral cap. bimestralmente
                    \task 5,25\% mensual cap. trimestralmente
                    \task 8,9\% anual cap. semestralmente
                    \task 12,3\% bimestral cap. mensualmente
                    \task 7,5\% trimestral cap. trimestralmente
                    \task 10,2\% semestral cap. anualmente
                \end{tasks}

                \textbf{Respuestas (Tasas efectivas por periodo):}
                \begin{multicols}{3}
                    \begin{itemize}
                        \item a) 0.5\% bim.
                        \item b) 1,33\% mens.
                        \item c) 2,625\% trim.
                        \item d) 8,00\% bim.
                        \item e) 0,3083\% diar.
                        \item f) 3,875\% sem.
                        \item g) 70,80\% anual
                        \item h) 2,30\% mens.
                        \item i) 4,65\% trim.
                        \item j) 11,00\% bim.
                        \item k) 24,60\% sem.
                        \item l) 0,8958\% mens.
                        \item m) 21,30\% trim.
                        \item n) 5,95\% mens.
                        \item o) 27,20\% anual
                        \item p) 3,20\% bim.
                        \item q) 15,75\% trim.
                        \item r) 4,45\% sem.
                        \item s) 6,15\% mens.
                        \item t) 7,50\% trim.
                        \item u) 20,40\% anual
                    \end{itemize}
                \end{multicols}

                \item Calcula el monto final después de 5 años si se invierten \$5,000 a una tasa de interés compuesto del 6\% anual.
                \\ \textbf{Respuesta:} \$6,691.13

                \item ¿Cuánto tiempo tomará para que una inversión de \$8,000 a una tasa de interés compuesto del 9\% anual duplique su valor?
                \\ \textbf{Respuesta:} 8 años, 0 meses y 16 días (aprox.)

                \item Calcula el monto total acumulado si se invierten \$3,000 a una tasa de interés compuesto del 7\% anual durante 3 años.
                \\ \textbf{Respuesta:} \$3,675.13

                \item Si se invierte \$400 a una tasa de interés compuesto del 10\% anual, ¿cuál será el monto acumulado después de 4 años?
                \\ \textbf{Respuesta:} \$585,64

                \item Si una inversión inicial de \$6,000 crece a \$9,000 en 6 años, ¿cuál es la tasa de interés compuesto anual?
                \\ \textbf{Respuesta:} 6,99\% anual

                \item Si una inversión inicial de \$1,000 crece a \$1,380 en 2 años, ¿cuál es la tasa de interés compuesto anual?
                \\ \textbf{Respuesta:} 17,47\% anual

                \item Calcula el monto final después de 8 años si se invierten \$2,000 a una tasa de interés compuesto del 5\% anual.
                \\ \textbf{Respuesta:} \$2,954.91

                \item Si se invierte \$1,200 a una tasa de interés compuesto del 4\% anual, ¿cuánto tiempo tomará para que el monto se duplique?
                \\ \textbf{Respuesta:} 17 años, 8 meses y 3 días.
            \end{enumerate}
            \subsection*{Problemas reto}
            \begin{enumerate}
                \item Eleuterio Choquetijlla depositó en el Banco Millonario a nombre de su hijo Evo Choquetijlla la suma de Bs10.000, 
                justo el día en que el niño cumplía 10 años de edad.  Las tasas de interés que el banco pagó fueron las siguientes: 
                \begin{itemize}
                    \item 13\% anual capitalizable mensualmente para los primeros 3 años. 
                    \item 12\% anual con capitalización semestral para los siguientes 6 años. 
                    \item 15\% anual con capitalización mensual a partir de ese momento. 
                \end{itemize}
                ¿Qué edad tenía Evito cuando su padre decide cerrar la cuenta bancaria y recibe un monto total de Bs84.200? ¿Cuantos intereses genero la cuenta con el tiempo?
                \textbf{26 años}
                \textbf{Bs74200}
                \item Usted invierte una determinada suma durante 15 años al cabo de los cuales recibe un monto total de Bs500.000. Las tasas de interés que su capital redituó fueron las siguientes: 
                \begin{itemize}
                    \item 18\% anual capitalizables bianualmente los primeros 6 años
                    \item 11\% trimestral capitalizables 2 veces cada bimestre hasta el año 8. 
                    \item 11\% anual capitalizables cuatrimestralmente los siguientes 3 años.
                    \item 18\% anual capitalizables bimestralmente el resto del tiempo.
                \end{itemize} 
                Considere también que durante estos 15 años ocurrieron los siguientes eventos:
                \begin{itemize}
                    \item A los 7 años y 9 meses de efectuada la inversión usted gana la lotería y decide depositar en su cuenta Bs20.000 que representa la cuarta parte del premio ganado.
                    \item Al inicio del año 10, decide sorprender a su pareja y retira de la cuenta Bs10.000 para efectuar un viaje a la “Isla Cabera” del Cabire. 
                    \item 76 meses antes de cumplirse el plazo de los 15 años, efectúa un retiro de Bs5.000 para viajar al cristo corcobado.
                    \item Durante el viaje al Cabire se infecto con un parasito, lo noto 4 meses despues de volver y entonces tuvo que retirar Bs20.000 para cubrir los gastos medicos.
                    \item En el año 13 perdio una demanda y cada 2 meses tuvo que pagar Bs500 durante un año para cumplir las ordenes de la corte
                \end{itemize}
                ¿Cuantos intereses genero la cuenta durante todo este tiempo? ¿Cuál fue el capital inicial que usted invirtió?
                \textbf{Bs486.965,94}
                \textbf{Bs31.034,06}
\end{enumerate}

\section{Tasas Equivalentes}
\paragraph{Definicion} Las tasas equivalente, son un instrumento para el analisis financiero, el 
objetivo de las mismas es permitirnos comprarar, trabajar y planificar; sobre tasas de interes con 
diferentes periodos de capitalizacion.\\
Una situacion muy común en el ambito financiero es la necesidad de comparar los rendimientos de varias 
opciones de inversion diferentes, pero entonces surge un dilema cuando uno encuentra algo similar a lo siguiente:\\\\
\fbox
{
    \parbox{\textwidth}
    {
        \textbf{Bolivia 2030, ASFI declara una tasa de interes minima del 10\% capitalizable anualmente en los DPFS 
        bancarios, ante esta noticia los siguientes bancos anuncian las siguientes tasas de interes para el siguiente año:}
        \begin{itemize}
            \item \textit{Banco BNB:} 12\% capitalizable mensualmente
            \item \textit{Banco Fasil:} 6\% semestral capitalizable bimestralmente 
            \item \textit{Banco Morales:} 8\% capitalizable trimestralmente
        \end{itemize}
    }
}
\\

En este momento, usted se abra dado cuenta de que aunque podemos ver todas las tasas efectivas, 
es dificil dar un juicio sobre cual es mejor oferta y si todos ellos cumplen efectivamente las 
exigencias de la ASFI, entonces es cuando nos resultan utiles las tasas equivalentes.\\
Para este propósito, es bueno utilizar la siguiente formula como guia para realizar estos calculos:
\begin{center}
    $\Large{\boxed{(1+i)^{t}=(1+i_e)^{t_e}}}$ 
    \begin{align*}
        i \rightarrow &\text{Tasa de interes}\\
        i_e \rightarrow &\text{Tasa equivalente}\\
        t \rightarrow &\text{Periodo de tiempo}\\
        t_e \rightarrow &\text{Periodo de tiempo equivalente}\\
    \end{align*}
\end{center}
Es bueno hacer una aclariacion del siguiente topico, cuando decimos periodo de tiempo equivalente 
nos referimos a que si tenemos una tasa de interes del 10\% efectiva mensual, pero queremos su equivalente 
en capitalzacion anual, entonces nuestro periodo de tiempo seria 12 meses y su equivalente seria 1 año, 
es asi que reemplazando datos en nuestra formula tendriamos $\bf{(1+10\%)^{12}=(1+i_e)^1}$ y lo unico que 
faltaria seria despejar la tasa equivalente puesto que es la unica incognita de la ecuacion.\\

\section*{Ejemplo ilustrativo}
\textit{Jason Voorhees es un hombre simple que disfrute de vivir en su cabaña al lado del lago, pero justamente un dia un hombre lo atropella, gracias a una demanda y un buen abogado, el señor Voorhees se consigue hacer con una buena suma de dinero, ante lo cual le empiezan a llegar ofertas bancarias para que deposite su dinero con ellos, ante lo cual el señor Voorhees decide contratarlo a usted, el señor Voorhees le aclara que no quiere complicarce la existencia y solo quiere tomar algunos de los DPFs que le ofrecen los bancos, donde el banco Krueger le ofrece una tasa de 72\% trianual capitalizable mensualmente, el banco Predator le ofrece un 19\% efectivo anual, el banco DOOM le ofrece un 12\% semestral capitalizable bimestralmente, el señor Voorhees le dice que como acesor se llevara como comision el primer interes generado por el DPF en el cual se deposite el dinero, ¿En que DPF le conviene al señor Voorhees depositar su dinero? ¿En que DPF le conviene a usted que el señor Voorhees deposite su dinero?}
\subsubsection*{Pasos de la resolucion}
\begin{enumerate}
    \item Volvemos a leer el ejercicio con la intencion de responder la pregunta ¿Que clase de ejercicio es?\\
    \textbf{Es un ejercicio de Tasas Equivalentes} || En este caso, es un ejercicio de tasas equivalentes puesto que necesitamos comparar diferentes tasas de interes, las cuales tienen distintos periodos de capitalizacion. Dicho asi sea, cada vez que deba comparar tasas efectivas de interes, debera referirse a las tasas equivalentes.
    \item Definimos en que escala temporal queremos trabajar, usualmente puede decidir esto de forma arbitraria pero como en este caso tenemos una tasa efectiva anual, podemos ahorrarnos trabajo llevando todo a la escala temporal de esta tasa efectiva.\\
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
\end{enumerate}

\section{Interes continuo}

\section{Inflacion}
\paragraph{Definicion} La inflacion es la perdida de poder adquisitivo de una moneda, puesto que, 
esta misma afecta a todas las personas en todas partes del mundo a todo momento es un elemento a tener en cuenta cuando hablamos de planeación financiera.\\
Es ahora que usted ya que pudo apreciar los elementos mas basicos de las finanzas por separado, es capaz de 
agregar este componente común de la realidad al analisis que realizamos.\\

Por tanto la pregunta que surge es como este fenomeno afecta a nuestros planes, una forma común de ejemplificarlo es con la siguiente situacion, 
el primero del mes un pedazo de pan vale Bs1 por cada hogaza, pero para la misma fecha el siguiente año la misma hogaza vale Bs2, 
para nosotros esto significaria que ahora para comprar la misma cantidad de pan necesitariamos el doble de dinero que antes.\\

Es asi que para cuantificar este efecto se utiliza la siguiente formula, usualmente conocida como teorema de Fisher:
\begin{center}
    $\Large{\boxed{(1+r)=\frac{(1+i)}{(1+\pi)}}}$ 
    \begin{align*}
        r \rightarrow   &\text{Tasa de rendimiento real}\\
        i \rightarrow   &\text{Tasa de interes}\\
        \pi \rightarrow &\text{Tasa de Inflacion}\\
    \end{align*}
\end{center}
Queda espacio para aclarar, para usar la formula de fisher todas las tasas tienen que estar en un mismo 
periodo efectivo, usted ya se encuentra familiarizado con este concpeto, puesto que, en capitulos anteriores 
usted ya se encontro con las tasas equivalentes, el llevar todas las tasas de la formula de Fisher a un mismo 
periodo, entonces no es mas que una simple aplicacion de estas mismas.\\
% PEDIR AUTORIZACION AL CESAR PARA PODER AGREGAR ESTA FORMULA MAS

% Aunque la formula de Fisher sea muy util para algunos movimientos simples, seria bueno que conozca esta segunda formula, la cual tiene alguna aplicacion extra que le puede ser util:
% \begin{center}
%     $\Large{\boxed{\frac{C_0}{P}(1+r)^t=\frac{C_t}{P(1+\pi)^t}}}$ 
%     \begin{align*}
%         r \rightarrow   &\text{Tasa de rendimiento real}\\
%         \pi \rightarrow &\text{Tasa de Inflacion}\\
%         C_0 \rightarrow &\text{Saldo inical de la cuenta}\\
%         C_t \rightarrow &\text{Saldo Final de la cuenta}\\
%         t \rightarrow &\text{Tiempo}\\
%     \end{align*}
% \end{center}
\section*{Ejemplo ilustrativo}
\textit{Lex Luthor, el hipermagnate inmoviliario, hace 2 meses decidio que deberia revisar su planeacion financiera, ahora mismo necesita revisar cuanto han estado rindiendo sus inversiones bancarias, las cuales le han ofrecido intereses compuestos a un interes del 15\% efectivo, pero como Luthor sabe que este resultado esta contaminado por la inflacion del pais, necesita saber cuanto a sido el rendimiento real de las mismas, para lo cual recupera la informacion de la inflacion de los ultimos 3 años, los datos indican que hubo las siguientes tasas de inflacion anual: 12\%, 6\% y 8\%. ¿Cuanto fue el rendimiento real de las inversiones bancarias de Luthor en cada uno de estos 3 años?}

\subsubsection*{Pasos de la Solucion}
\begin{enumerate}
    \item Volvemos a leer el ejercicio con la intencion de responder la pregunta ¿Que clase de ejercicio es?\\
    \textbf{Es un ejercicio de Inflacion}
    \item Tenemos que trabajar unicamente con tasas de interes efectivas, pero como en este caso ya nos dan efectivas no hay necesidad de realizar ningun procedimiento.
    \item Revisamos la ecuacion de tasas equivalentes $(1+r)=\frac{1+i}{1+\pi}$, en este caso necesitamos  los datos de inflacion e interes para poder obtener nuestros rendimientos reales.
    \item Finalmente ingresamos nuestras diferentes inflaciones, para obtener nuestros rendimientos particulares para cada año.\\
    \textbf{Primer año:}
    \begin{align*}
        (1+r)=\frac{1+15\%}{1+12\%}\\
        r=\frac{1+15\%}{1+12\%}-1\\
        r=\frac{3\%}{1+12\%}\approx2,6786\%
    \end{align*}
    \textbf{Segundo año:}
    \begin{align*}
        (1+r)=\frac{1+15\%}{1+6\%}\\
        r=\frac{1+15\%}{1+6\%}-1\\
        r=\frac{9\%}{1+6\%}\approx8,4906
    \end{align*}
    \textbf{Tercer año:}
    \begin{align*}
        (1+r)=\frac{1+15\%}{1+8\%}\\
        r=\frac{1+15\%}{1+8\%}-1\\
        r=\frac{7\%}{1+8\%}\approx6,4815\%
    \end{align*}
    \text{ }\\
    Con eso realizado el ejercicio se termina.
\end{enumerate}
\subsection{Ejercicios de Capitulo}
\subsection{Problemas para practicar}
\begin{enumerate}
    \item Un inversionista quiere un rendimiento de 12\% por año en un DPF, ¿cual deberia ser la tasa de interes, si se pronostica una inflacion del 4\% durante todo este año?
    \textbf{16,48\%}
    \item Tatiana decidio invertir su dinero en un DPF con un interes del 15\%, si la inflacion en el ultimo año fue del 10\%, ¿cual fue el rendimiento real del DPF?
    \textbf{4,54\%}
    \item María invierte en un bono con una tasa de interés nominal del 9.3\%. Si la inflación durante el período de inversión fue del 3.8\%, ¿cuál fue el rendimiento real del bono?
    \textbf{5,29\%}
    \item Pedro decide depositar su dinero en un fondo mutuo con una tasa de interés nominal del 7.2\%. Si la inflación anual es del 2.5\%, ¿cuál es el rendimiento real del fondo mutuo?    
    \textbf{5,29\%}
    \item Sofía está considerando una cuenta de ahorro, esperando un rendimiento del 6.8\%. Si la tasa de inflación esperada es del 1.2\%, ¿Cual deberia ser la tasa de interes?
    \textbf{8,0816\%}
    \item Luis tiene la opción de invertir esperando un rendimiento del 4\%. Dado que la tasas de interes es del 5.6\%, ¿cuál sería la inflacion?
    \textbf{1,538\%}
    \item Javier decide invertir en un fondo de inversión con una tasa de interés nominal del 10.2\%. Si la inflación esperada es del 3.9\%, ¿cuál sería el rendimiento real del fondo de inversión?
    \textbf{6,064\%}
    \item Marta está considerando un depósito a plazo fijo con una tasa de interés nominal del 7.5\%. Si la inflación proyectada es del 2.3\%, ¿cuál sería el rendimiento real del depósito?
    \textbf{5,083\%}
    \item Diego está evaluando un bono que promete un rendimiento del 9.8\%. Dado que la inflación es del 3.5\%, ¿cuál sería la tasa de interes del bono?
    \textbf{6,087\%}
    \item Carla decide abrir una cuenta de ahorro con una tasa de interés nominal del 5.9\%. Si la inflación durante el período es del 2.8\%, ¿cuál sería el rendimiento real de la cuenta de ahorro?
    \textbf{3,016\%}
    \item Andrés está considerando una inversión que ofrece una tasa de interés nominal del 11.1\%. Si el rendimiento esperado es del 4.9\%, ¿cuál sería la inflacion?
    \textbf{5,91\%}
    \item Laura invierte en bonos con una tasa de interés nominal del 8.9\%. Si la inflación durante el período de inversión es del 3.2\%, ¿cuál sería el rendimiento real de los bonos?
    \textbf{5,523\%}
    \item Carlos decide depositar su dinero en un fondo de inversión con una tasa de interés nominal del 6.5\%. Si la inflación proyectada es del 2.7\%, ¿cuál sería el rendimiento real del fondo de inversión?
    \textbf{3,7\%}
\end{enumerate}
\subsection*{Problemas reto}
\begin{enumerate}
    \item Si Marco Aurelio quiere un rendimiento del 35\% a lo largo de los siguientes 5 años, sabiendo que el pronostico de la inflacion 
    de los siguiente 5 años es del 5\% anual, ¿Cual deberia ser la tasa de interes a la que Marco debe invertir su dinero? ¿Si Marco invierte 
    Bs80.000 cuanto sera la cantidad de retorno? Por variaciones de la inflacion con respecto a las prediciones, Marco Aurelio obtiene un 40\% de rendimiento, 
    si la inflacion fue igual durante los ultimos 5 años, ¿Cual fue la inflacion anual?
    \textbf{56,28\%}\textbf{Bs125.023,5}\textbf{2,224\%}
\end{enumerate}