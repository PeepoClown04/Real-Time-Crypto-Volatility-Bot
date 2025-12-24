# Real-Time Crypto Volatility Bot ![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

Bot de monitoreo financiero que interactúa con APIs públicas para rastrear activos en tiempo real y emitir alertas instantáneas basadas en condiciones de volatilidad o precio.

## Funcionalidades
- **Conexión API:** Consultas asíncronas a CoinGecko/Binance API.
- **Alertas en Tiempo Real:** Integración con Telegram/Discord para mensajería instantánea.
- **Lógica de Umbral:** Algoritmo simple para detectar cambios porcentuales significativos (Pump/Dump alerts).
- **Seguridad:** Gestión de credenciales mediante variables de entorno (`.env`).

## Stack Tecnológico
- Python 3.x
- Requests / Aiohttp
- Python-telegram-bot
- Python-dotenv

## Configuración
Este proyecto requiere un archivo `.env` con las siguientes variables:
- `API_KEY`
- `TELEGRAM_BOT_TOKEN`
- `CHAT_ID`

## Disclaimer
Este software es para fines educativos y de monitoreo. No constituye asesoramiento financiero.
