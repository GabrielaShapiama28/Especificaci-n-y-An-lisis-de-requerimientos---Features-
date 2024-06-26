Feature: Acceso a entrenamientos de destinos

Scenario: Acceso a entrenamientos de destinos
  Given que el personal necesita conocer los destinos
  When participe en el entrenamiento en VR
  Then explorará virtualmente el destino
  And aprenderá sobre sus características y atractivos principales

Examples:
  | Destino           | Características Aprendidas                                                                 | Atractivos Principales Aprendidos                                                     |
  | París             | "Historia, arquitectura, gastronomía"                                                         | "Torre Eiffel, Louvre, Catedral de Notre Dame"                                        |
  | Gran Cañón        | "Geología, vida salvaje, senderismo"                                                          | "South Rim, North Rim, Colorado River"                                                |
  | Tokio             | "Cultura, tecnología, gastronomía"                                                            | "Tokyo Skytree, Shibuya Crossing, Templo Senso-ji"                                    |
  | Safari en África  | "Fauna, flora, conservación ambiental"                                                        | "Leones, elefantes, jirafas en su hábitat natural"                                    |
