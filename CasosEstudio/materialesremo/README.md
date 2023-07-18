## Materiales para Remos[^1]

Antes de la energía de vapor, los barcos podían propulsarse, a vela ,o con remos. Los remos ofrecían más control que los otros dos, cuyo potencial militar fue bien comprendido por los romanos., los vikingos y los venecianos. Poco a poco fueron participando caballeros(sobre todo los jóvenes caballeros de Oxford y Cambridge), sofisticando tantolas reglas y el equipamiento. El verdadero estímulo para el desarrollo de la barca y el remo llegó en 1900 con la proclamación del remo como deporte olímpico. Desde entonces ambos han aprovechado al máximo la artesanía y los materiales de su época. Pensemos, por ejemplo, en el remo.

### El Modelo

Mecánicamente hablando, un remo es una viga, cargada en flexión, debe ser lo bastante fuerte para soportar, sin romperse, el momento flexión ejercido por el remero, debe tener una rigidez que se ajuste a las características del remero y proporcionarle la ''sensación'' adecuada y, lo que es muy importante, ser lo más ligera posible.
Los remos se diseñan rigidez, es decir, para proporcionar una deflexión elástica especificada bajo una carga determinada.

<div align="center">
  <br><img src=https://github.com/dadfinem/EMSE/blob/main/CasosEstudio/materialesremo/Im%C3%A1genes/Remo.jpg width=40%"></br>
</div>



<div align="center">
  <sub>
      Figura 6.20: Un remo se diseña en función de la rigidez y peso lijero.
  </sub>
</div>


La parte superior de la figura muestra un remo: una pala o ''cuchara'' está unida a u un eje o ''telar'' que lleva un manguito y un collarín para proporcionar una posición en la esclusa. 
La parte inferior de la figura muestra cómo se mide la rigidez del remo:

Se cuelga un peso de 10 kg en el remo a 2,05 m del collarín y se mide la deflexión en este punto. Un remo blando se desviará casi 50 mm; uno duro, sólo 30mm.

Cuando un remero encarga un remo, especifica su dureza. El remo también debe ser ligero; el peso extra aumenta el área mojada del casco y la resistencia que con lleva. 

Así que ya lo tenemos: un remo es una viga rígida y un peso mínimo. El índice de material que queremos:

$\ M=\frac{E}{ρ} $

Donde: E es el módulo de Young y ρ es la densidad. 
Hay otras limitaciones los remos se caen y las palas a veces chocan. 

El material debe ser lo suficientemente resistente como para resistirlo, por lo que los materiales quebradizos (aquellos con una tenacidad G1C inferior a 1 kJ/m2 ) son inaceptables. Teniendo en cuenta estos requisitos, resumidos en Tabla 6.1, ¿qué materiales elegiría para fabricar remos?

### La selección

La figura 6.2 muestra el gráfico apropiado: aquel en el que el módulo de Young E frente a la densidad.

<div align="center">
  <br><img src=https://github.com/dadfinem/EMSE/blob/main/CasosEstudio/materialesremo/Im%C3%A1genes/Carta%20densidad%20m%C3%B3dulo.jpg width=40%"></br>
</div>


<div align="center">
  <sub>
      Figura 6.20: El CFRP es mejor que la madera porque se puede conrolar la estructura.
  </sub>
</div>

La línea de selección del índice M tiene una pendiente de 2; está colocada de forma que un pequeño grupo de materiales quede por encima de ella. Se trata de los materiales con los mayores valores de M y son éstos los que constituyen la mejor elección, siempre que satisfagan la otra restricción (un simple atributo-límite de tenacidad). 

Contienen tres clases de materiales maderas, polímeros reforzados con carbono y ciertas cerámicas (Tabla 6.2).Los materiales cerámicos son frágiles; el gráfico de módulo de tenacidad de la figura 4.7 muestra que todos los materiales cerámicos son frágiles. no cumplen los requisitos de diseño. La recomendación es clara. Haga remos de madera o, mejor aún, de CFRP.


<div align="center">
  <sup>
      Tabla 6.19: Requisitos de diseño para recipientes a presión seguros
  </sup>
</div>

| Criterios | Descripción |
| ------------- | ------------- |
| Función  | Remo (Viga lijera y rígida)  |
| Restricciones  | Longitud L determinada|
|                |Rigidez a la flexión S especificada|
|                |Tenacidad G1c=1kJ/m2|
| Objetivo  | Minimizar la masa de la rotula  |
| Variables libres  | *Selección del material* |

<div align="center">
  <br><img src=https://github.com/dadfinem/EMSE/blob/main/CasosEstudio/RecipientesPresion/Imagenes/Figura%20619.JPG width=40%"></br>
</div>

<div align="center">
  <sub>
     Figura 6.19: Un recipiente a presión que contiene un defecto. El diseño seguro de los recipientes a presión pequeños requiere que cedan antes de romperse; el de los recipientes a presión grandes puede requerir, en cambio que tengan fugas antes de romperse.
  </sub>
</div>

### El modelo

El esfuerzo en la pared de un recipiente a presión esférico de pared delgada con radio R (Figura 6.19) es: 
   
  $\ σ=\frac{pR}{2t} $

En el diseño de recipientes a presión, el espesor de pared, t, es seleccionado de tal forma que, a la presión de trabajo, p, este esfuerzo es menos que la resistencia a la fluencia σ<sub> f </sub> de la pared. Un recipiente a presión pequeño puede ser examinado con ultrasonido, o por métodos con rayos X, o comprobado, para establecer que no contiene grietas o defectos con diámetros mayores que 2a<sub> c </sub>; entonces el esfuerzo requerido para causar la propagación de la grieta sería

  $\ \sigma = \frac{CK_{1C}}{\sqrt{\pi a_{c}}}  $
    
Cuando C es una constante cercana a la unidad y K<sub> 1C </sub> es la tenacidad a la fractura por deformación plana. La seguridad puede ser alcanzada al asegurar que el esfuerzo de trabajo es menos que esto, dado que

  $\ p \leq \frac{2t}{R} \frac{K_{1C}}{\sqrt{\pi  a_{c}}} $

La mayor presión (para un R, t y a<sub> c </sub>) es soportada por el material con el mayor valor de
    
  $\ M_{1} = K_{1C} $

Pero este diseño no es a prueba de fallos. Si la inspección es defectuosa, o si, por alguna otra razón aparece una grieta cuya longitud es mayor que a<sub>c</sub>, sigue la catástrofe. Una mayor seguridad es obtenida al requerir que la grieta no se propagará incluso si el esfuerzo alcanza el esfuerzo a la fluencia general - porque entonces el recipiente se deformará establemente de forma que pueda detectarse. Esta condición es expresada al establecer σ igual a el esfuerzo a la fluencia σ<sub> f </sub> dado 

  $\ \pi a_{c} \leq  C^{2} [ \frac{K_{1C}}{\sigma _{f}}]^{2} $
    
El tamaño de grieta tolerable, y, por tanto, la integridad del recipiente se maximiza por seleccionar un material con el mayor valor de

  $\ M_{2} = \frac{K_{1C}}{\sigma_{f}} $
    
Los recipientes a presión de gran tamaño no siempre pueden someterse a rayos X o pruebas sónicas, y las pruebas de estanqueidad pueden resultar poco prácticas. Además, las grietas pueden crecer lentamente debido a corrosión o cargas cíclicas, por lo que un único examen al principio de vida útil no es suficiente. En ese caso, la seguridad puede garantizarse disponiendo que una grieta lo suficientemente grande como para penetrar tanto en la superficie interior como en la exterior del recipiente siga siendo estable, ya que se puede detectar la fuga causada por la grieta. Esto se consigue si la tensión es siempre inferior o igual a

  $\ \sigma = \frac{CK_{1C}}{\sqrt{\frac{\pi t}{2}}} $
    
El espesor de pared t del recipiente a presión se diseñó, por supuesto, para contener la presión p sin ceder. De la ecuación (6.38) se deduce que

  $\ t \geq \frac{pR}{2\sigma _{f}} $
    
Sustituyendo esto en la ecuación anterior (con σ = σ<sub> f </sub> ) se obtiene

  $\ p \leq \frac{4C^{2}}{\pi R} \frac{^{K_{1C}^{2}}}{\sigma _{f}} $
    
La presión máxima la soporta con mayor seguridad el material con mayor valor de

  $\ M_{3} = \frac{K_{1C}^{2}}{\sigma_{f}} $
 
Tanto M<sub> 1 </sub> como M<sub> 2 </sub> pueden hacerse grandes haciendo que el límite elástico de la pared, σ<sub> f </sub>, sea muy pequeño: el plomo, por ejemplo, tiene valores altos de ambos, pero no lo elegirías para un recipiente a presión. Esto se debe a que la pared del recipiente debe ser debe ser lo más fina posible, tanto para ahorrar material como para que sea ligera. La pared más delgada, según la ecuación (6.42), es la que tiene el mayor límite elástico, σ<sub> f </sub>. Por lo tanto, también queremos maximizar

  $\ M_{4} = \sigma_{f} $
    
reducir aún más la elección del material

### La selección. 
    
Estos criterios de selección se exploran utilizando el gráfico que se muestra en la figura 6.20: la tenacidad a la fractura, K<sub> 1C </sub>, representada gráficamente frente al límite elástico σ<sub> f </sub>. Los índices M <sub> 1 </sub>, M<sub> 2 </sub>, M<sub> 3 </sub> y M<sub> 4 </sub> aparecen como líneas de pendiente 0, 1, 1/2 y como líneas verticales. Tomemos como ejemplo el "límite elástico antes de la rotura". Una línea diagonal que corresponde a un valor constante de M<sub> 1 </sub> = K<sub> 1C </sub>/ σ<sub> f </sub> une materiales con igual rendimiento; los que están por encima de la línea son mejores. La línea que se muestra en la figura en M<sub> 1 </sub> = 0,6 m<sup> 1/2 </sup> (correspondiente a una zona de proceso de tamaño 100 mm) excluye los aceros más resistentes, el cobre, el aluminio y las aleaciones de titanio, aunque algunos polímeros casi lo consiguen. algunos polímeros casi lo consiguen (los envases de limonada y cerveza a presión están a presión). Una segunda línea de selección a M<sub> 3 </sub> = 50 MPa elimina las aleaciones de aluminio. Los detalles figuran en la tabla 6.20.
    
El criterio de fuga antes de rotura

  $\ M_{2} = \frac{K_{1C}^{2}}{\sigma_{f}} $
    
Favorece aceros de baja aleación, los aceros inoxidables y los aceros al carbono, pero no cambia mucho las conclusiones.

<div align="center">
  <br><img src=https://github.com/dadfinem/EMSE/blob/main/CasosEstudio/RecipientesPresion/Imagenes/CartaSeleccion.JPG width=75%"></br>
</div>

<div align="center">
  <sub>
      Figura 6.20: Materiales para recipientes a presión. El acero, las aleaciones de cobre y las aleaciones de aluminio cumplen mejor el criterio de criterio de "límite elástico antes de la rotura". Además, un alto límite elástico permite una alta presión de trabajo. Los materiales del triángulo ''zonas de búsqueda'' son la mejor elección. El criterio ''fuga antes de rotura'' conduce esencialmente a la misma selección.
  </sub>
</div>



<div align="center">
  <sup>
      Tabla 6.20: Materiales para recipientes a presión seguros
  </sup>
</div>

| Material | M<sub> 1 </sub> = K<sub> 1C </sub>/ σ<sub> f (m<sub> 1/2 </sub>) | M<sub> 3 </sub> = σ<sub> f (MPa) | Comentario |
| ------------- | ------------- | ------------- | ------------- |
| Acero inoxidable  | 0.35  | 300 | Los recipientes a presión nucleares están fabricados con acero inoxidable de grado 316 |
| Aceros de baja aleación  | 0.2  | 800 | Son estándar en esta aplicación |
| Cobre  | 0.5  | 200 | El cobre duro se utiliza para pequeñas calderas y recipientes a presión |
| Aleaciones de aluminio  | 0.15 | 200 | Los tanques de presión de los cohetes son de aluminio |
| Aleaciones de titaneo  | 0.13 | 800 | Bueno para recipientes a presión ligeros, pero costoso |  

### Posdata

Los grandes recipientes a presión son siempre de acero. Los destinados a maquetas -una maqueta de máquina de vapor, por ejemplo- son de cobre. Se elige, aunque sea más caro, por su mayor resistencia a la corrosión. Los índices de corrosión no varían con el tamaño. La pérdida de 0,1 mm por corrosión no es grave en un recipiente a presión de 10 mm de espesor. La pérdida de 0,1 mm por corrosión no es grave en un recipiente a presión de 10 mm de grosor, pero si el grosor es de sólo 1 mm se convierte en un problema.
  
Las averías en las calderas solían ser habituales, incluso hay canciones sobre ello. Ahora son raras, aunque cuando los márgenes de seguridad se reducen al mínimo (cohetes, nuevos diseños de aviones) los recipientes a presión siguen fallando de vez en cuando. Este éxito (relativo) es una de las principales aportaciones de la mecánica de la fractura a la práctica de la ingeniería.

[^1]: M. F. Ashby, Materials selection in mechanical design, 3a ed. Amsterdam: Elsevier Butterworth-Heinemann, 2005.

##
  <div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src=https://github.com/dadfinem/EMSE/blob/main/Imagenes/Logo_Escuela.png alt="Support by" width="25%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Escuela Colombiana de Ingeniería - Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>
