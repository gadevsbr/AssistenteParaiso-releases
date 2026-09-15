# Assistente Paraíso — Distribuição

Repositório público exclusivo para distribuir binários e instaladores do Assistente Paraíso no Termux. O código-fonte, configurações, bancos, sessões do WhatsApp e dados operacionais não são publicados aqui.

## Instalação ARMv7 (`armeabi-v7a`)

```bash
mkdir -p ~/instalador-paraiso
curl -fL -o ~/instalador-paraiso/instalador.tar.gz https://github.com/gadevsbr/AssistenteParaiso-releases/releases/download/v0.7.0-alpha.3/termux-installer-armv7-v0.7.0-alpha.3.tar.gz
tar -xzf ~/instalador-paraiso/instalador.tar.gz -C ~/instalador-paraiso
cd ~/instalador-paraiso && bash install-release-termux.sh
```

Depois da instalação, use `hotel-room-bot-update` para buscar versões novas sem login no GitHub. Todos os downloads são verificados por `SHA256SUMS.txt` antes da troca do executável.