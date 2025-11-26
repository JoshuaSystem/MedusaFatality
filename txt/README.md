# MedusaFatality


# 🔱 MedusaFatality
### Simulado de Ataque Brute Force com a Ferramenta Medusa

Este repositório contém os arquivos utilizados no projeto **SimuladoAtaqueBruteForceSenhasMedusa**, cujo objetivo é praticar e demonstrar técnicas de **ataque de força bruta** em um ambiente controlado e autorizado, utilizando a ferramenta **Medusa**.

---

## 📁 Arquivos do Repositório

- `users.txt` — Lista de possíveis usuários de teste  
- `pass.txt` — Wordlist de senhas para brute force  
- `smb_users.txt` — Usuários enumerados via SMB  
- `enum4_output.txt` — Output da ferramenta *enum4linux*  
- `senhas_spray.txt` — Arquivo de senhas usado para password spraying  
- `passoapasso_comandos.txt` — Registro de todos os comandos executados no simulado

---

## 🛠 Ferramentas Utilizadas

- **Medusa** → ataque de força bruta  
- **Enum4linux** → enumeração de usuários (SMB)  
- **Nmap** → varredura de portas e serviços  
- **Smbclient** → interação com compartilhamentos SMB  
- **Wordlists personalizadas**  

---

## 🎯 Objetivo do Projeto

O objetivo deste repositório é reunir todos os arquivos, outputs e listas usadas durante o simulado de brute force com a ferramenta Medusa, permitindo:

- Organização das evidências  
- Reexecução dos testes  
- Estudo detalhado das ferramentas  
- Documentação clara do processo  

---

## ▶️ Exemplo de Uso do Medusa

```bash
medusa -h 192.168.0.100 -u admin -P pass.txt -M smbnt

Nome_Do_Aluno: Josué.A.S.C.A