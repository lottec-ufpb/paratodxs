# Colabore com o ParaTodxs

Correções, melhorias e propostas são bem-vindas.

A maneira mais robusta de submetê-las é por meio das funcionalidades do GitHub.
Para tanto, é necessária uma conta no GitHub.
Confira as [instruções oficiais](https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github) para mais detalhes sobre como registrar-se.

## Levantar uma questão (*issue*)

Caso você tenha identificado algum erro ou gostaria de propor alguma melhoria, a maneira mais simples é [registrar uma questão ou problema](../../issues/new/choose).
Preencha o modelo apropriado.
Após avaliar e/ou discutir a questão, alguém efetuará a alteração/correção, caso pertinente.

Para mais informações sobre esta funcionalidade, consulte o [guia oficial](https://docs.github.com/pt/issues/tracking-your-work-with-issues/about-issues).

## Requisitar uma alteração (*pull request*)

Caso você já tenha alguma familiaridade com o Git e/ou GitHub, você pode solicitar diretamente que uma alteração seja incorporada no ramo principal do repositório.
Após revisada e/ou aprovada por alguém, será incorporada ao projeto.
É recomendável que a solicitação venha acompanhada de um breve arrazoado da proposta de alteração.

## Bifurcar o ParaTodxs

A principal vantagem de materiais didáticos livres é a possibilidade de derivar uma versão própria quando conveniente.

Num livro didático tradicional, com "todos os direitos reservados", somos forçados a conviver com suas imperfeições, mudar para outro livro didático (possivelmente com outras imperfeições), ou escrever algo do zero.
Com o ParaTodxs, você pode simplesmente reescrever as partes que não agradam e distribuir sua versão livremente.

Nós buscamos facilitar que pessoas mantenham versões derivadas como bifurcações deste repositório.
Além de outros benefícios, bifurcações facilitam a troca de melhorias (*PRs*) consensuais.

Não é necessária qualquer alteração no código do repositório para que a funcionalidade de compilação automática do PDF pelo GitHub seja usada por bifurcações. Contudo, no caso de bifurcações, o GitHub, por padrão, não habilita acesso de escrita para que o PDF seja depositado junto ao demais artefatos de lançamento (*Releases*). Para usar esta funcionalidade, portanto, você precisa habilitar este acesso nas configurações do repositório bifurcado (*Settings* -> *Actions* -> *General* -> *Workflow permissions*).

As referências na folha de rosto do PDF gerado pelo GitHub apontam automaticamente para o seu repositório.

Portanto, é possível manter uma bifurcação colaborativa do ParaTodxs sem se preocupar com modificações ou conflitos causados pela mera diferença de repositórios.

## Ambiente de trabalho online

Na expectativa de facilitar ainda mais eventuais contribuições, o repositório dispõe de uma configuração básica para um ambiente de trabalho do GitHub ([*codespace*](https://docs.github.com/pt/codespaces/overview)) com [Debian](https://www.debian.org/) + [TeXLive](https://www.tug.org/texlive/) + [Git](https://git-scm.com/) + [Visual Studio Code](https://code.visualstudio.com/) + [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop). Isto poupa a instalação e configuração de LaTeX e Git na sua máquina, uma vez que o ambiente de trabalho executa num *container* hospedado pelo GitHub e pode ser acessado usando qualquer navegador moderno.

Para fazer uso, [bifurque o repositório](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) e [crie um ramo novo](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository). No menu do botão verde, você encontrará uma aba *Codespaces* com outro botão verde para criar o ambiente trabalho no ramo atual. Na criação do ambiente de trabalho pode durar alguns minutos. Após a criação, você pode parar ou iniciar o ambiente de trabalho conforme necessário, o que costuma durar apenas alguns segundos. Note que o GitHub [pode expurgar ambientes de trabalho após certo período sem uso](https://docs.github.com/pt/codespaces/setting-your-user-preferences/configuring-automatic-deletion-of-your-codespaces). Consulte a documentação do [VS Code](https://code.visualstudio.com/docs) e/ou [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop/wiki) para mais informações sobre como usar estas ferramentas. Note que o uso de ambientes de trabalho online para além dos [limites gratuitos](https://docs.github.com/pt/billing/managing-billing-for-your-products/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#monthly-included-storage-and-core-hours-for-personal-accounts) atualmente concedidos pelo GitHub [pode estar sujeito a cobranças](https://docs.github.com/pt/billing/managing-billing-for-your-products/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#pricing-for-paid-usage).
