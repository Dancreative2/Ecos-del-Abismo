# Ecos del Abismo — prototipo v0.1

RPG de mazmorras en tiempo real. Prototipo web sin dependencias externas, diseñado para probarse en navegador de escritorio o móvil.

## Incluye
- Movimiento en tiempo real con WASD/flechas y controles táctiles.
- Ataque básico, habilidad mágica, maná y pociones.
- Experiencia, subida de nivel y mejora de atributos.
- Nueve mazmorras de dificultad creciente.
- Un jefe al final de cada bloque de tres mazmorras.
- Reclutamiento inicial de Lyra y Brom.
- Interfaz adaptable a móvil.
- Sin instalación, servidor ni librerías externas.

## Ejecutar localmente
Abre `index.html` en un navegador moderno. Para una prueba más fiable, sirve la carpeta con cualquier servidor estático local.

## Publicar con GitHub Pages
1. Crea un repositorio público llamado `ecos-del-abismo` en la cuenta `Dancreative2`.
2. Sube `index.html`, `style.css`, `game.js` y este README a la raíz del repositorio.
3. En GitHub entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
5. Espera a que finalice el despliegue. La URL tendrá normalmente la forma `https://dancreative2.github.io/ecos-del-abismo/`.

## Controles
- Movimiento: WASD o flechas.
- Ataque: barra espaciadora o botón ⚔ Atacar.
- Pulso arcano: E o botón correspondiente; consume 10 de maná.
- Poción: botón de poción.
- En móvil: usa el pad táctil y el botón de ataque.

## Estado y límites del prototipo
Esta versión es una prueba de concepto, no un juego terminado. No incluye guardado persistente, audio, arte final, inventario avanzado, autenticación, clanes ni multijugador en línea. El progreso se reinicia al recargar. El sistema de aliados y las mecánicas de combate están simplificados para validar el ciclo básico.

## Próximos hitos sugeridos
1. Ajustar balance y respuesta del combate.
2. Añadir animaciones, audio y arte original.
3. Guardado local y árbol de habilidades.
4. Misiones de aliados, botín y equipamiento.
5. Backend, cuentas y cooperativo en línea.
