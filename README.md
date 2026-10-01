# UnaAlerta 🌊

### Sistema de Monitoramento Preventivo do Rio Una em Palmares-PE

## 📌 Sobre o projeto

O **UnaAlerta** é um projeto acadêmico que propõe um sistema de monitoramento preventivo relacionado ao nível do Rio Una, em Palmares, Pernambuco.

A proposta é desenvolver uma interface web que reúna informações sobre níveis de risco, possíveis pontos de alagamento, histórico de ocorrências e orientações preventivas, facilitando a visualização dessas informações pelos usuários.

O projeto tem finalidade educativa e demonstrativa. Na versão inicial, as informações poderão ser simuladas, sem conexão direta com sensores, estações hidrológicas ou sistemas oficiais de monitoramento.

## 🎯 Problema identificado

A ocorrência de elevações no nível de rios e de alagamentos pode gerar riscos para moradores de áreas vulneráveis. Nesse contexto, a organização e a apresentação de informações preventivas podem contribuir para a conscientização da população.

O UnaAlerta busca demonstrar como uma aplicação web pode organizar essas informações em uma interface acessível e de fácil compreensão.

## 💡 Objetivo geral

Desenvolver um protótipo de sistema web para apresentar informações preventivas relacionadas ao Rio Una, em Palmares-PE.

## 🎯 Objetivos específicos

* Apresentar indicadores demonstrativos do nível do rio.
* Exibir alertas classificados por níveis de risco.
* Representar pontos de atenção e possíveis áreas de alagamento.
* Organizar um histórico demonstrativo de ocorrências.
* Disponibilizar orientações de prevenção e segurança.
* Aplicar boas práticas de desenvolvimento colaborativo com Git e GitHub.
* Praticar organização de equipe e gerenciamento de projeto.

## 🚀 Funcionalidades

* **Página inicial:** apresentação do sistema e acesso às funcionalidades.
* **Painel de alertas:** visualização de estados como normalidade, atenção e alerta.
* **Mapa de risco:** representação visual de pontos de atenção.
* **Histórico de ocorrências:** organização cronológica de registros demonstrativos.
* **Orientações preventivas:** informações gerais de segurança em situações de risco.

> **Atenção:** os alertas e os dados simulados não representam medições oficiais nem devem ser utilizados para tomar decisões reais de segurança. Em uma situação de emergência, consulte os órgãos oficiais competentes.

## 🛠️ Tecnologias utilizadas

* HTML5 — estrutura das páginas.
* CSS3 — estilização e layout.
* JavaScript — interatividade da interface.
* Git — controle de versão.
* GitHub — hospedagem do repositório e colaboração da equipe.

## 📁 Estrutura do projeto

```text
UnaAlerta/
├── index.html
├── alertas.html
├── mapa.html
├── historico.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
└── RELATORIO.md
```

A estrutura poderá ser atualizada conforme o desenvolvimento do projeto.

## ▶️ Como executar

1. Faça o download ou clone este repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.
4. Utilize os menus para navegar pelas páginas disponíveis.

Não é necessário instalar dependências para executar uma versão desenvolvida apenas com HTML, CSS e JavaScript, sem bibliotecas adicionais.

## 🌿 Estratégia de desenvolvimento

O projeto utiliza Git e GitHub para organizar o trabalho em equipe.

### Branch principal

```text
main
```

A branch `main` será destinada às versões integradas e revisadas do projeto.

### Branches de funcionalidades

```text
feature/*
```

Serão utilizadas para desenvolver novas funcionalidades.

Exemplos:

```text
feature/estrutura-inicial
feature/alertas
feature/mapa-risco
feature/historico
```

### Branches de correção

```text
hotfix/*
```

Serão utilizadas para correções urgentes.

Exemplo:

```text
hotfix/corrigir-alerta
```

### Fluxo de desenvolvimento

```text
Branch de desenvolvimento
          ↓
      Commits
          ↓
   Pull Request
          ↓
    Code Review
          ↓
       Aprovação
          ↓
        Merge
          ↓
         main
```

## 📝 Padrão de commits

O projeto adota mensagens inspiradas no padrão Conventional Commits:

* `feat:` — nova funcionalidade.
* `fix:` — correção de erro.
* `docs:` — documentação.
* `style:` — alterações de formatação ou apresentação visual.
* `test:` — testes.
* `refactor:` — reorganização do código sem alteração do comportamento.

### Exemplos

```text
feat: cria página inicial
feat: adiciona painel de alertas
feat: adiciona pontos de risco
style: melhora visual dos alertas
fix: corrige botão de alerta
docs: atualiza README
test: verifica navegação entre páginas
```

## 👥 Equipe

| Integrante              | Função                                            | Responsabilidades                                                                                                                                               |
| ----------------------- | ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ketsoanny Nathielly** | **Gerente do Projeto / Front-end / Documentação** | Gerenciamento e organização do projeto, acompanhamento das atividades, desenvolvimento das páginas, organização visual, documentação e acompanhamento do GitHub |
| **Ana Beatriz Costa**   | **Front-end e Interface**                         | Desenvolvimento das páginas, estilização, navegação e responsividade                                                                                            |
| **Fabio Mateus**        | **JavaScript e Funcionalidades**                  | Implementação das funcionalidades interativas, alertas, botões e recursos do sistema                                                                            |
| **Analy Samara**        | **Testes e Code Review**                          | Testes das funcionalidades, identificação de erros, revisão de código e registro dos resultados                                                                 |

### 👩‍💼 Gerenciamento do projeto

A **Gerente do Projeto, Ketsoanny Nathielly**, será responsável por acompanhar o andamento das atividades, auxiliar na organização das tarefas, acompanhar os prazos, coordenar a documentação e verificar a integração das contribuições da equipe.

O gerenciamento será realizado de forma colaborativa, com o acompanhamento das atividades por meio do GitHub, branches, commits, Pull Requests e Code Reviews.

## 📋 Organização das responsabilidades

### Ketsoanny Nathielly — Gerente do Projeto

* Organizar e acompanhar as atividades da equipe.
* Acompanhar o cronograma do projeto.
* Auxiliar na divisão das tarefas.
* Desenvolver partes do front-end.
* Organizar a documentação.
* Atualizar o `README.md`.
* Atualizar o `CHANGELOG.md`.
* Organizar o `CONTRIBUTING.md`.
* Acompanhar o relatório.
* Acompanhar o fluxo de Pull Requests e branches.

### Ana Beatriz Costa — Front-end e Interface

* Desenvolver páginas do sistema.
* Trabalhar na estrutura HTML.
* Desenvolver estilos utilizando CSS.
* Auxiliar na responsividade.
* Melhorar a organização visual da interface.
* Participar das revisões do código.

### Fabio Mateus — JavaScript e Funcionalidades

* Desenvolver funcionalidades utilizando JavaScript.
* Implementar interações da interface.
* Trabalhar no sistema de alertas.
* Implementar comportamentos dos botões.
* Corrigir problemas relacionados às funcionalidades.
* Participar das revisões do código.

### Analy Samara — Testes e Code Review

* Testar as funcionalidades desenvolvidas.
* Verificar a navegação entre as páginas.
* Identificar erros.
* Registrar problemas encontrados.
* Participar dos Code Reviews.
* Verificar as correções realizadas.
* Auxiliar no registro dos resultados dos testes.

> As responsabilidades apresentadas representam a organização planejada da equipe. As contribuições finais deverão corresponder às atividades efetivamente realizadas por cada integrante.

## 🔀 Pull Requests e Code Review

As funcionalidades desenvolvidas em branches específicas deverão passar por Pull Requests antes de serem integradas à `main`.

Durante o Code Review, outro integrante poderá:

* Verificar o funcionamento da funcionalidade.
* Analisar a organização do código.
* Sugerir melhorias.
* Identificar possíveis problemas.
* Aprovar a alteração após a revisão.

Quando forem solicitadas alterações, o responsável deverá corrigi-las antes da aprovação.

## ⚔️ Resolução de conflitos

Durante o desenvolvimento, alterações realizadas por diferentes integrantes poderão gerar conflitos de integração.

Quando isso acontecer, a equipe deverá:

1. Identificar o conflito.
2. Analisar as alterações realizadas.
3. Escolher o conteúdo que deverá permanecer.
4. Remover os marcadores de conflito.
5. Testar o resultado.
6. Registrar a resolução em um novo commit.

## 🔥 Hotfix

Correções urgentes poderão ser desenvolvidas utilizando branches específicas:

```text
hotfix/nome-da-correcao
```

Após a correção, deverá ser realizado o Pull Request, Code Review, aprovação e merge.

## 📚 Documentação

O projeto possui os seguintes documentos:

* [`README.md`](README.md) — apresentação e informações gerais do projeto.
* [`CHANGELOG.md`](CHANGELOG.md) — histórico de alterações.
* [`CONTRIBUTING.md`](CONTRIBUTING.md) — regras para contribuição.
* [`RELATORIO.md`](RELATORIO.md) — relatório acadêmico do projeto.

## ⚠️ Limitações

O UnaAlerta é um protótipo acadêmico e não constitui um sistema oficial de monitoramento ou alerta de enchentes.

Os dados utilizados na versão demonstrativa poderão ser simulados e não devem ser interpretados como medições oficiais do Rio Una.

O sistema não substitui informações ou alertas emitidos por órgãos oficiais.

## 🎓 Finalidade acadêmica

O UnaAlerta está sendo desenvolvido para fins educacionais, com o objetivo de aplicar conhecimentos de:

* Desenvolvimento web.
* HTML, CSS e JavaScript.
* Controle de versão.
* Git e GitHub.
* Trabalho colaborativo.
* Pull Requests.
* Code Review.
* Documentação.
* Gerenciamento de projeto.

## 📌 Status do projeto

**Em desenvolvimento 🚧**

As funcionalidades serão implementadas progressivamente até a versão final do projeto.

## 📄 Licença

Projeto desenvolvido para fins acadêmicos.
