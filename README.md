# CIENCIAS2 16/3

# ALFABETO
- Conjunto de simbolos
- No Vacio
- FINITO
- SIGMA (SUMATORIA) para alfabetos
# Palabra
- Secuencia *finita* de simbolos de dicho alfabeto
- Cadena de caracteres puede ser o no palabra dependiendo el alfabeto considerado
# Palabra Vacia
- Palabra de 0 letras, se habla de LA PALABRA pq es unica.(Epsilaund)
# Lenguaje
- Conjunto de palaras sobre el alfabeto (no alfabeto no party)
- Cadena de caracteres puede ser o no palabra dependiendo el alfabeto considerado
- Lenguaje no restricciones, a diferencia de alfabeto
# CIerre *
- Corresponde al lenguaje de TODAS las palabras posibles sobre Sigma.
- Epsilaund siempre en sigmasterisco.
# Operadores
   # Cardinal | | 
- funcion de sigma* a naturales*
- Cantidad de simbolos de la palabra DEPENDIENDO DEL ALFABETO
# Concatenación de PAlabras
- Punto sigma*xsigma*=sigma**
- agregar palabra
# Potencia 
- Multiplica
- TODO FINITO
# Cardinal para lenguaje
- |L|= 4 si L={a,ab,abb,b} sobre sigma={a,b}

# Lenguaje= COnjunto y trabaja como tal, union interseccion etc.

# COncatenacion para Lenguaje, toos con toos

- {a,b}*{b,a}={ab,aa,bb,ba}

# Potencia Para Lenguaje

- {a,b]^2={a,b}*{a,b]

# Cierre de un lenguaje
- Cierre estrella, Un lenguaje donde combino palabras de largo n, infinitum

# REGEXP
# Lenguaje Regular, 
- EJ {},{epsilon},sigma(un solo simbolo),Union de dos lenguajes regulares, concatenacion de dos lenguajes, l regular por lo tanto l* regular
# Demostracion de regularidad
- Usar reglas anteriores

# Expresiones regulares
- Resumen de como expresar lenguajes regulares (notacion), es decir, sin llaves de conjunto, sea fi (vacio) epsilon(epsilon)

# LUNES 20/3

# Automata finito deterministico (AFD)
- Maquina Reconocedora de palabras sobre un alfabeto (sigma)

- *Caja negra, Cosa que no me interesa que haya adentro (entrada salida, tipo control remoto)*

- Note que AFD sobre Sigma define un lenguaje sobre Sigma* formado por las palabras que el automata reconoce

- Automata define un lenguaje, definido por las palabras que reconoce el automata

- solo una entrada implica estado inicial, dos circulos, estados finales.
- Aristas implica Transicion entre estado

- SOLO ACEPTADAS SI TERMINAN EN ESTADOS FINALES!
- Lrara implica operador 
- Ej: Lrara(A)={xE{a,b}*| x comienza con cantidad par de b's*}
# Definicion formal de AFD 
- AFD ES UNA QUNTUPLA (5 elementos), SIgma S, S0 delta F
- S es conjunto de estados
- S0 estado inicial
- Delta  es funcion de transicion (toma un simbolo de alfabeto cruz estado y va a estado)
  F es estados finales
- Sigma alfabeto


 
