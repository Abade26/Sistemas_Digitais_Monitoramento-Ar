# 🌫️ Sistema IoT de Monitoramento da Qualidade do Ar (ESP8266)

Sistema embarcado para **monitoramento da qualidade do ar em tempo real**, utilizando **sensores MQ-135 e MQ-7**, executando em **ESP8266**, com exibição local em **display OLED** e envio dos dados para **Supabase** e **ThingSpeak** via Wi-Fi.

---

## 🎯 Objetivo do Projeto

Desenvolver um sistema IoT capaz de **coletar, processar, exibir e registrar dados ambientais**, permitindo o acompanhamento remoto da **qualidade do ar** para fins de monitoramento, análise e estudos ambientais.

O projeto simula um cenário real de **Internet das Coisas (IoT)**, integrando hardware, firmware e serviços em nuvem.

---

## ⚙️ Funcionalidades

- 🌫️ Leitura de gases e poluentes com **MQ-135**
- 🔥 Detecção de monóxido de carbono com **MQ-7**
- 📟 Exibição de dados em **display OLED (SSD1306)**
- 📊 Gráfico em tempo real no display
- 📡 Envio de dados para **Supabase (REST API)**
- ☁️ Envio de dados para **ThingSpeak**
- 📶 Conexão Wi-Fi automática
- ⏱️ Envio periódico de dados (intervalo configurável)
- 💡 LED indicador de funcionamento

---

## 🧱 Tecnologias Utilizadas

### 🔌 Hardware
- ESP8266
- Sensor MQ-135 (qualidade do ar)
- Sensor MQ-7 (monóxido de carbono)
- Display OLED SSD1306 (128x64)
- LED indicador
- Fonte 5V

### 💻 Software / Firmware
- Arduino (C/C++)
- ESP8266WiFi
- ESP8266HTTPClient
- Adafruit GFX
- Adafruit SSD1306
- WiFiClientSecure

### ☁️ Cloud
- Supabase (armazenamento dos dados)
- ThingSpeak (visualização e histórico)

---

## 🖥️ Arquitetura do Sistema

[Sensores MQ-135 / MQ-7]
↓
[ESP8266]
[Display OLED Local]
↓
[Wi-Fi Connection]
↓ ↓
[Supabase] [ThingSpeak]