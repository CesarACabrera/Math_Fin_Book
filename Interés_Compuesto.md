# 1.2 Interés Compuesto
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
* **Tasas Efectivas:** Son las tasas ``reales'', donde el periodo y la frecuencia de capitalización están en perfecta sintonía. Es la tasa que efectivamente afecta el bolsillo de Félix al final del día.

## 1.2.1 Ejemplo ilustrativo:
Freddy K. siempre ha sido considerado un hombre metódico y peculiar por sus colegas. Mientras otros gastaban sus bonos, él seguía el consejo de su consultor, Bruno, manteniendo una disciplina inquebrantable. Durante los últimos 25 años, realizó depósitos constantes en una cuenta que le ofrecía un interés compuesto del 12\% anual, con capitalización mensual. Hoy, Freddy sonríe al ver su saldo: ha logrado acumular la impresionante cifra de $1,000,000$ USD. Sin embargo, la curiosidad lo asalta. Recuerda que hace 30 años ganó un premio de lotería de $25,000$ USD que gastó en viajes y lujos. Llama a Bruno con una duda existencial: Si en lugar de gastar ese premio, lo hubiera depositado en esa misma cuenta hace 30 años y me hubiera olvidado de él, ¿tendría hoy más o menos dinero que con mi plan de ahorro actual?'' Además, se pregunta: ¿Y si hubiera tenido la paciencia de esperar 10 años más (40 años en total)?''
### Pasos a seguir
1. **Análisis del escenario:** Debemos contrastar el ahorro actual de Freddy ($1,000,000$ USD) contra el valor futuro ($S_t$) de un capital único invertido bajo el efecto del interés compuesto.
2. **Identificación de variables y herramientas:** Utilizaremos la ecuación fundamental del interés compuesto: $S_t = K_0(1+i)^n$. Del enunciado de Freddy extraemos:

    * **Capital inicial ($K_0$):** $25,000$ USD (el premio de lotería).
    * **Tasa Nominal ($j$):** 12\% anual capitalizable mensualmente.
    * **Tiempo ($t$):** Escenario A: 30 años. Escenario B: 40 años.

3. **Sincronización de la Tasa (Conversión a Efectiva):** Como nos enfrentamos a una tasa nominal (el periodo anual no coincide con la frecuencia mensual), debemos encontrar la tasa efectiva mensual ($i$) que realmente hará crecer el dinero: $$i = \frac{j}{m} = \frac{12\% \text{ anual}}{12 \text{ meses}} = 1\% \text{ mensual efectiva} = 0{.}01$$

4. **Sincronización del Tiempo ($n$):** Para que la fórmula funcione, el tiempo debe hablar el mismo ``idioma'' que la tasa (meses):
    * Para 30 años: $n = 30 \times 12 = 360$ meses.
    * Para 40 años: $n = 40 \times 12 = 480$ meses.
5. **Resolución Matemática:** Sustituimos en la ecuación para ambos escenarios:\
**Escenario A (30 años):**
$$\begin{align*}
    S_{360} &= 25.000 \cdot (1 + 0{.}01)^{360} \\
    S_{360} &\approx 898.741,03 \text{ USD}
\end{align*}$$
_Conclusión 1:_ Freddy habría obtenido menos dinero que con su plan actual. La disciplina de ahorrar mes a mes durante 25 años superó el efecto de un capital único de 30 años.

**Escenario B (40 años):**
$$\begin{align*}
    S_{480} &= 25.000 \cdot (1 + 0{.}01)^{480} \\
    S_{480} &\approx 2,966,193{.}13 \text{ USD}
\end{align*}$$
_Conclusión 2:_ Aquí vemos el verdadero poder del tiempo. Al esperar solo 10 años más, el saldo casi se triplica, superando por mucho el millón de dólares actual.

6. **Interpretación para la toma de decisiones:** Como le explicaría Bruno a Freddy: ``El interés compuesto no es una carrera de velocidad, sino de resistencia''. 10 años adicionales de capitalización sobre una base ya crecida generan un efecto exponencial masivo.

## 1.2.2 Problemas para practicar
1. **Conversión de Tasas:** Lleva las siguientes tasas de interés nominales a sus correspondientes tasas efectivas por periodo de capitalización:

- 12% anual cap. bimestralmente
- 8% semestral cap. mensualmente
- 10,5% anual cap. trimestralmente
- 12% trimestral cap. bimestralmente
- 9,25% mensual cap. diariamente
- 7,75% anual cap. semestralmente
- 11,8% bimestral cap. anualmente
- 6,9% trimestral cap. mensualmente
- 9,3% semestral cap. trimestralmente
- 5,5% mensual cap. bimestralmente
- 8,2% bimestral cap. semestralmente
- 10,75% anual cap. mensualmente
- 7,1% mensual cap. trimestralmente
- 11,9% bimestral cap. mensualmente
- 6,8% trimestral cap. anualmente
- 9,6% semestral cap. bimestralmente
- 5,25% mensual cap. trimestralmente
- 8,9% anual cap. semestralmente
- 12,3% bimestral cap. mensualmente
- 7,5% trimestral cap. trimestralmente
- 10,2% semestral cap. anualmente

**Respuestas (Tasas efectivas por periodo):**

- a) 0.5% bim.
- b) 1,33% mens.
- c) 2,625% trim.
- d) 8,00% bim.
- e) 0,3083% diar.
- f) 3,875% sem.
- g) 70,80% anual
- h) 2,30% mens.
- i) 4,65% trim.
- j) 11,00% bim.
- k) 24,60% sem.
- l) 0,8958% mens.
- m) 21,30% trim.
- n) 5,95% mens.
- o) 27,20% anual
- p) 3,20% bim.
- q) 15,75% trim.
- r) 4,45% sem.
- s) 6,15% mens.
- t) 7,50% trim.
- u) 20,40% anual

2. Calcula el monto final después de 5 años si se invierten $5,000 a una tasa de interés compuesto del 6% anual.

   **Respuesta:** $6,691.13

3. ¿Cuánto tiempo tomará para que una inversión de $8,000 a una tasa de interés compuesto del 9% anual duplique su valor?

    **Respuesta:** 8 años, 0 meses y 16 días (aprox.)

4. Calcula el monto total acumulado si se invierten \$3,000 a una tasa de interés compuesto del 7\% anual durante 3 años.

    **Respuesta:** \$3,675.13

5. Si se invierte \$400 a una tasa de interés compuesto del 10\% anual, ¿cuál será el monto acumulado después de 4 años?

    **Respuesta:** \$585,64

6. Si una inversión inicial de \$6,000 crece a \$9,000 en 6 años, ¿cuál es la tasa de interés compuesto anual?

    **Respuesta:** 6,99\% anual

7. Si una inversión inicial de \$1,000 crece a \$1,380 en 2 años, ¿cuál es la tasa de interés compuesto anual?

    **Respuesta:** 17,47\% anual

8. Calcula el monto final después de 8 años si se invierten \$2,000 a una tasa de interés compuesto del 5\% anual.

    **Respuesta:** \$2,954.91

9. Si se invierte \$1,200 a una tasa de interés compuesto del 4\% anual, ¿cuánto tiempo tomará para que el monto se duplique?

    **Respuesta:** 17 años, 8 meses y 3 días.
    
## 1.2.3 Problemas reto
1. Eleuterio Choquetijlla depositó en el Banco Millonario a nombre de su hijo Evo Choquetijlla la suma de Bs10.000, justo el día en que el niño cumplía 10 años de edad.  Las tasas de interés que el banco pagó fueron las siguientes: 
    * 13\% anual capitalizable mensualmente para los primeros 3 años. 
    * 12\% anual con capitalización semestral para los siguientes 6 años. 
    * 15\% anual con capitalización mensual a partir de ese momento.

    ¿Qué edad tenía Evito cuando su padre decide cerrar la cuenta bancaria y recibe un monto total de Bs84.200? ¿Cuantos intereses genero la cuenta con el tiempo?

    **Respuesta:** 26 años y Bs74200
2. Usted invierte una determinada suma durante 15 años al cabo de los cuales recibe un monto total de Bs500.000. Las tasas de interés que su capital redituó fueron las siguientes: 
    * 18\% anual capitalizables bianualmente los primeros 6 años
    * 11\% trimestral capitalizables 2 veces cada bimestre hasta el año 8. 
    * 11\% anual capitalizables cuatrimestralmente los siguientes 3 años.
    * 18\% anual capitalizables bimestralmente el resto del tiempo.

    Considere también que durante estos 15 años ocurrieron los siguientes eventos:

    * A los 7 años y 9 meses de efectuada la inversión usted gana la lotería y decide depositar en su cuenta Bs20.000 que representa la cuarta parte del premio ganado.
    * Al inicio del año 10, decide sorprender a su pareja y retira de la cuenta Bs10.000 para efectuar un viaje a la “Isla Cabera” del Cabire. 
    * 76 meses antes de cumplirse el plazo de los 15 años, efectúa un retiro de Bs5.000 para viajar al cristo corcobado.
    * Durante el viaje al Cabire se infecto con un parasito, lo noto 4 meses despues de volver y entonces tuvo que retirar Bs20.000 para cubrir los gastos medicos.
    * En el año 13 perdio una demanda y cada 2 meses tuvo que pagar Bs500 durante un año para cumplir las ordenes de la corte
    
    ¿Cuantos intereses genero la cuenta durante todo este tiempo? ¿Cuál fue el capital inicial que usted invirtió?

    **Respuesta:** Bs486.965,94 y Bs31.034,06