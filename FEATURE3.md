Feature: Creación de itinerarios personalizados para destinos en realidad virtual

Scenario: Creación de itinerarios personalizados
  Given que el usuario busca explorar un destino específico en realidad virtual
  When seleccione la opción de itinerarios sugeridos del destino de interés
  Then se mostrarán itinerarios prediseñados
  And el usuario tendrá opciones para personalizar el recorrido según sus intereses y la disponibilidad de tiempo

Examples:
  | Destino Virtual         | Itinerario Prediseñado                       | Intereses Personalizados                     | Disponibilidad de Tiempo   | Resultado Personalizado                     |
  | París Virtual           | Tour de Museos y Monumentos                  | Arte y Historia                              | 4 horas                    | Museos destacados y monumentos históricos   |
  | Gran Cañón Virtual      | Caminata por el borde y vistas panorámicas   | Fotografía y Senderismo                      | 3 horas                    | Rutas panorámicas con paradas fotográficas  |
  | Tokio Nocturno Virtual  | Tour de Tecnología y Cultura                 | Tecnología y Vida Nocturna                   | 5 horas                    | Distritos tecnológicos y áreas de entretenimiento nocturno |
  | Safari en África Virtual| Observación de la fauna y flora              | Vida Silvestre y Paisajes                    | 6 horas                    | Zonas de avistamiento de animales y paisajes impresionantes |
