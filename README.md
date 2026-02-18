# 🧩 [Space]

Um launcher modular focado em **segurança, leveza e praticidade**, inspirado na experiência da Steam, voltado principalmente para Minecraft (1.8.x), mas com possibilidade de expansão para outras versões.

O objetivo principal **não é impedir pirataria**, e sim **proteger o usuário** contra executáveis maliciosos, launchers modificados e arquivos contaminados espalhados pela internet.

---

## 🚀 Visão geral

- Core extremamente leve (baixo uso de CPU e RAM)
- Arquitetura modular (core + módulos)
- Atualizações frequentes sem precisar atualizar o app principal
- Execução supervisionada e validada
- Foco em estabilidade enquanto o jogador está em jogo

O app principal atua como um **supervisor**, não como um executador pesado.

---

## 🧠 Arquitetura

### 🔹 Core (App principal)
- Gerencia login e contas
- Valida integridade dos módulos
- Supervisiona processos
- Mantém comunicação local entre apps
- Mata qualquer módulo que não responda corretamente
- Consumo mínimo de recursos

O core **não executa lógica pesada**, apenas coordena.

---

### 🔹 Módulos
- São apps independentes, mas **não funcionam sem o core**
- Responsáveis por:
  - Interface
  - Hacks / injetores
  - Download e extração de arquivos
- Podem ser atualizados separadamente
- Executados sob supervisão total do core

---

## 🔒 Segurança (foco real do projeto)

Este projeto **não tenta ser inquebrável**, o foco é impedir que:

- alguém modifique o launcher
- injete código malicioso
- distribua executáveis infectados usando o nome do projeto

Medidas implementadas:
- Validação ativa entre core e módulos
- Comunicação local obrigatória
- Verificação de identidade em runtime

---

## 🧪 Testes e verificação

Todos os hacks/módulos distribuídos:
- São testados por longos períodos
- Utilizados em gameplay real
- Monitorados durante execução
- Verificados quanto a:
  - conexões suspeitas
  - webhooks
  - comportamento anormal

O objetivo é simples:
> **evitar que o usuário pegue vírus tentando baixar algo aleatório na internet**

---

## 🔓 Conteúdo aberto

- DLLs e hacks são disponibilizados livremente
- O objetivo é estudo, análise e discussão
- Transparência acima de controle

🚫 O launcher **não é open-source**, pois ele carrega a identidade e a responsabilidade do projeto.

---

## 📦 Atualizações

- Versionamento frequente
- Módulos atualizados de forma independente
- Core atualizado apenas quando necessário
- Correções rápidas para bugs críticos

---

## ⚠️ Aviso

Este projeto é destinado a **uso educacional e experimental**.  
O autor não se responsabiliza por qualquer uso indevido do conteúdo.  
O uso é opcional e de inteira responsabilidade do usuário.

---

## ❤️ Filosofia do projeto

> Fazer algo que funcione bem até em PC fraco,  
> que não atrapalhe o jogo,  
> e que não coloque o usuário em risco.

---

Se você chegou até aqui:  
obrigado por usar, testar, estudar ou contribuir 🤝
