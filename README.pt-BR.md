<div align="center">

# 🚩 CTF Writeups & Security Labs

**Anotações práticas de CTFs e labs: explorar e depois aprender a detectar.**

[🇺🇸 English](README.md) · 🇧🇷 Português

</div>

---

## 👋 Sobre

Sou o Mattheus, analista de cibersegurança júnior (SOC N1 / AppSec) do Brasil. Neste repositório eu documento os CTFs e labs que resolvo.

A maioria dos writeups tem uma seção curta de **"Visão Blue Team"**. Depois de explorar algo, eu registro como aquilo aparece do lado de quem defende: logs, tráfego de rede e como um analista de SOC poderia detectar.

Portfólio: [mattheusalfonso.github.io](https://mattheusalfonso.github.io)

## 🗂️ Estrutura

```
ctf-writeups/
├── tryhackme/        # Salas do TryHackMe
├── hackthebox/       # Hack The Box (só máquinas aposentadas)
├── picoctf/          # Desafios do picoCTF
├── cyberdefenders/   # Labs blue team (PCAP, logs, forense)
└── _template/        # Modelo de writeup
```

Cada writeup fica na sua própria pasta, `plataforma/nome-da-sala/README.md`, com os prints em `plataforma/nome-da-sala/img/`.

A tabela de progresso fica no [README em inglês](README.md#-progress), para não manter duas cópias.

## 📜 Regras que eu sigo

- **Sem flags nem respostas diretas.** Explico o método, não a resposta para copiar, e as flags ficam ocultas (`THM{REDACTED}`).
- **Hack The Box:** só publico writeups de máquinas **aposentadas**, como a plataforma exige.
- **Só ambientes legais e isolados.** Tudo aqui foi feito em plataformas de CTF ou no meu lab no VirtualBox, nunca contra sistemas que não são meus ou sem permissão.
- **Nada de segredos no git.** Arquivos de VPN (`.ovpn`), credenciais e capturas grandes são bloqueados pelo `.gitignore`.
