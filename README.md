# Robot-Study

Repositório de estudos e práticas com **Robot Framework**, criado para exercitar automação de testes no padrão **BDD**, organização de cenários, escrita de keywords reutilizáveis e validação de fluxos automatizados.

## Objetivo

O objetivo deste projeto é consolidar conhecimentos em automação de testes com Robot Framework, aplicando boas práticas de escrita, organização e manutenção de testes automatizados.

Este repositório demonstra conhecimentos úteis para atuação em **QA**, **QA Automation** e **Analista de Testes**, incluindo:

- Criação de cenários de teste automatizados.
- Uso de keywords reutilizáveis.
- Organização de suítes de teste.
- Escrita de testes legíveis e orientados a comportamento.
- Estruturação de testes no padrão BDD.
- Execução e análise de resultados de testes.

## Tecnologias e ferramentas

- Robot Framework
- Python
- BDD
- Test Automation
- QA
- Git
- GitHub

## Estrutura sugerida do projeto

```text
Robot-Study/
├── tests/
│   └── arquivos_de_teste.robot
├── resources/
│   └── keywords.robot
├── results/
│   └── relatorios_de_execucao
├── README.md
└── requirements.txt
```

## Como executar

### 1. Clonar o repositório

```bash
git clone https://github.com/Matheus-HX-Alves/Robot-Study.git
cd Robot-Study
```

### 2. Criar ambiente virtual

```bash
python -m venv venv
```

### 3. Ativar ambiente virtual

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

### 4. Instalar dependências

```bash
pip install robotframework
```

Caso exista um arquivo `requirements.txt` no projeto:

```bash
pip install -r requirements.txt
```

### 5. Executar os testes

```bash
robot tests/
```

## Relatórios

Após a execução, o Robot Framework gera arquivos de resultado automaticamente, como:

- `log.html`
- `report.html`
- `output.xml`

Esses arquivos ajudam na análise da execução, identificação de falhas e documentação dos testes realizados.

## Boas práticas aplicadas

- Separação entre cenários de teste e keywords reutilizáveis.
- Escrita de testes claros e objetivos.
- Organização de arquivos por responsabilidade.
- Uso de nomes descritivos para facilitar manutenção.
- Estrutura compatível com evolução para testes regressivos e integração contínua.

## Próximas melhorias

- Adicionar exemplos completos de testes automatizados.
- Criar arquivo `requirements.txt` com as dependências do projeto.
- Adicionar prints ou GIFs da execução dos testes.
- Incluir exemplos de relatórios gerados pelo Robot Framework.
- Configurar pipeline com GitHub Actions para execução automática dos testes.
- Expandir os cenários para fluxos web, API ou regressão.

## Competências demonstradas

- Automação de testes
- Robot Framework
- BDD
- Planejamento de testes
- Organização de cenários
- Qualidade de software
- Testes regressivos
- Documentação técnica

## Autor

Matheus Henrique Xavier Alves  
LinkedIn: https://www.linkedin.com/in/matheusalves22/  
GitHub: https://github.com/Matheus-HX-Alves
