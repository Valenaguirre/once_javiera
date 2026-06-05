# Análisis y Diseño de Software

---

## El problema de arrancar sin pensar

La mayoría de proyectos de software no fracasan por culpa del código. Fracasan porque nadie se sentó a pensar bien qué se necesitaba antes de empezar. El 66% de proyectos tienen problemas graves y casi siempre la causa es la misma: los requerimientos estaban mal definidos desde el inicio.

La idea clave es esta: el análisis define qué se va a construir, el diseño define cómo, y la programación es el último paso. No el primero.

---

## Análisis

Es la etapa donde se entiende qué necesita el sistema antes de tocar una sola línea de código. Se habla con los usuarios y el cliente, se hacen preguntas, se anotan todos los requerimientos y se documenta todo bien.

Las preguntas típicas son: quién va a usar el sistema, qué tiene que hacer exactamente, qué información maneja y qué restricciones hay de tiempo, plata o tecnología.

El resultado es un documento llamado especificación de requerimientos. Básicamente es el acuerdo de qué se va a hacer.

---

## Diseño

Ya se sabe qué se necesita. Ahora se planea cómo se va a construir. Se decide la arquitectura del sistema, qué módulos va a tener, cómo se conectan entre sí, qué base de datos se usa y cómo va a verse la interfaz.

El resultado son diagramas, prototipos y planos del sistema. Es como dibujar los planos de una casa antes de poner el primer ladrillo.

Primero análisis, después diseño, después código. Siempre en ese orden.

---

## El costo de equivocarse

Hay una regla en ingeniería de software que dice que arreglar un error en el análisis cuesta un peso. En el diseño cuesta diez. Programando cuesta cien. Y si el error llega a producción, cuesta mil o más.

O sea que cada vez que se salta una etapa o se hace a las carreras, el precio de equivocarse se multiplica. Por eso vale la pena tomarse el tiempo de analizar y diseñar bien antes de codear.

---

## Las fases del software

Todo software pasa por estas etapas desde que es una idea hasta que deja de usarse:

1. Análisis de requerimientos — se entiende qué necesita el cliente
2. Diseño — se planea cómo construirlo
3. Implementación — se escribe el código
4. Pruebas — se verifica que todo funcione y no haya errores
5. Despliegue — se entrega y se pone a funcionar de verdad
6. Mantenimiento — se corrigen errores y se agregan cosas nuevas

Cada fase tiene un resultado concreto y no se debería pasar a la siguiente sin terminar la anterior.

---

## Metodologías clásicas

La idea es planificar todo desde el inicio y seguir el plan. Funcionan bien cuando se sabe exactamente qué se necesita y eso no va a cambiar durante el proyecto.

**Cascada** es la más conocida. Las fases van una tras otra y no se vuelve atrás. Es fácil de administrar y tiene documentación completa, pero es muy rígida. Si algo cambia a mitad del proyecto, se complica todo.

**Modelo en V** es básicamente cascada pero cada fase de desarrollo tiene su propia fase de pruebas. Es más confiable en términos de calidad.

**Espiral** hace rondas donde cada vuelta reduce el riesgo y agrega más detalle. Es bueno para proyectos grandes donde hay mucha incertidumbre al inicio.

Estas metodologías se usan en sistemas donde un error puede ser muy grave, como bancos, hospitales o sistemas de aviación.

---

## Metodologías ágiles

En 2001 un grupo de desarrolladores hartos de lo rígido que era todo se reunieron y crearon el Manifiesto Ágil. La idea principal es entregar software funcionando rápido y poder adaptarse cuando las cosas cambian, que siempre cambian.

**Scrum** trabaja en ciclos de 1 a 4 semanas llamados sprints. Hay una reunión diaria de 15 minutos para saber quién hace qué y qué obstáculos hay. Al final de cada sprint se muestra al cliente lo que se construyó.

**Kanban** usa un tablero con columnas de por hacer, haciendo y hecho. La regla es no empezar nada nuevo hasta terminar lo que ya está en curso para no llenarse de trabajo a medias.

**XP o Extreme Programming** es el más técnico. Se programa en pares, se escribe la prueba antes que el código y se está mejorando el código constantemente.

Estas se usan cuando los requerimientos pueden cambiar, el equipo es pequeño o se necesita lanzar rápido y mejorar después.

---

## En resumen

Si los requerimientos son claros y estables, una metodología estructurada funciona bien. Si no se sabe exactamente qué quiere el cliente o todo puede cambiar mañana, algo ágil es mejor opción. Y en cualquier caso, analizar y diseñar antes de programar siempre va a dar mejores resultados que ponerse a codear sin pensar.
