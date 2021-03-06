# Contribuyendo

[Software Carpentry][swc-site] y [Data Carpentry][dc-site] son ​
proyectos de código abierto, y damos la bienvenida a contribuciones 
de todo tipo: nuevas lecciones, correcciones al material existente, 
informes de errores, y las revisiones de los cambios propuestos son 
bienvenidas.

## Acuerdo del Colaborador

Al contribuir, usted acepta que podemos redistribuir su trabajo bajo
[nuestra licencia](LICENCIA.md). A cambio, abordaremos sus problemas 
y / o evaluaremos su propuesta de cambio tan pronto como podamos, y 
ayudarlo a convertirse en miembro de nuestra comunidad. Todos los 
involucrados en [Software Carpentry][swc-site] y 
[Data Carpentry][dc-site]
acepta cumplir con nuestro [código de conducta](CONDUCT.md).

## Cómo contribuir

La forma más fácil de comenzar es presentar un problema para 
contarnos sobre un error ortográfico, algunas palabras incómodas,
o un error fáctico. Esta es una buena forma de presentarte 
y para conocer a algunos de los miembros de nuestra comunidad.

1. Si no tienes una cuenta [GitHub][github], puede [enviarnos comentarios por correo electrónico][contacto]. Sin embargo, podremos responder más rápidamente si usa uno de los otros métodos que se describen a continuación.

2. Si tiene una cuenta [GitHub][github], o están dispuestos a [crear uno][github-join], pero no sé cómo usar Git, puede informar problemas o sugerir mejoras al [crear un problema][nuevo-problema]. Esto nos permite asignar el elemento a alguien y para responder a ella en una conversación abierta.

3. Si te sientes cómodo con Git, y me gustaría agregar o cambiar material, puede enviar una solicitud de extracción (PR). Las  instrucciones para hacer esto son [se incluyen a continuación](# using-github).

## Donde Contribuir

1. Si deseas cambiar esta lección, por favor trabaje en <https://github.com/swcarpentry/git-novice>, que se puede ver en <https://swcarpentry.github.io/git-novice>.

2. Si desea cambiar la lección de ejemplo, por favor trabaje en <https://github.com/swcarpentry/lesson-example>, que documenta el formato de nuestras lecciones y se puede ver en <https://swcarpentry.github.io/lesson-example>.

3. Si desea cambiar la plantilla utilizada para los sitios web del taller, por favor trabaje en <https://github.com/swcarpentry/workshop-template>. La página de inicio de ese repositorio explica cómo configurar sitios web de talleres, mientras que las páginas adicionales en <https://swcarpentry.github.io/workshop-template> proporcionar más antecedentes sobre nuestras elecciones de diseño.

4. Si desea cambiar los archivos de estilo CSS, herramientas, o texto estándar HTML para lecciones o talleres almacenados en `_includes` o` _layouts`, por favor trabaje en <https://github.com/swcarpentry/styles>.

## Qué aportar

Hay muchas maneras de contribuir, de escribir nuevos ejercicios y
mejorar los existentes para actualizar o completar la documentación y
enviando [informes de error][nuevo-problema] sobre cosas que no
funcionan, no son claras o faltan. Si estás buscando ideas, por favor
vea [la lista de problemas para este repositorio][issues], o los 
problemas para [Data Carpentry][dc-issues] y 
[Software Carpentry][swc-issues] proyectos.

Los comentarios sobre problemas y revisiones de solicitudes de
extracción son igualmente bienvenidos: somos más inteligentes juntos
de lo que somos solos. Los comentarios de principiantes y recién 
llegados son particularmente valiosos: es fácil para las personas
que han estado usando estas lecciones por un tiempo olvidar lo 
impenetrable que puede ser parte de este material, por lo que los 
ojos frescos son siempre bienvenidos.

## Qué *No* para contribuir

Nuestras lecciones ya contienen más material de lo que podemos cubrir
en un taller típico, por lo que usualmente * no * buscamos más 
conceptos o herramientas para agregarles. Como una regla, si quieres
presentar una nueva idea, debe (a) estimar cuánto tiempo llevará 
enseñar y (b) explique lo que sacaría para darle espacio. El primero
alienta a los contribuyentes a ser honestos acerca de los requisitos;
el segundo, pensar mucho sobre las prioridades.

Tampoco buscamos ejercicios u otro material que solo se ejecute en 
una plataforma. Nuestros talleres suelen contener una mezcla de 
usuarios de Windows, Mac OS X y Linux; para ser utilizable, nuestras 
lecciones deben correr igualmente bien en las tres.

## Usando GitHub

Si eliges contribuir a través de GitHub, es posible que desee mirar
[Cómo contribuir a un proyecto de código abierto en GitHub][cómo-contribuir].

En breve:

1. La copia publicada de la lección está en la rama `gh-pages` del repositorio (para que GitHub lo regenere automáticamente). Por favor crea todas las ramas de eso, y fusiona la rama `gh-pages` de [repositorio maestro][repo] en la rama` gh-pages` antes de comenzar a trabajar. Por favor, * no * trabaje directamente en su rama `gh-pages`, ya que eso le dificultará trabajar en otras contribuciones.

2. Usamos [GitHub flow] [github-flow] para gestionar los cambios:
    1. Cree una nueva rama en su copia de escritorio de este repositorio para cada cambio significativo.
    2. Cometer el cambio en esa rama.
    3. Empuje esa rama a su tenedor de este repositorio en GitHub.
    4. Envíe una solicitud de extracción desde esa rama al [repositorio principal] [repo].
    5. Si recibe comentarios,
        hacer cambios en su escritorio y enviar a su sucursal en GitHub:
        la solicitud de extracción se actualizará automáticamente.

Cada lección tiene dos mantenedores que revisan problemas y solicitan 
extracción o alentar a otros a hacerlo. Los mantenedores son 
voluntarios de la comunidad, y tener una opinión final sobre lo que 
se fusiona en la lección.

## Otros recursos

Discusión general de [Software Carpentry][swc-site] y 
[Data Carpentry][dc-site] sucede en la 
[lista de distribución de discusiones][lista de discusión], 
a lo cual todos son bienvenidos. También puede 
[contactarnos por correo electrónico][contacto].

[contacto]: mailto:admin@software-carpentry.org
[dc-issues]: https://github.com/issues?q=user%3Adatacarpentry
[dc-lessons]: http://datacarpentry.org/lessons/
[dc-site]: http://datacarpentry.org/
[discuss-list]: http://lists.software-carpentry.org/listinfo/discuss
[github]: http://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[cómo-contribuir]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[nuevo-problema]: https://github.com/swcarpentry/git-novice/issues/new
[issues]: https://github.com/swcarpentry/git-novice/issues/
[repo]: https://github.com/swcarpentry/git-novice/
[swc-issues]: https://github.com/issues?q=user%3Aswcarpentry
[swc-lessons]: http://software-carpentry.org/lessons/
[swc-site]: http://software-carpentry.org/