I would like you to add HTML and LaTeX code to source of text that consists in several test questions. Each wording is followed by four possible answers. Keep that in mind when recognizing each test exersise.

Task: Your task is to add markup language to the text sended during this conversation inside a code window, so I can see all the added language and copy it.

Formatting Criteria:

- Make a table with one column; "Front". Each row must contain one answer with it's corresponding four possible answers.
- The text will be gradually passed to you. Don't build the entire table with all the text already processed; just make the row or rows corresponding to the last text passed.
- The text could contain some HTML code which indicates the importation of an image. That code must be in the output as it is.  
- The output is in a plain text window, so the code can be easily copied.
- Each formatted question and it's possible answers are in a single line. This is possible because HTLM is used to make newlines.

Reference Criteria for each "Statement":

- The language of the input text must be kept at the output. The mayority of it is in Spanish; however, if you find something in English, don't translate it.
- Use LaTeX for:
  - Mathematic expressions. 
  - Vectors. 
  - Variables pseudocode. 
  - Funtions names.
- Use HTML for spacing and listing the possible answers.
- I DON'T want you to respond the questions. I WANT to obtain the formatted text as explained above.

The next section present examples. First, the inputs and then, the corresponding outputs that are waited. Do not print the examples. Uppon finishing reading the example's section I want to know if do you understand it. All the following text I will send during this conversation must be formatted as explained above.

Input example:

Cuantantas lineas tiene el siguiente código?
Algoritmo SumaDeNaturales
Entrada: N (un número entero)
Salida: Suma de los primeros N números naturales
Inicio
suma ← 0
para i desde 1 hasta N hacer
  suma ← suma + i
fin para
retornar suma
Fin

  2
  3
  4
  Ninguna de las anteriores

Indica de entre los siguientes, cuál sería el coste mínimo de un algoritmo que dado un vector C[1..n] de números enteros distintos no ordenado, y un entero S, determine si existen o no dos elementos de C tales que su suma sea exactamente S.

 Θ(n log n).
 Θ(n).
 Θ(n2).
 Θ(n2 log n).

Considere dos vectores f y g de n elementos que representan los valores que toman dos funciones en el intervalo [0..n-1]. Los dos vectores están ordenados, pero el primero f es un vector estrictamente creciente (f[0] < f[1] < ... < f[n-1]), mientras g es un vector estrictamente decreciente (g[0] > g[1]>…> g[n-1]). Las curvas que representan dichos vectores se cruzan en un punto concreto, y lo que se desea saber es si dicho punto está contenido entre las componentes de ambos vectores, es decir, si existe un valor i tal que f[i] = g[i] para 0 <= i <= n - 1. La figura muestra un ejemplo en el que las gráficas se cruzan en i=8 que se corresponde con el valor 25 en ambas curvas. Se busca un algoritmo que compruebe si el punto de cruce está contenido en las componentes de ambos vectores. ¿Cuál de las siguientes opciones es cierta?
<br><img src="UNED/II/PREDA/Graphics/01.png"><br>
El algoritmo más eficiente que se puede encontrar es O(n2)
 Se puede encontrar un algoritmo recursivo de coste logarítmico.
 El algoritmo más eficiente que se puede encontrar es O(n).
 Ninguna de las otras opciones.

 Dado un grafo con n vértices y a aristas sobre el que se pueden realizar las siguientes operaciones:

 esAdyacente: comprueba si dos vértices son adyacentes.
 borrarVértice: Borra el vértice especificado y todas sus aristas.
 añadirVértice: Añade un nuevo vértice al grafo.

¿Cuál es la complejidad de cada una de las operaciones anteriores según se utilice una matriz de adyacencia (MA) o una lista de adyacencia (LA)?

MA	LA
esAdyacente	O(1)	O(n)
borrarVértice	O(1)	O(n+a)
añadirVértice	O(1)	O(1)
MA	LA
esAdyacente	O(1)	O(1)
borrarVértice	O(n)	O(n)
añadirVértice	O(n)	O(1)
MA	LA
esAdyacente	O(1)	O(n)
borrarVértice	O(n)	O(n+a)
añadirVértice	O(n)	O(1)
MA	LA
esAdyacente	O(1)	O(1)
borrarVértice	O(n)	O(n)
añadirVértice	O(n)	O(n)

Considérese el vector [10,7,7,4,3,1] que representa un montículo. ¿Cuál sería la representación resultante de insertar en este montículo el valor 11 usando la función flotar?
 [10,7,11,4,3,1,7].
 [11,7,7,4,3,1,10].
 [10,7,11,4,3,1,7].
 Ninguna de las otras opciones

 Dado el grafo no dirigido de la figura, indique cuál sería el orden en que se seleccionarían (pasan a pertenecer al árbol) los nodos al aplicar el algoritmo de Prim comenzando por el nodo A:
 <br><img src="UNED/II/PREDA/Graphs/04.png"><br>
  A, F, E, C, B, D
  A, B, C, E, D, F
  A, C, D, B, F, E
  Ninguna de las otras opciones
  
Output example:

| Front |
| --- |
| # Formatted exercise
Cuantas líneas tiene el siguiente código? <pre> Algoritmo SumaDeNaturales <br> &nbsp;&nbsp;&nbsp;&nbsp;Entrada: N (un número entero) <br> &nbsp;&nbsp;&nbsp;&nbsp;Salida: Suma de los primeros N números naturales <br> &nbsp;&nbsp;&nbsp;&nbsp;Inicio <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;suma &larr; 0 <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;para i desde 1 hasta N hacer <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;suma &larr; suma + i <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fin para <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;retornar suma <br> &nbsp;&nbsp;&nbsp;&nbsp;Fin </pre> <ol type="a"><li>2</li><li>3</li><li>4</li><li>Niguna de las anteriores</li></ol>

|# Formatted exercise
Indica de entre los siguientes, cuál sería el coste mínimo de un algoritmo que dado un vector \(C[1..n]\) de números enteros distintos no ordenado, y un entero \(S\), determine si existen o no dos elementos de \(C\) tales que su suma sea exactamente \(S\).<br><br><ol type="a"><li>\(\Theta(n \log n)\)</li><li>\(\Theta(n)\)</li><li>\(\Theta(n^{2})\)</li><li>\(\Theta(n^{2} \log n)\)</li></ol>

|# Formatted exercise
Considere dos vectores \( f \) y \( g \) de \( n \) elementos que representan los valores que toman dos funciones en el intervalo \([0..n-1]\). Los dos vectores están ordenados, pero el primero \( f \) es un vector estrictamente creciente (\( f[0] < f[1] < ... < f[n-1] \)), mientras \( g \) es un vector estrictamente decreciente (\( g[0] > g[1] > ... > g[n-1] \)). Las curvas que representan dichos vectores se cruzan en un punto concreto, y lo que se desea saber es si dicho punto está contenido entre las componentes de ambos vectores, es decir, si existe un valor \( i \) tal que \( f[i] = g[i] \) para \( 0 \leq i \leq n - 1 \). La figura muestra un ejemplo en el que las gráficas se cruzan en \( i=8 \) que se corresponde con el valor 25 en ambas curvas. Se busca un algoritmo que compruebe si el punto de cruce está contenido en las componentes de ambos vectores. <br><img src="UNED/II/PREDA/Graphics/01.png"><br>¿Cuál de las siguientes opciones es cierta? <ol type="a"><li>El algoritmo más eficiente que se puede encontrar es \( O(n^2) \)</li><li>Se puede encontrar un algoritmo recursivo de coste logarítmico.</li><li>El algoritmo más eficiente que se puede encontrar es \( O(n) \)</li><li>Ninguna de las otras opciones.</li></ol>

| # Formatted exercise
Dado un grafo con \(n\) vértices y \(a\) aristas sobre el que se pueden realizar las siguientes operaciones: <ul><li>esAdyacente: comprueba si dos vértices son adyacentes.</li><li>borrarVértice: Borra el vértice especificado y todas sus aristas.</li><li>añadirVértice: Añade un nuevo vértice al grafo.</li></ul> ¿Cuál es la complejidad de cada una de las operaciones anteriores según se utilice una matriz de adyacencia (MA) o una lista de adyacencia (LA)? <ol type="a"><li> <table><tr><th>MA</th><th>LA</th></tr><tr><td>esAdyacente O(1)O(1)</td><td> O(n)O(n)</td></tr><tr><td>borrarVértice O(1)O(1)</td><td> O(n+a)O(n+a)</td></tr><tr><td>añadirVértice O(1)O(1)</td><td> O(1)O(1)</td></tr></table> </li><li> <table><tr><th>MA</th><th>LA</th></tr><tr><td>esAdyacente O(1)O(1)</td><td> O(1)O(1)</td></tr><tr><td>borrarVértice O(n)O(n)</td><td> O(n)O(n)</td></tr><tr><td>añadirVértice O(n)O(n)</td><td> O(1)O(1)</td></tr></table> </li><li> <table><tr><th>MA</th><th>LA</th></tr><tr><td>esAdyacente O(1)O(1)</td><td> O(n)O(n)</td></tr><tr><td>borrarVértice O(n)O(n)</td><td> O(n+a)O(n+a)</td></tr><tr><td>añadirVértice O(n)O(n)</td><td> O(1)O(1)</td></tr></table> </li><li> <table><tr><th>MA</th><th>LA</th></tr><tr><td>esAdyacente O(1)O(1)</td><td> O(1)O(1)</td></tr><tr><td>borrarVértice O(n)O(n)</td><td> O(n)O(n)</td></tr><tr><td>añadirVértice O(n)O(n)</td><td> O(n)O(n)</td></tr></table> </li></ol>

| # Formatted exercise
Considérese el vector \([10,7,7,4,3,1]\) que representa un montículo. ¿Cuál sería la representación resultante de insertar en este montículo el valor 11 usando la función \(flotar\)?<br><br><ol type="a"><li>\([10,7,11,4,3,1,7]\).</li><li>\([11,7,7,4,3,1,10]\).</li><li>\([10,7,11,4,3,1,7]\).</li><li>Ninguna de las otras opciones</li></ol>

| # Formatted exercise
Dado el grafo no dirigido de la figura, indique cuál sería el orden en que se seleccionarían (pasan a pertenecer al árbol) los nodos al aplicar el algoritmo de Prim comenzando por el nodo \(A\):<br><img src="UNED/II/PREDA/Graphs/04.png"><br><br><ol type="a"><li>\(A, F, E, C, B, D\)</li><li>\(A, B, C, E, D, F\)</li><li>\(A, C, D, B, F, E\)</li><li>Ninguna de las otras opciones</li></ol>

|
