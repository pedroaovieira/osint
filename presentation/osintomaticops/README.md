
### **Guion para la Presentación de Ciberseguridad**

**(Diapositiva 1: Título)**

"Hola a todos y bienvenidos. Mi nombre es Pedro Vieira y hoy les presentaré 'Negocios Privados, Consecuencias Públicas'. En esta charla, les mostraré una guía paso a paso sobre cómo aprovechar la inteligencia de fuentes abiertas, conocida como OSINT, para descubrir la información públicamente disponible que alimentó un escándalo que involucró a un primer ministro portugués, lo que finalmente llevó al colapso del gobierno. Utilizando técnicas del mundo real, exploraremos cómo los negocios privados se convirtieron en una crisis pública, demostrando el poder de OSINT para exponer conexiones ocultas."

**(Diapositiva 2-3: Quién Soy y Descargo de Responsabilidad)**

"Antes de empezar, permítanme presentarme brevemente. Soy Pedro Vieira, Ingeniero de Ciberseguridad, desarrollador full stack y especialista en OSINT.

Ahora, algunos puntos importantes. **Esta presentación tiene fines exclusivamente educativos y de concienciación. No es una declaración política**. Es crucial que cada uno de ustedes verifique la legalidad de las herramientas y métodos OSINT en su propio país. Además, lo que presento aquí no está relacionado de ninguna manera con mi trabajo o mi empleador."

**(Diapositiva 4: Descargo de Responsabilidad y Tecnologías)**

"Quiero enfatizar un punto clave en cualquier investigación OSINT: usen las tecnologías disponibles, pero siempre, **siempre verifiquen los hechos**. Y cuando hablo de tecnología, recuerden que la inteligencia artificial va más allá de ChatGPT. Utilicen diversas herramientas como Grok, Claude, etc., para contrastar y enriquecer su análisis. De hecho, varias de ellas fueron utilizadas para preparar esta presentación."

**(Diapositiva 5-6: Agenda y ¿Qué es OSINT?)**

"Nuestra agenda para hoy es simple: hablaremos de OSINT y luego aplicaremos estos conceptos al caso del Primer Ministro.

Entonces, ¿qué es OSINT? Según Wikipedia, la inteligencia de fuentes abiertas es **la recopilación y el análisis de datos obtenidos de fuentes públicas y abiertas para producir inteligencia accionable**. Esto significa que toda la información que vamos a ver es accesible para cualquiera con una conexión a internet."

**(Diapositiva 7: Fuentes de Información)**

"¿De dónde obtenemos esta información? De una gran variedad de fuentes: sitios web gubernamentales, motores de búsqueda como Google, redes sociales, mapas y mucho más. El verdadero poder del OSINT no está solo en recolectar datos, sino en **extraer, relacionar e inferir nueva información con un valor mucho mayor**."

**(Diapositiva 8-10: Caso Práctico - Portal do Governo)**

"Comencemos nuestra investigación. Un excelente punto de partida son los portales gubernamentales, donde podemos encontrar información sobre administraciones anteriores y funcionarios. Aquí vemos los datos iniciales de Luís Montenegro obtenidos del 'Portal do Governo'. Tenemos su nombre, fecha de nacimiento, estado civil, educación y experiencia laboral previa, como abogado fundador del bufete SP&M y presidente de la Asamblea General del Grupo Ferpinta y Rádio Popular. También vemos su carrera política, incluyendo 16 años como diputado. La clave aquí es recordar que **cada dato puede conducir a más información. Hay que investigarlo todo**."

**(Diapositiva 11: Portal da Assembleia da República)**

"El siguiente paso nos lleva al portal del parlamento, el 'Portal da Assembleia da República'. Una fuente muy valiosa aquí es el registro de intereses. Al consultar este registro, enriquecemos nuestro perfil. Ahora tenemos su nombre completo, Luís Filipe Montenegro Cardoso de Morais Esteves, y el nombre de su esposa. Y, lo que es más importante, aparecen nuevas empresas en las que tiene participación: Oliveiras Gold de Portugal y Luimonteago, Lda. Como ven, empezamos a construir una red de conexiones: familia, empresas...."

**(Diapositiva 12-13: Diário da República y Empresas)**

"Para profundizar en estas empresas, consultamos el 'Diário da República Eletrónico', el boletín oficial del estado. Esto nos permite confirmar los detalles de las empresas vinculadas a Montenegro, como su participación del 50% en el bufete SP&M, el 95% en Luimonteago y el 25% en Oliveiras Gold de Portugal. **Cada empresa es un nuevo hilo del que tirar**: socios comerciales, clientes, etc.."

**(Diapositiva 14-16: Publicación de Actos Societários)**

"Las publicaciones de actos societarios del Ministerio de Justicia son otra mina de oro. A través de estos registros, obtenemos datos cruciales que antes no teníamos, como su número de identificación fiscal (NIF) y, muy importante, su dirección personal en Espinho. Una dirección es un identificador casi único que nos puede abrir muchas puertas."

**(Diapositiva 17-19: Profundizando en SP&M)**

"Vamos a centrarnos en el bufete de abogados, SP&M. Usando portales de información de empresas como 'einforma', descubrimos que el nombre anterior de la firma era 'SOUSA PINHEIRO & MONTENEGRO'. También obtenemos la dirección de la oficina, lo que nos permite buscar otras empresas en la misma ubicación.

Con herramientas como la Wayback Machine, podemos encontrar versiones antiguas del sitio web del bufete. Así es como descubrimos una dirección de correo electrónico, lmontenegro@spm-advogados.com, y confirmamos su número de colegiado, aunque ahora está inactivo. **Recuerden 'waybackear' todo**. Ahora nuestro perfil de la persona está mucho más completo, incluyendo su email y número de colegiado."

**(Diapositiva 20-21: Portal BASE y Contratos Públicos)**

"Ahora que tenemos el NIF de la empresa, podemos buscar contratos públicos en el 'Portal BASE'. Y aquí es donde las cosas se ponen interesantes. Descubrimos que la firma SP&M, de la que Montenegro era socio al 50%, obtuvo contratos públicos por valor de más de 800.000 euros con entidades como el Municipio de Espinho, donde él había sido concejal y presidente de la asamblea municipal."

**(Diapositivas 22-26: Nuevas Empresas - Semanário Expresso)**

"Una investigación periodística del semanario Expresso reveló la existencia de otra empresa, Spinumviva, Lda, donde Montenegro tenía una participación del 62.5%. Esto no estaba en el registro de intereses inicial."

**(Diapositivas 27-29: Actualizando el Perfil)**

"Con la información de esta nueva empresa, actualizamos nuestro perfil. Ahora conocemos los nombres de sus hijos y una nueva dirección en Espinho. Más importante aún, encontramos un nuevo correo electrónico, spinumviva@gmail.com, y un número de teléfono. La automatización de tareas en este punto es fundamental para procesar y correlacionar toda esta nueva información."

**(Diapositivas 30-31: Códigos de Actividad y Línea de Tiempo)**

"Analizando los códigos de actividad económica (CAE) de sus empresas, vemos una diversidad de intereses: consultoría, viticultura y negocios inmobiliarios.

Al organizar toda la información en una línea de tiempo, la historia se vuelve clara. Vemos cómo registra la empresa Spinumviva con su familia justo después de perder una elección interna del partido. Luego, se convierte en presidente del partido, renuncia a la gerencia de la empresa y sus hijos asumen ese rol. Finalmente, se convierte en Primer Ministro, y poco después, el gobierno colapsa."

**(Diapositiva 32: Conclusión)**

"Para concluir, este caso demuestra el poder de OSINT para transformar datos públicos dispersos en inteligencia accionable. Siguiendo estos pasos, cualquiera con acceso a internet podría haber reconstruido la información que llevó al escándalo que derribó al gobierno de Portugal.

La lección más importante es que, en una era de transparencia, **los negocios privados no pueden escapar del escrutinio público cuando OSINT entra en juego**."

**(Diapositivas 33-35: Herramientas y Siguientes Pasos)**

"Aquí tienen una lista de los portales y herramientas que se utilizaron en esta investigación, desde portales gubernamentales y registros de empresas hasta herramientas de archivo web.

El camino a seguir es claro: necesitamos mapear a las personas y entidades clave, trazar sus conexiones financieras y, sobre todo, exigir transparencia a todos los políticos y servidores públicos."

**(Diapositiva 36: Preguntas)**

"Muchas gracias por su atención. Ahora estaré encantado de responder a sus preguntas."

---