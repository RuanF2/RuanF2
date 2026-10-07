<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Ruan&fontSize=70&animation=fadeIn&fontAlignY=35" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Estudante+de+IA+🤖;Dev+em+formação+💻;Construindo+sistemas+internos+🎫;Automação+com+Apps+Script+⚙️;Sempre+aprendendo+🚀" />
</p>

<p align="center">
  Tecnólogo em Inteligência Artificial · Teresina, PI 🇧🇷
</p>

---

## Sobre mim

- Cursando **Tecnólogo em Inteligência Artificial** na **Faculdade PIT** (Piauí Instituto de Tecnologia)
- Atuo com **automação e suporte técnico**: scripts em Google Apps Script, integração com APIs, análise de logs, geração de relatórios e documentação interna
- Meu objetivo é ingressar no mercado de **desenvolvimento de software**
- Aprendo na prática: escrevo o código, erro, reviso e evoluo
- Estudando agora: **Engenharia de Dados** (Databricks, camadas bronze/silver) e **Machine Learning**
- Próximos passos: **React** e **Java**

---

## Projetos em destaque

### Sistema de Gestão de Chamados · *projeto profissional (código privado)*
Web App que desenvolvi do zero para a empresa onde trabalho, para organizar a abertura, o atendimento e a aprovação de solicitações de correção e suporte, substituindo trocas de e-mail por um fluxo rastreável. O código é de propriedade da empresa e não é público.

```mermaid
flowchart LR
    A[Pendente] -->|gestor aceita| B[Em Execução]
    B -->|gestor resolve| C[Resolvido pelo Gestor]
    C -->|solicitante aprova| D[Concluído]
    C -->|solicitante reprova + motivo| B
```

**O que o sistema faz**
- **Perfis de acesso**: ações exclusivas de gestor e aprovação restrita a quem abriu o chamado
- **Fila de atendimento por ordem de chegada (FIFO)**
- **Temporizadores em tempo real**: tempo em aberto e tempo de atendimento
- **Ciclo de aprovação com histórico**: aprovação ou reprovação com motivo e imagens anexadas
- **Alertas para o gestor** a cada chamado novo ou reprovação (som, notificação do navegador e título da aba)
- **Anexos de imagem** armazenados no Google Drive
- **Painel do gestor** para administrar sistemas/módulos e limpar chamados

**Desafios que resolvi**
- Evitar que dois usuários gravem ao mesmo tempo e sobrescrevam os dados um do outro (controle de concorrência)
- Validar regras de negócio no servidor, e não só na interface
- Separar o armazenamento de anexos em um projeto à parte, para o sistema principal não pedir permissões extras aos usuários

`Google Apps Script` `JavaScript` `HTML/CSS` `Google Drive` `Web Audio API` `Notification API`

---

### [Cofre de Senhas](https://github.com/RuanF2/cofre-de-senhas)
Gerenciador de senhas completo, com autenticação **JWT**, login com **Google OAuth** (Passport.js), criptografia **AES-256-GCM** e banco **PostgreSQL**.
`Node.js` `PostgreSQL` `JWT` `OAuth`

### Post+
Rede social full-stack com back-end em **Node.js/Express**, **PostgreSQL** e front-end em HTML, CSS e JavaScript puro.
`Node.js` `Express` `PostgreSQL` `JavaScript`

### AgroDash Brasil
Dashboard interativo com dados agrícolas dos **27 estados brasileiros**, tema neon e partículas animadas.
`JavaScript` `Chart.js` `HTML/CSS`
---

## O que faço no dia a dia

- Desenvolvimento de **sistemas internos** com Google Apps Script (como o sistema de chamados acima), com controle de acesso, concorrência e integrações
- Integração com **APIs REST** (paginação, filtros por data, mapeamento de dados)
- Análise de logs e geração de relatórios
- Documentação técnica e fluxogramas de processos

---

## Tecnologias

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,js,nodejs,express,postgres,flask,nextjs,prisma,html,css,git,arduino&perline=12" />
</p>

---

## Atividade

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RuanF2&theme=tokyo-night&hide_border=true&area=true" width="100%" />

<img src="https://raw.githubusercontent.com/RuanF2/RuanF2/output/snake.svg" width="100%" />

---

## Vamos conversar?

<p align="center">
  <a href="https:https://www.linkedin.com/in/ruan-francelino-3262a334b/?isSelfProfile=true"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ruanfrancelino47@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" width="100%" />
