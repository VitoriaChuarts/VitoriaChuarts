<table>
<tr>
<td width="220" align="center">

<img src="assets/foto.jpg" width="200" alt="Vitória Chuarts"/>

</td>
<td>

# Vitória Chuarts

![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=00FF9C&vCenter=true&width=460&height=32&lines=Full+Stack+Developer;Detection+Engineering;Building+honeypots+and+SIEMs)

Software Engineering student · Java · Python · Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitória-chuarts-687b26191)
[![Email](https://img.shields.io/badge/Email-111111?style=flat&logo=gmail&logoColor=white)](mailto:vitoriachuarts@icloud.com)

</td>
</tr>
</table>

```text
vitoria@kali:~$ whoami
Vitória Chuarts · Software Engineering student at Uniube (Brazil)

vitoria@kali:~$ cat focus.txt
> Full stack development with Java and Spring Boot
> Detection engineering: honeypots, NIDS and SIEM
> Open to relocation
> Languages: Portuguese (native) · Spanish (advanced) · English (intermediate)
```

## How I build security tools

```mermaid
flowchart LR
    A["Honeypot SSH"] --> D
    B["NIDS"] --> D
    C["Phishing Analyzer"] --> D
    D["mini-SIEM<br/>Spring Boot + PostgreSQL"] --> E["Real-time dashboard"]
    D --> F["Detection rules<br/>MITRE ATT&CK"]
```

## Flagship project

**[mini-SIEM](https://github.com/VitoriaChuarts/mini-siem)** correlates alerts from an SSH honeypot, a packet-level NIDS and a phishing analyzer in a single real-time dashboard.
`Java` `Spring Boot` `PostgreSQL` `Docker`

<!-- Quando o docs/demo.gif estiver no repositório mini-siem, apague esta linha e a última deste comentário:
[<img src="https://github.com/VitoriaChuarts/mini-siem/raw/main/docs/demo.gif" width="85%" alt="mini-SIEM demo"/>](https://github.com/VitoriaChuarts/mini-siem)
-->

## Security projects

| Project | What it does | Stack |
|---|---|---|
| [**honeypot-ssh**](https://github.com/VitoriaChuarts/honeypot-ssh) | Fake SSH server that captures attacker credentials | Python, paramiko |
| [**nids-python**](https://github.com/VitoriaChuarts/nids-python) | Detects port scans and SYN floods from live packets | Python, Scapy |
| [**analisador-de-phishing**](https://github.com/VitoriaChuarts/analisador-de-phishing) | Risk scoring for URLs and `.eml` emails | Python |

## Tech stack

![Java](https://img.shields.io/badge/Java-111111?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-111111?style=flat&logo=springboot&logoColor=6DB33F)
![Python](https://img.shields.io/badge/Python-111111?style=flat&logo=python&logoColor=3776AB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111111?style=flat&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-111111?style=flat&logo=linux&logoColor=white)
![Kali](https://img.shields.io/badge/Kali-111111?style=flat&logo=kalilinux&logoColor=557C94)
![Git](https://img.shields.io/badge/Git-111111?style=flat&logo=git&logoColor=F05032)

## Currently building

`Detection Engineering Lab`: YAML rule engine mapped to MITRE ATT&CK, with automated response.
