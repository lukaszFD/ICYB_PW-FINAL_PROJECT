# Home Network Guardian – Final Thesis Project

## Abstract (English)

This repository contains documentation and configuration files for my postgraduate thesis project at Warsaw University of Technology, "Home Network Guardian: Building a Secure Home Network Environment Based on Open Source Solutions".

The project focuses on the practical design and implementation of a home cybersecurity ecosystem using the following open-source and free tools:
- **Pi-hole** as the primary DNS server,
- **Unbound** for DNS privacy,
- **Squid** as a proxy server,
- **Suricata** for IDS (Intrusion Detection System) functionality,
- **Graylog** (with **Elasticsearch** and **MongoDB**) for log aggregation and analysis,
- **Prometheus** and **Grafana** for server monitoring and visualization,
- **Firefox** (containerized) for secure web browsing,
- **Portainer** for managing Docker containers,
- **Filebeat** for log shipping (installed directly on the server).

Most services are containerized using Docker Compose to ensure strong network segmentation and easy management. The project includes a hardened firewall configuration, with only necessary ports exposed, increasing the overall security of the environment. Isolation between different services (e.g., dedicated DNS resolver for Firefox) has also been implemented.

The documentation and diagrams (draw.io) illustrate the architecture, deployment steps, and the rationale for individual design decisions. The project also discusses the benefits of running such an ecosystem in a separated Docker network, as well as practical firewall policies.

In addition, the work is complemented by a dedicated website describing the implementation: [ICYB_PW: Home Network Guardian](https://lukaszfd.github.io/ICYB_PW/pages/raspberry_phase2.html).

**Keywords**: DNS, Pi-hole, Unbound, Suricata, Graylog, Prometheus, Grafana, Docker, Firewall, Cybersecurity, Raspberry Pi

---

## Streszczenie (Polski)

Repozytorium zawiera dokumentację oraz pliki konfiguracyjne do mojej pracy końcowej na studiach podyplomowych „Inżynieria Cyberbezpieczeństwa” na Politechnice Warszawskiej, zatytułowanej „Home Network Guardian: Budowa bezpiecznego środowiska sieci domowej na bazie rozwiązań open source”.

Projekt skupia się na praktycznym zaprojektowaniu oraz wdrożeniu ekosystemu bezpieczeństwa domowego, z wykorzystaniem następujących rozwiązań:
- **Pi-hole** jako główny serwer DNS,
- **Unbound** dla prywatności zapytań DNS,
- **Squid** jako serwer proxy,
- **Suricata** jako system IDS (Intrusion Detection System),
- **Graylog** (wraz z **Elasticsearch** i **MongoDB**) do agregacji i analizy logów,
- **Prometheus** oraz **Grafana** do monitoringu serwera,
- **Firefox** (w kontenerze) do bezpiecznego przeglądania Internetu,
- **Portainer** do zarządzania kontenerami Docker,
- **Filebeat** do przesyłania logów (zainstalowany bezpośrednio na serwerze).

Większość usług uruchomiona jest w kontenerach Docker Compose, co zapewnia silną segmentację sieci i łatwość zarządzania. Projekt obejmuje również utwardzoną konfigurację firewalla – otwarte są jedynie niezbędne porty, co znacząco podnosi poziom bezpieczeństwa. Zaimplementowano też separację usług, np. oddzielny resolver DNS dla przeglądarki Firefox.

Dokumentacja oraz diagramy (draw.io) ilustrują architekturę, kroki wdrożenia oraz uzasadnienie wyborów projektowych. Praca opisuje także korzyści z uruchamiania takiego środowiska w odizolowanej sieci Dockera oraz praktyczne aspekty konfiguracji firewalla.

Dodatkowo przygotowana została strona internetowa z opisem wdrożenia: [ICYB_PW: Home Network Guardian](https://lukaszfd.github.io/ICYB_PW/pages/raspberry_phase2.html).

**Słowa kluczowe**: DNS, Pi-hole, Unbound, Suricata, Graylog, Prometheus, Grafana, Docker, Firewall, Cyberbezpieczeństwo, Raspberry Pi

