# esp32cam-basic

# Configurando o ESP32-CAM no Arduino IDE

Este guia mostra como instalar o **Arduino IDE** e configurar o **ESP32 / ESP32-CAM** para começar a programar rapidamente.

## Pré-requisitos

* Computador com **Windows, Linux ou macOS**
* Cabo **USB**
* Programador **MB (FTDI / USB–Serial)**
* Placa **ESP32-CAM**
* Conexão com a internet

## Instalando a IDE Arduino

A instalação da **Arduino IDE** é simples e rápida.

1. Acesse o site oficial da Arduino:
   👉 [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

2. Faça o download da versão compatível com o seu sistema operacional.

3. Execute o instalador e siga os passos padrão.

Após a instalação, você poderá programar **Arduino**, **ESP32** e **ESP32-CAM** sem problemas.

## Conectando o ESP32-CAM ao computador

1. Conecte o **programador MB** ao **ESP32-CAM**.
2. Em seguida, conecte o programador ao computador usando um **cabo USB**.
3. Abra o **Arduino IDE**.

> ⚠️ Atenção: certifique-se de que o ESP32-CAM está corretamente alimentado (5V) e com os pinos conectados corretamente.

## Instalando o pacote da placa ESP32 no Arduino IDE

Se você ainda **não tem o ESP32 instalado** no Arduino IDE, siga os passos abaixo.

### Passo a passo

1. No Arduino IDE, vá em:
   **Arquivo → Preferências**

2. No campo **“URLs Adicionais do Gerenciador de Placas”**, insira o seguinte endereço:


https://dl.espressif.com/dl/package_esp32_index.json


3. Clique em **OK** para salvar.

## Instalando a placa ESP32

1. Vá em:
   **Ferramentas → Placa → Gerenciador de Placas**

2. Pesquise por **ESP32**.

3. Selecione **“esp32 by Espressif Systems”**.

4. Clique em **Instalar** e aguarde a conclusão.

## Selecionando a placa correta

Após a instalação:

1. Vá em **Ferramentas → Placa**

2. Selecione o modelo adequado, por exemplo:

   * **AI Thinker ESP32-CAM** (mais comum)

3. Em **Ferramentas → Porta**, selecione a porta correspondente ao ESP32.

## Pronto!

Agora seu ambiente está configurado e você já pode:

* Enviar códigos para o **ESP32-CAM**
* Criar projetos de **IoT**
* Trabalhar com **câmera, Wi-Fi, MQTT, WebServer**, entre 
