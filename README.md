# PROJETO-FINAL - Sistema de Irrigação Automatizado Inteligente

# Dispositivo de Entrada:
* Sensor de Umidade do Solo: Para medir o nível de umidade no vaso da planta.
* Botão: Para acionar um ciclo de irrigação manual ou para calibrar o sistema.

# Periférico Dedicado:
* ADC (Conversor Analógico-Digital): Será utilizado para ler os dados analógicos do sensor de umidade do solo.
* Timer: Para controlar a frequência das leituras do sensor e/ou a duração do acionamento da bomba d'água.
* PWM: Poderia ser usado para controlar a velocidade da bomba d'água ou o brilho de LEDs indicadores, caso queira adicionar mais complexidade.

# Dispositivo de Saída:
* Mini Bomba d'Água: Para realizar a irrigação da planta.
* Display LCD (ou LEDs indicadores): Para mostrar o nível de umidade atual, o status do sistema (ex: "irrigando", "monitorando") ou alertas.
* LEDs: Indicadores visuais de status (ex: LED verde para umidade OK, LED amarelo para umidade baixa, LED azul para irrigando).

# Rotina de Interrupção (ISR):
* Implementada com o botão de acionamento manual. Ao pressionar o botão, uma interrupção seria gerada para executar a rotina de irrigação ou outra função definida.
* Um Timer também pode ser configurado para gerar uma interrupção em intervalos regulares, acionando a rotina de leitura do sensor e verificação da necessidade de irrigação.

# Protótipo Operacional em Bancada:
* O projeto é possível de ser montado em uma protoboard ou bancada com componentes eletrônicos comuns (microcontrolador como Arduino, ESP32, STM32, sensores, atuadores, display) - cheguei a ver alguns modelos e vou iniciar o desenvolvimento em simulador.

# Documentação no GitHub:
* Criação de um repositório contendo o código-fonte, esquemáticos, lista de materiais, e um README.md detalhado explicando o projeto, montagem e funcionamento.

# Vídeo de Apresentação:
* Um vídeo demonstrando o protótipo em funcionamento, explicando suas funcionalidades e os componentes utilizados.
