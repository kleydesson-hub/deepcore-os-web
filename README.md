# 🌐 Deepcore OS | Web Interface

Interface de monitoramento web para o sistema de gerenciamento térmico **Deepcore OS**. Este repositório contém o frontend (HTML/CSS) responsável por exibir os dados de temperatura coletados pelo ESP32 e o status do sistema de resfriamento líquido.

## 🚀 Sobre a Interface
Esta interface foi projetada para ser leve, responsiva e de baixa latência, garantindo que o operador possa monitorar o estado do data center em qualquer dispositivo (mobile ou desktop) conectado à rede local do ESP32.

## 🛠 Tecnologias
- **HTML5:** Estrutura semântica e limpa.
- **CSS3:** Design responsivo com interface em modo escuro (Dark Mode).
- **JavaScript:** Atualização assíncrona para monitoramento em tempo real sem necessidade de recarregar a página manualmente.

## 🎨 Funcionalidades da UI
- **Dashboard de Temperatura:** Exibição clara e imediata da temperatura atual (°C).
- **Indicador de Status:** Feedback visual (Normal vs. Alerta) baseado no comportamento do sistema.
- **Design Minimalista:** Focado na legibilidade e na rapidez de acesso às informações críticas.

## 📋 Como funciona a integração
A interface se comunica com o ESP32 via protocolo HTTP. O microcontrolador injeta os dados reais do sensor diretamente no template HTML através de *placeholders* (variáveis), permitindo que o usuário veja a temperatura real do hardware sem a necessidade de um servidor externo robusto.
