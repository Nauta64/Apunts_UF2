# Apuntes_UF2_1

## QUE ES FA EN AQUESTA UF?

- Identificar els diferents tipus de proves.
- Definir casos de prova.
- Efectuar proves unitàries de classes i funcions.
- Efectuar proves d'integració, de sistema i d'acceptació.
- Realitzar mesures de qualitat sobre el programari desenvolupat.


### OBJECTIUS PROVES

Les proves es centren en dos objectius:
1. Provar si el programari no fa el que ha de fer.
2. Provar si el programari fa el que no ha de fer.

Per fer les proves utilizem diferents **frameworks**.

### Model en V

Es un model molt semblant a el model en cascada.
- Visió jerarquitzada amb diferents nivells.
- Els nivells superiors indiquen major abstracció.
- Els nivells inferiors indiquen major nivell de detall.
- El resultat d'una fase és l'entrada de la següent fase.
- Existeixen diferents variants amb més o menys quantitat d'activitats.



### FRAMEWORK

Els framework estan compostos per:

- un conjunt de les millors pràctiques i suposicions
- eines comunes
- biblioteques

Permet unificar el procés de desenvolupament entre desenvolupadors.




## **PROVES**

Tenim dos tipus:

- **Proves dinàmiques:** Requereixen l'execució de l'aplicació. Permeten mesurar el comportament de l'aplicació desenvolupada.

- **Proves estàtiques:** Es realitzen sense executar el codi de l'aplicació. S'examina el codi font.



### ESTRATÈGIES DE PROVA DE CAIXA NEGRA
- S'estudia el sistema des de fora.
- Es treballa sobre la interfície.
- No es tenen en compte els detalls interns de funcionament.
- Es proporcionen entrades i s'estudien les sortides.
- Principals tècniques:
  - Particions d'equivalència
  - Valors límit

### ESTRATÈGIES DE PROVA DE CAIXA BLANCA
- S'examina el codi font i la seva execució.
- Es comproven els fluxos d'execució dins de cada unitat (funció, classe, mòdul, etc.)
- També poden comprovar els fluxos entre unitats durant la integració.
- I fins i tot entre subsistemes, durant les proves de sistema.
- Principals tècniques:
  - Cobertura de codi
  - Prova de bucles


### TIPUS DE PROVES
**Funcionals:** Avaluen el compliment dels requisits.

**No funcionals:** Avaluen aspectes addicionals com rendiment, seguretat, ...



### PROVES FUNCIONALS
- Proves unitàries (o d'unitat)
- Proves de regressió
- Proves d'integració
- Proves de fum (proba de foc)
- Proves de sistema
- Proves alfa i beta
- Proves d'acceptació (validació per part de client)


### PROVES NO FUNCIONALS
- Proves d'usabilitat
- Proves de rendiment
- Proves d'estrés
- Proves de seguretat
- Proves de compatibilitat
- Proves de portabilitat

### MECANISMES DE PROVA
Tenim dos tipus:
- **Manual:** Mitjançant proves realitzades per personal de l'empresa o extern.
- **Automàtic:** Mitjançant programari que executa codi de forma automatitzada i compara els resultats obtinguts i els resultats esperats.


## INTEGRACIÓ
### FORMES D'INTEGRACIÓ
- Integració Big Bang
- Integració Descendent
- Integració Ascendent
- Integració Contínua (**CI**)

### SERVIDORS D'INTEGRACIÓ CONTINUA
    CI: Integració continua
    CD: Entrega continua
    
- Jenkins
- Bamboo
- TravisCI
- CircleCI

### COBERTURA DEL CODI
Mesura que indica el percentatge de codi que ha estat executat durant les proves.
- Es recomana que sigui lo mñes proper a 100%.
- Si és **de l'100%** llavors s'ha executat tot el codi font durant les proves.
- Si és **menor de l'100%** llavors existeix codi font que no s'ha executat durant les proves.
- És possible realitzar la cobertura tant des del IDE com des d'un servei web apropiat.


## QUALITAT
### CONTROL DE QUALITAT
Objectiu:
- Aconseguir una mesura de la qualitat d'un producte
Per aconseguir-ho necessitem fer:
- Proves

### QUALITAT DE L'PROCÉS / PRODUCTE (QA / QC)
- **QA:** és un conjunt d'activitats per a garantir la qualitat en els processos mitjançant els quals es desenvolupen els productes.
- **QC:** és un conjunt d'activitats per a garantir la qualitat dels productes. Les activitats se centren en identificar defectes en els productes reals produïts.


### FACTORS DE QUALITAT
Els factors de qualitat s'agrupen en **3 àmbits**:
- Operació de l'producte
- Revisió del producte
- Transició del producte

**Operació del Producte**
- Correcció
- Fiabilitat
- Eficiència
- Seguretat
- Facilitat d'ús

**Revisió del Producte**
- Mantenibilitat
- Flexibilitat
- Facilitat de prova

**Transició del producte**
- Portabilitat
- Reusabilitat
- Interoperativitat
