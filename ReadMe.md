## Prova 2 - Engenharia de Software

Nomes: Emanuelle Passos Martins, Matheus Carlos Lima e Silva </br>

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
* **Criando uma conta no GitHub**
  1. Acesse a página https://github.com/
  2. Clique em **Inscreva-se**.
  3. Siga os prompts para criar sua conta.
  4. Verifique o seu e-mail.
   
  Em caso de dúvidas, [clique aqui](https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github).
     
* **Instalando o Git e configurando no GitHub** </br>

  Há diversas formas de instalar o Git, a depender do sistema operacional da máquina e da ferramenta a ser utilizada. Siga o passo a passo para instalar o Git no **Windows** e no **Linux**. </br>
  Para outros casos, [clique aqui para mais informações na documentação](https://github.com/git-guides/install-git). </br>
  ##### Para Windows:
  Vá ao [site oficial do Git](https://git-scm.com/download/win) e baixe o instalador da última versão para Windows, então execute o instalador. Você pode verificar a instalação através do seguinte comando no terminal (Prompt de comando ou Windows PowerShell):
  ```
  git --version
  ```

  ##### Para Linux:
  No seu terminal de comando rode os seguintes comandos para atualizar a lista de pacotes disponíveis para instalação, instalar o Git e verificar a versão instalada.
  ```
  sudo apt-get update
  sudo apt-get install git-all 
  git --version 
  ```

  Após a instalação, tanto no Windows quanto no Linux pode-se configurar o Git da seguinte forma:
  1. No terminal, rode o código a seguir para configurar o nome de usuário e e-mail:
  ```
  git config --global user.name <Seu nome>
  git config --global user.email <seu-email@exemplo.com>
  ``` 
  2. Verifique se as configurações foram aplicadas corretamente:
  ```
  git config --list
  ```

  Depois disso é possível autenticar-se no GitHub através do Git usando HTTPS ou SSH.
  #### Usando HTTP:
  Conforme a documentação do GitHub:
  > Se você estiver clonando repositórios do GitHub usando HTTPS, recomendamos que use o GitHub CLI ou o Git Credential Manager (GCM) para lembrar suas credenciais. </br>

  Para usar o **GitHub CLI**: </br>
  1. [Instale](https://github.com/cli/cli#installation) o GitHub CLI
  2. No terminal, digite ```gh auth login```
  3. Quando questionado sobre a sua preferência de protocolo no Git, selecione ```HTTP```.
  4. Quando questionado se gostaria de autenticar no Git através das suas credenciais dp GitHub, digite ```Y```.

  Para usar o **Git Credential Manager (GCM)**: </br>
  A instalação do Git inclui o GCM, assim no próximo clone de repositório usando HTTPS, o Git solicitará o login no navegador. Após isso, suas credenciais serão armazenadas e serão utilizadas a cada nova clonagem HTTPS.

  #### Usando SSH:
  1. Gere uma nova chave SSH digitando o seguinte comando no terminal:
  ```
  ssh-keygen -t ed25519 -C <seu-email@exemplo.com>
  ```
  2. Então digite uma frase secreta segura, conforme for requisitado.
  3. Para adicionar sua chave SSH ao agente SSH, inicie-o em uma nova janela do PowerShell com privilégios de administrador:
  ```
  Get-Service -Name ssh-agent | Set-Service -StartupType Manual
  Start-Service ssh-agent
  ```
  4. Adicione sua chave privada SSH ao agente ssh: </br>
     No Windows:
     ```
     ssh-add c:/Users/YOU/.ssh/id_ed25519
     ```
     No Linux:
     ```
     ssh-add ~/.ssh/id_ed25519
     ```
  
  5. [Adicione a chave pública SSH à sua conta GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  
* **Primeiros passos: criando e clonando repositórios** </br>
  Para clonar um repositório:
  1. No GitHub, encontre o repositório que deseja clonar.
  2. Clique em ```Code``` e copie a URL.
  3. Vá para o diretório em que deseja clonar o repositório.
  ```
  cd diretório
  ```
  4. No terminal, digite:
  ```
  git clone <URL>
  ```

  Para criar um repositório Git no GitHub: </br>
  Na [página web](https://github.com/) clique no símbolo ```+```, então em ```Novo repositório```. Indique o nome do repositótio e uma descrição (opcional). Escolha a visibilidade dele e se desejado, clique em ```Adicionar um arquivo README```, para criar um documento cujo objetivo é descrever o seu projeto. Por fim, clique em ```Criar repositório```. </br>

**3. Comandos Básicos do Git** </br>
* Estrutura de um repositório Git </br>
  De acordo com Oliveira (2019), um diretório .git possui a seguinte estrutura: </br>
  **.git (Pasta):** pasta oculta com os arquivos de configuração do repositório Git, tais como identificação do repositório remoto, histótico de commits locais, identificação  da Branch em uso, entre outros. </br>
  **.gitignore (Arquivo):** arquivo oculto com uma lista de parstas e arquivos que não podem ser versionados pelo Git, assim, eles devem ser ignorados a cada commit pelo Git. </br>
  **.gitkeep (Arquivo):** arquivo oculto que cria uma pasta vazia no repositório remoto para garantir que diretórios vazios sejam incluídos no repositório. </br>
  **README.md (Arquivo):** página inicial do repositório no servidor Git que contém as principais informações sobre o projeto. </br> </br>
   Sobre isso, o ```.``` (ponto) no inicio do nome dos arquivos e pastas os torna ocultos nos sistemas MAC OS e Linux, o que não se aplica para Windows. Já o ```md``` indica se tratar de um arquivo do tipo Markdown, que transforma o texto em um HTML válido. </br>
  
* Iniciando um repositório </br>
  Para iniciar um repositório no terminal de comando, navegue até o diretório do seu projeto e então execute o comando: </br>
  ```
  git init
  ```

  Isso criará um novo repositório Git no diretório atual. </br>
  
* Principais comandos: git init, git add, git commit, git push, git pull </br>
  **git init**: inicializa um novo repositório Git no diretório atual </br>
  **git add**: adiciona arquivos à uma área de preparação (staging area), preparando-os para serem comitados </br>
  **git commit**: registra as mudanças na área de preparação com uma mensagem descritiva </br>
  **git push**: envia os commits locais para um repositório remoto, podendo ser o GitHub </br>
  **git pull**: atualiza o repositório local com mudanças do repositório remoto </br>
  
* Gerenciamento de branches </br>
  Branches (ou em português, ramificações) são usados para desenvolver funcionalidades em ambientes isolados uns dos outros. A branch principal normalmente é chamada de **main** ou **master**. </br> </br>
  **Para criar uma nova branch:** </br>
  ```
  git branch <nome-da-branch>
  ```

  **Para mudar para outra branch:** </br>
  ```
  git checkout <nome-da-branch>
  ```
  
  **Para criar e mudar para uma nova branch:** </br>
  ```
  git checkout -b <nome-da-branch>
  ```

  **Para unir (merge) uma branch à branch atual:** </br>
  ```
  git merge <nome-da-branch>
  ```
  
  **Para excluir uma branch:** </br>
  ```
  git branch -d <nome-da-branch>
  ```

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

GITHUB. *Getting started with Git.* Disponível em: https://docs.github.com/en/get-started/getting-started-with-git. Acesso em 22 jul. 2024. </br>

GITHUB. *Understanding GitHub Actions.* Disponível em: https://docs.github.com/pt/actions/learn-github-actions/understanding-github-actions. Acesso em 22 jul. 2024. </br>

*History of GitHub.* Disponível em: https://pslmodels.github.io/Git-Tutorial/content/background/GitHubHistory.html. Acesso em 22 jul. 2024. </br>

TASHIA, T. *15 most popular GitHub repositories every developer should know.* Disponível em: https://www.hostinger.com/tutorials/most-popular-github-repos#:~:text=Copied!,of%20over%20100%20million%20developers. Acesso em 22 jul. 2024. </br>

LOUZADA, Vinícius. O que é Git e GitHub: os primeiros passos nessas ferramentas. Disponível em: https://www.alura.com.br/artigos/o-que-e-git-github?utm_term=&utm_campaign=%5BSearch%5D+%5BPerformance%5D+-+Dynamic+Search+Ads+-+Artigos+e+Conte%C3%BAdos&utm_source=adwords&utm_medium=ppc&hsa_acc=7964138385&hsa_cam=11384329873&hsa_grp=164068945139&hsa_ad=703934879696&hsa_src=g&hsa_tgt=dsa-1298415354460&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjwhvi0BhA4EiwAX25uj4VT5XMEodsNLQth1VAAdqaCyYZeaFgoIP2wDtdORv5PCx14XvzXvxoCWrgQAvD_BwE#o-que-e-github?. Acesso em 22 jul. 2024. </br>

OLIVEIRA, Marcos. Introdução ao Git: Estrutura básica. Medium, 2019. Disponível em: https://medium.com/@MarcosOlivDev/introdu%C3%A7%C3%A3o-ao-git-estrutura-b%C3%A1sica-88856a429f9e. Acesso em 27 jul. 2024. </br>

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
**Assunto:** Gerência de Projeto </br>
**Entrega:** A resposta deverá ser entregue em formato digital PDF e disponibilizada em um repositório público em que o professor possui acesso. O link da resposta deverá ser enviado no SIGAA. </br>

No contexto de gerenciamento de projetos de software, explique o processo de análise de riscos. </br>
Uma empresa de desenvolvimento de software de médio porte precisa desenvolver um software de vendas de pacotes de viagens para uma companhia de turismo. Explique como XP e Scrum podem ser combinados por esta empresa no desenvolvimento de software.
