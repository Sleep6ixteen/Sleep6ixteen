<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Security+%26+Low-Level+Research;Android+%2F+ARM64+Internals;AI+Agents+%26+Autonomous+Systems;Reverse+Engineering+%26+Exploitation" alt="Typing SVG" />
</a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/Sleep6ixteen?style=for-the-badge&color=58a6ff&labelColor=0d1117)](https://github.com/Sleep6ixteen)
[![Profile views](https://komarev.com/ghpvc/?username=Sleep6ixteen&style=for-the-badge&color=58a6ff&labelColor=0d1117)](https://github.com/Sleep6ixteen)

</div>

---

## O que faço

Trabalho na interseção entre segurança ofensiva, sistemas de baixo nível e inteligência artificial. A maior parte do meu tempo vai para entender como as coisas funcionam por dentro — drivers, kernels, protocolos — e construir ferramentas que resolvem problemas reais a partir disso.

Tenho foco especial em Android/ARM64: desde compilação de kernels customizados e engenharia reversa de binários nativos até contornar camadas de proteção do sistema para habilitar recursos que o fabricante bloqueou. Faço isso sem root quando possível — o desafio é exatamente esse.

Em paralelo, desenvolvimento de agentes autônomos de IA é outro eixo forte do meu trabalho. Construí do zero um ecossistema completo de orquestração de agentes em Go, com daemon persistente, loop cognitivo ReAct e suporte a múltiplos workspaces.

---

## Projetos em destaque

### ⚡ [hascat](https://github.com/Sleep6ixteen/hascat)
hashcat rodando com aceleração de GPU real no Termux, sem root.  
O chip PowerVR BXM-8-256 do MediaTek MT6855 tem o driver OpenCL bloqueado por 4 camadas independentes do Android. Contornei todas via hooking de namespace do linker, interceptação de propriedades de build e redirecionamento do gate do gralloc. Resultado: **181 MH/s em NTLM** num celular comum, direto do terminal.

### 🤖 Crom Agent *(privado)*
Motor de agentes autônomos local-first, escrito em Go.  
Daemon com loop cognitivo ReAct, orquestração multi-agente em goroutines paralelas, suporte a MCP (Model Context Protocol), sandbox ajustável e sistema Human-in-the-Loop. Parte de um ecossistema modular com CLI, SDK, app desktop (Tauri + React) e gateway de LLMs em nuvem.

### 🔬 Deep Eye *(pesquisa)*
Framework de análise de segurança com integração a múltiplos provedores de IA.  
Focado em reconhecimento, fingerprinting e análise automatizada de alvos.

### 🧠 Neural Bot / IA-Torch *(experimental)*
Experimentos com redes neurais em PyTorch para comportamento autônomo.  
Inclui série de iterações (`IA-torch.py` → `IA-torch-11.py`) testando arquiteturas diferentes para agentes com memória e auto-melhoria.

---

## Stack

```
Linguagens    Go · Python · C · Bash · JavaScript
Plataformas   Android (ARM64/aarch64) · Linux · Termux
Segurança     Reverse Engineering · Fuzzing · Network Recon · Binary Patching
Android       Kernel Build · Driver Hooking · OpenCL · LD_PRELOAD · Frida
IA / ML       PyTorch · LLM Agents · ReAct Loop · MCP · RAG
Ferramentas   Radare2 · Frida · Metasploit · Nuclei · Burp · Nmap · Masscan
```

---

## Áreas de interesse

- Internals de Android e drivers de hardware proprietários
- Desenvolvimento de agentes autônomos de IA com raciocínio estruturado
- Segurança ofensiva: reconhecimento, exploração e pós-exploração
- Compilação e modificação de kernels para dispositivos ARM
- Engenharia reversa de binários nativos (ARM64, x86_64)

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sleep6ixteen&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)](https://github.com/Sleep6ixteen)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Sleep6ixteen&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)](https://github.com/Sleep6ixteen)

</div>
