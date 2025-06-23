# Home Network Guardian – Final Project

👉 **Live project documentation available at:** [https://lukaszfd.github.io/ICYB_PW-FINAL_PROJECT/#](https://lukaszfd.github.io/ICYB_PW-FINAL_PROJECT/#)

## Abstract (English)

This repository contains the main text (in `.tex` format) of my postgraduate thesis, "Home Network Guardian: Building a Secure Home Network Environment Based on Open Source Solutions", prepared for the postgraduate studies in Cybersecurity Engineering at Warsaw University of Technology.

The thesis documents the process of designing and implementing a secure home network ecosystem using open-source and free tools:
- **Pi-hole** as the primary DNS server,
- **Unbound** for DNS privacy,
- **Squid** as a proxy server,
- **Suricata** for intrusion detection (IDS),
- **Graylog** (with **Elasticsearch** and **MongoDB**) for log aggregation and analysis,
- **Prometheus** and **Grafana** for server monitoring,
- **Firefox** (containerized) for secure browsing,
- **Portainer** for Docker container management,
- **Filebeat** for log shipping (installed directly on the server).

All key architectural, deployment, and configuration details are described in the thesis (see `main.tex`).

> **Configuration files and Docker Compose setups are available in a separate repository:**  
> [github.com/lukaszFD/home-network-guardian](https://github.com/lukaszFD/home-network-guardian)

The project discusses the rationale for service segmentation (Docker networks), firewall configuration, and the benefits of running such an isolated environment. Additional resources, such as architectural diagrams (draw.io) and a dedicated project website, complement the written documentation.

Read more about the project at:  
[ICYB_PW: Home Network Guardian](https://lukaszfd.github.io/ICYB_PW/pages/raspberry_phase2.html)

**Keywords**: DNS, Pi-hole, Unbound, Suricata, Graylog, Prometheus, Grafana, Docker, Firewall, Cybersecurity, Raspberry Pi

---

## Streszczenie (Polski)

To repozytorium zawiera główny tekst mojej pracy końcowej (plik `.tex`), przygotowanej na studiach podyplomowych „Inżynieria Cyberbezpieczeństwa” na Politechnice Warszawskiej, zatytułowanej „Home Network Guardian: Budowa bezpiecznego środowiska sieci domowej na bazie rozwiązań open source”.

Praca szczegółowo opisuje projekt oraz wdrożenie domowego ekosystemu bezpieczeństwa z wykorzystaniem rozwiązań open source:
- **Pi-hole** jako główny serwer DNS,
- **Unbound** dla prywatności zapytań DNS,
- **Squid** jako serwer proxy,
- **Suricata** jako system IDS,
- **Graylog** (wraz z **Elasticsearch** i **MongoDB**) do agregacji i analizy logów,
- **Prometheus** oraz **Grafana** do monitorowania serwera,
- **Firefox** (w kontenerze) do bezpiecznego przeglądania internetu,
- **Portainer** do zarządzania kontenerami Docker,
- **Filebeat** do przesyłania logów (zainstalowany bezpośrednio na serwerze).

Wszystkie kluczowe aspekty architektury, wdrożenia i konfiguracji zostały opisane w pracy (plik `main.tex`).

> **Pliki konfiguracyjne oraz Docker Compose znajdują się w osobnym repozytorium:**  
> [github.com/lukaszFD/home-network-guardian](https://github.com/lukaszFD/home-network-guardian)

W pracy omówiono także uzasadnienie segmentacji usług (sieci Dockera), konfigurację firewalla oraz korzyści wynikające z izolacji środowiska. Całość uzupełniają diagramy architektury (draw.io) oraz dedykowana strona internetowa projektu.

Więcej informacji o projekcie:  
[ICYB_PW: Home Network Guardian](https://lukaszfd.github.io/ICYB_PW/pages/raspberry_phase2.html)

**Słowa kluczowe**: DNS, Pi-hole, Unbound, Suricata, Graylog, Prometheus, Grafana, Docker, Firewall, Cyberbezpieczeństwo, Raspberry Pi
