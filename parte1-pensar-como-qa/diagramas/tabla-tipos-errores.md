| Tipo de error | Descripcion                                  | Ejemplo                                            | Riesgo asociado          | Tipo de prueba                    |
| ------------- | -------------------------------------------- | -------------------------------------------------- | ------------------------ | --------------------------------- |
| Funcional     | El sistema no cumple un requisito            | El boton "Guardar" no guarda todos los campos      | Riesgo de incumplimiento | Testing de requisitos             |
| Tecnico       | Error en logica interna del codigo           | Calculo de impuestos con redondeo mal implementado | Riesgo tecnico           | Testing estructural               |
| Integracion   | Modulos que no interactuan correctamente     | API devuelve JSON diferente al esperado            | Riesgo de integracion    | Tests end-to-end                  |
| Performance   | Fallos bajo carga o tiempo de respuesta alto | Checkout colapsa con 500 usuarios                  | Riesgo de estabilidad    | Pruebas de carga                  |
| Seguridad     | Vulnerabilidades o accesos indebidos         | Endpoint sin autenticacion                         | Riesgo de seguridad      | Pentesting / pruebas de seguridad |
