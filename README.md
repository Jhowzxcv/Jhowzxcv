<h1 align="center">Jhonathan Dourado</h1>

<p align="center">
  Construo APIs REST em <strong>Java/Spring Boot</strong> e interfaces em <strong>Angular</strong>.<br/>
  São Paulo · Eng. de Software na FIAP
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jhonathan-dourado-846239324/">
    <img src="https://img.shields.io/badge/Vamos_conversar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

### Onde estou

Backend e frontend de painéis operacionais na **Virtsel** — endpoints de dados
ao vivo e histórico, exportação de relatórios, modelagem de domínio e regras de
cálculo rodando em produção. Código privado, então o que está aqui embaixo é o
que dá pra mostrar.

---

### Projetos

**[Ficha Forge](https://github.com/Jhowzxcv/ficha-forge)** · Python
Escreve a história de um personagem de Ordem Paranormal, recebe a ficha pronta.
A decisão de projeto: **LLM não calcula**. O modelo interpreta a história e
escolhe classe, origem e perícias; o motor em código calcula PV/PE/Sanidade e
valida a build contra as regras — se vier ilegal, devolve os erros e pede
correção, até 3 rodadas. Roda como desktop, CLI e PWA sobre a mesma engine.

**[Jodrix](https://github.com/Jhowzxcv/jodrix-releases)** · TypeScript / Electron
App Windows que testa cada jogo da sua biblioteca em dois emuladores, mede
CPU/memória/travamento e elege o vencedor com score 0–10. Auto-update,
sync de saves entre máquinas e leaderboard anônimo com backend Cloudflare.

---

### Como trabalho

- Modelo o domínio antes de sair criando endpoint
- Separo DTO de entidade — o contrato da API não é o banco
- Coloco a validação em código determinístico, não na camada que pode alucinar
- Prefiro corrigir a causa da query lenta a botar cache em cima dela

---

### Stack

| Camada | Tecnologias |
|---|---|
| **Backend** | Java · Spring Boot · JPA/Hibernate · Maven · REST |
| **Frontend** | Angular · TypeScript · RxJS |
| **Dados** | PostgreSQL · Oracle · SQL |
| **Outros** | Docker · Git · Python · Electron |
