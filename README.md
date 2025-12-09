# BOT ECO HOGAR

Bot Eco Hogar está diseñado para adultos que desean comenzar a reducir
los residuos que generan en casa y combatir la contaminación, pero no
saben por dónde empezar. Este bot ofrece acciones simples, realistas
y aplicables desde el hogar, que generan impacto a través de hábitos
diarios sostenidos en el tiempo.

---

# ¿Qué hace este bot?

Bot Eco Hogar brinda orientación y sugerencias prácticas en cuatro
aspectos principales:

- Reducir la cantidad de basura generada en casa.
- Disminuir el consumo de energía eléctrica.
- Conservar agua de manera responsable.
- Acceder a contenido visual informativo.
- Entender rápidamente qué ofrece cada comando mediante una función de ayuda.

El objetivo es que cualquier persona pueda empezar sin necesidad de
conocimientos técnicos ni grandes inversiones.

---

# Comandos Disponibles

 Comando      Descripción 
 $ayuda       Muestra todos los comandos y su propósito 
 $reducir     Consejos para reducir residuos en el hogar 
 $energia     Acciones para consumir menos electricidad 
 $agua        Estrategias para ahorrar agua 
 $horario     Indica la hora actual 
 $imagen1     Envía imagen informativa #1 
 $imagen2     Envía imagen informativa #2 

---

# Instalación

1. Instala **Python 3.8 o superior**

2. Instala la librería necesaria:
pip install discord.py

3. Crea la carpeta:
/images

4. Coloca dentro los archivos `1.png` y `2.png`

5. Edita la línea final del archivo del bot:
bot.run('your token here')
y reemplázala por tu token real de Discord.

---

# Cómo modificar el bot

## Agregar nuevos consejos
Dentro del archivo del bot encontrarás las listas:
acciones_reduccion = [...]
acciones_energia = [...]
acciones_agua = [...]
Puedes añadir recomendaciones simplemente agregando texto dentro
de estas listas.

## Crear un nuevo comando personalizado
Debajo de los demás comandos añade:
@bot.command()
async def nuevocomando(ctx):
await ctx.send("Mensaje personalizado")

## Cambiar el prefijo del bot
Modifica:
command_prefix="$"
por otro símbolo o palabra, ejemplo:
command_prefix="!"

---

# Objetivo ambiental

Bot Eco Hogar busca facilitar un cambio progresivo en los hogares,
demostrando que pequeñas decisiones, repetidas de forma constante,
pueden disminuir la contaminación, reducir los desechos y generar un
impacto positivo en el planeta.

Este bot es un punto de partida: comenzar es tan simple como un comando,
y cada acción suma.
