# 🌾 Agrinho 2026 | Projeto Agrorobótica & Programação

<p align="center">
  <img src="https://img.shields.io/badge/Agrinho-2026-green?style=for-the-badge" alt="Agrinho 2026">
  <img src="https://img.shields.io/badge/Tema-Campo%20e%20Cidade-orange?style=for-the-badge" alt="Tema">
  <img src="https://img.shields.io/badge/Foco-Inovação%20e%20Sustentabilidade-blue?style=for-the-badge" alt="Foco">
</p>

---

## 📋 Sobre o Projeto
Este repositório contém o código-fonte, a documentação e os esquemas de hardware do protótipo desenvolvido para o **Concurso Agrinho 2026**. O projeto foi concebido sob o tema **"Campo e Cidade: Conexões que transformam"**, buscando aproximar a tecnologia urbana das necessidades reais do produtor rural, otimizando processos e promovendo a sustentabilidade.

## 🎯 Objetivos do Projeto
* **Conectar Campo e Cidade:** Desenvolver uma solução tecnológica que utilize automação e dados para estreitar os laços entre a produção rural e o consumo urbano.
* **Otimização de Recursos:** Minimizar o desperdício de insumos agrícolas (como água, energia ou fertilizantes) através de monitoramento inteligente.
* **Acessibilidade Tecnológica:** Criar um protótipo de baixo custo utilizando materiais alternativos, recicláveis e componentes eletrônicos acessíveis.
* **Sustentabilidade:** Promover práticas agrícolas que respeitem o meio ambiente através da automação consciente.

---

## 🛠️ Tecnologias Utilizadas

### Hardware e Robótica
* **Microcontrolador:** Arduino (UNO/Nano) ou ESP32 (para projetos com IoT).
* **Sensores:** Sensor de umidade do solo (YL-69), sensor de temperatura e umidade do ar (DHT11/DHT22), e sensores ultrassônicos.
* **Atuadores:** Servomotores, mini bombas de água (5V), módulos relé e LEDs indicadores.
* **Estrutura:** Materiais recicláveis (papelão, garrafas PET) combinados com peças de filamento PLA (impressão 3D).

### Software e Programação
* **Linguagem Principal:** C++ (Ambiente Arduino IDE) / Bloco de programação ( Scratch / BitBloq se aplicável).
* **Pensamento Computacional:** Algoritmos de tomada de decisão baseados em leitura analógica e digital dos sensores.
* **Interface (Opcional):** Dashboard em HTML/CSS via rede local (caso use ESP32) ou exibição em Display LCD 16x2.

---

## ⚙️ Recursos Técnicos Implementados

1.  **Leitura Automatizada de Sensores:** Coleta de dados em tempo real sobre as condições climáticas e do solo da plantação.
2.  **Sistema de Irrigação Inteligente (Feedback Loop):** O algoritmo analisa a umidade do solo. Se estiver abaixo do nível crítico, aciona a bomba de água automaticamente; ao atingir o nível ideal, interrompe o fluxo para evitar desperdício.
3.  **Modo de Economia de Energia:** Implementação de rotinas de *Sleep* no código para simular o funcionamento com placas de energia solar no campo.
4.  **Alertas Visuais/Sonoros:** Feedback em tempo real usando LEDs e Buzzers para indicar anomalias no sistema (ex: falta de água no reservatório urbano/rural).

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Para replicar ou testar o código deste projeto, você precisará de:
* [Arduino IDE](https://www.arduino.cc/en/software) instalada.
* Biblioteca `DHT sensor library` instalada na IDE (se usar o sensor DHT).

### Passo a Passo
1. Clone este repositório em sua máquina local:
   ```bash
   git clone [https://github.com/seu-usuario/agrinho-2026.git](https://github.com/seu-usuario/agrinho-2026.git)
