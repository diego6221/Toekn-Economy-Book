
> Las redes de blockchain y registros distribuidos similares usan criptografía de llave pública para identificar a todos los actores de la red. Estos sistemas de identidad, sin embargo, son insuficientes para la gama de posibles aplicaciones de Web3. Identificadores descentralizados (DIDs) combinados con registros distribuidos pueden proveer soluciones de  identidad “centrada en el usuario” que son adecuadas para la Web3, permitiendo una mayor privacidad y control sobre los activos digitales de uno y dejar una huella digital, que las soluciones usadas en la Web2 “centradas en el servidor”

Deslinde: La intención de este capítulo es dar una visión general, y llevar luz a  la importancia y a la urgencia de soluciones adecuadas de identidad digital como base fundacional de la Web3. sin embargo, el tópico de la identidad digital es mucho más complejo que lo tratado en este capítulo, y no puede ser desarrollado en detalle, ya que ello excede el alcance de este libro. 

La gestión de la identidad refiere al proceso en virtud del cual organizaciones, individuos y objetos pueden ser identificados de manera confiable, autenticados y certificados. Los servicios de identidad confiables son la base de la gestión de derechos de acceso en la Internet y un pre-requisito necesario para  muchas actividades socioeconómicas en general - offline y online. Los casos de uso relacionados a la identidad pueden encontrarse en gobiernos (partidas de nacimiento, tarjetas de identidad, pasaportes, o licencias de conducir), educación (certificados y licencias), salud (registros de datos personales de salud), comercio electrónico, banca o finanzas (clientes, B2B y datos de empleados). En la Internet de las Cosas, un número creciente de objetos que están conectados a Internet también necesitan un sistema adecuado de identificación (tales como los números de serie). Desde una perspectiva de ciencia de la computación, el término “identidad” puede reducirse a los elementos de datos relacionados al proceso de gestión de identidad: “identificador”, “autenticación” y “credenciales”.

<span style="text-decoration:underline;">Los identificadores</span> son necesarios para identificar de manera unívoca a una persona, institución u objeto. Un número de teléfono o una dirección de correo electrónico es unívoco por naturaleza y calificaría como un identificador. El nombre de una persona no necesariamente es unívoco, y no siempre calificará como un identificador. Por otro lado, mientras el domicilio legal y el número de teléfono de una persona son únicos por naturaleza, pueden cambiar con el tiempo. Idealmente, un identificador debe ser unívoco y persistente en el tiempo. Un número de seguridad social, un número de pasaporte, o el número de una licencia de conducir pueden ser un identificador unívoco para una persona, si no cambian en el tiempo. Si tales identificadores persisten en el tiempo dependerá del país en cuestión y de si el número del documento expira o no. Identificadores únicos existen también para objetos y empresas: un número serial es un identificador único para un objeto. El número de registración de una sociedad es un identificador único para una organización con fines de lucro, de modo tal que las autoridades saben cómo identificar sociedades para cobrar impuestos o darles subsidios. 

<span style="text-decoration:underline;">La autenticación</span> es un proceso con el cual una persona, institución u objeto puede demostrar que son quienes dicen ser. Una persona puede autenticarse a sí misma demostrando el dominio de un objeto (cédula de identidad, billetera hardware, billetera software), conocimiento (clave o PIN), o por una cualidad personal (datos biométricos, firma). A menudo se usa una combinación de estos sistemas. Al menos un método fuerte y confiable debe existir para autenticar a una persona, institución u objeto. La biometría es la forma más robusta de autenticar personas. Una cédula de identidad es una forma analógica de autenticación,  dado que la foto y la firma manuscrita en la cédula de identidad son métodos de autenticación. Las contraseñas son el equivalente digital a la firma manuscrita en la Internet actual. Sin embargo, los nombres de usuarios, las contraseñas y todos los demás datos personales son controlados en su mayoría por instituciones privadas como tu banco, tu universidad, o Facebook, Twitter y Google. Las redes de blockchain y otros registros distribuidos han puesto de moda otros sistemas de identidad centrados en el usuario, aplicando criptografía de llave pública como método de autenticación.

<span style="text-decoration:underline;">Declaraciones y Credenciales</span>: Una identidad es inútil si no vincula información relevante a una persona (datos personales), a una institución (datos  institucionales) o a un objeto (datos relacionados al objeto). Los datos personales, por ejemplo, son declaraciones hechas por las propias personas (una declaración), o por otras personas o instituciones (una credencial). Tales declaraciones pueden incluir información sobre quién soy, dónde vivo, dónde nací, o qué títulos obtuve y deben ser atestiguados por autoridades confiables. Los datos personales también pueden incluir datos adicionales, como el historial de búsquedas, la actividad en redes sociales, o la geo-localización, que son automáticamente autenticados por máquinas y también vinculados al identificador personal.

Históricamente, los procesos de identidad, como los pasaportes, licencias de conducir, números de seguridad social, o números de serie para bienes, han sido creados por instituciones centralizadas tales como gobiernos locales o nacionales y otras instituciones confiables. La irrupción de Internet creó la necesidad de sistemas de identificación digital. Sin embargo, la Internet actual no ofrece una capa nativa de identidad para las personas, instituciones u objetos, salvo por los nodos operativos en una red de computadoras. Problemas tales como “puedo confiar en que mi cliente pagará la factura?” o “puedo confiar en que el proveedor de servicios entregará mis productos?” no pudieron ser resueltos por el protocolo de Internet. Las empresas y las instituciones públicas buscaron otras formas de resolver ese problema en Internet, usando normalmente bases de datos internas y combinaciones de usuario y contraseña, el tipo de sistema de identificación que ha estado en uso desde el tiempo de las computadoras mainframe y desde antes de la aparición de Internet. 


## Identidades Centradas en el Servidor

El Protocolo de Internet no tiene un formato nativo para gestionar la identidad de las personas, organizaciones y objetos. Soluciones alternativas se han desarrollado en la capa de aplicaciones usando bases de datos internas (infraestructuras privadas) para gestionar todos los datos involucrados con el proceso de gestión de identidad digital. Dada  la estructura de cliente-servidor de la Internet, cualquier servicio basado en la Web -desde páginas de universidades hasta la banca online, las redes sociales y las páginas de comercio electrónico- ofrecen su propio servicio de gestión de identidad, lo que significa que todos los datos vinculados al usuario están gestionados por el proveedor del servicio, en su infraestructura privada de computación. Todos los elementos vinculados al proceso de gestión de identidad -tales como emitir un identificador, establecer un método de autenticación, entregar credenciales, y gestionar los datos del usuario- están centralizados. La consecuencia son una serie de silos de datos incompatibles con servicios de gestión de identidad también incompatibles, que han creado muchos costos considerables, tanto para las empresas como para los usuarios, tales como:

<span style="text-decoration:underline;">Caos de contraseñas</span>: Con el paso de las décadas, a medida que crecía la cantidad de servicios en Internet, la gestión de contraseñas se volvió una tarea caótica. Los usuarios tienen que gestionar cientos de nombres de usuarios y contraseñas para cada aplicación o nuevo servicio online en el que se registren. Fragmentos de sus datos personales están distribuidos por toda la Internet. En los primeros días de Internet, todo servicio online requería a los usuarios que se registraran con un usuario y una contraseña, y a veces con más datos. Hoy, los usuarios pueden usar “soluciones de registración única” ofrecidas por empresas como Google,  Facebook y Twitter, con la salvedad que estas identidades pueden ser observadas y revocadas unilateralmente en cualquier momento  por el proveedor del servicio, lo que puede tener un efecto cascada de exclusión en todos los otros servicios que uno use con dicha registración.

<span style="text-decoration:underline;">Protección contra los malos actores</span>: En una configuración de comercio electrónico, las empresas necesitan identificar a los malos actores que pueden pedir bienes que nunca pagarán, para prevenir pérdidas de negocio potenciales. Dada la naturaleza fragmentada de los actuales sistemas de identidad digital, el proceso de identificación de los actores malos para protección contra el fraude es un gasto costo-intensivo. “El 82% de los negocios pelea con usuarios falsos y en promedio el 10% de la base de usuarios de un negocio online será falso. El costo promedio para el distribuidor por cada registro robado que contenga información sensible y confidencial es $165. $15 billones en pérdidas sobre un total de 13.1 millón de consumidores en 2015 sólo en EE.UU.”

<span style="text-decoration:underline;">Protección de datos y costos de custodia</span>: Los usuarios tienen que confiar en que sus proveedores de servicios mantendrán la integridad y privacidad de sus datos. Una cantidad creciente de datos personales está bajo custodia de instituciones generalmente privadas que gestionan una creciente cantidad de datos de sus clientes en sus servidores privados, lo que resulta en lo que muchos activistas de la privacidad llaman como “Capitalismo de Vigilancia”[^2]. Las combinaciones de usuario y contraseña son frecuentemente comprometidas por fuga de datos internas o externas. Soluciones alternativas como autenticación multi-factor se han introducido para mitigar este problema. Pero la gestión de seguridad de datos relacionados a la identidad contra pérdidas o robos sigue siendo una tarea cara e irregular. Con la aparición de un cuerpo creciente de leyes sobre protección de datos, y ante la posibilidad de demandas potenciales y multas gubernamentales, recolectar información sensible sobre sus usuarios y almacenar esos datos en servidores propios se ha vuelto un riesgo de negocio para las empresas.

<span style="text-decoration:underline;">Portabilidad de datos</span>: En aplicaciones Empresa-a-Empresa, la portabilidad es especialmente relevante a lo largo de la cadena de suministro de bienes y servicios para procesar la procedencia de bienes y servicios y reducir costos de gestión documental. En aplicaciones Empresa-a-Consumidor, nueva legislación como el Artículo 20 de la Regulación General de Protección  de Datos de la Unión Europea le dan al usuario el derecho de portabilidad de sus datos de una empresa a otra, y obliga a las empresas a ofrecer dicha portabilidad de datos. Sin embargo en una configuración de cliente-servidor tal portabilidad con otras instituciones tiene altos costos operacionales.

<span style="text-decoration:underline;">Falta de Control y Soberanía</span>: Los usuarios no tienen control directo sobre qué ocurre con sus datos, y no saben si han sido transferidos o a quién. Dependiendo de la regulación de un país, los usuarios de servicios basados en Internet pueden ser bloqueados de usar tales servicios (y sus datos) en cualquier momento. La  protección de datos depende de la ética de negocios de la empresa que ofrece los servicios de identidad, y está también sujeta a la jurisdicción del país de esa empresa.

<span style="text-decoration:underline;">Re-centralización de la Internet</span>: Los efectos de red tienen la tendencia de atar a clientes y socios comerciales en el uso de un único proveedor de servicios. Tómese como ejemplo Amazon o eBay. Una vez que los usuarios han realizado el proceso de autenticación con Amazon o eBay, tienden a quedarse en Amazon o eBay, antes que comprar productos online a otros. Comprar un producto en un sitio de Internet de un comercio barrial requeriría un proceso separado de autenticación en el sitio web de tal comercio y crear una nueva identidad (usuario y contraseña) incluyendo información de pago, lo  que muchos  tienden a evitar debido al tiempo que consume este proceso. Por otro lado, mientras más usuarios tienen Amazon o eBay, más atractivos se vuelven estos servicios para los vendedores, y viceversa. Como resultado de tales efectos de red, el poder comienza a acumularse en estas redes. Esto ha llevado a una re-centralización de la Internet alrededor de estos proveedores de plataformas de Internet, quienes no solo gestionan identidades de sus usuarios, sino que también controlan todos los demás datos relacionados a usuarios. La “huella digital” de todos los usuarios frecuentemente es almacenada en texto plano (no encriptado) en los servidores de las empresas y es usado para minería de datos que crea algoritmos de recomendación, algoritmos de publicidad, y otras formas de perfilamiento de usuarios que generan más ingresos para estas plataformas de Internet. 


## Historia de la Gestión de Identidades Digitales

Con el paso de las décadas, varias iniciativas intentaron encontrar una solución alternativa a la gestión centralizada de identidad. En 1999, “Microsoft Passport” lanzó una iniciativa para ofrecer una “solución federada de identidad” que las personas pudieran usar en varios servicios de Internet. La idea principal era ofrecer un servicio online de identidad que mitigase el caso de contraseñas a los usuarios. Sin embargo, esta solución ponía a Microsoft en el centro de la federación. Microsoft inició la “Alianza de la Libertad” en 2001 como una solución más distribuida, donde el control sobre las identidades digitales estaba dividido ahora entre varias instituciones, pero los datos personales seguían bajo la autoridad de cada sitio individual.  En 2001, los “Comunes de la Identidad” comenzó a consolidar todos los trabajos sobre identidad digital con foco en la descentralización, lo que finalmente motivó la creación del “Workshop de Identidad en Internet” en 2005. La comunidad de desarrolladores de código abierto comenzó a trabajar conceptos alternativos, como “Identidad Abierta”, que enfrentaba al “modelo centrado en servidores” con un “modelo centrado en el usuario” donde los individuos podrían controlar sus identidades usando su nombre como propio un dominio propio, y completando sus datos personales, los que podrían ser provistos a otras organizaciones con el permiso de cada individuo. Sin embargo, estas soluciones no eran muy amigables con el usuario y requerían de conocimientos técnicos.

Mientras tanto, empresas como Facebook adoptaron la idea de “Identidad Abierta” pero le dieron mejor usabilidad, que fue una de las razones por las cuales “Facebook Conecta” fue más exitoso que “Identidad Abierta” en 2008. Cualquiera podía usar su identidad de Facebook para registrarse en otros servicios de Internet, los que ahora podía usar una API de Facebook en lugar de gestionar sus propias identidades. Esto fue muy útil para pequeñas startups de Internet que podían ahorrar costos en gestión de identidad, y para los usuarios  que ahorraban tiempo y dolores de cabeza en gestión de contraseñas. Pronto Google, Amazon, Apple y Twitter siguieron  y ofrecieron similares soluciones de identidad “centradas en el servidor” - todas ellas controlan hoy la mayoría del mercado de identidad online. Esto también incluye el historial personal de búsquedas, el comportamiento en redes sociales y la geo-localización de sus usuarios. 

Paralelamente, una cantidad creciente de iniciativas continúo trabajando en la idea de soluciones de identidad más “centradas en el usuario”, tales como la iniciativa Red-de-Confianza, que tuvo sus orígenes en el movimiento Pretty Good Privacy (PGP). Proponían el uso de criptografía asimétrica a donde todos podrían ser  validadores de identidades. Lamentablemente ambas iniciativas se enfocaron en la dirección de correo electrónico como identificador, lo que significa que todavía dependían de instituciones como ICANN[^3] para emitir nombres de dominio en los que estas direcciones de correo electrónico estaban basadas. Por muchas razones, PGP nunca fue ampliamente adoptada.

Años más tarde, individuos como Christopher Allen e iniciativas como Reiniciando-la-Red-de-Confianza retomaron estos esfuerzos, especialmente cuando irrumpieron las redes de blockchain y nos permitieron el uso de criptografía de llave pública para identificación pseudo-anónima sin vincular identidades a una dirección de correo electrónico. La aparición de las redes de blockchain y otros registros distribuidos le dieron una continuación natural a los esfuerzos previos de descentralización. Christopher Allen y otros individuos elevaron la discusión de la gestión de identidad a un nivel político y propusieron el concepto de “Identidad Auto-Soberana”, un tipo de sistema de gestión de identidad centrado en el usuario que debe cumplir una serie de principios rectores:

<span style="text-decoration:underline;">Acceso y  Control</span>: Control directo de los datos personales de identidad, donde los usuarios son la última autoridad y tiene control sobre el nivel de anonimidad de sus datos.

<span style="text-decoration:underline;">Transparencia & Interoperabilidad</span>: Los algoritmos que gobiernan datos relacionados a identidad deben ser transparentes, de código abierto e independientes de cualquier infraestructura particular. Los datos relacionados a la identidad deben ser de larga vida, y preferentemente debieran durar para siempre, o al menos el plazo que el usuario quiera.   

<span style="text-decoration:underline;">Portabilidad</span>: Los datos relacionados a identidad deben ser portables hacia otros dispositivos, de lo contrario están sujetos a censura o control. Las identidades portables aseguran a los usuarios que ellos siguen en control de sus identidades independientemente de qué servicios usan.

<span style="text-decoration:underline;">Consentimiento & Minimización</span>: Los usuarios deben, en todo momento, consentir el acceso de terceros a sus datos personales. Más aún, cuando los datos personales son divulgados, esa divulgación sólo debe involucrar la mínima cantidad de datos necesaria. 

En su manifiesto Allen resaltó el delicado balance entre el derecho a la privacidad y la necesidad de divulgar cierta información para la seguridad de toda la red de personas. Advirtió que estos principios pueden ser una espada de doble filo, utilizados tanto para el bien como para el mal, y concluyó que un sistema de identidad debe balancear la transparencia, la justicia, y el apoyo a los intereses comunes de un grupo mientras al mismo tiempo garantizar la protección del individuo. Sin embargo, tales discusiones no son nuevas y han sido estudiadas por la ciencia política, al igual que siglos de debates que  han sido resueltos en grados variables, dependiendo del régimen político y las leyes de una nación en la materia. El balance entre la privacidad individual y el interés público ha sido, y aún es, un tópico de derecho constitucional en muchos países democráticos, sujeto a regulación en torno al “secreto de la correspondencia” y la “inviolabilidad del hogar” (leer más: Parte 3 - Tokens de Privacidad).

Los principios arriba listados han sido incorporados en una serie de iniciativas de identidad centrada en el usuario y en grupos de trabajo a lo largo de los años, tales como “Social Linked Data”, “Rebooting the Web of Trust”, “WebIDs”, y más recientemente en el  “W3C Working Group on Decentralized Identifiers (DIDs)”. El propósito de todas estas iniciativas es proveer estándares abiertos internacionales que desacoplen el proceso de emisión de credenciales y de declaraciones del proceso de verificación de esas declaraciones por parte de un conjunto de actores, lo que elimina muchos de los problemas que tienen las soluciones centradas en el servidor. 

***
![History of Identities](https://github.com/Token-Economy-Book/SpanishTranslation/blob/main/graphics/30_HistoryOfIdentities_Spanish.png) 
***

### Identidades Centradas en el Usuario utilizando Identificadores Descentralizados

Las redes de blockchain actualmente ofrecen solo un mínimo grupo de atributos de identidad que no son suficientes para muchas interacciones socioeconómicas en la Web. Sin embargo, si se configuran correctamente, el registro puede ofrecer componentes críticos para un sistema de gestión de identidad que sea centrado en el usuario y preserve la privacidad, ofreciendo menores fricciones y menores costos para todos los involucrados. Los Identificadores Descentralizados (DIDs) en combinación con registros distribuidos permiten un sistema de gestión de identidad más sofisticado. 

Un Identificador Descentralizado (DID) es un identificador digital único, público y pseudo-anónimo de una persona, empresa u objeto que otorga control personal sobre la identidad digital de uno sin necesidad de instituciones centralizadas que gestionen dichos identificadores.  Para garantizar la independencia de registros centralizados, los DIDs deben tener ciertas propiedades.  Necesitan ser permanentes así no pueden ser reasignados a otras entidades por quien sea que tenga el control. Necesitan ser solubles así todos entienden cómo interactuar con un sujeto identificado con un DID, y necesitan ser verificables criptográficamente.  

***
![User-Centric Identities](https://github.com/Token-Economy-Book/SpanishTranslation/blob/main/graphics/29_UserCentricIdentities_Spanish.png) 
***

La infraestructura de llave pública, inherente a los registros distribuidos, permite la registración de DIDs de todos los actores involucrados de una manera públicamente verificable. Cualquier usuario puede crear y registrar un DID cuando activa una nueva billetera de blockchain, lo que crea un par de llaves pública y privada. Cualquiera DID puede ser vinculado a credenciales que son emitidas por otras personas o instituciones atestiguando características especiales del dueño de la identidad (declaraciones que hacen sobre sí mismos), como el nombre, dirección, correo electrónico, edad, títulos, y otras certificaciones como la licencia de conducir. 

La billetera es el equivalente digital a la billetera física, que - además de usarse para llevar dinero- también se usa para llevar identificaciones, como la licencia de conducir, tarjetas bancarias, membresías de gimnasios, cédula de identidad nacional, tarjeta de seguridad social, o tarjetas de lealtad. Una billetera de Web3 puede ser usada para gestionar todas tus credenciales digitales criptográficamente aseguradas que otros han emitido sobre uno, credenciales tokenizadas que representan la versión digital de la licencia de conducir, la tarjeta bancaria, la membresía del gimnasio, la cédula nacional de identidad, la tarjeta de la seguridad social, tarjetas de lealtad, etc. Tal como solo abrís tu billetera para mostrar tu cédula de identidad, debes activar tu billetera de Web3 para mostrar tus credenciales digitales a terceros (usando una contraseña).  Nadie puede ver qué tenés en tu billetera sin tu consentimiento. El contenido de tu billetera se mantiene secreto hasta que elegís revelar algo. Los jugadores en esta configuración son: 

<span style="text-decoration:underline;">Emisores de identidad</span>: instituciones confiables como gobiernos locales, universidades y otras instituciones públicas y privadas, y en algunos casos, individuos privados. Estos emisores de identidad pueden otorgar credenciales para un dueño de identidad (tales como el nombre, edad, y fecha de nacimiento) y atestiguar sobre la validez de estos datos personales.  

<span style="text-decoration:underline;">Dueños de la identidad</span>: gestionan las credenciales que han sido emitidas por los terceros mencionados arriba, a través de su billetera Web3, y pueden usarlas en cualquier momento para acreditar declaraciones sobre su identidad a terceras partes. 

<span style="text-decoration:underline;">Verificadores de Identidad</span>: son terceros que proveen servicios para verificar ciertos atributos relacionados con la identidad. Por ejemplo, si hay un límite de edad para comprar alcohol, o para ver una película, el verificador de identidad (el comercio o el cine) puede validar la firma del gobierno que emitió y atestiguó la credencial. 

Las credenciales son firmadas por sus emisores usando criptografía de llave pública. Una vez firmada por el emisor, las credenciales pueden ser gestionadas por el dueño de la identidad para hacer declaraciones, simplemente usando su billetera. Los dueños de la identidad usan su billetera para divulgar los datos que quieren compartir con el mundo exterior. Pueden decidir y controlar no sólo a quién le compartes sus datos, sino también cuándo compartir sus datos. Para hacerlo, deben atestiguar a la red su consentimiento para compartir datos seleccionados con instituciones autorizadas.

Tanto los emisores de identidad como los dueños de la identidad deben registrarse en un registro público con sus DIDs. En tal configuración, los registros distribuidos pueden ser usados para atestiguar la autenticidad de los datos y sus certificaciones, registrando solo “punteros” para fines de verificación. Los registros distribuidos pueden ser usados como una infraestructura pública para facilitar la verificación de datos relacionados a la identidad. Cualquiera en una red de blockchain ahora puede verificar si una declaración hecha por un dueño de la identidad es válida y qué instituciones atestiguaron la validez de una declaración, sin tener que revelar los datos en sí.

Aparear la llave privada con un DID permite al dueño de la identidad crear un código QR, que por ejemplo representa representa el identificador verificado. Al escanear el código QR, un proveedor de servicios puede ahora correr los ratos por la red de blockchain o similares registros distribuidos y verificar si una atestiguación está asociada al DID de una persona. La llave pública es usada para atestiguar la autenticidad de la firma de la autoridad emisora asociada a una credencial. Si la atestación y el DID coinciden, el acceso se concede, y una persona puede calificar para comprar alcohol, alquilar un auto, etc. En adición a tales atestiguaciones, otros datos pueden ser asociados a un DID y ser directamente controlados por el dueño de la identidad a través de su software billetera. Ejemplos de tales datos “no atestiguados” son el historial personal de búsqueda o las publicaciones en redes sociales. En tales configuraciones, uno no dependería más de terceros que proveen servicios de identidad digital como Google o Facebook. El “Brave browser” es un ejemplo práctico de cómo las billeteras Web3 permiten  el control directo de tu huella digital (leer más: Parte 4 - Tokens de Atención Básica).

Los registros de revocaciones le dan a los emisores de identidades la posibilidad de revocar declaraciones dado que ciertos datos relacionados a la identidad pueden cambiar con el tiempo. Los datos personales tales como la dirección, el estado conyugal, y la cantidad de hijos pueden cambio con el tiempo y por ello necesitan ser actualizados. 

La separación de los procesos de (i) emisión de credenciales, (ii) hacer una declaración y (iii) validar esas declaraciones de cada credencial es crucial para una configuración centrada en el usuario. Puede ser visto como un sistema de pesos y contrapesos en una economía basada en datos que garantiza el nivel de autonomía y privacidad sobre la huella digital de uno, y es muy opuesto a cómo Internet está configurada hoy.  

KERI (Key Event Receipt Infrastructure)  es una nueva tecnología -un tipo de red de consenso- que permite trasladar ciertas funciones de los sistemas descentralizados de gestión de identidad fuera del blockchain hacia una capa diferente, y minimizar el rol de los registros distribuidos. El propósito es ofrecer un sistema de gestión de identidad simple, escalable, y más modular, que sea más interoperable entre diferentes redes de blockchain y  otros registros distribuidos. Actualmente está siendo adoptado por varios jugadores en el espacio de la identidad centrada en el usuario y muestra mucho potencial como un catalizador de identidades centradas en el usuario. 


## Panorama

Las soluciones de identidad centradas en el usuario basadas en registros distribuidos y DIDs pueden desintermediar a la industria de la identidad. Pueden incrementar la eficiencia operacional con auditorías inmediatas y acceso directo en tiempo real a los datos, reduciendo a la vez costos. Si se la configura de manera correcta, pueden ofrecer mayor seguridad de los datos y protección contra impostores de identidad, y permitir un cumplimiento regulatorio más eficiente, dándoles  más control a los de los datos. Las soluciones de identidad centrada en el usuario pueden permitir la portabilidad de los datos, de modo tal que los individuos y las instituciones puedan fácilmente reusar credenciales para re-verificarse para nuevos servicios. Para las empresas, esto puede reducir los costos y el tiempo asociado a las tasas de captación y pérdida de clientes, y también los  costos de oportunidad asociados al proceso completo de identificación de Conozca-a-Su-Cliente. 

Para el almacenamiento de los datos personales, las soluciones de identidad centradas en el usuario pueden usar tanto depósitos de datos personales como redes de almacenamiento distribuido de archivos. Las credenciales  pueden ser almacenadas directamente en el dispositivo del usuario o de manera segura en un depósito privado de identidad, o en un concentrador de identidad (identity hub), como “TrustGraph” o “3Box”. Los datos menos sensibles pueden  ser colectivamente gestionados por  redes de almacenamiento distribuido de archivos, como el “InterPlanetary File System” (IPFS) o “OrbitDB”, para reducir la redundancia de los datos y desintermediar el proceso de gestión de identidad. En  ambas configuraciones, los datos están diseñados alrededor del usuario, y por ello son más interoperables entre múltiples proveedores de servicio que pueden usar el mismo conjunto de información para diferentes fines. Los datos del usuario no quedan atrapados en una sola plataforma. 

Si bien algunas formas de la criptografía de zero prueba de conocimiento (ZKP) ya está siendo usada el soluciones centradas en el usuario, hay espacio para mejorar y fortalecer las herramientas criptográficas de preservación de la privacidad. Un conjunto de redes de la Web ya está trabajando para incorporar más mecanismos criptográficos de preservación de la privacidad en los registros distribuidos, como “Zero-Knowledge Proofs” implementada por “Zcash,” o las “Ring Signatures” implementada por “Monero”, or realizar computación en información encriptada usando  “Secure-Multi-Party-Computation” (leer más: Parte 3 - Tokens de Privacidad). KERI también podría cambiar el juego en esta materia. 

Uno de los casos de usos futuros más interesante será la identificación digital de objetos. Actualmente, la mayoría de los dispositivos con Internet-de-las-Cosas no tienen una identidad digital segura ni funcionalidades de gestión de accesos. Un número serial que a la vez sea un Identificador Descentralizado (DID) puede permitir que cualquier objeto sea visible en la Web3. Cuando empecemos a marcar objetos con mini computadoras (cripto aceleradores) que vienen con un número serial con un DID y que pueden comunicarse con una red de registro distribuido, cualquier objeto a lo largo de la cadena de suministro puede demostrar su dominio y sus credenciales a otros en la red usando pruebas criptográficas. Los objetos que tengan su propia y única identidad en la Web3 y tengan una billetera Web3 se pueden convertir en entidades económicas autónomas y confiables. Ese vínculo “ciber-físico” entre objetos e Identificadores Descentralizados (DID) permite trazabilidad efectiva de productos y compartir datos sobre la procedencia de bienes y servicios entre productores y consumidores.

Las soluciones de identidad basadas en la Web3 seleccionadas son: “[Ageif](https://age-ify.com/)”, “[Civic](https://www.civic.com/)”, “[Edge](https://edge.app/)”, “[Hu-manity.co](http://hu-manity.co/)”,  “[Jolocom](https://jolocom.io/)”,  “[Keyp](https://keyp.io/)”, “[Madana](https://www.madana.io/)”, “[Metadium](https://www.metadium.com/)”, “[NewBanking Identity](https://newbanking.com/),”“[ObjectTech](https://www.objecttechgroup.com/)”, “[THEKEY](https://www.thekey.vip/#/homePage)”, “[Trusti,”](https://trusti.com/) “[PeerMountain](https://www.peermountain.com/)”, “[REMME](https://remme.io/)”, “[Riddle & Code](https://www.riddleandcode.com/)”, “[Spherity](https://spherity.com/)”, “[uPort](https://www.uport.me/)”,“[UniquID](https://uniquid.com/)”, “[ValidatedID](https://www.validatedid.com/)”, and “[WoTT](https://www.wott.io/)”. 


### Resumen del Capítulo

> Históricamente, los procesos de identidad, como los pasaportes, licencias de conducir, tarjetas de seguridad social, o números seriales para bienes, han sido emitidos por instituciones centralizadas como los gobiernos locales o nacionales y otras instituciones confiables. La aparición de Internet creó la necesidad de un sistema de identificación digital. 

> Desde la perspectiva de la ciencia de la computación, el término  “identidad” se puede limitar a los datos relacionados con el proceso de gestión de la identidad: “identificador”, “autenticación”, y “credenciales”. 

> Los identificadores son necesarios para identificar de manera unívoca a una persona, una institución o un objeto. Un identificar necesita ser único y persistente en el tiempo.  

> La autenticación es el proceso con el cual una persona, una institución o un objeto puede demostrar que es quien dice ser. Una persona se puede autenticar demostrando la posesión de un objeto (una cédula de identidad, un software billetera, una billetera hardware), de un conocimiento (PIN o contraseña), o por sus propiedades  personales (datos biométricos, la firma). Generalmente se utiliza una combinación de estos sistemas.

> Una identidad es inútil si no vincula datos de la persona (datos personales), de la institución (datos institucionales), o de un objeto (datos del objeto) con un identificador.  

> La Internet actual  se construyó sobre computadoras conectadas, no personas. Internet no ofrece una capa nativa de identidad para personas, instituciones u objetos, aparte de los nodos operativos en una red de computadoras. Soluciones alternativas se han desarrollado en la capa de aplicaciones, usando bases de datos internas (infraestructura privada) para gestionar todos los datos asociados a los procesos de gestión de identidad digital. Todos los datos del usuario están gestionados por el proveedor del servicio, en su infraestructura privada, y así, todos los elementos relacionados a los procesos de gestión de la identidad están centralizados. \

> Estos silos de datos y las soluciones de identidad propietarias han creado considerables costos y dificultades, tanto para empresas como para usuarios,  como ser (i) el caos de contraseñas, (ii) la protección contra actores malos, (iii) costos de protección y  custodia  de datos, (iv) portabilidad de datos, (v) falta de control y soberanía sobre los datos y (vi) la re-centralización de la Internet. \

> Las redes de blockchain y similares registros distribuidos usan criptografía de llave pública para  identificar a todos los actores de la red, pero son insuficientes para una floreciente economía tokenizada. Sin embargo, al combinarse con DIDs, pueden ofrecer componentes críticos para soluciones de identidad “centradas en el usuario” que son adecuadas para la Web3, y ofrecen mayor privacidad y control que las soluciones “centradas en el servidor” usadas en la Web2. 

> Los procesos de identidad centrados en el usuario requieren tres actores: (i) emisores de identidad, (ii) dueños de la identidad, y (iii) verificadores de la identidad. Si se la configura correctamente, cualquiera en una red de blockchain puede verificar si un conjunto de datos (credencial) es válido y qué institución atestiguó la validez de los datos, sin revelar los datos en sí. 

> Si bien datos planos nunca debieran ser almacenados en un registro público, un sistema de gestión de la identidad que preserve la privacidad puede usar registros distribuidos para permitir a una persona acreditar que sus datos relacionados a su identidad cumplen ciertos requisitos, sin tener que revelar los datos en sí. En tal configuración, los registros distribuidos pueden ser usados para atestiguar la autenticidad de los datos y de las atestaciones, sólo registrando “marcadores” indirectos para fines de verificación.  

> Un usuario puede crear y registrar un DID cuando activa una billetera de blockchain, lo que crea un par de llaves pública y privada. La criptografía de llave pública es usada para autenticación y encriptación. Solo la llave privada puede demostrar la identidad de uno. La llave privada actúa como tu candado personal en la billetera.

> Cualquier DID puede ser vinculado a atestaciones (credenciales verificables) que son emitidas por otras personas e instituciones, dando fe de ciertas características del dueño de la identidad, tales como el nombre, domicilio, correo electrónico, edad, títulos adquiridos, u otras certificaciones tales como licencia de conducir. Las credenciales son firmadas por sus emisores usando criptografía de llave pública. Una vez firmada por el emisor, la credencial puede ser gestionada directamente usando la  billetera del dueño de la identidad. 

> La separación entre  “identificador”, “autenticación” y los “datos” es crucial en una configuración centrada en el usuario.  Puede ser visto como un  sistema de pesos y contrapesos en una economía basada en datos, que garantiza un nivel de autonomía y privacidad sobre la propia huella digital de cada uno, y es muy opuesto a cómo Internet está configurada hoy. Al usar una infraestructura pública como un registro colectivamente mantenido como la única fuente de verdad, y al dividir  los roles del proceso de gestión de identificaciones, el sistema de gestión de identidad centrada en el usuario se “descentraliza”. [^1]

La billetera actúa como un depósito personal que te permite controlar tus identidades digitales. La billetera es equivalente digital a una billetera física, en la que normalmente guardas tus identificaciones, como la licencia de conducir, tarjetas de banco, membresías del gimnasio, cédula nacional de identidad, tarjeta de la seguridad social, tarjetas de lealtad, además de tu dinero. Si bien al inicio estará vacía, con el tiempo, uno puede ir llenando la billetera con credenciales que representan la versión digital de tu licencia de conducir, tu tarjeta de banco, tu membresía del gimnasio, tu cédula nacional de identidad, tu tarjeta de la seguridad social, tarjetas de lealtad, etc.  

> Al igual que abrís tu billetera para mostrar tus identificaciones, necesitás activar una billetera Web3 para mostrar tus credenciales digitales a terceros (usando una contraseña). Nadie puede ver el contenido de tu billetera Web3 sin tu permiso. Vos eliges con  quién compartir tus credenciales. El contenido de la billetera se mantiene secreto hasta que quieras mostrar algo. La billetera digital es portable, sea como un dispositivo de hardware dedicado, o una aplicación en tu teléfono móvil o en tu notebook.


### Referencias del Capítulo & Lecturas Complementarias
_* Allan, Christoper: “The Path to Self-Sovereign Identity,” March 1 2017, [https://github.com/ChristopherA/self-sovereign-identity/blob/master/ThePathToSelf-SovereignIdentity.md](https://github.com/ChristopherA/self-sovereign-identity/blob/master/ThePathToSelf-SovereignIdentity.md)_

_* Ellison,[ ](http://irl.cs.ucla.edu/index.html)Carl: “Establishing Identity without Certification Authority,” 1996, [https://irl.cs.ucla.edu/index.html](https://irl.cs.ucla.edu/index.html) _

_* Feisthammel, Patrick: “[Pretty good Privacy, PGP](https://www.rubin.ch/pgp/weboftrust.en.html), Web of Trust,” Oct 7 2004, [https://www.rubin.ch/pgp/weboftrust.en.html](https://www.rubin.ch/pgp/weboftrust.en.html)_

_* Jordan, Ken; Hauser, Jan; Foster, Steven: “The Augmented Social Network,” White paper, 2000, [https://firstmonday.org/ojs/index.php/fm/article/view/1068/988](https://firstmonday.org/ojs/index.php/fm/article/view/1068/988) _

_* Kameron, Kim: “The Laws of Identity,” March 2007, [https://docs.microsoft.com/en-us/previous-versions/dotnet/articles/ms996456(v=msdn.10)?redirectedfrom=MSDN](https://docs.microsoft.com/en-us/previous-versions/dotnet/articles/ms996456(v=msdn.10)?redirectedfrom=MSDN)_

_* Kütt, Andres: "MyData Webinar #5: Identity in the Digital Era," Mydata Global, Youtube Video, retrieved from: [https://www.youtube.com/watch?v=XjzJeys7PvM&fbclid=IwAR0qMDGYuZVk0c6aDHOX46AdFQMGdsI24SSZ6-lMfj7XZY-TrbkbT5LFlqk](https://www.youtube.com/watch?v=XjzJeys7PvM&fbclid=IwAR0qMDGYuZVk0c6aDHOX46AdFQMGdsI24SSZ6-lMfj7XZY-TrbkbT5LFlqk)_

_* Many authors: “[Rebooting the Web of Trust](http://www.weboftrust.info/papers.html),” Papers and Specs, [http://www.weboftrust.info/papers.html](http://www.weboftrust.info/papers.html)_

_* Many authors: “Charta for Digital Human Rights,” Version: 01.12.2016 Unofficial English translation of the German original text, published by ZEIT-Stiftung Ebelin und Gerd Bucerius [https://digitalcharta.eu/wp-content/uploads/2016/12/Digital-Charta-EN.pdf](https://digitalcharta.eu/wp-content/uploads/2016/12/Digital-Charta-EN.pdf)_

_* Many authors: “Self-sovereign Identity A position paper on blockchain enabled identity and the road ahead,”  October 23 2018, Identity Working Group of the German Blockchain Association, [https://www.bundesblock.de/wp-content/uploads/2019/01/ssi-paper.pdf](https://www.bundesblock.de/wp-content/uploads/2019/01/ssi-paper.pdf)_

_* Many authors: “The Respect Trust Framework, “ Version 2.1,  Feb 2016,  [https://oixnet.org/wp-content/uploads/2016/02/respect-trust-framework-v2-1.pdf](https://oixnet.org/wp-content/uploads/2016/02/respect-trust-framework-v2-1.pdf)_

_* Marlinspike, Moxie: “Sovereign Source Authority,” Moxytongue, Feb 2012, [https://www.moxytongue.com/2012/02/what-is-sovereign-source-authority.html](https://www.moxytongue.com/2012/02/what-is-sovereign-source-authority.html)_

_* Miller, Ron: "[The Promise of managing identities on the blockchain](https://techcrunch.com/2017/09/10/the-promise-of-managing-identity-on-the-blockchain/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_recent_activity_details_all%3BknkLT7NkR5Cex9bx3zogKg%3D%3D),” Sep 10, 2017, [https://techcrunch.com/2017/09/10/the-promise-of-managing-identity-on-the-blockchain/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_recent_activity_details_all%3BknkLT7NkR5Cex9bx3zogKg%3D%3D&guccounter=1](https://techcrunch.com/2017/09/10/the-promise-of-managing-identity-on-the-blockchain/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_recent_activity_details_all%3BknkLT7NkR5Cex9bx3zogKg%3D%3D&guccounter=1)_

_* Mire, Sam: “Blockchain Research Technologies Blockchain For Identity Management: 7 Possible Use Cases” Dec 5 2018, [https://www.disruptordaily.com/blockchain-use-cases-identity-management/](https://www.disruptordaily.com/blockchain-use-cases-identity-management/)_

_* N.N.: “Enterprise Ethereum Blockchain in Digital Identity,” Consensys website, [https://consensys.net/blockchain-use-cases/digital-identity/#usecases](https://consensys.net/blockchain-use-cases/digital-identity/#usecases)_

_* N.N.: “Identity Management with Blockchain: The Definitive Guide (2020 Update),”  TYKN website: [https://tykn.tech/identity-management-blockchain/](https://tykn.tech/identity-management-blockchain/)_

_* Preukschat, Alex; Reed , Drummond: "Self-Sovereign Identity Decentralized Digital Identity and Verifiable Credentials" MEAP began December 2019  Publication in January 2021 (estimated) ISBN 9781617296598  300 pages (estimated), electronically retrieved from:[https://www.manning.com/books/self-sovereign-identity](https://www.manning.com/books/self-sovereign-identity)_

_* Reed, Drummond; Tobin, Andrew: “[Sovereign White Paper](https://sovrin.org/wp-content/uploads/2017/07/The-Inevitable-Rise-of-Self-Sovereign-Identity.pdf),” Sept 29 2016, [https://sovrin.org/wp-content/uploads/2017/07/The-Inevitable-Rise-of-Self-Sovereign-Identity.pdf](https://sovrin.org/wp-content/uploads/2017/07/The-Inevitable-Rise-of-Self-Sovereign-Identity.pdf)_

_* Reed, Drummond; Sabadello, Markus: "Chapter 8 Decentralized identifiers" in Self Sovereign Identity, retrieved from on October 27, 2020: in [https://livebook.manning.com/book/self-sovereign-identity/chapter-8](https://livebook.manning.com/book/self-sovereign-identity/chapter-8)_
_* Ruff, Timothy: "When Explaining SSI, Start with the Wallet," Apr 21 2020, [https://medium.com/@rufftimo/when-explaining-ssi-start-with-the-wallet-bee5d2af6696](https://medium.com/@rufftimo/when-explaining-ssi-start-with-the-wallet-bee5d2af6696)_

_* Sabadello, Markus: “Human Rights in the Information Society,” 2011, [https://danubetech.com/download/Human-Rights-in-the-Information-Society.pdf](https://danubetech.com/download/Human-Rights-in-the-Information-Society.pdf)_

_* Shea, Michael;Smith, Samuel M.; Stöcker,Carsten, Caballero, Juan; Condon, Matt G.: “Decentralized Identity as a Meta-platform: How Cooperation Beats Aggregation a white paper from Rebooting the Web of Trust IX, [https://nbviewer.jupyter.org/github/WebOfTrustInfo/rwot9-prague/blob/master/final-documents/CooperationBeatsAggregation.pdf](https://github.com/SmithSamuelM/rwot9-prague.githttps://nbviewer.jupyter.org/github/WebOfTrustInfo/rwot9-prague/blob/master/final-documents/CooperationBeatsAggregation.pdf)_

_* Spike, Marlin: “Self Sovereign Identity, how the term has evolved,” Feb 2016, [https://www.moxytongue.com/2016/02/self-sovereign-identity.html](https://www.moxytongue.com/2016/02/self-sovereign-identity.html)_

_* Smith, Samuel M.: "Key Event Receipt Infrastructure (KERI)", Cornell University, retrieved from: [https://arxiv.org/abs/1907.02143](https://arxiv.org/abs/1907.02143)_

_* Smolenski, Natalie: ”The EU General Data Protection Regulation and the Blockchain,” Aug 2 2017, [https://medium.com/learning-machine-blog/the-eu-general-data-protection-regulation-and-the-blockchain-1f1d20d24951](https://medium.com/learning-machine-blog/the-eu-general-data-protection-regulation-and-the-blockchain-1f1d20d24951)_

_* Stöcker, Carsten: “The Economic Value of Decentralized Identity — Part 2 Reimagining the economics of trust and reputation,” Mar 11 2020, [https://medium.com/spherity/the-economic-value-of-decentralized-identity-part-2-733aa977eaf8](https://medium.com/spherity/the-economic-value-of-decentralized-identity-part-2-733aa977eaf8)_

_* Stöcker, Carsten: “Spherity’s Identity Tech Predictions for the decade of the 2020’s — Part 1,” Jan 16 2020 [https://medium.com/spherity/spheritys-identity-tech-predictions-for-the-decade-of-the-2020-s-part-1-410bc9b48be4](https://medium.com/spherity/spheritys-identity-tech-predictions-for-the-decade-of-the-2020-s-part-1-410bc9b48be4)_

_* Stöcker, Carsten: “Spherity’s Identity Tech Predictions for the decade of the 2020’s — Part 2,” Feb 13 2020 [https://medium.com/spherity/spheritys-identity-tech-predictions-for-the-decade-of-the-2020-s-part-2-6e480d2a57ea](https://medium.com/spherity/spheritys-identity-tech-predictions-for-the-decade-of-the-2020-s-part-2-6e480d2a57ea)_

_* Stöcker, Carsten: “SSI201: Upgrading products with intelligent serial numbers and DIDs How smart can an object’s identifier be? How can it enable cradle-to-grave traceability and other innovative capabilities?” Nov 26, 2019 ·, [https://medium.com/spherity/ssi201-upgrading-products-with-intelligent-serial-numbers-and-dids-78da623b91dd](https://medium.com/spherity/ssi201-upgrading-products-with-intelligent-serial-numbers-and-dids-78da623b91dd)_

_* Stöcker, Karsten: "KERI: A more Performant Ledger for Trusted Identities Securing the control of decentralized identifiers at the root with ambient verifiability", Medium, Sperity Blog, July 2 2020, [https://medium.com/@cstoecker](https://medium.com/@cstoecker)_

_* Voshmgir, Shermin: “Identity as a Bottleneck for Blockchain,” Oct 17, 2017, [https://stories.jolocom.com/identity-blockchain-the-road-to-self-sovereign-identity-f9f4439c52cb](https://stories.jolocom.com/identity-blockchain-the-road-to-self-sovereign-identity-f9f4439c52cb)_

_* Voshmgir, Shermin: “Self Sovereign — Identity vs Data?” Feb 27 2018, [https://stories.jolocom.com/self-sovereign-identity-vs-data-5abe5947a62](https://stories.jolocom.com/self-sovereign-identity-vs-data-5abe5947a62)_

_* Wikipedia contributors: "Pretty Good Privacy," Wikipedia, The Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Pretty_Good_Privacy&oldid=959437666 (accessed May 31, 2020)._

_* Zuboff, Shoshana: “ The Age of Surveillance Capitalism: The Fight for a Human Future at the New Frontier of Power.” New York: PublicAffairs, 2019._

_* Ageif: [https://age-ify.com/](https://age-ify.com/)_

_* Civic: [https://www.civic.com/wallet/](https://www.civic.com/wallet/)_

_* Edge: https://edge.app/_

_* General Data Protection Regulation (GDPR): [https://gdpr-info.eu/](https://gdpr-info.eu/)_

_* Hu-manity.co: [https://hu-manity.co/](https://hu-manity.co/)_

_* Jolocom: [https://jolocom.io/](https://jolocom.io/)_

_* Keyp: [https://keyp.io/](https://keyp.io/)_

_* List of Blockchain & Identity Solutions: [https://github.com/peacekeeper/blockchain-identity](https://github.com/peacekeeper/blockchain-identity)_

_* Madana: [https://www.madana.io/](https://www.madana.io/)_

_* Metadium: [https://www.metadium.com/](https://www.metadium.com/)_

_* NewBanking Identity: [https://newbanking.com/#/](https://newbanking.com/#/)_

_* ObjectTech: [https://www.objectivetgg.com/](https://www.objectivetgg.com/)_

_* THEKEY: [https://www.thekey.vip/#/homePage](https://www.thekey.vip/#/homePage)_

_* Trusti: [https://trusti.com/](https://trusti.com/)_

_* PeerMountain: [https://www.peermountain.com/](https://www.peermountain.com/)_

_* PGP WOT: [https://www.linux.com/training-tutorials/pgp-web-trust-core-concepts-behind-trusted-communication/](https://www.linux.com/training-tutorials/pgp-web-trust-core-concepts-behind-trusted-communication/)_

_* Rebooting the Web of Trust:[http://www.weboftrust.info/papers.html](http://www.weboftrust.info/papers.html)_

_* REMME: [https://remme.io/](https://remme.io/)_

_* Riddle & Code: [https://www.riddleandcode.com/](https://www.riddleandcode.com/)_

_* Spherity: [https://spherity.com/](https://spherity.com/)_

_* SPKI/SDSI project: [http://world.std.com/~cme/html/spki.html](http://world.std.com/~cme/html/spki.html)_

_* SoLid (Social Linked Data: [https://github.com/solid/solid-spec](https://github.com/solid/solid-spec)_

_* uPort: [https://www.uport.me/](https://www.uport.me/)_

_* UniquID: [https://uniquid.com/](https://uniquid.com/)_

_* ValidatedID: [https://www.validatedid.com](https://www.validatedid.com/)_

_* WebIDs: [https://www.w3.org/2005/Incubator/webid/spec/tls/](https://www.w3.org/2005/Incubator/webid/spec/tls/)_

_* WoTT: [https://wott.io/](https://wott.io/)_

_* W3C working group on verifiable claims: [https://www.w3.org/2017/vc/WG/](https://www.w3.org/2017/vc/WG/)_

_* W3C Verifiable Claims Task Force FAQ: [https://w3c.github.io/webpayments-ig/VCTF/charter/faq.html](https://w3c.github.io/webpayments-ig/VCTF/charter/faq.html)_

_* W3C initiative of Decentralized Identifiers (DIDs): [https://w3c.github.io/did-core](https://w3c.github.io/did-core/)_


### Notas al pie
[^1]:
https://sovrin.org/wp-content/uploads/2017/07/The-Inevitable-Rise-of-Self-Sovereign-Identity.pdf

[^2]:
Como por ejemplo Zuboff, Shoshana en “The Age of Surveillance Capitalism: The Fight for a Human Future at the New Frontier of Power.” New York: PublicAffairs, 2019. Zuboff describe la comoditización de la información personal. Describe la tendencia a la acumulación de datos, criticando que muchas empresas e instituciones cosechan y capitalizan los datos personales sin mecanismos de consentimiento. Compara el “capitalismo industrial” y el “capitalismo de vigilancia”, explicando que el “capitalismo industrial” es una explotación de la naturaleza, y el “capitalismo de vigilancia” es una explotación de la naturaleza humana.

[^3]:
ICANN (Internet Corporation for Assigned Names and Numbers) es una organización sin fines de lucro que coordina el mantenimiento y los procedimientos de varias bases de datos relacionadas a los nombres de dominio y espacios numéricos en la Internet, asegurando la operación estable y segura de la red. Es un grupo con múltiples partes interesadas basada en EE.UU.