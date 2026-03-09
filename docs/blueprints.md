# Blueprints — 16 Proyectos Individuales‌‌‌​‌​‌‌​﻿‍‍‌‍​‌​﻿​​​﻿‌​​﻿‍​‌‍​‌​﻿‌‍​﻿​‍​﻿‌‍‌‍‌‍​﻿​​​﻿​‍​﻿​​​﻿‌‌​﻿​‌​﻿‌​‌‍​‍

En los dias 13-14, cada alumno elige **uno** de los 16 blueprints disponibles y construye su propio proyecto con Spring Boot + Hibernate.

!!! warning "Regla importante"
    Cada alumno elige un blueprint **diferente**. Si dos alumnos eligen el mismo, se considera copia.

---

## Lista de Blueprints

| # | Blueprint | Dominio | Entidades principales |
|:---:|---|---|---|
| 01 | [CineEstrella](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/01_CineEstrella_Blueprint.md) | Cine / Peliculas | Pelicula, Sala, Sesion, Entrada |
| 02 | [VacunasSalud](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/02_VacunasSalud_Blueprint.md) | Salud / Vacunacion | Paciente, Vacuna, Dosis, Centro |
| 03 | [AgenciaViajes](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/03_AgenciaViajes_Blueprint.md) | Turismo | Destino, Viaje, Cliente, Reserva |
| 04 | [Mensajeria](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/04_Mensajeria_Blueprint.md) | Logistica | Paquete, Ruta, Repartidor, Entrega |
| 05 | [CarniceriaManolo](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/05_CarniceriaManolo_Blueprint.md) | Comercio | Producto, Proveedor, Pedido |
| 06 | [Ferreteria](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/06_Ferreteria_Blueprint.md) | Comercio | Herramienta, Categoria, Venta |
| 07 | [Impresora3D](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/07_Impresora3D_Blueprint.md) | Fabricacion | Material, Diseno, Impresion |
| 08 | [BarReservas](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/08_BarReservas_Blueprint.md) | Hosteleria | Mesa, Reserva, Cliente, Consumo |
| 09 | [Peluqueria](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/09_Peluqueria_Blueprint.md) | Servicios | Estilista, Servicio, Cita, Cliente |
| 10 | [FutbolPrimera](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/10_FutbolPrimera_Blueprint.md) | Deporte | Equipo, Jugador, Partido, Gol |
| 11 | [EscapeRoom](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/11_EscapeRoom_Blueprint.md) | Entretenimiento | Sala, Enigma, Reserva, Equipo |
| 12 | [Zoo](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/12_Zoo_Blueprint.md) | Zoologico | Animal, Habitat, Cuidador, Visita |
| 13 | [SalaConciertos](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/13_SalaConciertos_Blueprint.md) | Musica | Artista, Concierto, Entrada, Sala |
| 14 | [BibliotecaMariano](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/14_BibliotecaMariano_Blueprint.md) | Biblioteca | Libro, Autor, Prestamo, Socio |
| 15 | [Restauracion](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/15_Restauracion_Blueprint.md) | Restaurante | Plato, Menu, Pedido, Mesa |
| 16 | [BarajaEspanola](https://github.com/TodoEconometria/curso-spring-hibernate/blob/main/blueprints/16_BarajaEspanola_Blueprint.md) | Juegos | Carta, Baraja, Partida, Jugador |

---

## Que incluye cada blueprint?

Cada blueprint define:

- **Dominio:** contexto del proyecto
- **Entidades:** minimo 3, con campos y tipos
- **Relaciones:** `@ManyToOne`, `@ManyToMany`, `@OneToMany`
- **Endpoints REST:** CRUD completo + queries custom
- **Datos iniciales:** sugerencias para `data.sql`

---

## Dominio propio

Si prefieres un dominio que no esta en la lista, puedes proponerlo al profesor. Requisitos:

- Minimo 3 entidades
- Al menos una relacion `@ManyToOne` y una `@ManyToMany`
- CRUD completo con REST
- Aprobacion del profesor antes de empezar
