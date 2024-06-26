
Feature: HU01 - Acceso a reseñeas y recomendaciones

Scenario:  Consultar reseñas y recomendaciones de destinos en realidad virtual
 Given que el usuario busca explorar un destino específico en realidad virtual
  When seleccione la opción de reseñas y recomendaciones del destino de interés
  Then se mostrarán las reseñas y recomendaciones de otros viajeros
  And incluirán puntuaciones y comentarios detallados

    Examples:
  | Destino Virtual         | Reseñas Totales | Puntuación Promedio | Comentario Más Útil                                      |
  | París Virtual           | 150             | 4.7                 | "Una experiencia increíble, la recreación es perfecta."  |
  | Gran Cañón Virtual      | 95              | 4.5                 | "La sensación de profundidad es impresionante."          |
  | Tokio Nocturno Virtual  | 200             | 4.8                 | "Me sentí como si realmente estuviera caminando allí."   |
  | Safari en África Virtual| 120             | 4.6                 | "Los detalles de los animales son asombrosos."           |
