# PEC3

Hemos usado el LLM Gemini 3.0 Flash Nano Banana para generar la portada de la presentación PowerPoint con el siguiente Promp:
<img width="840" height="651" alt="image" src="https://github.com/user-attachments/assets/68087adb-9504-4173-b144-49dd5b37bdef" />

Hemos convertido el fichero .Rmd proporcionado a lenguaje Python para poder generar las visualizaciones mostradas en la presentación.

# Guión de la Historia
Punto de inicio: La dirección de la cadena hotelera está preocupada por el alto volumen de cancelaciones que han visto que sufrimos.

Presentamos nuestro negocio en la PPT:
- Comenzamos contando que ya ha pasado un tiempo y lo ilustramos con el desarrollo del negocio a lo largo del tiempo -gráfico de líneas con la evolución de reservas de ambos hoteles-.
- Mostramos otra gráfica de múltiples líneas con el número de reservas de los 5 principales paises de origen agrupadas por meses de llegada y un "Otros" donde agrupamos al resto.
- Nuestros principales paises clientes y a qué hotel prefieren acudir -gráfico de barras paralelas con el eje X mostrando el país y el eje Y el porcentaje de preferencia de cada hotel-
- Cómo son nuestros clientes en cada hotel: Agrupamos por cómo vienen agrupados y lo mostramos en un gráfico de tarta.
- Mostramos una visión global del negocio mostrando de mayor a menor los paises con más reservas y un gráfico de barras apiladas con el nº de reservas en cada hotel.
- **Planteamos la pregunta a resolver**: ¿Qué está pasando con las cancelaciones?
1. Quiénes cancelan más reservas -grafíco de barras apiladas con los paises que más cancelan-
2. La tipología de las cancelaciones según el tipo de reserva -barras paralelas para los principales paises según el tipo de reserva-
3. Analizamos cómo la antelación marca una importante diferencia -heatmap con tramos para cada tipo de hotel junto a gráfica de líneas mostrando el tiempo en el eje X y el % de cancelaciones en el eje Y-
4. Concluimos con un gráfico de tarta que muestra como esas altas tasas de cancelación se dan sobre todo en reservas hechas con mucha anticipación, lo que minimiza el problema, da tranquilidad a la dirección sobre el motivo del mismo y a la vez da pie para endurecer/mejorar las condiciones de reserva si pretendemos evitar tan alta tasa de cancelaciones.
