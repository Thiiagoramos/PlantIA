#  Smart Irrigation System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/IoT-00B4D8?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Artificial%20Intelligence-FF6F00?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=android&logoColor=white"/>
</p>

Sistema completo de **irrigação automatizada com diagnóstico de plantas por inteligência artificial**. O sistema coleta dados do solo via sensores, analisa imagens das plantas com IA para identificar problemas de saúde, e exibe tudo em um aplicativo mobile — permitindo monitoramento e controle remoto da irrigação.

---

##  Visão Geral da Arquitetura

```
┌─────────────────────────────────────────────────────┐
│                  SMART IRRIGATION SYSTEM             │
│                                                     │
│  [Sensor de Solo]──┐                                │
│                    ↓                                │
│             [Controlador IoT]                       │
│                    │                                │
│  [Câmera]──────────┤                                │
│                    ↓                                │
│          [IA — Diagnóstico de Imagem]               │
│                    │                                │
│                    ↓                                │
│             [Banco de Dados]                        │
│                    │                                │
│                    ↓                                │
│             [PlantIA API]  ←──→  [App Mobile]       │
└─────────────────────────────────────────────────────┘
```

---

##  Repositórios do Projeto

| Módulo | Repositório | Descrição | Status |
|--------|------------|-----------|--------|
|  API Back-end | [PlantIA-api](https://github.com/Thiiagoramos/PlantIA-api) | API REST Flask que serve os dados de irrigação e diagnósticos | ✅ Disponível |
|  App Mobile | *(em breve)* | Aplicativo de visualização e controle da irrigação | 🚧 Em desenvolvimento |
|  Módulo de IA | *(em breve)* | Análise de imagens para diagnóstico de saúde das plantas | 🚧 Em desenvolvimento |

---

##  Funcionalidades do Sistema

-  **Irrigação automatizada** com base em dados de sensores de solo
-  **Diagnóstico por IA** — identifica doenças e problemas nas plantas via análise de imagem
-  **Monitoramento em tempo real** via aplicativo mobile
-  **Arquitetura modular** — cada componente é independente e se comunica via API

---

##  Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-----------|
| Back-end / API | Python, Flask |
| Inteligência Artificial | IA generativa para análise de imagens |
| Mobile | *(a definir)* |
| Banco de Dados | *(a definir)* |
| IoT / Sensores | *(a definir)* |

---

##  Como Começar

Cada módulo do sistema possui seu próprio repositório com instruções de instalação e execução. Acesse os links na tabela acima e siga o README de cada um.

Para rodar apenas a API localmente, consulte o [README da PlantIA-api](https://github.com/Thiiagoramos/PlantIA-api).

---

##  Motivação

Projeto desenvolvido com o objetivo de unir **IoT**, **Inteligência Artificial** e **desenvolvimento de software** em uma solução prática para agricultura automatizada — reduzindo o desperdício de água e auxiliando no diagnóstico precoce de problemas nas plantas.

---

## 👤 Autor

**Thiago Ramos** — [LinkedIn](https://www.linkedin.com/in/thiago-ramos-a86107279)
