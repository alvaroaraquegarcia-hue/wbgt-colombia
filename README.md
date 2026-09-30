# WBGT Colombia V1 · SCHO

**Herramienta gratuita para estimar el índice WBGT y evaluar el estrés térmico ocupacional según los criterios de la ACGIH.**
Sociedad Colombiana de Higienistas Ocupacionales (SCHO) · Álvaro Araque García, Comité Académico.

## Acceso

**https://alvaroaraquegarcia-hue.github.io/wbgt-colombia/**

- **iPhone (Safari):** abra el enlace → Compartir → *Añadir a pantalla de inicio*.
- **Android (Chrome):** abra el enlace → menú ⋮ → *Instalar app* o *Añadir a pantalla de inicio*.
- **Computador:** abra el enlace en cualquier navegador.

## Funciones

- **Ciudad (tiempo real):** WBGT estimado ahora y pronóstico por horas para 10 ciudades colombianas, al sol o a la sombra.
- **Cálculo manual:** WBGT a partir de temperatura, humedad, viento y radiación solar propios.
- **Mediciones ISO 7243:** WBGT a partir de Tnw, Tg y Ta medidos con monitor.
- **Evaluación ACGIH:** TLV y Límite de Acción según la carga metabólica, ajuste por vestimenta (CAF) y aclimatación.
- **Historial:** últimos 30 cálculos guardados solo en el dispositivo, exportables a CSV.

## Método

- WBGT exterior = 0,7·Tnw + 0,2·Tg + 0,1·Ta; interior o sombra = 0,7·Tnw + 0,3·Tg (ISO 7243).
- Cuando no hay medición directa, Tnw y Tg se estiman con el modelo de Liljegren et al. (2008), traducido del código de referencia del Argonne National Laboratory.
- TLV = 56,7 − 11,5·log₁₀(M); AL = 59,9 − 14,1·log₁₀(M), con M en vatios (ACGIH).
- Datos meteorológicos: Open-Meteo.com (CC BY 4.0).

Los resultados son estimaciones y no reemplazan la medición en el puesto de trabajo con un monitor WBGT calibrado.

## Referencias

- Liljegren JC, Carhart RA, Lawday P, Tschopp S, Sharp R. Modeling the Wet Bulb Globe Temperature Using Standard Meteorological Measurements. *J Occup Environ Hyg.* 2008;5(10):645-655.
- ISO 7243:2017. Ergonomics of the thermal environment — Assessment of heat stress using the WBGT index.
- ACGIH. TLVs® and BEIs® — Heat Stress and Strain.

## Historial de versiones

- **Versión 1.0 (septiembre 2026):** primera versión oficial SCHO. Motor de cálculo con el modelo de Liljegren e ISO 7243, criterios ACGIH con CAF y aclimatación, pronóstico horario real. Reemplaza el prototipo anterior, que subestimaba el WBGT.

Contacto: alvaroaraquegarcia@hotmail.com
