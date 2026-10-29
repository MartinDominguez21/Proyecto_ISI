# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como [usuario de la aplicación], quiero [poder filtrar la búsqueda de recetas], para [que estas no supongan un peligro para mi o se adapten mejor a mis condiciones].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Para poder cubrir plenamente todos las maneras de filtro que puede ofrecer la aplicación]

## US-01

**Título:** [Buscar mediante una palabra o frase]

Como [usuario], quiero [poder buscar una receta mediante su nombre], para [encontrar mas fácilmente la receta que se me ha sido recetada].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** [Buscar por ingredientes incluidos]

Como [usuario], quiero [poder buscar recetas filtradas por sus ingredientes incluidos], para [encontrar una receta que se adapte mejor a mis condiciones].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [una coincidencia en el texto], cuando [se realice la busque], entonces [la aplicación mostrara un listado de las recetas coincidentes].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** [Excluir ingredientes]

Como [usuario], quiero [poder buscar recetas y excluir ingredientes], para [evitar ingredientes a los que no sea tolerable].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [una inclusion de todos los ingredientes], cuando [se realice la busqueda], entonces [la aplicación mostrara un mensaje que informara que por incompatibilidad entre ingredientes no existe la receta buscada].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí] | [Sí] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
