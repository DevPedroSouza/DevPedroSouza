<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=F1F1F1&center=true&vCenter=true&random=false&width=560&lines=%E2%8A%B9+Bem-vindo+ao+meu+perfil!+%CB%99%E1%B5%95%CB%99+%E2%8A%B9)](https://git.io/typing-svg)

</div>

---

Me chamo **Pedro Souza Ramos**, tenho 18 anos e moro em São Paulo - SP. Atualmente curso Análise e Desenvolvimento de Sistemas (ADS) na UNICSUL, e estou no segundo semestre. Tenho muito interesse por tecnologia e hardware, e hoje trabalho como gestor de automação e desenvolvedor.

---

<img align="right" width="45%" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWdlNmtyYnMxZnJkeDY4N21yZ3dhMDVqcWFzdDJjdzBicjcwc2F6aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/1dcLFNKRUKvte/giphy.gif" alt="GIF do perfil">

### Connect with me!

[![Instagram](https://img.shields.io/badge/-Instagram-000?style=for-the-badge&logo=instagram&logoColor=FF00F6&color:FFF)](https://www.instagram.com/dev.pedrobr_/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=FF00F6&color:FFF)](https://www.linkedin.com/in/pedro-s-b1b15a3aa/)

### My Stack ~

<a href="https://n8n.io"><img src="https://cdn.simpleicons.org/n8n/EA4B71" alt="n8n" title="n8n" width="40" height="40"/></a> <a href="https://www.python.org"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40"/></a> <a href="https://www.java.com"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" title="Java" width="40" height="40"/></a> <a href="https://git-scm.com"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" title="Git" width="40" height="40"/></a> <a href="https://github.com/pedro-souza-ramos"><img src="https://cdn.simpleicons.org/github/FFFFFF" alt="GitHub" title="GitHub" width="40" height="40"/></a>

<br clear="right">

### My Automations ~

Alguns fluxos que mantenho no dia a dia com o **n8n**:

**Atendimento e chamados pelo WhatsApp**
Um assistente virtual recebe a solicitação do usuário no WhatsApp e o n8n abre o chamado direto no sistema de suporte. Antes disso, valida os dados e avisa se deu certo ou se faltou alguma informação.
*Conecta:* WhatsApp → n8n → API do sistema de chamados

<details>
<summary>Ver como funciona</summary>

```mermaid
flowchart LR
    A["WhatsApp: assistente virtual"] --> B["Webhook no n8n"]
    B --> C["Normaliza os dados"]
    C --> D{"Tem título e descrição?"}
    D -- sim --> E["Abre o chamado no sistema"]
    D -- não --> F["Pede a informação que faltou"]
    E --> G{"Deu certo?"}
    G -- sim --> H["Confirma: chamado aberto"]
    G -- não --> I["Avisa da falha"]
```

</details>

**Agendamento automático para pet shop**
Clientes agendam serviços e consultas pelo WhatsApp. O fluxo consulta o preço do serviço, verifica a disponibilidade do dia, registra o agendamento na planilha, cria o evento na agenda e envia lembretes no dia anterior.
*Conecta:* WhatsApp → n8n → Google Sheets → Google Calendar

<details>
<summary>Ver como funciona</summary>

```mermaid
flowchart LR
    A["Cliente no WhatsApp"] --> B["Webhook no n8n"]
    B --> C["Valida acesso, data e horário"]
    C --> D["Consulta o preço na planilha"]
    D --> E{"Horário disponível?"}
    E -- sim --> F["Salva na planilha e cria evento no Google Calendar"]
    E -- não --> G["Avisa que o dia está cheio"]
    F --> H["Confirma o agendamento"]
    I["Todo dia: busca os agendamentos de amanhã"] --> J["Envia lembrete no WhatsApp"]
```

</details>

### GitHub Stats

[![GitHub Stats](https://github-readme-stats-two-omega-43.vercel.app/api?username=pedro-souza-ramos&show_icons=true&locale=pt-br&commits_year=2026&hide=contribs&cache_seconds=21600&bg_color=000000&title_color=ffffff&text_color=ffffff&icon_color=ffffff&border_color=ffffff&ring_color=ffffff&custom_title=My%20GitHub%20Statistics)](https://github.com/pedro-souza-ramos)

[![Stack](https://github-readme-stats-two-omega-43.vercel.app/api/top-langs/?username=pedro-souza-ramos&layout=compact&custom_title=Stack&langs_count=8&bg_color=000000&title_color=ffffff&text_color=ffffff&icon_color=ffffff&border_color=ffffff&ring_color=ffffff)](https://github.com/pedro-souza-ramos)

![github contribution grid snake animation](https://raw.githubusercontent.com/pedro-souza-ramos/pedro-souza-ramos/output/github-contribution-grid-snake-dark.svg)
