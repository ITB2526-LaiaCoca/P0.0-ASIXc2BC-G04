# Planificació

## 1. Metodologia

El projecte es planifica amb **ProofHub** seguint una metodologia àgil:

- Sprints quinzenals de 10 h de feina per persona (5 h setmanals).
- 3 sprints en total.
- Projecte a ProofHub: `P0.0-ASIXc2gC-G04`.
- Backlog de projecte amb totes les tasques definides a ProofHub.

## 2. Equip i responsabilitats

| Persona | Equips assignats |
|---|---|
| Laia | R-N04 (router), S-N04 (SSH), F-N04 (FTP) |
| Brenda | DN-N04 (DNS), DH-N04 (DHCP), PW-N04 (client Windows) |
| Aleshka | W-N04 (web), B-N04 (BBDD), PU-N04 (client Ubuntu) |

## 3. Calendari de sprints

| Sprint | Dates (MODIFICAR!!!!!) | Objectiu |
|---|---|---|
| Sprint 1 | 07/10 – 20/10 | Xarxa base i serveis fonamentals |
| Sprint 2 | 21/10 – 03/11 | Serveis de dades, web i clients |
| Sprint 3 | 04/11 – 18/11 | Aplicació de proves, documentació i tancament |

## 4. Backlog de projecte

### Sprint 1 · Xarxa base i serveis fonamentals

| Tasca | Estat |
|---|---|
| Definir diagrama d'arquitectura | ✅ |
| Crear repositori GitHub i estructura de documentació | ✅ |
| Desplegar router R-N04 (3 interfícies) | ✅ |
| Configurar IP forwarding i NAT al router | ✅ |
| Regles de filtratge entre DMZ, Intranet i NAT | ✅  |
| Desplegar servidor DNS DN-N04 | ✅  |
| Desplegar servidor DHCP DH-N04 | ✅  |
| Crear usuari `bchecker` a tots els sistemes | ✅  |

### Sprint 2 · Serveis de dades, web i clients

| Tasca | Estat |
|---|---|
| Desplegar servidor SSH S-N04 | ✅ |
| Desplegar servidor FTP F-N04 | ☐ |
| Desplegar B-N04 amb MySQL | ☐ |
| Descarregar CSV i carregar-lo a la BBDD | ☐ |
| Desplegar servidor web W-N04 | ☐ |
| Configurar DNS: resolució de `R-N04` i `R` | ☐ |
| Client Windows PW-N04 (DHCP + SSH) | ☐ |
| Client Ubuntu PU-N04 (DHCP + SSH) | ☐ |
| Instal·lar SSH i `bchecker` a tots els equips | ✅  |

### Sprint 3 · Aplicació, documentació i tancament

| Tasca | Estat |
|---|---|
| Aplicació que mostri les taules carregades | ☐ |
| Regla del router: web (DMZ) → MySQL (Intranet) | ☐ |
| Clau pública/privada servidor ↔ GitHub | ☐ |
| Documentar control de versions (git add/commit/push/pull/clone) | ☐ |
| Documentació de cada servei amb captures | ☐ |
| Proves finals d'extrem a extrem | ☐ |
| Revisió final del repositori i lliurament | ☐ |

## 5. Seguiment

- Reunió de revisió al final de cada sprint.
- Estat de les tasques actualitzat a ProofHub.
- Els problemes trobats es documenten a cada README de servei.

## 6. Captures de ProofHub

(PONER LAS CAPTURAS DEL PROOFHUB!!!!!!!!!!!!!!!!!!!!!!!!! gracias.)
