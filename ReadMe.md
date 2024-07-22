## Prova 2
* [Questão 1](#questao1)
* [Questão 2](#questao2)
* [Questão 3](#questao3)

<a name="questao1"></a>
# Questão 1

**Assunto:** Gerência de Configuração de Software

### Objetivo
Desenvolver um manual sobre o GitHub, abrangendo desde conceitos básicos até funcionalidades avançadas. Este manual servirá como uma referência prática para usuários iniciantes e intermediários, facilitando o uso da plataforma GitHub para gerenciamento de repositórios e colaboração em projetos.

### Estrutura do Manual
O manual será dividido em seções, cada uma abordando um aspecto específico do GitHub. As seções incluirão explicações teóricas, exemplos práticos e exercícios para fixação do conteúdo.
### Seções do Manual

**1. Introdução ao GitHub** </br>

**O que é GitHub?** </br>

GitHub é uma plataforma em nuvem de compartilhamento e desenvolvimento de códigos e projetos. Através do sistema Git é possível fazer o controle de versões dadas quaisquer alterações, que inclusive podem ser feitas diretamente na plataforma. Dessa forma, ela facilita a colaboração entre usuários de comunidades open source e entre membros de projetos privados, o que explica a sua popularidade principalmente diante de desenvolvedores de software. </br>

* **História e evolução do GitHub** </br>

Desenvolvido pela empresa GitHub, Inc., que foi fundada em 2007 contando com os membros Chris Wanstrath, Scott Chacon, P. J. Hyett e Tom Preston-Werner, o GitHub foi lançado em 2008. Criado com o objetivo de hospedar código baseado em Git para possibilitar a colaboração de desenvolvedores em seus projetos de software, a sua popularidade foi crescendo ao longo dos anos. Tendo atingido ao final de 2008 33 mil repositórios públicos, hoje ele conta com aproximadamente 300 milhões, gerenciados por mais de 100 milhões de desenvolvedores. <br>

O ano de 2018 foi o marco para a plataforma. Especificamente em junho de 2018 a sua compra foi anunciada pela Microsoft por US$ 7,5 bilhões em ações, o que gerou muitas incertezas pelos usuários quanto ao futuro dela. Contudo, ainda em 2018 a empresa já era um dos principais usuários do GitHub, gerenciando na plataforma que se manteve aberta vários dos repositórios mais ativos e integrando-a a outros serviços dela, tais como o serviço de nuvem Azure. </br>

Infelizmente, graças à sua popularidade, o GitHub acabou se tornando também alvo de ataques. Em fevereiro de 2018 a plataforma passou por um ataque DDoS de 1,35 terabit por segundo, registrando um recorde. A consequência disso foi a paralização dos seus serviços por 6 minutos, conseguindo sair após isso graças à atenuação do ataque pelo serviço Akamai. Contudo, ainda em 2015 o GitHub já havia passado por outro ataque DDoS, com vários acessos a dois projetos que visavam contornar a censura estatal do governo chinês. <br>

* **Principais funcionalidades e benefícios** <br>

O GitHub oferece dentre várias, as seguintes funcionalidades aos repositórios do Git que ele hospeda:
  - **Controle de versão:** através do serviço Git cada atualização no projeto/código é salva, assim se torna possível controlar as versões dele, retornando para uma anterior se for necessário e colaborando com o trabalho de outros usuários.
    
  - **Repositórios:** os projetos são armazenados em repositórios, podendo ser públicos ou privados. Isso permite centralizar as informações sobre o projeto, como a documentação, códigos e demais arquivos relevantes, o que facilita o aceso e organização.
    
  - **Pull requests:** como o próprio nome sugere, se trata de uma sugestão de versão nova, pois qualquer alteração no projeto/código deve ser submetido ao repositório para que ele seja atualizado e os demais usuários tenham acesso à versão nova. Os pull requests podem ser revisados e comentados antes de serem integrados ao projeto principal. Tudo isso facilita a colaboração e funciona como um mecanismo de segurança para que atualizações no projeto principal não sejam feitas antes de serem revisadas.
    
  - **Issues:** funciona como "respostas" ao projeto/código e podem ser criados em um repositório para discutir, planejar e monitorar o fluxo de trabalho. Graças à sua flexibilidade pode ser aplicada em diversos cenários, se adaptando às necessidades do projeto.
    
  - **Branches:** ramificações do projeto principal criadas por questões de organização ou mesmo para correção de erros sem afetar outros branches. Facilita a experimentação e o desenvolvimento paralelo. Por padrão, ao criar um repositório o GitHub gera um branch principal, também chamado de ```main``` ou projeto principal.
    
  - **GitHub Actions:** plataforma do GitHub que possibilita a integração e entrega contínua de um projeto/código através da configuração de fluxos de trabalho, automatização de processos, como compilação, teste e pipeline de implantação. Trata-se de um serviço que visa otimizar o tempo do usuário, como se pode notar nos exemplos apresentados na documentação do GitHub:
    > "É possível criar fluxos de trabalho que criam e testam cada pull request no seu repositório, ou implantar pull requests mesclados em produção." </br>
    
    > Permite a ocorrência simultânea de eventos: "Por exemplo, você pode executar um fluxo de trabalho para adicionar automaticamente as etiquetas apropriadas sempre que alguém cria um novo problema no repositório."
    
  - **Wikis:** seção do repositório que tem o intuito de hospedar a documentação do projeto/código. Isso facilita a organização e acesso à informações pertinentes sobre o projeto/código.
    
  - **GitHub pages:** oferece a oportunidade de ter um site estático hospedado pelo GitHub. É possível utilizar arquivos HTML, JavaScript e CSS diretamente do repositório. Ademais, pode-se utilizar um domínio próprio ou o ```github.io```.
    
  - **Comunidade:** plataforma colaborativa que permite interações entre desenvolvedores de todo o mundo. Promove o compartilhamento de conhecimento, contribuindo para a inovação e o aprendizado contínuo.

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

### Metodologia
* **Pesquisa e Referências:** Utilização de documentação oficial do GitHub, tutoriais, e livros especializados. </br>
* **Exemplos Práticos:** Inclusão de exemplos reais de uso, com explicações passo a passo. </br>
* **Exercícios:** Atividades práticas para reforçar o aprendizado. </br>
* **Recursos Visuais:** Capturas de tela, diagramas e fluxos para facilitar a compreensão. </br>

### Ferramentas
* GitHub (obrigatório para prática)
* Editor de texto (VSCode, Sublime Text, etc.)
* Terminal ou Git Bash

### Avaliação
A avaliação será baseada em:
* **Clareza e Organização:** Estrutura lógica e clareza na apresentação das informações. </br>
* **Completude:** Cobertura abrangente dos tópicos necessários. </br>
* **Praticidade:** Qualidade e relevância dos exemplos e exercícios propostos. </br>
* **Precisão Técnica:** Correção e atualização das informações apresentadas. </br>

### Referências
CAMERON, Dell. O maior ataque DDoS da história foi contra o GitHub, mas o serviço saiu numa boa. Disponível em: https://gizmodo.uol.com.br/github-ataque-ddos/. Acesso em 22 jul. 2024. </br>

GITHUB. *About branches.* Disponível em: https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches#about-the-default-branch. Acesso em 22 jul. 2024. </br>

GITHUB. *About GitHub and Git.* Disponível em: https://docs.github.com/en/get-started/start-your-journey/about-github-and-git. Acesso em 22 jul. 2024. </br>

GITHUB. *About GitHub Pages.* Disponível em: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages. Acesso em 22 jul. 2024. </br>

GITHUB. *About issues.* Disponível em: https://docs.github.com/pt/issues/tracking-your-work-with-issues/about-issues. Acesso em 22 jul. 2024. </br>

GITHUB. *About pull requests.* Disponível em: https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests. Acesso em 22 jul. 2024. </br>

GITHUB. *About wikis.* Disponível em: https://docs.github.com/pt/communities/documenting-your-project-with-wikis/about-wikis. Acesso em 22 jul. 2024. </br>

GITHUB. *Understanding GitHub Actions.* Disponível em: https://docs.github.com/pt/actions/learn-github-actions/understanding-github-actions. Acesso em 22 jul. 2024. </br>

*History of GitHub.* Disponível em: https://pslmodels.github.io/Git-Tutorial/content/background/GitHubHistory.html. Acesso em 22 jul. 2024. </br>

TASHIA, T. *15 most popular GitHub repositories every developer should know.* Disponível em: https://www.hostinger.com/tutorials/most-popular-github-repos#:~:text=Copied!,of%20over%20100%20million%20developers. Acesso em 22 jul. 2024. </br>

LOUZADA, Vinícius. O que é Git e GitHub: os primeiros passos nessas ferramentas. Disponível em: https://www.alura.com.br/artigos/o-que-e-git-github?utm_term=&utm_campaign=%5BSearch%5D+%5BPerformance%5D+-+Dynamic+Search+Ads+-+Artigos+e+Conte%C3%BAdos&utm_source=adwords&utm_medium=ppc&hsa_acc=7964138385&hsa_cam=11384329873&hsa_grp=164068945139&hsa_ad=703934879696&hsa_src=g&hsa_tgt=dsa-1298415354460&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwhvi0BhA4EiwAX25uj4VT5XMEodsNLQth1VAAdqaCyYZeaFgoIP2wDtdORv5PCx14XvzXvxoCWrgQAvD_BwE#o-que-e-github?. Acesso em 22 jul. 2024. </br>

VENTURA, Felipe. O maior ataque DDoS já registrado teve como alvo o GitHub. Disponível em: https://tecnoblog.net/noticias/maior-ataque-ddos-github/. Acesso em 22 jul. 2024. </br>

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

### Referências

<a name="questao3"></a>
# Questão 3
**Assunto:** Gerência de Projeto
**Entrega:** A resposta deverá ser entregue em formato digital PDF e disponibilizada em um repositório público em que o professor possui acesso. O link da resposta deverá ser enviado no SIGAA. </br>

No contexto de gerenciamento de projetos de software, explique o processo de análise de riscos. </br>
Uma empresa de desenvolvimento de software de médio porte precisa desenvolver um software de vendas de pacotes de viagens para uma companhia de turismo. Explique como XP e Scrum podem ser combinados por esta empresa no desenvolvimento de software.
