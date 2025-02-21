### Como ejecutar localmente

**1. Clonar repositorio**

`git clone https://github.com/21pele-ipb/Pokemon-TFG.git`

**2. Instalar requisitos**

`pip install -r requirements.txt`.

ES NECESARIO TENER RUST INSTALADO

**3. Configura tu fichero env**

Ejemplo:
```
BATTLE_BOT=safest
WEBSOCKET_URI=wss://sim3.psim.us/showdown/websocket
PS_USERNAME=MyUsername
PS_PASSWORD=MyPassword
BOT_MODE=SEARCH_LADDER
POKEMON_MODE=gen7randombattle
RUN_COUNT=1
```

**4. Ejecución**

`python run.py`