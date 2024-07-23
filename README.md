# CasinoGame
Contrato para conectar con interfaz y jugar juegos de  casino con Ethereum.

Conexiòn de interfaz: 
Agregar parámetros como se observa en _minimubet (apuesta mínima permitida) y _houseedge (margen de ganancia).
Luego iremos a ver una interfaz para interactuar con el contrato: 
Para ello debes copiar la ABI, en la sección de compilado, esto será un código un tanto largo.
Debes copiar la ABI y reemplaza YOUR_CONTRACT_ABI en app.js 
Luego abrir el HTML en el navegador, index.html
Desde ahí y con MetaMask podras interactuar con el contrato.
Te dejo funciones del contrato: 
 Player: Estructura para almacenar información sobre un jugador.
Bet: Estructura para almacenar información sobre una apuesta.
playerInfo: Mapeo para almacenar información de los jugadores.
bets: Lista de todas las apuestas realizadas.
players: Lista de todas las direcciones de jugadores.
BetPlaced: Emitido cuando se realiza una apuesta.
BetResult: Emitido cuando se determina el resultado de una apuesta.
placeBet: Permite a los jugadores realizar apuestas.
generateRandomNumber: Genera un número aleatorio entre 1 y 10.
distributePrizes: Distribuye los premios a los ganadores.
withdrawFunds: Permite al propietario retirar fondos del contrato.
getBalance: Devuelve el saldo actual del contrato.
receive: Función para recibir Ether directamente.
