<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=250&section=header&text=hackion&fontSize=80&fontColor=00ff9d&animation=twinkling&fontAlignY=35&desc=Hacking%20%E2%80%A2%20Breaking%20things%20to%20understand%20how%20they%20work&descAlignY=58&descSize=18" width="100%"/>

<img src="https://raw.githubusercontent.com/trinib/trinib/main/assets/matrix.gif" width="100%" height="120"/>

<h3>⚡ Attacks are evolving using AI ⚡</h3>

<img src="https://img.shields.io/badge/VAPT-Certified%20Mindset-black?style=for-the-badge&logo=hackthebox&logoColor=00ff9d&labelColor=000000" />
<img src="https://komarev.com/ghpvc/?username=deepansh39&style=for-the-badge&color=00ff9d&label=PROFILE+VIEWS" />

<br><br>

<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" />
<img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Shodan-EA1F2D?style=for-the-badge&logo=shodan&logoColor=white" />
<img src="https://img.shields.io/badge/Censys-000000?style=for-the-badge&logo=censys&logoColor=00ff9d" />
<img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />

<img src="https://readme-typing-svg.demolab.com/?lines=whoami+%3E+deepansh39;Building+offensive+%26+defensive+security+tools;Python+%7C+Networking+%7C+SOC+%7C+VAPT;Scanning+ports...+exploiting+curiosity;Watching+attacks+evolve+as+AI+gets+smarter;Claude+%2B+ChatGPT+%3D+recon+on+steroids;sudo+access+granted...;Welcome+to+my+terminal.&font=Fira%20Code&center=true&width=750&height=50&color=00ff9d&vCenter=true&size=22&pause=1500" />

<img src="https://user-images.githubusercontent.com/74038190/213866269-5d00981c-7c98-46d7-8a8e-16f462f15227.gif" width="100%">

</div>

<br>

### `> cat about_me.txt`

```yaml
name:        Deepanshu
handle:      hackion
role:        Cybersecurity Enthusiast / Python Developer
focus:       Network Security · SOC Analysis · Pentesting Tools · VAPT
currently:   busy with my laptop 💻
fun_fact:    I write tools instead of using them sometimes
```

<br>

### `> echo $AI_THREAT_LANDSCAPE`

> ⚡ **Attacks are evolving as fast as the AI writing them.** Recon, payload generation, phishing pretexts, even exploit-chaining logic — the offense side is being automated in real time. I use **Claude** and **ChatGPT** as force multipliers in my own workflow: scripting faster, parsing logs at scale, and staying ahead of how adversaries are already weaponizing the same models.

<br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

### `> nmap -sV --topology target_network/24`

```
                              ┌────────────────────┐
                              │   INTERNET (WAN)    │
                              └──────────┬──────────┘
                                         │
                     ┌───────────────────┴───────────────────┐
                     │                                        │
             ┌───────▼────────┐                     ┌─────────▼─────────┐
             │  Shodan Index   │                     │   Censys Index     │
             │  203.0.113.14   │                     │   198.51.100.27    │
             │  banners · CVEs │                     │   certs · assets   │
             └───────┬────────┘                      └─────────┬──────────┘
                     │                                          │
                     └───────────────────┬──────────────────────┘
                                          │
                                ┌─────────▼─────────┐
                                │   Edge Firewall     │
                                │   10.0.0.1  :443/22 │
                                └─────────┬───────────┘
                          ┌───────────────┼────────────────┐
                          │               │                │
                ┌─────────▼───┐  ┌────────▼────┐  ┌────────▼────┐
                │  Web Server  │  │  DB Server   │  │  SOC / SIEM  │
                │ 10.0.0.15    │  │ 10.0.0.42    │  │ 10.0.0.99    │
                │ :80 :443     │  │ :3306        │  │ log-analyzer │
                └──────────────┘  └──────────────┘  └──────────────┘
                    ▲                                       ▲
                    │                                       │
             [ Burp Suite ]                          [ soc-log-analyzer ]
             intercept · fuzz                         detect · alert
```

<div align="center">

*Recon → Shodan / Censys pull exposed banners & certs → Burp Suite intercepts & fuzzes the app layer → findings feed back into the SOC pipeline.*

</div>

<br>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,flask,docker,linux,git,bash,mysql,postman&theme=dark" />

<br><br>

![Nmap](https://img.shields.io/badge/Nmap-000000?style=for-the-badge&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-004080?style=for-the-badge&logo=python&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

<br>

### `> ./run --project featured`

<div align="center">

<table>
<tr>
<td width="50%">

**🛰️ [NetProbe](https://github.com/deepansh39/NetProbe)**
Lightweight Python network scanner inspired by Nmap — TCP port scanning, SYN scanning & service/version detection.
`Python` `Networking` `Recon`

</td>
<td width="50%">

**🧠 [soc-log-analyzer](https://github.com/deepansh39/soc-log-analyzer)**
Parses Linux logs to catch brute-force attempts, suspicious IPs, HTTP anomalies & sensitive sudo commands.
`Python` `Blue Team` `SOC`

</td>
</tr>
<tr>
<td width="50%">

**📡 [analyzer-packet](https://github.com/deepansh39/analyzer-packet)**
Scapy-powered live packet capture tool that extracts protocol, source & destination details in real time.
`Python` `Scapy` `Traffic Analysis`

</td>
<td width="50%">

**🛡️ [websentinel](https://github.com/deepansh39/websentinel)**
Dockerized OWASP ZAP platform with a Flask dashboard for scan management & persistent findings.
`Docker` `Flask` `OWASP ZAP`

</td>
</tr>
</table>

</div>

<br>

### `> tail -f github_stats.log`

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=deepansh39&theme=matrix&no-frame=true&no-bg=true&row=1&column=6" />

<img height="165" src="https://github-readme-stats.vercel.app/api?username=deepansh39&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=00ff9d&icon_color=00ff9d&text_color=c9d1d9" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=deepansh39&theme=dark&hide_border=true&background=0d1117&ring=00ff9d&fire=00ff9d&currStreakLabel=00ff9d" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepansh39&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=00ff9d&text_color=c9d1d9" />

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">

</div>

<br>

### `> netstat --connect`

<div align="center">

<a href="https://github.com/deepansh39"><img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github"/></a>

</div>

<br>

<div align="center">

*"There is no patch for human stupidity — but there's always a script for it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
