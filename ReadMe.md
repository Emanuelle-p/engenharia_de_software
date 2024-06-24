## Prova 2
* [Questão 1](#questao1)
* [Questão 2](#questao2)

<a name="questao1"></a>
# Questão 1

**Assunto:** Gerência de Configuração de Software

#### Objetivo
Desenvolver um manual sobre o GitHub, abrangendo desde conceitos básicos até funcionalidades avançadas. Este manual servirá como uma referência prática para usuários iniciantes e intermediários, facilitando o uso da plataforma GitHub para gerenciamento de repositórios e colaboração em projetos.

#### Estrutura do Manual
O manual será dividido em seções, cada uma abordando um aspecto específico do GitHub. As seções incluirão explicações teóricas, exemplos práticos e exercícios para fixação do conteúdo.
#### Seções do Manual

**1. Introdução ao GitHub** <br>
**O que é GitHub?** <br>
GitHub é uma plataforma de em nuvem de compartilhamento e desenvolvimento de códigos e projetos. <br>

* **História e evolução do GitHub** <br>

* **Principais funcionalidades e benefícios** <br>

**2. Configuração Inicial**
* Criando uma conta no GitHub
* Instalando o Git e configurando no GitHub
* Primeiros passos: criando e clonando repositórios

**3. Comandos Básicos do Git**
* Estrutura de um repositório Git
* Iniciando um repositório
* Principais comandos: git init, git add, git commit, git push, git pull
* Gerenciamento de branches

**4. Trabalho Colaborativo**
* Clonando e forkeando repositórios
* Pull requests: como criar e gerenciar
* Revisão de código e merge de pull requests
* Resolvendo conflitos

**5. Funcionalidades Avançadas**
* GitHub Actions: automatizando fluxos de trabalho
* Issues e Projects: gerenciamento de tarefas e projetos
* GitHub Pages: criando sites estáticos com GitHub
* Integrações e APIs

**6. Boas Práticas e Dicas**
* Escrevendo bons commits e mensagens
* Estrutura organizacional de repositórios
* Segurança e permissões
* Uso de templates e arquivos de configuração (.gitignore, README.md)

#### Metodologia
* **Pesquisa e Referências:** Utilização de documentação oficial do GitHub, tutoriais, e livros especializados. </br>
* **Exemplos Práticos:** Inclusão de exemplos reais de uso, com explicações passo a passo. </br>
* **Exercícios:** Atividades práticas para reforçar o aprendizado. </br>
* **Recursos Visuais:** Capturas de tela, diagramas e fluxos para facilitar a compreensão. </br>

#### Ferramentas
* GitHub (obrigatório para prática)
* Editor de texto (VSCode, Sublime Text, etc.)
* Terminal ou Git Bash

#### Avaliação
A avaliação será baseada em:
* **Clareza e Organização:** Estrutura lógica e clareza na apresentação das informações. </br>
* **Completude:** Cobertura abrangente dos tópicos necessários. </br>
* **Praticidade:** Qualidade e relevância dos exemplos e exercícios propostos. </br>
* **Precisão Técnica:** Correção e atualização das informações apresentadas. </br>

#### Referências


<a name="questao2"></a>
# Questão 2

**Assunto:** Gerência de Configuração de Software

Considere trecho de código em C que implementa uma função para verificar se um número é primo:

```
#include <stdio.h>
#include <stdbool.h>

bool ehPrimo(int num) {
    if (num <= 1) {
        return false;
    }
    
    for (int i = 2; i * i <= num; i++) {
        if (num % i == 0) {
            return false;
        }
    }
    
    return true;
}

int main() {
    int numero = 29;
    if (ehPrimo(numero)) {
        printf("%d é primo\n", numero);
    } else {
        printf("%d não é primo\n", numero);
    }
    return 0;
}
```

Utilizando o teste estrutural (também conhecido como teste de caixa branca), responda o que se pede a seguir:

**a)** Qual o grafo de fluxo de controle para este código? </br>
**b)** Quantos caminhos independentes existem neste código? </br>
**c)** Liste todos os caminhos independentes identificados. </br>
**d)** Para cada caminho independente, descreva um caso de teste que garantiria a cobertura desse caminho. </br>
**e)** Quais são as condições lógicas presentes no código? </br>
**f)** Descreva um conjunto mínimo de casos de teste que garantam a cobertura de todas as condições lógicas. </br>
**g)** Descreva os casos de teste usando análise de valor limite considerando que um número primo é aquele que é maior que 1 é divisível apenas por 1 e por ele mesmo. </br>

#### Referências
