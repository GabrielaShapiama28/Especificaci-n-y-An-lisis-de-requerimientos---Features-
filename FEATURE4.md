Feature: Experimentación de sensaciones en realidad virtual

Scenario: Experimentación de sensaciones en realidad virtual
  Given que el viajero desea experimentar los sonidos característicos de cada destino turístico
  When seleccione la opción de experiencias sensoriales del destino de interés
  Then será transportado a una experiencia multisensorial
  And se recrearán los sonidos, aromas y sensaciones táctiles característicos del destino turístico
  And el viajero se sentirá inmerso en la atmósfera del lugar
  
Examples:
  | Destino Virtual         | Sonidos Característicos                         | Aromas Característicos         | Sensaciones Táctiles                        |
  | París Virtual           | Murmullo de la ciudad, acordeones               | Cafés y panaderías              | Brisa suave del Sena, textura de adoquines  |
  | Gran Cañón Virtual      | Viento entre las rocas, sonido de aves          | Tierra y vegetación desértica   | Calor del sol, rugosidad de las rocas       |
  | Tokio Nocturno Virtual  | Ruido de la ciudad, anuncios en japonés         | Comida callejera, flor de cerezo| Vibración del metro, superficies urbanas    |
  | Safari en África Virtual| Rugidos de leones, sonidos de la sabana         | Tierra húmeda, plantas silvestres| Calor del sol, textura de la hierba         |
