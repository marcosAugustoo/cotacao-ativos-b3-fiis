# 📈 Coleta de Cotações B3 com Selenium

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Em%20Desenvolvimento-yellow)
![Excel Output](https://img.shields.io/badge/output-.xlsx-success?logo=microsoft-excel)

Projeto que coleta **cotações de ações e FIIs** no site da UOL Economia usando **Selenium com Chrome WebDriver automático (via webdriver_manager)** e salva os dados em um arquivo Excel (`.xlsx`).  

> Não é necessário fazer download manual do ChromeDriver. Ele é gerenciado automaticamente!

---

## 📌 Funcionalidades

- Coleta automatizada de cotações de ativos que tem em sua carteira (ações/FIIs)
- Navegação em modo invisível (`headless`)
- Armazenamento em Excel com data e hora da coleta
- Atualização dinâmica dos dados a cada execução

---

## 🚀 Como executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/coleta-cotacoes-b3.git
   cd coleta-cotacoes-b3
