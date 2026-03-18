# Guia de Inicio‌‌‌​‌​‌‌​﻿‍‍‌‍‌​​﻿‍​​﻿‌﻿‌‍​‌​﻿​‌‌‍​﻿​﻿​‌​﻿‍‌​﻿‌‌‌‍‌​‌‍‌‌‌‍​‍​﻿​​​﻿‌‌‌‍‌‍​﻿‍‌

Como empezar con el curso: fork, clone y primeros pasos.

---

## 1. Haz fork del repositorio

1. Ve a [github.com/TodoEconometria/curso-spring-hibernate](https://github.com/TodoEconometria/curso-spring-hibernate)
2. Clic en el boton **Fork** (arriba a la derecha)
3. Deja las opciones por defecto y clic en **Create fork**

!!! tip "Que es un fork?"
    Un fork es una copia del repositorio en TU cuenta de GitHub. Puedes modificarla sin afectar el original.

---

## 2. Clona tu fork

```bash
git clone https://github.com/TU_USUARIO/curso-spring-hibernate.git
cd curso-spring-hibernate
```

Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub.

---

## 3. Configura el upstream

```bash
git remote add upstream https://github.com/TodoEconometria/curso-spring-hibernate.git
```

Esto te permite recibir actualizaciones del repositorio original.

---

## 4. Sincroniza tu fork

Cuando el profesor publique material nuevo:

```bash
git fetch upstream
git merge upstream/main
git push
```

!!! warning "Conflictos"
    Si al hacer `git merge` aparecen conflictos, pide ayuda al profesor. No uses `--force`.

---

## 5. Abre los manuales

Los manuales estan en la carpeta `manuales/`. Empieza por `00_INDICE_CURSO.md`.

```
manuales/
├── 00_INDICE_CURSO.md          # Indice general
├── DIA_06_MANUAL_MAVEN_STREAMS.md
├── DIA_07_MANUAL_MAVEN_PIZZERIA.md
├── DIA_08_MANUAL_MAVEN_AVANZADO.md
└── DIA_09_MANUAL_HIBERNATE_INTRO.md
```

---

## 6. Estructura del repositorio

```
curso-spring-hibernate/
├── manuales/                   # Manuales paso a paso (dias 6-20)
├── pizzeria/                   # Codigo esqueleto de la Pizzeria
│   └── src/com/pizzeria/...    # Java puro (punto de partida)
├── blueprints/                 # 16 proyectos individuales
│   ├── README.md               # Indice de blueprints
│   └── 01_CineEstrella.md ...  # Un blueprint por archivo
├── entregas/                   # Aqui van tus entregas
│   ├── ejercicios/             # Ejercicios diarios
│   └── trabajo_final/          # Trabajo final
├── trabajo_final/              # Enunciado + plantilla
│   ├── README.md               # Instrucciones completas
│   └── plantilla/              # Archivos plantilla para copiar
└── docs/                       # Documentacion del sitio web
```

---

## Herramientas necesarias

| Herramienta | Version | Descarga |
|---|---|---|
| **Java JDK** | 21 (LTS) | [adoptium.net](https://adoptium.net/) |
| **IntelliJ IDEA** | 2024+ | [jetbrains.com](https://www.jetbrains.com/idea/download/) |
| **Maven** | 3.9+ | Incluido en IntelliJ |
| **Git** | 2.40+ | [git-scm.com](https://git-scm.com/downloads) |
| **Postman** | Ultima | [postman.com](https://www.postman.com/downloads/) |
| **DBeaver** | Ultima | [dbeaver.io](https://dbeaver.io/download/) |
| **Docker Desktop** | Ultima | [docker.com](https://www.docker.com/products/docker-desktop/) |
