# 1.1 Interés Simple

> $$S_t = K_0 + K_0 \cdot i \cdot t$$
> 
> * **$S_t$** : Saldo en el tiempo $t$
> * **$K_0$** : Capital inicial
> * **$i$** : Tasa de interés
> * **$t$** : Tiempo

Tras una breve negociación, Bruno acepta el trato bajo la modalidad de interés simple. En este esquema, el ``extra'' que Félix pagará se calcula exclusivamente sobre el monto original prestado, sin acumularse sobre sí mismo en periodos siguientes. Es una forma lineal y transparente de entender el crecimiento de una deuda o inversión. Por ejemplo, si Félix recibe 100 dólares con un interés simple del 5\% anual, al cabo de un año el agradecimiento se traduce en 5 dólares adicionales. El interés simple es la base fundamental de las finanzas porque nos permite modelar el crecimiento del capital de manera constante.

Para dominar estas decisiones financieras, debemos traducir la realidad al lenguaje de las ecuaciones. La fórmula maestra que utilizaremos es: $S_t = K_0 + K_0 \cdot i \cdot t$, donde cada variable cuenta una parte de la historia: el inicio ($K_0$), el costo del tiempo ($i$), la duración ($t$) y el desenlace final ($S_t$).

## 1.1.1 Ejemplo ilustrativo:

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

## 1.1.2 Problemas para practicar
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
## 1.1.3 Problemas reto
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