# Prueba REAL TIME openai

Este repositorio es un resultado de un spike para probar la herramienta real time de OpenAI que permite realizar llamadas con IA utilizando el proovedor twilio

## Requisitos:

- Tener una cuenta de OpenAI y su API KEY
- Tener una cuenta de Twilio con un número
- API KEY de twilio
- Visibilizar el endpoint de media stream para que sea consumido de manera externa (Sugerido usar la herramienta ngrok)
- Tener Python instalado


## Comandos para ejecutar

python pruebarealtime.py 

o

python pruebarealtime.py --call=+5732123456789 (para llamadas outbound)

ngrok http 5050 (teniendo ngrok instalado)
