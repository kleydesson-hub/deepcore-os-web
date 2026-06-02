# 🧊 Deepcore OS - Monitoramento Térmico IoT

O **Deepcore OS** é um sistema de monitoramento inteligente para data centers, focado na otimização de resfriamento líquido através da integração entre hardware embarcado (ESP32) e interfaces de visualização em tempo real.

## 📋 Sobre o Projeto
Este repositório contém a documentação e o código do sistema de monitoramento que rastreia a carga térmica em tempo real. O sistema utiliza sensores de precisão para coletar dados que, processados pelo ESP32, permitem o controle automático de bombas de água e a visualização imediata da temperatura em displays OLED e dashboards web.

## 🛠 Tecnologias e Hardware
- **Microcontrolador:** ESP32 (Wi-Fi/Bluetooth integrado).
- **Sensores:** Sensores de temperatura de alta precisão.
- **Atuação:** Controle de bombas de água via PWM (Pulse Width Modulation).
- **Interface:** Display OLED 0.96" I2C para leitura local.
- **Linguagem:** C++ (Arduino Framework).



## 🚀 Funcionalidades
- **Monitoramento em Tempo Real:** Leitura constante dos sensores térmicos.
- **Resfriamento Dinâmico:** Ajuste da velocidade das bombas de água baseado na temperatura (lógica PID/PWM).
- **Interface Local:** Exibição imediata de dados no display OLED.
- **Conectividade:** Pronto para integração com plataformas de IoT para dashboards remotos.

## 🏗 Arquitetura do Sistema
O sistema funciona seguindo o fluxo:
1. **Coleta:** Sensores captam a temperatura atual.
2. **Processamento:** O ESP32 calcula a necessidade de resfriamento.
3. **Atuação:** O PWM envia o sinal para a bomba de água ajustar a vazão.
4. **Exibição:** O dado é atualizado no display OLED e enviado para o log do sistema.



## 📁 Como Utilizar
1. Clone este repositório.
2. Configure o seu ambiente de desenvolvimento (Arduino IDE ou PlatformIO).
3. Conecte o ESP32 ao computador.
4. Carregue o código contido na pasta `/src`.
5. Garanta que as bibliotecas necessárias para o display e sensores estejam instaladas.

## 🤝 Contribuições
Este é um projeto acadêmico do curso de ADS. Sugestões de melhoria, como a implementação de protocolos MQTT para dashboards em nuvem, são muito bem-vindas!

---
**Desenvolvido por:** Kleydesson
- [LinkedIn](https://www.linkedin.com/in/kleydesson-jos%C3%A9-guinsberg-de-meira-64532a193/)
- [Instagram do Projeto](https://www.instagram.com/deepcoreos_oficial/)
