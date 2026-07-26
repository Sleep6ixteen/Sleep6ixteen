<div align="center">

<p align="center">
  <img src="https://media.giphy.com/media/dLolp8dtrYCJi/giphy.gif" width="100%" alt="Mr. Robot" />
</p>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=Security+Researcher+%26+Tool+Builder;Android+%2F+ARM64+Low-Level+Hacking;Network+Recon+%26+Exploitation;Reverse+Engineering+%2F+Binary+Patching;%22Hello+friend...%22" alt="Typing SVG" />
</a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/Sleep6ixteen?style=for-the-badge&color=00ff41&labelColor=0d1117&logo=github)](https://github.com/Sleep6ixteen)
[![Profile views](https://komarev.com/ghpvc/?username=Sleep6ixteen&style=for-the-badge&color=00ff41&labelColor=0d1117)](https://github.com/Sleep6ixteen)

</div>

---

```
whoami
───────────────────────────────────────────────────────────────
  Pesquisador de segurança ofensiva com foco em sistemas de
  baixo nível — drivers Android, kernels ARM64, protocolos
  de rede e engenharia reversa de binários nativos.

  Construo ferramentas do zero. Se preciso entender como algo
  funciona por dentro, abro no radare2 e leio o assembly.

  Sem root quando possível. O desafio é exatamente esse.
───────────────────────────────────────────────────────────────
```

---

## 🔧 Projetos

<table>
<tr>
<td width="50%">

### ⚡ [hascat](https://github.com/Sleep6ixteen/hascat)
hashcat com GPU real no Termux, sem root.

O driver OpenCL do PowerVR BXM-8-256 está bloqueado por **4 camadas independentes** do Android. Contornei todas: namespace do linker, propriedades de build (`userdebug`), gate do gralloc (`-22`) e patch de local memory no hashcat.

**181 MH/s em NTLM** num celular comum.

`C` `ARM64` `OpenCL` `LD_PRELOAD` `Radare2`

</td>
<td width="50%">

### 👻 Phantom Engine
Suite de reconhecimento e varredura stealth.

Motor adaptativo com jitter randômico, rotação de User-Agent, fingerprinting passivo de OS, fuzzing de paths, probe UDP/SNMP/RPC e análise de timing de portas. Projetado para evadir detecção por anomalia de padrão.

`Python` `Scapy` `Network` `OSINT` `Evasion`

</td>
</tr>
<tr>
<td width="50%">

### 🗺️ osint-map
Mapa mundial no terminal com geolocalização por IP.

Escrito em Go, renderiza mapa responsivo com blocos Unicode, crosshairs e coordenadas exatas. Integrado ao `pxcli` para pixel art no terminal.

`Go` `CLI` `OSINT` `Unicode` `Geolocation`

</td>
<td width="50%">

### 🔍 Deep Eye
Scanner de vulnerabilidades com IA multi-provider.

Integra OpenAI, Claude, Grok, Ollama e Mistral para geração inteligente de payloads, reconhecimento passivo e relatórios PDF/HTML. 45+ métodos de ataque, awareness de CVE.

`Python` `AI` `Pentest` `Recon` `Bug Hunting`

</td>
</tr>
<tr>
<td width="50%">

### 📡 Scanner Stealth (Go)
Port scanner com anti-detecção nativo.

Jitter de 500ms–2s por conexão para confundir sistemas de detecção por anomalia. Concorrência controlada com goroutines e sync.WaitGroup.

`Go` `Networking` `Evasion` `Concurrency`

</td>
<td width="50%">

### 🛡️ DNS Monitor
Monitor de DNS com evasão de análise estática.

Domínios de rastreamento ofuscados em Base64 no binário para evitar strings detectáveis. Resolução e análise de tráfego DNS em tempo real.

`Python` `DNS` `Network` `Obfuscation`

</td>
</tr>
</table>

---

## 🛠️ Arsenal

<div align="center">

| Categoria | Ferramentas |
|-----------|-------------|
| **Linguagens** | Go · Python · C · Bash · JavaScript |
| **RE / Binary** | Radare2 · Frida · GDB · strace · ltrace |
| **Recon** | Amass · Subfinder · httpx · nuclei · katana · gau · ffuf |
| **Exploitation** | Metasploit · Hydra · ncrack · Burp Suite |
| **Network** | Nmap · Masscan · Responder · Wireshark · Scapy |
| **Android** | Kernel Build · LD_PRELOAD · OpenCL · ADB · apktool |
| **Platform** | Android ARM64 · Linux · Termux |

</div>

---

## 📊 Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Sleep6ixteen&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sleep6ixteen&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Sleep6ixteen&theme=terminal&hide_border=true&background=0D1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41)](https://git.io/streak-stats)

</div>

---

## 🔬 Áreas de pesquisa

```python
research = {
    "android_internals": ["kernel build", "driver hooking", "OpenCL", "namespace linker"],
    "offensive_security": ["recon", "exploitation", "post-exploitation", "evasion"],
    "reverse_engineering": ["ARM64 disasm", "binary patching", "hook injection"],
    "network": ["stealth scanning", "protocol fingerprinting", "traffic analysis"],
    "tooling": ["CLI tools in Go", "automation frameworks", "custom scanners"],
}
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00ff41&height=80&section=footer&fontColor=00ff41" />
</div>
