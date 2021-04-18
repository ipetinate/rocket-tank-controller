# Rocket Tank Controller
Aplicativo Android para controle do carrinho de esteira `RoboCore Rocket Tank` ou outro dispositivo que implemente a mesma interface de comunicação do controle.

> Descrição

- O aplicativo tem como objetivo fornecer uma interface amigável e intuitiva para controle de carrinhos movidos a esteira.
- Inicialmente o controle irá fazer a comunicação via bluetooth, eu irei usar um `Módulo Bluetooth HC05 master Slave`, então de início a app será feita para esse dispositivo, caso futuramente eu tenha outros módulos em mão, posso adicionar compatibilidade ao App (caso a comunicação seja diferente também);

---

> Montagem do Rocket Tank

- Em breve...

---


> Funcionalidades

- Controles Direcionais e de Aceleração/Frenagem [`em implementação`]
- Painel para Leitura de Sensores: umidade, proximidade e luz [`futuramente`]
- Acionamento de Lanterna (Led branco) [`futuramente`]
- Setas indicadores (Leds amarelos: esquerda e direita) [`futuramente`]
- Acionamento da garra [`futuramente`]
- Área para visualização de câmera [`futuramente`]
- Buzina [`futuramente`]
- Interface para controle via Módulo WiFi (Lolin NodeMCU CH340G) [`futuramente`]

---

> Sobre o App

- Esse aplicativo implementa a nova API de Composição de UI do Android, o Jetpack Compose, e tem como especificações e requisitos mínimos os itens abaixo:

| Plataforma | Linguagem | UI Composer      | Versão Mínima Requerida        |
| -----------|-----------|------------------|--------------------------------|
| Android    | Kotlin    | Jetpack Compose  | Android 5.0 (Lollipop) [API21] |
