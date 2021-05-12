> _La criptografía es una herramienta importante para la gestión segura de tokens en una red de actores anónimos y no confiables. Permite transparencia en las interacciones manteniendo a la vez la privacidad de todos los actores de la red. La criptografía  se usa para  identificar de manera confiable a todos los actores de la red  y también es una parte integral del protocolo de consenso en una red de blockchain._

La criptografía es la práctica y el estudio de comunicaciones seguras ante la presencia de terceros.   La finalidad es crear un sistema de información que sea resiliente contra la manipulación, las  escuchas y otras formas de ataque. Mientras que la historia de la criptología se remonta a la aparición de textos escritos, evolucionó significativamente durante la era de las computadoras. La criptografía es un subcampo de la criptología y se refiere principalmente al proceso de encriptación, en el cual una pieza de información (texto puro) se convierte en texto ininteligible (texto cifrado). Un texto cifrado es ilegible sin su correspondiente cifrado para desencriptarlo.

Los cifrados fueron una de las primeras técnicas de encriptación desarrolladas para encriptar texto puro, sea a través de cifrados de sustitución (donde unidades del texto puro son reemplazadas por letras, pares de letras o tripletes de letras) o cifrados de transposición (donde las unidades del texto puro son re-acomodadas en un modo diferente y generalmente complejo). La desencriptación es el proceso inverso de convertir un texto cifrado ilegible en su texto puro original. Un cifrado es, por ello, un par de algoritmos que crea la encriptación y su desencriptación inversa: está diseñado de un modo tal que hace fácil encriptar el mensaje, pero muy difícil desencriptarlo si no conoces el código. 

Históricamente, la criptografía ha sido usada en varias formas, como texto cifrado tallado en piedras en Egipto. Otras formas de cifrado se remontan a la Persia Sasánida, la Antigua Grecia, el Imperio Romano, India, etc.  Desde el desarrollo de la máquina enigma (una máquina de cifrado a rotor) en la Primera Guerra Mundial, y la aparición de las computadoras en la Segunda Guerra Mundial, las aplicaciones criptográficas y sus métodos han evolucionado de manera radical. Los cifrados clásicos se volvieron inútiles porque eran muy fáciles de decodificar con simples “ataques de fuerza bruta”, donde un algoritmo de computación intenta todas las combinaciones posibles hasta que acierta el código adecuado. Las computadoras no sólo potenciaron las posibilidades de criptoanálisis, que refiere al proceso de romper encriptados, sino que también hicieron posible formas de cifrado más complejas. Los modernos algoritmos criptográficos están diseñados para que sea improbable romperlos en términos de tiempo y dinero aplicando la fuerza bruta. Sin embargo, tales “asunciones de robustez computacional” tienen que considerar el contínuo incremento en el poder de cómputo de las computadoras. 

Es más, las computadoras introdujeron nuevas formas de encriptación de todo tipo de información digital, y no sólo de partes de texto. Con el surgimiento de la computación cuántica, muchos investigadores están estudiando la relación entre los problemas de criptografía y la física cuántica. La criptografía post-quantum está siendo desarrollada por ciertos investigadores y desarrolladores quienes ya han comenzado a tener en cuenta los efectos potenciales de la computación cuántica a la hora de diseñar algoritmos. En la era de la información, el uso de la criptografía genera muchas cuestiones legales. Algunos gobiernos limitan o prohíben el uso de criptografía, y en algunos casos, la clasifican como un arma. Ciertas jurisdicciones pueden permitir que autoridades gubernamentales puedan obligar a divulgar llaves de encriptación de documentos que pueden ser relevantes para una investigación. Adicionalmente, la criptografía puede ser un factor interesante a la hora de discutir derechos humanos en la era digital.  La cuestión de cómo garantizar la privacidad en la era de las máquinas lentamente se vuelve una discusión impulsada por el público más general, y probablemente se volverá dominante en los próximos años. La pregunta crucial, en este contexto, es cómo y en qué circunstancias el derecho constitucional a la privacidad de las comunicaciones, o la inviolabilidad del hogar, se corresponden con el derecho a tener comunicaciones encriptadas o a encriptar registros de datos (leer más: Parte 3 - Tokens de Privacidad).

Los primeros intentos de encriptar comunicaciones electrónicas se concentraron en proveer secreto y preservar tecnologías para comunicaciones de instituciones gubernamentales, pero el campo se ha expandido. En las últimas décadas, las tecnologías de encriptación han sido aplicadas en varios otros dominios, tales como el comercio electrónico, los pagos digitales, la gestión de derechos digitales, la gestión de contraseñas, corroboración de integridad de mensajería, autenticación de identidad, firmas electrónicas, pruebas interactivas, y computación segura. En el contexto de las redes de blockchain y de otros registros distribuidos, la criptografía es utilizada para identificación, verificación y para seguridad a nivel del protocolo central. Tres bases fundacionales relevantes de la criptografía son utilizadas en el contexto de redes públicas de blockchain y otras tecnologías de la Web3: (i) función de hash, (ii) criptografía simétrica, y (ii) criptografía asimétrica (criptografía de llave pública). 

<span style="text-decoration:underline;">Las Funciones de Hash</span> son algoritmos matemáticos que convierten cualquier tipo de dato de cualquier tamaño (mensaje) en datos de un tamaño fijo (valor del hash o hash). La única forma de recrear los datos originales (mensaje) desde el hash es intentando todas las variaciones posibles para ver cuál coincide. Si bien esto es posible, insume tiempo y por ende es costoso, y es por lo que se lo llama función unidireccional.  Las funciones de hash pueden ser usadas para asegurar la integridad de los datos enviados y la privacidad. Las aplicaciones seleccionadas son firmas digitales, servicios de autenticación, huellas digitales, detección de duplicados, identificación única de archivos, o la creación de checks para detectar manipulación de datos. Para ser considerado resiliente, las funciones de hash criptográficas deben tener ciertas propiedades: deben ser diseñadas de modo tal que: (i) sean fáciles de computar, (ii) determinística, significando que el mismo mensaje siempre resultará en el mismo hash, (iii) debe  insumir tiempo y ser caro poder generar el mensaje desde su valor hash con pura fuerza  bruta, (iv) pequeños cambios al dato original debieran cambiar el valor del hash. Además, debiera ser (v) improbable encontrar dos mensajes diferentes (input) que produzcan el mismo valor de hash (output).

<span style="text-decoration:underline;">Sistemas simétricos</span>: Antes de la aparición de la criptografía de llave pública, dos  partes dependían de una llave de encriptación que debían intercambiar de manera no criptográfica, a través de reuniones secretas, sobres cerrados, o un correo confiable. Si te querías comunicar privadamente con alguien, necesitabas reunirte físicamente y acordar una llave secreta. En el mundo de las comunicaciones modernas, donde uno necesita coordinar en una red de muchos actores no confiables (la Internet), tales métodos no eran posibles. Por esto la encriptación simétrica no es usada para comunicaciones en redes públicas. Sin embargo, es más rápida y eficiente que la encriptación asimétrica, y por ello es usada para encriptar grandes cantidades de datos, ciertas aplicaciones de pago, o generación aleatoria de números. 

<span style="text-decoration:underline;">Los sistemas asimétricos</span>, también llamados criptografía de llave pública, resolvió el problema de coordinación creando dos llaves, una pública y una privada. La llave privada sólo es conocida por el dueño y debe ser  mantenida privada, mientras que la llave pública puede ser compartida con cualquiera. La llave pública puede ser transmitida a la red,  lo que permite a cualquiera de la red usar la llave pública para enviar un mensaje al “dueño” de la llave pública. El mensaje encriptado sólo puede ser desencriptado con la llave privada del destinatario. Los remitentes pueden pueden combinar un mensaje con su llave privada para crear una firma digital en el mensaje. Ahora, cualquiera puede verificar con la correspondiente llave pública si la firma es válida. Cómo se generan las llavees dependerá del algoritmo criptográfico utilizado. Ejemplos de sistemas asimétricos incluyen RSA (Rivest-Shamir-Adleman) y ECC (Elliptic-Curve Cryptography), que es también usada en Bitcoin. El uso de encriptación asimétrica potenció la seguridad de las comunicaciones en redes no confiables, como Internet, de una manera escalable. Los siguientes capítulos se enfocarán en cómo la criptografía es usada en la red de Bitcoin y en otras redes similares de blockchain. 

La red de Bitcoin principalmente usa hashes en combinación con firmas digitales para proteger la integridad de los datos que fluyen a través de la red usando criptografía de llave pública. Los hashes además son usados en el contexto del protocolo de consenso “Prueba-de-Trabajo”. Bitcoin usa la criptografía de llave pública, y más específicamente, la criptografía de curva elíptica. Por favor tener en cuenta que otras redes alternativas de blockchain y otros sistemas de registro distribuido pueden usar herramientas  de criptografía alternativas a las descriptas abajo. Algunas redes de blockchain, por ejemplo, usan criptografía que preserva más la privacidad, como el caso de “[Zcash](https://z.cash/)” (zero-knowledge proofs)[^2] y “[Monero](https://getmonero.org/)” (firmas anillo)[^3]. La misma comunidad de Bitcoin está actualmente buscando formas alternativas de firma criptográfica que resguarden más la privacidad y sean más escalables, como por ejemplo, con “Mimblewimble” (leer más: Parte 3: Tokens de Privacidad).

***
![Symmetric Cryptography vs. Assymmetric Cryptography](https://github.com/sherminvo/TokenEconomyBook/blob/main/imgs/06_Symmetric_Assymmetric_Cryptography.png)
***

## Criptografía de Llave Pública

La red de Bitcoin usa criptografía de llave pública para crear una referencia digital segura sobre la identidad de un usuario con un par de llaves criptográficas: una llave privada y una llave pública. Las referencias digitales seguras sobre quién es quién, y quién posee qué, son la base de las transacciones P2P. Al combinarse con una transacción, estas llaves pueden crear una firma digital que prueba el dominio de los tokens que uno tiene y permite controlar los tokens con un software billetera. De manera similar a librar un cheque a mano, y con contraseñas que autentican en la banca en Internet, la criptografía de llave pública es usada para autenticar y firmar transacciones de Bitcoin.

La llave pública es matemáticamente generada desde la llave privada. Si bien es muy fácil computar la llave pública desde la llave privada, la operación inversa sólo es posible con mucha fuerza bruta, adivinar la llave es posible pero prohibitivamente caro. Sería necesario utilizar la supercomputadora  más poderosa del mundo durante trillones de años para romper la clave, algo prácticamente imposible. Esto significa que, aún cuando la llave pública de uno es conocida por todos, nadie puede derivar la llave privada desde ella. Un mensaje que está encriptado con la llave pública puede viajar de manera segura al dueño de la llave privada, y solo el dueño de esta llave privada puede desencriptar el mensaje. Este método también funciona a la inversa. Cualquier mensaje con la llave privada puede ser verificado con la correspondiente llave pública.

Un ejemplo analógico de una llave pública sería el ejemplo  de un candado. Si Juan quiere enviar un mensaje a María, pero tiene miedo de que alguien lo intercepte y lo lea, le pedirá a María que le envíe su candado (abierto), y que se quede con la llave del candado. Juan puede ahora guardar su carta en una pequeña caja y cerrarla con el candado que María le envío. La carta ahora puede ser enviada por el mundo sin ser interceptada por personas no autorizadas. Solo María, que tiene la llave de su candado, puede abrir la carta. Por supuesto, alguien podría intentar romper la caja con pura fuerza bruta, en lugar de usando la llave. Si bien es posible, la dificultad dependerá de la resiliencia de la caja y de la fuerza del candado. Los mismos principios básicos aplican a la criptografía moderna. 

## Algoritmos Seguros

La pregunta crucial en la criptografía de llave pública gira en torno a asunciones de robustez computacional: ¿Cómo puede uno ampliar los esfuerzos computacionales entre derivar la llave privada de la llave pública, comparado a derivar la llave pública de la llave privada?¿Cuán difícil es romper el encriptado adivinando el resultado, cuánto tiempo llevaría adivinar la llave privada, y cuán costoso sería? La llave privada está representada por un número, lo que significa que mientras más largo el número, más difícil es adivinar ese número (aleatorio) por parte de alguien que no conoce el número. Si llevaría un par de décadas adivinar el número aleatorio, el número es considerado seguro. Sin embargo, todo algoritmo criptográfico es vulnerable a ataques por fuerza bruta, que significa adivinar la llave privada de uno intentando todas las combinaciones posibles hasta encontrar la solución. A medida que las computadoras se vuelven más rápidas y más eficientes, uno deberá inventar algoritmos más sofisticados, sea usando más números o inventando algoritmos más resilientes. 

Para asegurarse que un número es difícil de adivinar, una llave privada resiliente tiene unos requisitos mínimos: necesita ser (i) un número generado aleatoriamente. Necesita ser (ii) un número muy largo. Necesita (iii) usar un algoritmo seguro para generar las llaves. La aleatoriedad es importante, dado que no queremos que una persona o una máquina use la misma llave, y los humanos no son buenos para crear aleatoriedades. Llaves de gran tamaño permiten mayor distribución de aleatoriedad, y son más difíciles de romper con fuerza bruta, pero son más lentas de computar. Debido a su complejidad, los algoritmos seguros necesitan estar científicamente demostrados y ser testeados contra intrusiones. Uno debería evitar inventar su propio algoritmo. Este tema se volvió obvio cuando el equipo de desarrollo de la red IOTA decidió implementar su propia función de hash, llamada Curl. IOTA es una solución de registro distribuido alternativo a blockchain, que afirma haber resuelto el problema de escalabilidad de Bitcoin con un mecanismo alternativo de consenso y criptografía alternativa. Tiempo después,  se descubrió que su función auto-generada Curl no era “resistente a colisiones”[^4]. Desde la aparición de Bitcoin, los algoritmos criptográficos usados en la red de Bitcoin han resistido todos los intentos de manipulación de datos. 

Sin la criptografía, no podría haber consenso distribuido en una red de actores que no se conocen o no se confían mutuamente. A medida que las computadoras se vuelven más poderosas y pueden adivinar números más rápidamente, los algoritmos usados deberán resistir y rápidamente evolucionar hacia estándares tecnológicos para mantener los niveles actuales de seguridad. Muchos investigadores y desarrolladores afirman que las supercomputadoras, en particular las computadoras cuánticas, pronto podrán romper los algoritmos más convencionales a través de la fuerza bruta. Esto no es del todo cierto y depende del algoritmo criptográfico. Mientras que las computadoras cuánticas no son significativamente mejores para romper hashes, si son muy poderosas en lo relacionado a curvas elípticas y factorización prima. Las respuestas son complejas y aún no están del todo resueltas. Los algoritmos criptográficos resistentes a las computadoras cuánticas son, por tanto, un área crítica de investigación. Para más detalles sobre este tópico, ver referencias al final de este capítulo. 

## Hasheo

El hasheo es un método para transformar grandes cantidades de datos en números cortos que son difíciles de adivinar. Uno puede convertir un texto o una imagen, que representa una secuencia de bits de longitud variable, para producir una secuencia de bits de longitud fija en la forma de un hash. Estas funciones aseguran la integridad de los datos. La red de Bitcoin usa Algoritmos de Hasheo Seguro (SHA), como el SHA-256. Una propiedad importante de los hashes es que si un solo bit de la entrada es modificado, la salida cambia significativamente, lo que hace fácil detectar pequeños cambios en grandes archivos de texto, por ejemplo. Como se puede ver en el ejemplo abajo[^5], se genera un hash completamente nuevo cuando se cambia sólo un símbolo. Esto se debe al “efecto avalancha”, y es útil para fácilmente corroborar la integridad de los datos.  Una tira totalmente diferente resulta de hashear el hash.


> **Hash de la oración “**Cómo comprar Bitcoin?**”: \
 156aedcfab1d49f73abddd89faf78d9930e4b523ab804026310c973bfa707d37 \

> **Hash de la oración “**Cómo comprar Bitcoin”**: \
 4314d903f04e90e4a5057685243c903fbcfa4f8ec75ec797e1780ed5c891b1bf \

> **Hashear el hash** produce: \
 4c9622e1148ff0b855de50e62999d194039eb2faa9e715cc9d9ef604015aa1fe \


El efecto avalancha describe el comportamiento de una función matemática cuando un pequeño cambio en una entrada debiera causar que el valor resultante del hash cambie drásticamente. Esto significa que si uno agrega solo una palabra, o solo una coma, a un documento de varios cientos de páginas, el hash del documento cambiará. El valor del hash del documento, por ende, sirve como un gemelo criptográfico del documento, que es la razón por la cual se los llama “huellas digitales”. Como consecuencia, uno no necesita encriptar el documento entero con la llave privada del remitente, dado que esto consume tiempo, ancho de banda y dinero. En cambio, uno puede computar el valor hash del documento.

El hashing en la red de Bitcoin es parte del siguiente proceso: (i) codificación de direcciones de billeteras; (ii) codificación de transacciones entre billeteras; (iii) verificando y validando los balances de cuentas de las billeteras; y para el mecanismo de consenso (iv) Prueba-de-Trabajo.

***
![Generation of keys and adresses](https://github.com/sherminvo/TokenEconomyBook/blob/main/imgs/04_GenerationKeysAdresses_alt.png)
***

## Billeteras & Firmas Digitales

Una billetera de blockchain es una pieza de software que almacena tus llaves privadas, llave pública, y dirección de blockchain, y que se comunica con la red de blockchain. Este software billetera puede correr en una computadora o en un teléfono móvil (como [ “Bitcoin Core](https://bitcoin.org/de/download)”,[ “Electrum](https://electrum.org/#home)”) o en un dispositivo de hardware dedicado (como[ “Trezor](https://trezor.io)” y[ “Ledger](https://www.ledger.com)”). El software billetera permite autenticar al usuario y gestionar los tokens. Con un software billetera uno puede enviar tokens y verificar la recepción de tokens que nos fueron enviados. Cada vez que envías tokens de Bitcoin, necesitas usar una billetera para firmar la transacción con tu llave privada. Seguidamente, tu balance personal de tokens es ajustado en todas las copias del registro, que está distribuido en una red de computadoras P2P.

Cuando se la inicia por primera vez, una billetera de Bitcoin genera un par de llaves consistentes en una llave privada y una llave pública. En un primer paso, la llave privada es un número entero de 256 bits generado aleatoriamente. La llave pública es luego matemáticamente derivada de la llave privada, usando criptografía de llave elíptica.  En un segundo paso, la dirección de blockchain es derivada de la llave pública, usando una función criptográfica distinta a la utilizada para derivar la llave pública, agregando metadatos como checksums y prefijos. Usar una función criptográfica distinta para derivar la dirección le agrega un nivel adicional de seguridad: si se rompe el primer nivel de seguridad, criptografía de llave elíptica, entonces quien tenga la llave pública podría descifrar la llave privada. Esto es importante, dado que la criptografía de llave elíptica es especialmente vulnerable a ser rota si las computadoras cuánticas se vuelven una realidad, mientras que el hashing, que es usado en el segundo nivel de seguridad para derivar la dirección, no es tan vulnerable a un ataque de fuerza bruta con computadoras cuánticas. Esto significa que si alguien tiene la dirección de blockchain, y pudo romper la criptografía  de llave elíptica, esa persona aún debería atravesar el segundo nivel de seguridad que fue usado para derivar la dirección de la llave pública. Esto es similar a por qué te da más seguridad usar doble candado para asegurar tu bicicleta en la calle, con dos candados diferentes que tienen distintos mecanismos de seguridad (llave o clave). Como resultado de esto, la dirección actúa como una huella digital de la llave pública pero no da ninguna información acerca de la llave pública de una persona (a menos que envíen la primera transacción). Las direcciones de blockchain cumplen una función similar al número de cuenta bancaria en el contexto de transacciones financieras tradicionales, o a un correo electrónico cuando gente quiere enviarte un correo electrónico.

Las firmas digitales en la red de Bitcoin y redes de blockchain similares se realizan usando un software billetera. Al igual que una firma manuscrita, una firma digital se usa para verificar que tú eres quien dices ser. Cuando se las implementa de manera adecuada, son más difíciles de falsificar que una firma manuscrita. Las firmas digitales se han usado por décadas, principalmente en el contexto de transacciones financieras, licencias de software, o software de gestión de contratos. En una red de blockchain, las firmas digitales se usan para la autentificación (como prueba de que quien envía tokens es, en los hechos, quien lo envía) y para integridad de la transacción (i.e. la cantidad de tokens enviados). La llave privada es usada para firmar transacciones de tokens. La llave pública es usada para los nodos validadores de la red para verificar la firma. De este modo, una billetera no puede pretender ser otra billetera. Esto es denominado “no-repudiación”. Hablando prácticamente, esto significa que otra persona no puede pretender controlar tu billetera, salvo que tenga tu llave privada.


### Tipos de Billeteras y Gestión de Llaves

Tu llave privada siempre debe ser mantenida secreta y no debiera ser compartida con otras personas a menos que quieras darles deliberadamente acceso a  tus tokens. Debido al proceso de dos pasos para derivar la llave pública desde la llave privada y la dirección desde la llave pública, uno sólo necesita tener resguardos de la llave privada; todo lo demás puede ser derivado de la llave privada con el algoritmo criptográfico usado en la red. Si pierdes acceso a tu billetera, sin tener de resguardo una frase semilla [^6] para recuperar el acceso, o tu clave privada, perderás acceso a tus tokens. Mientras tus tokens seguirán existiendo en la red, no podrás acceder a ellos. 

Contrario a la creencia popular, una  billetera de blockchain no almacena ningún token. Solo almacena el par de llaves pública y privada asociadas a tu dirección en blockchain.  También lleva un registro de todas las transacciones en las que la llave pública de la billetera estuvo involucrada, junto con otros datos. De allí que el término “billetera” sea equívoco. La palabra “llavero” sería más apropiada, ya que actúa como un depósito seguro de llaves, y como una herramienta de comunicación con la red de blockchain. Una billetera de blockchain tiene más similitudes con un llavero que tiene las llaves de tu casa. Si pierdes las llaves de tu departamento, el departamento sigue siendo tuyo, pero no puedes acceder hasta tanto recuperes las llaves; quizás tengas una llave de repuesto que le dejaste a un vecino, amigo o a un familiar, o consigues un cerrajero que te ayude a entrar a tu propia casa. Romper tu cerradora sería equivalente a un ataque por fuerza bruta para adivinar tu llave privada. Hay dos tipos de billeteras, billeteras con custodia y billeteras sin custodia:

<span style="text-decoration:underline;">Las billeteras controladas por el usuario</span> ofrecen control personal sobre los tokens que uno tiene. Las llaves privadas están bajo la custodia y responsabilidad exclusiva de los usuarios y las transacciones se firman directamente desde los dispositivos de los usuarios. Con las billeteras controladas por el usuario, sin embargo, el usuario se convierte en el único punto de falla en el caso de robo o pérdida de sus llaves.

<span style="text-decoration:underline;">Las billeteras alojadas</span> son servicios de custodia, ofrecidos por los servicios de casas de cambio  online, donde el proveedor del servicio gestiona la billetera de uno en sus servidores. En la mayoría de los casos, las llaves privadas de la billetera de uno también son gestionadas por estos intermediarios. El software billetera replica la llave privada del usuario de modo tal que un tercero puede realizar transacciones en nombre del usuario. Mucha gente prefiere, por ello, almacenar sus tokens en una casa de cambio online y delegar la responsabilidad por la gestión de llaves en estas instituciones confiables. Al igual que con los bancos hoy por hoy, estas casas de cambio de tokens actúan como custodios de nuestros fondos (leer más: Parte 3 - Casas de cambio de Tokens).

Una solución más autónoma al problema de perder tus llaves privadas podrían ser las  llamadas “soluciones sociales de recuperación de llaves”, donde designas a un conjunto de amigos, familiares o instituciones de confianza para que confirmen tu identidad y permitan recuperar la llave en un proceso multi-firma. En tal configuración, podrías por ejemplo designar a cinco personas de confianza a quienes se contactará en caso que pierdas tu llave privada. Tres de cinco pueden ser designados para firmar con sus llaves privadas para que vos puedas recuperar  tu llave privada. De este modo, afinás en quién confiás, sin convertirte en el único punto de falla. Sin embargo, si esas personas se conocen entre sí, podrían coludir o ser sobornados para coludir en contra tuya. Para permitir una verdadera economía del token P2P, donde las personas puedan enviar y recibir tokens de billetera a billetera, sin tener que confiar en terceros, necesitaremos mejores soluciones de gestión de billeteras, donde el individuo es el soberano de sus tokens, manteniendo altos niveles de seguridad y usabilidad. Una solución menos sofisticada para recuperar tus llaves sería automáticamente crear un backup en un servicio en la nube como Google Drive. Si bien esto no es para nada recomendable, por razones de conveniencia, parece haberse convertido en la tendencia con algunas casas de cambio de tokens, como “[Coinbase](https://www.coinbase.com/)”.

Al momento de escribir este libro, la mayoría de las billeteras sólo permiten la gestión de un solo tipo de token, y en algunos casos, con una cantidad limitada de tokens.  Esto se debe al hecho de que los diferentes sistemas de registro distribuido no son, en su mayoría, interoperables. La mayoría de los sistemas de tokens tienen diferentes especificaciones técnicas, que dependen del tipo de registro distribuido en el cual se los emitió, y por ello requieren desarrollos de billeteras individualizados.  Las billeteras que son compatibles con múltiples registros consumen tiempo y son caras de desarrollar. La compatibilidad multi-registro también ensancha el software billetera. Otro aspecto del diseño de billeteras es si la billetera (en combinación con  el registro distribuido subyacente) permite firma múltiple de transacciones. Muchas redes de blockchain, como Ethereum, no permiten transacciones nativas multi-firma. En el caso de Ethereum, necesitás resolver esto a través de un contrato inteligente, que ha estado sujeto a problemas de seguridad.

Las firmas anillo, firmas colectivas, y “Shamir’s Secret Sharing” [^7] son todos ejemplos de algoritmos criptográficos alternativos que necesitan ser habilitados por las redes de blockchain y soportados por los softwares billeteras para permitir firmas conjuntas de transacciones. Las firmas conjuntas son un atributo importante que permite transferir la custodia de tus tokens a alguien más (un banco o una casa de cambio gestiona tus tokens), la gestión colectiva de activos (en casos de condominio sobre el mismo activo, o gestión colectiva como en el caso de una DAO) o la recuperación social de llaves. Los capítulos 3 y 4 de este libro se adentrarán profundamente en aspectos de gestión de tokens y casos de uso de tokens, en los cuales el rol de las billeteras se volverá más tangible. 

***
![DigitalSignatures BlockchainWallets](https://github.com/sherminvo/TokenEconomyBook/blob/main/imgs/03_DigitalSignatures_BlockchainWallets.png)
***
## Enviando Tokens

Si Alicia quiere enviar tokens de Bitcoin a Roberto, ella usará un software billetera para autentificarse, especificar la cantidad que quiere transferir e indicar la dirección de Roberto. Su billetera transmite la transacción a todas las computadoras de la red. Cada computadora en la red puede ahora chequear que la transacción es válida, según las reglas de la red. Los pasos son los siguientes:

* Alicia usa un software billetera para gestionar sus llaves privadas. Al realizar operaciones matemáticas estándar, el software billetera puede siempre derivar su llave pública y su dirección desde la llave privada.

* Si Alicia quiere enviar tokens a Roberto, ella usará su software billetera para crear  una transacción que incluye todos los detalles necesarios: su llave pública. Alicia necesita especificar la dirección de Roberto, y el número de tokens que quiere enviar. Alicia luego crea una firma digital para esta transacción, un hash (realizado por su software billetera).

* Para demostrar al resto de la red que ella es dueña de la dirección, y por ende de sus tokens, Alicia firma el hash con su llave privada (realizado automáticamente por su software billetera).

* Alicia ahora transmite su transacción a cualquier computadora de la red: ella envía tanto la transacción en texto plano como su hash firmado (realizado automáticamente por su software billetera).

* Cualquier computadora de red que reciba la transacción ahora puede verificar la validez de la transacción. Pueden usar la llave pública de Alice para matemáticamente verificar si el hash firmado fue efectivamente firmado por ella. Pueden usar las operaciones de hasheo en su transacción legible y recibirán el mismo valor de hash. También pueden usar la llave pública de Alice para verificar si el hash firmado fue efectivamente firmado por ella.

* Luego de verificados todos estos detalles, por consenso de todos los actores de la red, las transacciones validadas son almacenadas en un bloque y hasheadas. Este bloque se convierte en parte del registro actualizado si las otras computadoras de la red validan que el valor del hash en el bloque es válido. Este proceso de creación de nuevos bloques de transacciones está sujeto al mecanismo de consenso Prueba-de-Trabajo (leer más sobre Prueba-de-Trabajo en el próximo capítulo).

* Todos los nodos de la red modificarán su registro de manera acorde a la creación del próximo bloque, de modo tal que Bob ahora pasará a ser dueño de los fondos que Alicia le envío. Esta transacción se vuelve parte del estado universal de la red de Bitcoin y es resistente a manipulación. La información del registro puede ser alterada, pero a un costo prohibitivamente alto (leer más sobre cuánto cuesta en el próximo capítulo). 

### Resumen del Capítulo

> La criptografía es la práctica y estudio de comunicaciones seguras en presencia de terceros. El propósito es crear sistemas de información que sean resilientes contra escuchas, manipulación y otras formas de ataque.

> La criptografía en redes de blockchain permite la transparencia de las interacciones manteniendo, a la vez, la privacidad de todos los actores de la red.

> La criptografía de llave pública es usada para demostrar la identidad de uno con un par de llaves criptográficas: una llave privada y una llave pública, que al combinarse con una transacción crean una firma digital. Esta firma digital demuestra la propiedad de nuestros tokens y permite que los controlemos a través de una pieza de software llamada “billetera”.

> Al igual que las firmas manuscritas, las firmas digitales son usadas para verificar que uno es quien dice ser. En Bitcoin y otras blockchains, las firmas digitales son funciones matemáticas que referencian a una dirección específica de una billetera que gestiona nuestros tokens en una blockchain.

> Una función de hash es un algoritmo matemático que puede convertir cualquier clase de entrada, tales como una cadena, un archivo de texto o un archivo de imagen, en una salida en forma de cadena con una longitud fija llamada hash. Es una función unidireccional, lo que significa que la única forma de recrear la entrada original de datos (mensaje) desde el hash es intentando todas las variaciones posibles para ver si producen el mismo valor. Si bien esto es posible, consume tiempo y es por tanto costoso.


### Referencias del Capítulo & Lecturas Complementarias
_* Alonso, Kurt M.: “Zero to Monero: First Edition a technical guide to a private digital currency; for beginners, amateurs, and experts”, June 26, 2018 (v1.0.0): [https://www.getmonero.org/library/Zero-to-Monero-1-0-0.pdf](https://www.getmonero.org/library/Zero-to-Monero-1-0-0.pdf)_

_* Antonopoulos, Andreas M.: “Mastering Bitcoin: Programming the Open Blockchain”, O’Reilly, 2017_

_* Becket, B.: “Introduction to Cryptology”, Blackwell Scientific Publications, 1988_

_* Ben-Sasson, Eli;Chiesa, Alessandro; Garman, Christina; Green, Matthew; Miers, Ian; Tromer, Eran; Virza, Madars: „Zerocash: Decentralized Anonymous Payments from Bitcoin“ May 18, 2014 (extended version): [http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf](http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf)_

_* Ben-Sasson, Eli; Chiesa, Alessandro; Tromer, Eran; Virza, Madars: “Succinct Non-Interactive Zero Knowledge for a von Neumann Architecture”, February 5, 2019 (updated version): [https://eprint.iacr.org/2013/879.pdf](https://eprint.iacr.org/2013/879.pdf)_

_* Boyle, David: “The Little Money Book”, Alastair Sawday Publishing, 2003_

_* Buterin, Vitalik: “Bitcoin Is Not Quantum-Safe, And How We Can Fix It When Needed”: [https://bitcoinmagazine.com/articles/bitcoin-is-not-quantum-safe-and-how-we-can-fix-1375242150/](https://bitcoinmagazine.com/articles/bitcoin-is-not-quantum-safe-and-how-we-can-fix-1375242150/)_

_* Buterin, Vitalik: “Privacy on the Blockchain”, January 2016: [https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain/](https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain/)_

_* Castryck, Wouter: “ELLIPTIC CURVES ARE QUANTUM DEAD, LONG LIVE ELLIPTIC CURVES”, n COSIC Cryptography Blog, 31/05/2017: [https://www.esat.kuleuven.be/cosic/elliptic-curves-are-quantum-dead-long-live-elliptic-curves/](https://www.esat.kuleuven.be/cosic/elliptic-curves-are-quantum-dead-long-live-elliptic-curves/)_

_* Esslinger, Bernhard: “The CrypTool Script: Cryptography, Mathematics, and More”, 10th edition, distributed with CrypTool version 1.4.30: [https://web.archive.org/web/20110722183013/http://www.cryptool.org/download/CrypToolScript-en.pdf](https://web.archive.org/web/20110722183013/http://www.cryptool.org/download/CrypToolScript-en.pdf)_

_* Flannery, Sarah; Flannery, David: “In Code: A Mathematical Journey”, Workman Publishing Company, 2001_

_* Goldreich, Oded: “Foundations of Cryptography” Cambridge University Press, 2001_

_* Ito, Joi: “Our response to „A Cryptocurrency Without a Blockchain Has Been Built to Outperform Bitcoin“, Dec. 20, 2017: [https://www.media.mit.edu/posts/iota-response/](https://www.media.mit.edu/posts/iota-response/)_

_* Katz, Jonathan; Lindell, Yehuda: “Introduction to Modern Cryptography”, Chapman & Hall/CRC, Cryptography and Network Security Series, 2nd Edition, 2014_

_* Nakamoto, Satoshi: “Bitcoin: A Peer-to-Peer Electronic Cash System”, 2008: [https://bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)_

_* Narula, Neha: “Cryptographic vulnerabilities in IOTA”, September 7, 2017[ https://medium.com/@neha/cryptographic-vulnerabilities-in-iota-9a6a9ddc4367](https://medium.com/%2540neha/cryptographic-vulnerabilities-in-iota-9a6a9ddc4367)_

_* Narula, Neha:“IOTA Vulnerability Report: Cryptanalysis of the Curl Hash Function Enabling Practical Signature Forgery Attacks on the IOTA Cryptocurrency”, 7 September, 2017: [https://github.com/mit-dci/tangled-curl/blob/master/vuln-iota.md](https://github.com/mit-dci/tangled-curl/blob/master/vuln-iota.md)_

_* N.N.: “Bitcoin”, Github repository: [https://github.com/bitcoin](https://github.com/bitcoin)_

_* N.N.: “Bitcoin Core”, Github repository, [https://github.com/bitcoin/bitcoin](https://github.com/bitcoin/bitcoin)_

_* N.N.: “Bitcoin Core Integration”, Staging tree: [https://bitcoincore.org/en/download](https://bitcoincore.org/en/download)_

_* N.N.: “Mimblewimble Protocol”, Github Archives: [https://github.com/mimblewimble/grin/blob/master/doc/intro.md](https://github.com/mimblewimble/grin/blob/master/doc/intro.md)_

_* N.N.: Monero Research Lab, Technical Resources: [https://ww.getmonero.org/resources/research-lab/](https://ww.getmonero.org/resources/research-lab/)_

_* N.N.: “Post-Quantum Cryptography” Information Technology Laboratory, COMPUTER SECURITY RESOURCE CENTER: [https://csrc.nist.gov/projects/post-quantum-cryptography/round-1-submissions](https://csrc.nist.gov/projects/post-quantum-cryptography/round-1-submissions)_

_* Prasanna: “Litecoin To Implement Mimblewimble”, Altcoin News, February 8, 2019: [https://cryptoticker.io/en/litecoin-implement-mimblewimble/](https://cryptoticker.io/en/litecoin-implement-mimblewimble/)_

_* Rogaway, Phillip; Bellare, Mihir: “Introduction to Modern Cryptography”, May 11, 2005:[ http://web.cs.ucdavis.edu/~rogaway/classes/227/spring05/book/main.pdf](http://web.cs.ucdavis.edu/%257Erogaway/classes/227/spring05/book/main.pdf)_

_* Schär, Fabian; Berentsen, Aleksander: “Bitcoin, Blockchain und Kryptoassets: Eine umfassende Einführung”, Books on Demand, 2017_

_* Schor, Lukas: “On Zero-Knowledge Proofs in Blockchains”, Argon Group, March 2018:[ https://medium.com/@argongroup/on-zero-knowledge-proofs-in-blockchains-14c48cfd1dd1](https://medium.com/%2540argongroup/on-zero-knowledge-proofs-in-blockchains-14c48cfd1dd1)_

_* Stallings, William: “Cryptography and Network Security: Principles and Practice”, Prentice Hall, 6th ed., 2013_

_* Stolbikova, Veronika: „Can Elliptic Curve Cryptography be Trusted? A Brief Analysis of the Security of a Popular Cryptosystem“, ISACA Journal Volume 3, 2016 [https://www.isaca.org/Journal/archives/2016/volume-3/Pages/can-elliptic-curve-cryptoraphy-be-trusted.aspx](https://www.isaca.org/Journal/archives/2016/volume-3/Pages/can-elliptic-curve-cryptoraphy-be-trusted.aspx)_

_* Tibco, Nelson Petracek: “What zero-knowledge proofs will do for blockchain”, Venturebeat, Dec 16, 2017: [https://venturebeat.com/2017/12/16/what-zero-knowledge-proofs-will-do-for-blockchain/](https://venturebeat.com/2017/12/16/what-zero-knowledge-proofs-will-do-for-blockchain/)_

_* Wetzel, Tyler: “Understanding the Jargon of the Blockchain and Cryptocurrency World” Medium, Aug 23, 2018: [https://medium.com/@twwetzel76/understanding-the-jargon-of-the-blockchain-and-cryptocurrency-world-64b5f431bcd5](https://medium.com/@twwetzel76/understanding-the-jargon-of-the-blockchain-and-cryptocurrency-world-64b5f431bcd5)_

_* Wikipedia contributors, "Cryptography," Wikipedia, The Free Encyclopedia, [https://en.wikipedia.org/wiki/Cryptography](https://en.wikipedia.org/wiki/Cryptography) (accessed Jun 10, 2017)._

_* Wikipedia contributors, "Digital signature," Wikipedia, The Free Encyclopedia, [https://en.wikipedia.org/wiki/Digital_signature](https://en.wikipedia.org/wiki/Digital_signature) (accessed Jun 10, 2017)._

_* Wikipedia contributors, "Cryptographic hash function," Wikipedia, The Free Encyclopedia, [https://en.wikipedia.org/wiki/Cryptographic_hash_function](https://en.wikipedia.org/wiki/Cryptographic_hash_function) (accessed Jun 10, 2017)._

_* Young, Joseph: “Anonymous Cryptocurrencies: Why Edward Snowden Supports Zero-Knowledge Proofs”, January 2018: [https://journal.binarydistrict.com/anonymous-cryptocurrencies-why-edward-snowden-supports-zero-knowledge-proofs/](https://journal.binarydistrict.com/anonymous-cryptocurrencies-why-edward-snowden-supports-zero-knowledge-proofs/)_

_* Bitcoin Core: [https://bitcoin.org/de/download](https://bitcoin.org/de/download)_

_* Electrum: [https://electrum.org/](https://electrum.org/)_

_* Ledger: [https://www.ledger.com/](https://www.ledger.com/)_

_* Monero: [https://getmonero.org/](https://getmonero.org/)_

_* Mimblewimble: [https://github.com/mimblewimble/grin/blob/master/doc/intro.md](https://github.com/mimblewimble/grin/blob/master/doc/intro.md)_

_* Trezor: [https://trezor.io/](https://trezor.io/)_

_* Zcash: [https://z.cash/](https://z.cash/)_


### Footnotes

[^1]:
Mientras que  la criptografía de curva elíptica ofrece el mismo nivel de seguridad que RSA, necesita menos computación y un menor tamaño de llaves, lo que reduce los requerimientos de almacenamiento y transmisión. Por ello permite menores requisitos de almacenamiento y transmisión. 

[^2]: La criptografía de zero-prueba-de-conocimiento permite validar información sin revelar tal información al verificador de la información.

[^3]:
Las firmas anillo pueden usarse para ofuscar la identidad del dueño de los tokens, combinando un grupo de firmas digitales parciales de varias transacciones enviadas por diferentes usuarios, formando una única firma que se usa para firmar una transacción.

[^4]:
Las funciones de hashing toman una entrada de longitud arbitraria y entregan un valor que parece aleatorio pero tiene una longitud fija. Cuando más de una entrada produce el mismo valor, serios problemas pueden generarse por tal colisión. Un equipo de investigadores del MIT y de la Universidad de Boston descubrieron tal defecto en la función Curl de IOTA. Si bien el equipo IOTA arregló la vulnerabilidad, denunciaron que esta vulnerabilidad había sido introducida a propósito, lo que fue muy criticado por la comunidad open-source. 

[^5]:
Calcular valores de hashes aquí: [https://www.browserling.com/tools/all-hashes](https://www.browserling.com/tools/all-hashes)

[^6]: 
Una frase semilla, también llamada una  “semilla mnemotécnica”, es un método para vincular llaves privadas con una combinación de palabras fácil de recordar, que puede ser provista y gestionada por tu software billetera. La mnemotecnia es una técnica cartográfica que ayuda a reproducir algo que es difícil de recordar, con palabras aleatorias que son fáciles de recordar. 

[^7]: 
Shamir’s Secret Sharing es un algoritmo criptográfico que divide una (llave) secreta en partes, distribuyendo partes del secreto en diferentes personas. Para reconstruir el secreto, todas las partes deben agruparse. En la configuración del umbral, solo se requiere un cierto número de partes para reconstruir el secreto. 
