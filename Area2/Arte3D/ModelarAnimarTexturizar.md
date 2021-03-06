## Sub-área 2. Arte 3D ##

### Modelar, Animar, Texturizar: ###
**Conceptos notables:** 
  - **Referencia/Turn-around:** Una imagen, dibujo o fotografía que muestra de frente, ambos lados y de espalda al objeto, persona o personaje que se desea modelar.
  - **Topología:** El acamodo de los vértices en la malla (mesh) del modelo, entre más detalle tenga el modelo tiene más vértices y es más compleja la topología.
  - **Rigging:** Llamamos rigging al proceso por el que construimos un esqueleto con sus cadenas de huesos para que funcionen según nuestras necesidades. Al modelo se le colocan joints (articulaciones) que funcionan para el esqueleto. Éstas se mueven con la ayuda de controladores.
  - **FK Joint:** Joint con _forward kinematics (FK)_, Los Joints FK solo afectan a los joints que sean dependientes de ellos en una cadena
  - **IK Joint:** Joint con _inverse kinematics (IK)_, Los Joints IK afectan toda la cadena de joints si uno es alterado.
  - **Skinning:** Llamamos skinning al proceso por el cual se asigna el rigging a una malla (mesh).
  - **Modelar:** El modelar es crear un objeto tridimensional digitalmente.
  - **Animar:** La animación consiste en poner en la posición deseada al modelo, y crear keyframes. De igual manera que en la animación 2D, se siguen los principios y se puede trabajar en straight ahead o pose to pose, para crear los movimientos del modelo.
  - **Texturizar:** El proceso de texturizar consiste en la obtención del UV Mapping del modelo para poder crear el Texture Mapping. Se debe hacer también una prueba de escala con las UVs, usualmente se usa la textura de "checkers" para ver si los cuadros concuerdan, léase: partes pequeñas del modelo se deben de ver con cuadros pequeños. De no ser así, en el mapa de las UVs, esas partes se deben poner más chicas a comparación de las demás.
  - **Tris:** Cantidad de lados que tiene una cara o un poligono de un objeto.
  - **HighPolyModel:** Modelo de alta resolución, con cualquier cantidad de geometria.
  - **LowPolyModel:** Modelo de baja resolución, se utilizan generalmente para videojuegos ya que son más optimizados.
  - **Normal Map:** Mapa de textura para proyectar disfrazar detalle de HP _(HP = HighPoly)_ cuando esta mapeado en LP _(LP= LowPoly)_.
  - **Diffuse Map:** Mapa de color
  - **Specular Map:** Mapa de textura que Controla la intensidad de color de los brillos o highlights para luces en tiempo real
  - **Glow Map:** Brillo o iluminación dependiendo del objeto. 
  - **Ambient Oclusion Map:** Mapa resultante del proceso de calcular las sombras que se proyectan múltiples objetos entre sí.
  - **Blending:** Combinar, mezclar colores 
  - **Render Passes:** Son contenedores para los valores de los canales, los cuales ayudan a controlar cada aspecto de la escena.
    - **Diffuse:** también conocido como beauty pass o color pass, es el pase principal, es todo el color de nuestro objeto, incluye iluminación difusa, color y mapas de color.
    - **Shadow:** contiene las sombras de nuestro objeto o escena. Las sombras proyectadas son las que nuestro objeto proyecta sobre otro objeto 3D. Las sombras adjuntas son las que están proyectadas sobre el mismo objeto.
    - **Ambient Occlusion:** Se refiere al bloqueo de la luz indirecta o difusa sobre un objeto. Se refiere a las áreas más oscuras del objeto, comúnmente pliegues, grietas y hendiduras. La oclusión ambiental es ocasionada por la inhabilidad de la luz indirecta para rebotar alrededor e iluminar áreas que están bloqueadas por un objeto cercano que absorbe los rayos de luz.
    - **Specular:** También conocido como highlight pass, aísla los reflejos especulares de los objetos. El resultado es un render de todos los reflejos especulares en la escena sobre un fondo negro, sin ningún otro tipo de sombreado.
    - **Reflection:** La reflexión se produce cuando la luz rebota en un objeto. Este pase puede complementar al specular.
    - **Depth:** Este pase almacena la información de la profundidad en cada punto de la escena.


