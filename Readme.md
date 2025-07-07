# OUTILS DE CYBERSÉCURITÉ : NMAP, DMITRY, WIRESHARK

##  Présentation rapide

- **Nmap** : scanner les ports ouverts sur une machine ou un réseau.
- **Dmitry** : collecter des informations sur un site ou une IP.
- **Wireshark** : analyser les paquets qui circulent sur un réseau.

---

##  Détails utiles

### 🔹 NMAP (Network Mapper):
- Sert à découvrir les ports ouverts, les services actifs et les versions logicielles sur une cible.
- Très utile pour savoir ce qui tourne sur un serveur ou un PC.
  Exemple :
  nmap -sV 192.168.1.1
  
###  🔹 DMITRY (Deepmagic Information Gathering Tool)
-Permet de collecter passivement des infos sur un domaine : WHOIS, DNS, e-mails, sous-domaines.
-Idéal pour faire du "footprinting" avant un test de sécurité.
Exemple :
dmitry -winsep example.com


###🔹 WIRESHARK
-Sert à capturer et examiner tout ce qui transite sur un réseau (HTTP, DNS, TCP, etc.).
On peut y voir les IP, les ports, les requêtes, etc.
Étapes :
1. Lancer Wireshark
2. Choisir l’interface réseau (ex : wlan0)
3. Cliquer sur “Start”
4. Utiliser des filtres comme http, tcp, ip.addr == 192.168.1.1

