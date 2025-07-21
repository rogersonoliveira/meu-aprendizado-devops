# Plano de Estudos DevOps - 30 Dias para Iniciantes

## 🎯 Objetivo
Construir uma base sólida em DevOps partindo do zero, com foco prático e projetos reais.

---

## **SEMANA 1: Git & Versionamento (Dias 1-7)**

### **Dia 1** - Primeiros Passos
**Teoria (30min):**
- O que é Git e por que é importante
- Conceitos: repositório, commit, branch

**Prática (1h):**
- Criar repositório no GitHub "meu-aprendizado-devops"
- Primeiro clone e commit
- Documentar aprendizado no arquivo `dia-01-aprendizado.md`

### **Dia 2** - Comandos Básicos
**Teoria (30min):**
- Fluxo básico do Git: add → commit → push

**Prática (1h):**
- Praticar `git add`, `git commit`, `git push`
- Modificar README.md
- Documentar aprendizado no arquivo `dia-02-comandos-git.md`

### **Dia 3** - Histórico e Logs
**Teoria (30min):**
- Comando `git log`
- Ver histórico de commits

**Prática (1h):**
- Explorar histórico do repositório
- Fazer múltiplos commits pequenos
- Praticar mensagens de commit descritivas
- Documentar aprendizado no arquivo `dia-03-historico-e-logs-git.md`

### **Dia 4** - Branches (Ramificações)
**Teoria (30min):**
- O que são branches
- Por que usar branches

**Prática (1h):**
- Criar primeira branch: `git branch estudos-semana1`
- Alternar entre branches: `git checkout`
- Fazer commits em branch separada
- Documentar aprendizado no arquivo `dia-04-Branches-git.md`

### **Dia 5** - Merge e Conflitos
**Teoria (30min):**
- Como fazer merge de branches
- O que são conflitos

**Prática (1h):**
- Fazer merge da branch de estudos
- Criar conflito proposital e resolver
- Documentar processo
- Documentar aprendizado no arquivo `dia-05-erge e Conflitos-git.md`

### **Dia 6** - GitHub Interface
**Teoria (30min):**
- Interface do GitHub
- Pull Requests básico

**Prática (1h):**
- Explorar interface web
- Editar arquivos pelo GitHub
- Fazer pull do repositório atualizado

### **Dia 7** - Revisão e Projeto
**Prática (2h):**
- Criar projeto "git-cheatsheet"
- Documentar todos os comandos aprendidos
- Organizar repositório com pastas
- **Milestone:** Dominar fluxo básico Git

---

## **SEMANA 2: Linux Essencial (Dias 8-14)**

### **Dia 8** - Introdução ao Linux
**Teoria (45min):**
- O que é Linux e por que é importante em DevOps
- Diferenças entre Windows e Linux

**Prática (1h):**
- Usar Docker para criar container Ubuntu
- Comandos básicos: `ls`, `cd`, `pwd`
- Documentar comandos aprendidos

### **Dia 9** - Sistema de Arquivos
**Teoria (30min):**
- Estrutura de diretórios Linux
- Caminhos absolutos vs relativos

**Prática (1h):**
- Navegar pelo sistema de arquivos
- Criar/remover diretórios: `mkdir`, `rmdir`
- Comando `tree` para visualizar estrutura

### **Dia 10** - Manipulação de Arquivos
**Teoria (30min):**
- Comandos de arquivo essenciais

**Prática (1h):**
- `touch`, `cp`, `mv`, `rm`
- `cat`, `less`, `head`, `tail`
- Criar script simples de backup

### **Dia 11** - Permissões e Usuários
**Teoria (45min):**
- Sistema de permissões Linux
- Usuários e grupos

**Prática (1h):**
- `chmod`, `chown`
- `ls -la` para ver permissões
- Criar usuário no container

### **Dia 12** - Processos e Monitoramento
**Teoria (30min):**
- O que são processos
- Como monitorar sistema

**Prática (1h):**
- `ps`, `top`, `htop`
- `kill` e sinais
- `jobs`, `nohup`

### **Dia 13** - Redes Básicas
**Teoria (45min):**
- Conceitos básicos de rede
- IP, portas, protocolos

**Prática (1h):**
- `ping`, `curl`, `wget`
- `netstat`, `ss`
- Testar conectividade

### **Dia 14** - Shell Scripting Introdução
**Teoria (30min):**
- O que é shell script
- Quando usar

**Prática (1h30):**
- Criar primeiro script bash
- Variáveis e echo
- Script para organizar arquivos
- **Milestone:** Confortável com terminal Linux

---

## **SEMANA 3: Docker Fundamentos (Dias 15-21)**

### **Dia 15** - Docker Conceitos
**Teoria (45min):**
- O que é Docker e containerização
- Docker vs Máquinas Virtuais

**Prática (1h):**
- Verificar instalação Docker
- `docker --version`
- `docker run hello-world`

### **Dia 16** - Imagens e Containers
**Teoria (30min):**
- Diferença entre imagem e container
- Docker Hub

**Prática (1h):**
- `docker images`, `docker ps`
- Baixar imagens: `docker pull`
- Executar containers interativos

### **Dia 17** - Dockerfile Básico
**Teoria (45min):**
- O que é Dockerfile
- Comandos principais

**Prática (1h):**
- Criar primeiro Dockerfile
- Buildar imagem própria
- Documentar processo

### **Dia 18** - Volumes e Networking
**Teoria (45min):**
- Persistência de dados
- Comunicação entre containers

**Prática (1h):**
- Montar volumes
- Criar networks
- Conectar containers

### **Dia 19** - Docker Compose Introdução
**Teoria (30min):**
- O que é Docker Compose
- Arquivos YAML

**Prática (1h):**
- Criar primeiro docker-compose.yml
- Subir stack simples
- Logs e debugging

### **Dia 20** - Projeto Web Simples
**Prática (2h):**
- Criar aplicação web simples (HTML)
- Containerizar com Nginx
- Usar compose para orquestrar

### **Dia 21** - Boas Práticas Docker
**Teoria (45min):**
- Segurança básica
- Otimização de imagens

**Prática (1h):**
- Refatorar Dockerfiles
- Multi-stage builds
- **Milestone:** Criar e gerenciar containers

---

## **SEMANA 4: CI/CD Introdução (Dias 22-28)**

### **Dia 22** - CI/CD Conceitos
**Teoria (1h):**
- O que é CI/CD
- Por que é importante
- Ferramentas populares

**Prática (30min):**
- Planejar pipeline simples
- Documentar conceitos

### **Dia 23** - GitHub Actions Básico
**Teoria (30min):**
- O que é GitHub Actions
- Workflows e jobs

**Prática (1h):**
- Criar primeiro workflow
- Trigger em push
- Hello world action

### **Dia 24** - Testes Automatizados
**Teoria (45min):**
- Importância dos testes
- Tipos de testes

**Prática (1h):**
- Integrar testes no pipeline
- HTML validator
- Lint checks

### **Dia 25** - Deploy Automatizado
**Teoria (30min):**
- Estratégias de deploy
- Ambientes (dev, prod)

**Prática (1h30):**
- Deploy para GitHub Pages
- Pipeline completo: test → build → deploy

### **Dia 26** - Monitoramento Básico
**Teoria (45min):**
- Por que monitorar
- Métricas básicas

**Prática (1h):**
- Implementar health checks
- Logs estruturados
- Alertas simples

### **Dia 27** - Projeto Final Planejamento
**Prática (2h):**
- Planejar projeto integrado
- Aplicação web + Docker + CI/CD
- Definir requirements

### **Dia 28** - Projeto Final Execução
**Prática (3h):**
- Implementar projeto final
- Documentar processo
- **Milestone:** Pipeline CI/CD funcionando

---

## **DIAS 29-30: Revisão e Próximos Passos**

### **Dia 29** - Revisão Geral
- Revisar todos os conceitos
- Testar conhecimentos
- Identificar lacunas

### **Dia 30** - Planejamento Futuro
- Avaliar progresso
- Planejar próximos 30 dias
- Definir especializações

---

## 📋 **Estrutura de Cada Dia**

### **Template Diário:**
```markdown
# Dia X - [Tópico]

**Data:** DD/MM/AAAA

## Teoria Estudada:
- Ponto 1
- Ponto 2

## Prática Realizada:
- Exercício 1
- Exercício 2

## Comandos/Códigos Aprendidos:
```bash
comando exemplo
```

## Dificuldades Encontradas:
- Problema 1 e como resolvi

## Para Revisar Amanhã:
- Item 1
- Item 2

## Próximo Passo:
O que vou estudar amanhã
```

---

## 🎯 **Milestones Semanais**

- **Semana 1:** Dominar Git básico
- **Semana 2:** Conforto com Linux terminal  
- **Semana 3:** Criar e gerenciar containers
- **Semana 4:** Pipeline CI/CD funcionando

---

## 📚 **Recursos Recomendados**

### **Git:**
- Git Handbook (GitHub)
- Atlassian Git Tutorials
- Oh My Git! (jogo)

### **Linux:**
- LinuxCommand.org
- Bandit OverTheWire
- Linux Journey

### **Docker:**
- Play with Docker
- Docker Official Docs
- Katacoda Docker

### **CI/CD:**
- GitHub Learning Lab
- GitLab CI/CD Tutorial