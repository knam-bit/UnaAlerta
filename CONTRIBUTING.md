# Contribuindo com o UnaAlerta

Obrigado por contribuir com o **UnaAlerta — Sistema de Monitoramento Preventivo do Rio Una em Palmares-PE**.

Este documento define as regras de desenvolvimento, organização das branches, commits, Pull Requests, Code Review e resolução de conflitos do projeto.

O objetivo é manter o projeto organizado, facilitar o trabalho em equipe e registrar corretamente o histórico de desenvolvimento no GitHub.

---

## 1. Sobre o projeto

O **UnaAlerta** é um projeto acadêmico desenvolvido para apresentar informações de forma simples e visual sobre:

* nível do Rio Una;
* níveis de risco;
* possíveis pontos de alagamento;
* histórico de ocorrências;
* orientações preventivas.

> **Importante:** os dados apresentados pelo sistema são simulados para fins acadêmicos e não representam dados oficiais ou monitoramento em tempo real.

---

# 2. Equipe

| Integrante              | Função                                       |
| ----------------------- | -------------------------------------------- |
| **Ketsoanny Nathielly** | Gerente do Projeto, Front-end e Documentação |
| **Ana Beatriz Costa**   | Front-end e Interface                        |
| **Fabio Mateus**        | JavaScript e Funcionalidades                 |
| **Analy Samara**        | Testes e Code Review                         |

## Gerente do Projeto

**Ketsoanny Nathielly**

Responsável por:

* organizar o projeto;
* acompanhar os prazos;
* dividir as tarefas;
* acompanhar as branches;
* acompanhar Pull Requests;
* auxiliar na resolução de conflitos;
* desenvolver o Front-end;
* manter a documentação;
* organizar o README;
* manter o CHANGELOG;
* manter o CONTRIBUTING;
* desenvolver o relatório;
* acompanhar o fluxo de Git e GitHub.

---

# 3. Tecnologias utilizadas

O projeto utiliza:

* HTML5;
* CSS3;
* JavaScript;
* Git;
* GitHub.

---

# 4. Organização das branches

A branch `main` representa a versão principal e estável do projeto.

Não é recomendado desenvolver funcionalidades diretamente na `main`.

## Branch principal

```text
main
```

É utilizada para armazenar versões revisadas e integradas do projeto.

## Branches de funcionalidade

Para desenvolver uma nova funcionalidade:

```text
feature/nome-da-funcionalidade
```

Exemplos:

```text
feature/estrutura-inicial
feature/alertas
feature/mapa-risco
feature/historico
```

## Branches de documentação

Para alterações na documentação:

```text
docs/nome-da-documentacao
```

Exemplos:

```text
docs/documentacao-inicial
docs/atualiza-readme
docs/relatorio
```

## Branches de correção

Para corrigir problemas:

```text
hotfix/nome-da-correcao
```

Exemplo:

```text
hotfix/corrigir-alerta
```

## Branches de testes

Quando necessário, podem ser utilizadas:

```text
test/nome-do-teste
```

Exemplo:

```text
test/teste-alertas
```

---

# 5. Fluxo de desenvolvimento

O desenvolvimento deve seguir este fluxo:

```text
Criar branch
      ↓
Desenvolver
      ↓
Fazer commits
      ↓
Enviar branch para o GitHub
      ↓
Criar Pull Request
      ↓
Code Review
      ↓
Correções, se necessário
      ↓
Aprovação
      ↓
Merge
      ↓
main
```

Esse processo permite registrar as etapas do desenvolvimento e facilita o trabalho colaborativo.

---

# 6. Criando uma nova branch

Antes de iniciar uma funcionalidade, crie uma nova branch.

Exemplo:

```bash
git checkout -b feature/alertas
```

Depois do desenvolvimento, envie a branch para o GitHub:

```bash
git push -u origin feature/alertas
```

---

# 7. Padrão de commits

Os commits devem ser pequenos, objetivos e descrever claramente o que foi alterado.

Utilizamos os seguintes prefixos:

| Prefixo     | Utilização                    |
| ----------- | ----------------------------- |
| `feat:`     | Nova funcionalidade           |
| `fix:`      | Correção de erro              |
| `docs:`     | Documentação                  |
| `style:`    | Alterações visuais/formatação |
| `test:`     | Testes                        |
| `refactor:` | Refatoração do código         |

## Exemplos

### Nova funcionalidade

```text
feat: adiciona pagina de alertas
```

### Correção

```text
fix: corrige botao de alerta
```

### Documentação

```text
docs: atualiza README
```

### Estilo

```text
style: ajusta layout da pagina inicial
```

### Testes

```text
test: adiciona testes da pagina de alertas
```

### Refatoração

```text
refactor: organiza codigo do sistema de alertas
```

---

# 8. Boas práticas para commits

Os commits devem:

* realizar uma alteração específica;
* possuir uma mensagem clara;
* evitar alterações desnecessárias;
* não misturar várias funcionalidades diferentes;
* facilitar a identificação das mudanças.

### Evite

```text
mudanças
```

```text
teste
```

```text
coisas novas
```

### Prefira

```text
feat: adiciona pagina de historico
```

ou:

```text
fix: corrige exibicao do nivel de risco
```

---

# 9. Pull Requests

Toda funcionalidade desenvolvida em uma branch deve ser enviada para análise através de um **Pull Request (PR)**.

Exemplo:

```text
feature/alertas
        ↓
Pull Request
        ↓
main
```

O Pull Request deve informar:

* o que foi desenvolvido;
* quais arquivos foram alterados;
* quais problemas foram corrigidos;
* quais testes foram realizados;
* se existe alguma observação importante.

## Exemplo de título

```text
feat: adiciona sistema de alertas
```

## Exemplo de descrição

```text
## O que foi feito?

- Criada a página de alertas.
- Adicionados níveis de risco.
- Criada identificação visual dos níveis.

## Testes realizados

- Verificada a navegação da página.
- Verificados os botões.
- Verificada a exibição dos níveis de risco.

## Observações

Os dados utilizados são simulados para fins acadêmicos.
```

---

# 10. Code Review

Antes do Merge, o código deve ser analisado por outro integrante da equipe.

O objetivo do Code Review é verificar:

* se a funcionalidade está funcionando;
* se existem erros;
* se o código está organizado;
* se os nomes utilizados são claros;
* se a alteração está relacionada à tarefa;
* se a documentação necessária foi atualizada.

O responsável pelo Code Review pode:

* aprovar o Pull Request;
* solicitar alterações;
* comentar pontos específicos;
* informar possíveis problemas.

---

# 11. Aprovação do Pull Request

Após o Code Review, caso não existam problemas importantes, o Pull Request poderá ser aprovado.

Fluxo:

```text
Pull Request
     ↓
Code Review
     ↓
Aprovado
     ↓
Merge
     ↓
main
```

Caso sejam encontradas falhas, o responsável pela branch deverá realizar as correções antes do Merge.

---

# 12. Resolução de conflitos

Conflitos podem acontecer quando duas pessoas modificam a mesma parte de um arquivo.

Quando ocorrer um conflito, os integrantes devem:

1. identificar os arquivos em conflito;
2. analisar as alterações;
3. conversar com os responsáveis pelas alterações;
4. decidir qual código deve permanecer;
5. corrigir o conflito;
6. testar novamente o sistema;
7. realizar um novo commit;
8. atualizar o Pull Request.

Exemplo:

```bash
git pull origin main
```

Após resolver os conflitos:

```bash
git add .
git commit -m "fix: resolve conflito de merge"
git push
```

---

# 13. Hotfix

Correções urgentes podem utilizar uma branch `hotfix`.

Exemplo:

```bash
git checkout -b hotfix/corrigir-alerta
```

Após realizar a correção:

```text
fix: corrige botao de alerta
```

Depois:

```text
Hotfix
   ↓
Commit
   ↓
Pull Request
   ↓
Code Review
   ↓
Merge
   ↓
main
```

---

# 14. Testes

Antes de solicitar o Merge, o responsável pela alteração deve verificar se:

* a página abre corretamente;
* os links funcionam;
* os botões funcionam;
* os elementos aparecem corretamente;
* não existem erros no navegador;
* o layout funciona em diferentes tamanhos de tela;
* a alteração não prejudicou outras páginas.

Os testes realizados devem ser descritos no Pull Request quando forem relevantes.

---

# 15. Organização dos arquivos

A estrutura principal do projeto é:

```text
UnaAlerta/
│
├── index.html
├── alertas.html
├── mapa.html
├── historico.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
└── RELATORIO.md
```

Cada integrante deve evitar criar arquivos desnecessários ou modificar arquivos que não estejam relacionados à tarefa.

---

# 16. Documentação

As alterações importantes no projeto devem ser acompanhadas de documentação quando necessário.

Os principais documentos são:

### README.md

Apresenta o projeto e explica como utilizá-lo.

### CONTRIBUTING.md

Apresenta as regras para contribuição e desenvolvimento.

### CHANGELOG.md

Registra as alterações realizadas nas versões do projeto.

### RELATORIO.md

Apresenta o desenvolvimento acadêmico do projeto.

---

# 17. Dados simulados

O UnaAlerta possui finalidade acadêmica.

Por isso, informações que não forem provenientes de fontes oficiais devem ser identificadas como **simuladas**.

Não devemos apresentar dados simulados como se fossem informações oficiais do Rio Una.

Exemplo:

```text
Dados simulados para fins acadêmicos.
```

---

# 18. Integridade das informações

Os integrantes devem evitar:

* inventar dados e apresentá-los como oficiais;
* copiar código sem verificar seu funcionamento;
* apagar alterações de outros integrantes sem comunicação;
* realizar alterações diretamente na `main` sem necessidade;
* fazer commits com mensagens que não expliquem a alteração;
* inserir informações falsas no sistema ou relatório.

---

# 19. Comunicação da equipe

Antes de realizar uma alteração que possa afetar o trabalho de outro integrante, a equipe deve comunicar a mudança.

Quando houver conflito entre tarefas, a decisão deve ser registrada e alinhada com a **Gerente do Projeto**.

A comunicação deve ajudar a evitar:

* trabalho duplicado;
* conflitos desnecessários;
* perda de código;
* alterações incompatíveis;
* atrasos no projeto.

---

# 20. Responsabilidades da equipe

### Ketsoanny Nathielly

**Gerente do Projeto / Front-end / Documentação**

Responsável por organização, acompanhamento, documentação e desenvolvimento do Front-end.

### Ana Beatriz Costa

**Front-end e Interface**

Responsável pelas páginas, estilos, navegação e responsividade.

### Fabio Mateus

**JavaScript e Funcionalidades**

Responsável pelas interações e funcionalidades implementadas em JavaScript.

### Analy Samara

**Testes e Code Review**

Responsável pela realização dos testes, identificação de problemas e revisão do código.

---

# 21. Regra principal

Antes de fazer qualquer alteração importante:

```text
1. Entender a tarefa
2. Criar uma branch
3. Desenvolver
4. Testar
5. Fazer commit
6. Enviar para o GitHub
7. Criar Pull Request
8. Realizar Code Review
9. Corrigir problemas, se necessário
10. Fazer Merge
```

---

# 22. Objetivo do fluxo

O fluxo definido neste documento tem como objetivo:

* organizar o trabalho em equipe;
* manter o histórico do projeto;
* facilitar a identificação das alterações;
* permitir revisão do código;
* reduzir erros;
* demonstrar o uso correto do Git e GitHub;
* facilitar a apresentação do processo de desenvolvimento.

---

## 23. Status

Este documento faz parte da documentação oficial do projeto **UnaAlerta** e poderá ser atualizado conforme o desenvolvimento do sistema.

**Projeto:** UnaAlerta
**Finalidade:** Acadêmica
**Repositório:** GitHub
**Branch principal:** `main`
