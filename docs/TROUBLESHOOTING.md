# 🐛 Solución de Problemas - Realistic Spiders

## Problemas Comunes

### Las arañas no aparecen en el mundo

**Síntomas:**
- No ves arañas incluso de noche
- Comando summon no funciona
- Otros addons funcionan normalmente

**Soluciones:**
1. Verifica que ambos packs estén activados:
   - Ve a Configuración del Mundo
   - Packs de Comportamiento → Verifica "Realistic Spiders BP"
   - Packs de Recursos → Verifica "Realistic Spiders RP"

2. Reinicia Minecraft completamente:
   - Cierra el juego
   - Espera 10 segundos
   - Reabre Minecraft

3. Verifica tu versión:
   ```
   Configuración → Acerca de
   Debe ser 1.21.40 o superior
   ```

4. Usa comandos para spawnear:
   ```
   /summon realistic_spiders:wolf_spider
   ```
   Si funciona, el addon está instalado correctamente.

5. Comprueba la iluminación:
   - Las arañas aparecen en luz baja (< nivel 10)
   - Ve a una cueva o espera a la noche
   - Coloca el mundo en modo Difícil

---

### Texturas vistas incorrectamente

**Síntomas:**
- Las arañas están rosa/magenta (texturas faltantes)
- Texturas distorsionadas o pixeladas
- Colores incorrectos

**Soluciones:**
1. Reinstala el Resource Pack:
   - Desactiva "Realistic Spiders RP"
   - Reinicia el juego
   - Vuelve a activar el pack
   - Reinicia de nuevo

2. Ajusta prioridad de packs:
   - Ve a Packs de Recursos
   - Arrastra "Realistic Spiders RP" hacia arriba
   - Reinicia

3. Limpia caché:
   ```
   Configuración → Almacenamiento
   → Limpiar caché de Minecraft
   ```
   Reinicia el juego

4. Verifica espacio disponible:
   - Mínimo 200MB libres en dispositivo
   - Borra archivos temporales si es necesario

---

### Bajo rendimiento / Lag severo

**Síntomas:**
- FPS muy bajo cuando hay arañas
- Game freeze o stuttering
- Dispositivo se calienta mucho

**Soluciones:**
1. Reduce entidades spawning:
   - En el mundo, ve a Configuración
   - Busca "Spawn" o "Entidades"
   - Reduce spawn rate al 50%

2. Desactiva efectos gráficos:
   - Configuración → Gráficos
   - Desactiva "Partículas"
   - Reduce distancia de renderización
   - Desactiva efectos de sombra

3. Cierra aplicaciones en segundo plano:
   - Cierra navegador, Discord, etc.
   - Libera RAM antes de jugar

4. Reduce calidad gráfica:
   - Configuración → Gráficos
   - Calidad: Baja
   - Suavizado: Desactivado
   - Reflejos: Desactivados

5. Desactiva otros addons temporalmente:
   - Mantén solo Realistic Spiders
   - Prueba rendimiento
   - Si mejora, hay conflicto

6. Especificaciones mínimas recomendadas:
   - RAM: 4GB (mínimo 2GB)
   - CPU: Quad-core 2.5GHz+
   - GPU: 1GB VRAM

---

### Conflicto con otros addons

**Síntomas:**
- Crashes después de instalar
- Comportamiento extraño de otras criaturas
- Efectos visuales raros
- Mundo corrupto

**Soluciones:**
1. Verifica orden de carga:
   ```
   Packs de Comportamiento (en orden):
   1. Vanilla
   2. Realistic Spiders BP
   3. Otros addons de comportamiento
   ```

2. Identifica addon conflictivo:
   - Desactiva todos excepto Realistic Spiders
   - Activa un addon a la vez
   - Prueba después de cada uno
   - Identifica cuál causa conflicto

3. Addons conocidos compatibles:
   ✅ Aquatic Paradise
   ✅ Better Animals Plus
   ✅ Furniture Addon
   ✅ Custom Mobs
   ✅ Paleolithic

4. Addons con conflictos conocidos:
   ❌ Arachnophobia Mod (duplica arañas)
   ❌ Dark Souls Creatures (incompatible IA)
   ❌ Creepy Creatures (comportamiento inestable)

---

### Crash al cargar el mundo

**Síntomas:**
- Error al entrar al mundo
- Pantalla negra y cierre
- Mensaje de excepción

**Soluciones:**
1. Restaura desde backup:
   - Copia de seguridad del mundo
   - Desactiva el addon
   - Carga el backup

2. Regenera chunks problemáticos:
   ```
   /forceload add [x] [y] [z] [x2] [y2] [z2]
   /fill [x] [y] [z] [x2] [y2] [z2] air
   ```

3. Verifica integridad de archivos:
   - Ve a Almacenamiento
   - Busca archivos corruptos
   - Elimina y reinstala addon

4. Datos corruptos:
   - Backup del mundo está en:
   ```
   Windows: %appdata%/Minecraft/saves/[Mundo]
   Mobile: Carpeta de aplicación Minecraft
   ```

---

### Arañas atacan todo el tiempo

**Síntomas:**
- Arañas agresivas incluso en modo pacífico
- Atacan incluso en luz brillante
- No se pueden domesticar

**Soluciones:**
1. Modo Pacífico:
   - Configuración del Mundo
   - Dificultad: Pacífica
   - Las arañas serán completamente inofensivas

2. Construye refugio:
   - Usa bloques fuertes (piedra, hierro)
   - Ilumina bien con antorchas
   - Las arañas evitarán luz intensa

3. Usa pociones:
   - Poción de Resistencia
   - Poción de Velocidad
   - Poción de Fuerza

---

### Telarañas desaparecen muy rápido

**Síntomas:**
- Telarañas se van en segundos
- No hay tiempo para verlas
- No funcionan como trampa

**Soluciones:**
1. Espera hasta la noche:
   - Las telarañas duran más de noche
   - Sistema ligado al ciclo día/noche

2. No destruyas la araña:
   - Si matas la araña, telaraña desaparece
   - Deja la araña en paz

3. Crea zona oscura:
   - Bloquea la luz natural
   - Las telarañas duran más tiempo

---

### Sonidos de araña muy fuertes

**Síntomas:**
- Sonidos de araña muy altos
- Sonidos frecuentes
- Distractores

**Soluciones:**
1. Ajusta volumen:
   ```
   Configuración → Sonido y Volumen
   → Volumen de Jugador: 30-50%
   ```

2. Desactiva sonidos de arañas:
   - Ve a Packs de Recursos
   - Busca opciones de sonido
   - Desactiva sonidos de arañas

3. Usa cascos:
   - Los cascos reducen sonidos ambientales
   - En Minecraft especialmente efectivo

---

### Las arañas no dropean items

**Síntomas:**
- Matas araña pero no cae loot
- Items desaparecen
- Inventario vacío

**Soluciones:**
1. Verifica que mueren correctamente:
   - Usa espada de diamante
   - Ataca varias veces
   - Espera 2 segundos después

2. Recoge items rápidamente:
   - Los items desaparecen después de 5 minutos
   - Camina cerca de items para recoger

3. Problema de permisos:
   - En servidor: verifica permisos
   - En mundo local: reinicia

---

### Comando summon no funciona

**Síntomas:**
- /summon realistic_spiders:wolf_spider no hace nada
- Error de comando desconocido
- Nada aparece

**Soluciones:**
1. Verifica sintaxis exacta:
   ```
   /summon realistic_spiders:wolf_spider
   /summon realistic_spiders:jumping_spider
   /summon realistic_spiders:tarantula
   /summon realistic_spiders:poison_spider
   /summon realistic_spiders:orb_weaver
   /summon realistic_spiders:house_spider
   ```

2. Cheats deben estar activos:
   - Configuración del Mundo
   - Activar Cheats: ON

3. Addon debe estar cargado:
   - Verifica packs activos
   - Reinicia mundo

4. Coordenadas válidas:
   ```
   /summon realistic_spiders:wolf_spider ~ ~ ~
   ^ Te spawnea donde estás
   ```

---

### Mundo se corrompe después de instalar

**Síntomas:**
- Archivos de mundo dañados
- No se puede cargar
- Pérdida de datos

**Prevención:**
1. **SIEMPRE hacer backup antes:**
   ```
   Configuración del Mundo → Copiar Mundo
   ```

2. Instalación correcta:
   - Cierra Minecraft completamente
   - Instala addons
   - Reabre Minecraft
   - Carga mundo lentamente

3. Si ocurre corrupción:
   - Restaura desde backup
   - Desactiva todos los addons
   - Reactiva uno a uno

---

## Obtener Soporte Adicional

### Antes de reportar

Reúne esta información:
1. Versión exacta de Minecraft (ej: 1.21.42)
2. Dispositivo (Windows/Mobile/Xbox/Switch)
3. Otros addons instalados
4. Pasos para reproducir problema
5. Captura de pantalla o video si es posible

### Canales de soporte

📧 **GitHub Issues**
- Abre issue en el repositorio
- Proporciona detalles técnicos
- Incluye logs si es posible

🐛 **Bug Report Format**
```
**Versión:** 1.21.40
**Dispositivo:** Windows 10
**Problema:** [Descripción clara]
**Pasos:**
1. Haz X
2. Luego Y
3. Entonces pasa Z
**Resultado esperado:** [Qué debería pasar]
**Resultado actual:** [Qué pasó]
```

---

## FAQ Rápido

**¿Las arañas pueden entrar a mi casa?**
No si está bien iluminada. Luces brillantes las repelen.

**¿Se pueden domesticar?**
No, siempre serán salvajes. Pero puedes usar leash.

**¿Interfieren con el juego normal?**
No, son completamente opcionales.

**¿Funcionan en mundos antiguos?**
Sí, puedes añadirlas a cualquier mundo existente.

**¿Hay límite de arañas?**
Sí, hay límite de spawning para rendimiento.

**¿Puedo editar las arañas?**
Sí, modificar los archivos .json del addon.

---

¡Si el problema persiste, reporta en GitHub con la máxima información posible! 🕷️
