# PRD — guia-restaurantes

## 1. Problema
Los usuarios tienen dificultades para centralizar, descubrir y consultar información organizada de restaurantes (como categorías gastronómicas, ubicación, horarios y reseñas) al elegir dónde comer. Además, se requiere una estructura ordenada para mantener el catálogo de locales sin mezclar responsabilidades ni adelantar módulos restringidos de etapas posteriores.

## 2. Usuarios
- *Visitante / comensal:* Busca, filtra y consulta restaurantes según categoría gastronómica, ubicación, horarios y reseñas.
- *Administrador / gestor de catálogo:* Organiza y actualiza la información del catálogo de restaurantes y sus categorías.

## 3. Alcance
### Incluido en el alcance inicial
- Definición del producto y requisitos base del proyecto (AGENTS.md y docs/PRD.md).
- Consulta, búsqueda y filtrado de restaurantes por categoría gastronómica, ubicación y horarios.
- Visualización de la información detallada del restaurante y sus reseñas.
- Organización del catálogo de locales en la aplicación.

### Fuera del alcance inicial
- Escribir o adelantar el código de src/shared/structures/ ni de src/shared/algorithms/ (correspondientes a las épicas E3 y E4).
- Funcionalidades avanzadas fuera del alcance inicial del Sprint 0.

## 4. Requisitos
### Requisitos funcionales
- *RF-01:* Consultar y listar restaurantes con su información principal.
- *RF-02:* Buscar y filtrar restaurantes por categoría gastronómica, ubicación y horarios.
- *RF-03:* Ver el detalle de un restaurante y consultar sus reseñas.
- *RF-04:* Gestionar y actualizar datos de restaurantes en el catálogo.

### Requisitos no funcionales
- *RNF-01:* Interfaz web clara y sencilla para descubrir y consultar locales.
- *RNF-02:* Organización modular del código y documentación clara y mantenible.
- *RNF-03:* Comprobaciones automáticas (CI) en verde y ejecución estable de la aplicación.

## 5. Funcionalidades y carpeta en src/
- *Catálogo y consulta de restaurantes:* src/modules/restaurants/
- *Búsqueda y filtros (categoría, ubicación, horarios):* src/modules/search/ o src/modules/restaurants/
- *Reseñas de restaurantes:* src/modules/reviews/
- *Componentes e interfaz web:* src/components/ o src/pages/ / src/ui/
- *Utilidades y servicios generales:* src/lib/ o src/services/
- *Estructuras y algoritmos (épicas E3 y E4 — restringidas en esta etapa):* src/shared/structures/ y src/shared/algorithms/