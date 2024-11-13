Etapa 1: Identificação do Problema na Área de Energia Renovável

Problema: Muitas instalações de energia renovável, como as residenciais com painéis solares, enfrentam dificuldades para monitorar e gerenciar eficientemente a geração e o uso de energia. Em especial, sistemas autônomos sem conexão à internet têm pouca capacidade de ajustar o consumo com base na energia disponível. O desperdício ocorre quando há excesso de geração (por exemplo, em dias ensolarados), mas sem um método para gerenciar e armazenar a energia, ela se perde.
Etapa 2: Solução Proposta com Arduino

Solução: Vamos usar um sistema com Arduino para monitorar em tempo real a energia gerada e o consumo, utilizando sensores e atuadores disponíveis no Wokwi. A ideia é criar um dispositivo que mostre os dados de geração e consumo em uma tela LCD, ajuste o consumo local com base nos níveis de energia e exiba alertas quando a geração está baixa.
Componentes e Circuito

    Arduino Uno ou ESP32 (no Wokwi): Plataforma principal para processamento.
    Sensor de Luz: Simulará a quantidade de luz solar disponível para os painéis solares.
    Sensor de Corrente: Medirá a quantidade de energia consumida.
    Display LCD: Exibirá informações de geração e consumo.
    LEDs: Indicadores visuais (verde para geração suficiente, vermelho para geração insuficiente).
    Atuador (relé): Simula o gerenciamento de dispositivos conectados, ativando-os ou desativando-os conforme a disponibilidade de energia.
