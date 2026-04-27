# 🚀 Projeto Windows Server 2022 - Simulação de Ambiente Corporativo

Este projeto consiste na implementação de uma infraestrutura completa de rede, simulando um ambiente corporativo real utilizando Windows Server 2022.

O objetivo foi aplicar na prática conceitos de administração de redes, centralização de serviços e controle de acesso em um domínio corporativo.

---

## 🧠 Arquitetura do Ambiente

- Servidor Windows Server 2022 como Controlador de Domínio
- Estações clientes integradas ao domínio
- Serviços centralizados de autenticação, rede e políticas

---

## 🔧 Tecnologias e Serviços Utilizados

- Active Directory Domain Services (AD DS)
- DNS (resolução de nomes)
- DHCP (distribuição automática de IP)
- Group Policy (GPO)
- WSUS (Windows Server Update Services)
- File Server (compartilhamento de arquivos)
- IIS (servidor web para intranet)
- Backup automatizado

---

## ⚙️ Implementações Realizadas

### 🔐 Active Directory
- Criação de domínio corporativo (ghc.local)
- Estruturação de Unidades Organizacionais (OUs) por departamento
- Gerenciamento de usuários e grupos

### 🌐 Rede (DNS e DHCP)
- Configuração de DNS integrado ao AD
- Distribuição automática de IPs via DHCP
- Reserva de IP e controle de escopo

### 🛡️ Políticas de Segurança (GPO)
- Mapeamento automático de unidades de rede
- Restrições de acesso ao sistema
- Padronização de ambiente para usuários

### 💾 File Server
- Compartilhamento de pastas por setor
- Controle de permissões (NTFS e compartilhamento)
- Implementação de cotas de armazenamento

### 🔄 Atualizações (WSUS)
- Centralização de atualizações Windows
- Controle de aprovação de patches
- Redução de consumo de banda na rede

### 🌐 IIS (Intranet)
- Configuração de servidor web interno
- Publicação de página institucional

### 💽 Backup
- Implementação de rotina de backup automatizado
- Garantia de recuperação de dados

---

## 📊 Resultados Obtidos

- Centralização da autenticação de usuários
- Melhoria na organização e segurança do ambiente
- Automatização de processos administrativos
- Simulação de cenário real de infraestrutura corporativa

---

## 📸 Imagens do Projeto

![AD](imagens/ad.png)
![GPO](imagens/gpo.png)
![WSUS](imagens/wsus.png)
![FileServer](imagens/fileserver.png)

---

## 📄 Documentação Completa

A documentação detalhada do projeto está disponível em:

📂 docs/projeto.pdf

---

## ⚠️ Observação

Projeto desenvolvido para fins de estudo e aprimoramento técnico em administração de redes e infraestrutura.

---

## 🔗 Repositório

https://github.com/bancadabd-bot/projeto-windows-server
