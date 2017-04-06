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

# 27 MARZO, JERARQUIAs DE LENGUAJES Y AUTOMATAS
- Chomsky el autor -> Crrespondencia entre lenguajes, sus reconocedores (automatax) y sus gramaticas (Sistemas productivos de expresiones)

# MIRAR PPT! TIPOS DE LENGUAJES; GRAMATICA Y AUTOMATA
- Cada tipo subconjunto de otro, siendo el mejor tio turingo

 
# # # # ### # # # # # # # # # # # # # # # # # # # # #

# Gramaticas y Gramaticas Regulares

 - Gramatica
   - Sistema para produccion de expresiones bien formadas de un lenguaje.
   - Cuadrupla :Sigma,V,s,R
     - Sigma, alfabeto de simbolos llamados terminales
     - V, alfabetos de simbolos variables
     - Sigma y V no elementos en comun!
     - s, simbolo inicial, perteneciente a Variables
     - R, reglas para producion para produccion de la forma a->b donde a es una palaabra construida por simbolos de los primeros 2 alfabetos, pero debe tener a lo menos un elemento del segundo alfabeto.
   - Ej: A=({a,b},{A,B},A,{A->Bb,B->aB,B->e})
   
   - TIpos de gramatica
     - Libre a contexto, izquierda solo 1 simbolo
     - Regular, derecha formas aB, b o epsilon
  
 - Formato de Oracion
   - Dado G =(Sigma,V,s,R), una gramatica, se dice que el formato de oracion gamm
   
   - Derivacion Directa
     - Con G, se dice que gamma 2 deriva de gamma 1, lo que se escribe gamma1 implica gamma2
     - mirar ppt
