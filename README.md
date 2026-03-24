# Miuva

<p align="center">
  <img src="assets/logos/logo-intesc.png" alt="Intesc" width="340">
</p>

<p align="center">
  Repositorio base para concentrar proyectos, ejemplos, pruebas, documentación y recursos visuales relacionados con <strong>Miuva</strong>.
</p>

---

## ¿Qué es este repositorio?

Este repo será la casa de todo lo que se vaya construyendo alrededor de **Miuva**.

La idea es simple: cada proyecto vive en su propia carpeta y adentro lleva todo lo necesario para que alguien más pueda entenderlo, ejecutarlo, compilarlo, cargarlo y modificarlo sin andar jugando a las adivinanzas.

Nada de código huérfano.  
Nada de archivos regados.  
Nada de “luego acomodo esto”.  
Aquí las cosas entran con estructura o no entran.

---

## Estructura actual

```text
Miuva/
├── assets/
│   └── logos/
│       ├── logo-intesc-300x300.png
│       ├── logo-intesc.png
│       └── logo-intesc.webp
├── 01-hola-mundo/
│   └── .gitkeep
├── .gitignore
└── README.md
```

---

## Primer proyecto

### 01 - Hola Mundo

La carpeta `01-hola-mundo` queda creada como punto de arranque del repositorio.

Por ahora está vacía a propósito, salvo por el `.gitkeep`, porque Git tiene la elegante costumbre de ignorar carpetas vacías. Dramático, pero consistente.

Más adelante, esta carpeta podrá incluir por ejemplo:

```text
01-hola-mundo/
├── README.md
├── src/
├── docs/
├── assets/
├── bin/
└── hardware/
```

---

## Cómo se organizarán los siguientes proyectos

Cada proyecto deberá intentar ser **autónomo**.  
Eso significa que, cuando aplique, debería incluir:

- código fuente
- instrucciones de compilación o carga
- dependencias
- imágenes o diagramas
- notas de conexión
- archivos binarios o salidas generadas, si vale la pena conservarlos
- documentación mínima para que el proyecto se entienda sin contexto externo

Formato sugerido:

```text
nombre-del-proyecto/
├── README.md
├── src/
├── docs/
├── assets/
├── hardware/
├── bin/
└── tools/
```

No todos los proyectos necesitarán todas esas carpetas, pero sí deben respetar la misma lógica: **orden, claridad y reproducibilidad**.

---

## Assets

La carpeta `assets/` guarda recursos compartidos del repositorio.

Por ahora incluye los logos de **Intesc** en distintos formatos:

- `assets/logos/logo-intesc-300x300.png`
- `assets/logos/logo-intesc.png`
- `assets/logos/logo-intesc.webp`

---

## Objetivo

Este repositorio nace para documentar y publicar, de forma ordenada, el avance de proyectos relacionados con Miuva, desde ejemplos básicos hasta desarrollos más completos.

Aquí irán entrando cosas como:

- ejercicios iniciales
- pruebas por módulo
- proyectos completos
- documentación técnica
- recursos gráficos
- material reutilizable para futuras implementaciones

---

## Estado actual

En este momento el repositorio incluye:

- estructura base
- carpeta de assets con logos
- primer proyecto creado: `01-hola-mundo`
- reglas de exclusión en `.gitignore` para evitar basura del sistema y archivos locales innecesarios

Bonito, limpio y sin la porquería clásica que luego aparece en los commits por andar arrastrando el Finder, el editor o media vida de la laptop.

---

## Regla no escrita, pero ahora sí escrita

Si un proyecto entra al repo, debe entrar bien.

Eso significa:

- con nombre claro
- con archivos entendibles
- con una mínima explicación
- y con lo necesario para que no dependa de memoria humana, milagros ni telepatía

Ese es el plan.  
Y ahora sí, desde el inicio.
