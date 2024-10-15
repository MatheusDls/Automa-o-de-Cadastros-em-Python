# Projeto de Automação Web com Python 🤖

[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Automação para inserção de dados de funcionários em formulário web utilizando Python e bibliotecas de automação.

## 📋 Índice

- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Como Usar](#-como-usar)
- [Observações](#-observações)
- [Dicas](#-dicas)
- [Contribuindo](#-contribuindo)
- [Documentação](#-documentação)

## 🛠️ Tecnologias Utilizadas

* [Python 3.x](https://www.python.org/) - Linguagem de programação principal
* [Pandas](https://pandas.pydata.org/) - Manipulação de dados e leitura de Excel
* [Selenium WebDriver](https://www.selenium.dev/) - Automação web
* [PyAutoGUI](https://pyautogui.readthedocs.io/) - Controle do mouse e interação com a tela
* [Google Chrome](https://www.google.com/chrome/) - Navegador automatizado

## 📦 Pré-requisitos

- Python 3.7 ou superior
- Google Chrome instalado
- Planilha Excel com os dados dos funcionários

## 💻 Instalação

1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Instale as dependências
```bash
pip install pandas pyautogui selenium
```

3. Verifique se o Chrome WebDriver está instalado e compatível com sua versão do Chrome

## 🚀 Como Usar

1. Abra o prompt de comando e execute:
```bash
"C:\Program Files\Google\Chrome\Application\chrome.exe" --remote-debugging-port=9222 --user-data-dir="C:/chrome-automation"
```

2. Certifique-se que seu arquivo "Planilha.xlsx" contenha as seguintes colunas:

| Coluna | Descrição |
|--------|-----------|
| FOLHA | Número da folha do funcionário |
| NOME | Nome completo |
| PIS | Número do PIS |
| CPF | CPF do funcionário |
| ADMISSÃO | Data de admissão |
| FUNÇÃO | Cargo do funcionário |
| DEPARTAMENTO | Setor de trabalho |
| EMAIL | E-mail do funcionário |

## ⚠️ Observações

Colunas e descrição podem ser alterados na planilha conforme for a sua necessidade !

3. Execute o script Python:
```bash
python automacao.py
```

⚠️ Observações
- O script utiliza coordenadas do mouse codificadas (ajuste conforme a sua coordenada)
- Há delays programados para carregamento de página
- A iteração começa da linha 1 do Excel
- Mantenha o navegador em foco durante a execução

## 📝 Dicas

1. **Ajuste de tempo:** Modifique os `time.sleep()` conforme sua conexão
2. **Verificação de XPath:** Confirme se os XPaths correspondem ao seu formulário
3. **Teste inicial:** Comece com poucos registros para validar
4. **Foco da janela:** Não utilize o computador durante a execução

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📚 Documentação

Para mais informações, consulte a documentação oficial das tecnologias:

| Tecnologia | Documentação |
|------------|--------------|
| Python | [Documentação Python](https://docs.python.org/pt-br/3/) |
| Pandas | [Documentação Pandas](https://pandas.pydata.org/docs/) |
| Selenium | [Documentação Selenium](https://www.selenium.dev/documentation/webdriver/) |
| PyAutoGUI | [Documentação PyAutoGUI](https://pyautogui.readthedocs.io/) |
| Chrome DevTools | [Protocolo Chrome DevTools](https://chromedevtools.github.io/devtools-protocol/) |

---

<p align="center">
  Desenvolvido por <a href="https://github.com/seu-usuario">MatheusDLS</a>
</p>
