### Exercici 1
_Explica, amb les teves paraules, què és la programació concurrent i quins avantatges i inconvenients presenta._

**Avantatges**

- Millora l'aprofitament de la CPU
- Velocitat d'execució
- Permet executar diverses tasques simultàneament + d'un processador
- Amb un sol nucli comparteix el temps de processador

**Inconvenients**

- Consum de recursos quan hi ha diversos processos
- Dificultat de desenvolupament
- Dificultat de Verificació
- Si s'aplica malament pot donar resultat erronis


### Exercici 2
_Quines són les diferències entre programació concurrent, programació paral·lela i
programació distribuïda?_
 
**Programació concurrent**  

La programació concurrent es forma de computar processos simultanement utilitzant el temps de processador on es superposen. Son propietats d'un ordinador amb un sol nucli.

**Programació paral·lela**

La programació paral·lela es la forma de computar diferents processos simultàneament, fent servir diferents nuclis per dur les tasques.

**Programació distribuïda**
La programació distribuida és la forma de computar processos comuns, però els components que duen a terme aquesta tasca estan en diferents ordinadors conectats per xarxa.



### Exercici 3
_Explica què és un servei (daemon). Posa algun exemple._
  
Un servei daemon es un proces que s'executa en segon pla i l'usuari el te fora de control. Aquests processos s'executen al iniciar l'ordinador, la funció més comú d'aquest processos es donar servei a altres programes.

### Exercici 4

_Explica en quins estats es pot trobar un procés i com pot passar d’un estat a un altre._

- **Nou:** Quan un procés es creat.
- **Executant/Actiu:** El procés esta executant les seves instruccions en la CPU, i poden haver-hi tant processos com processador hi hagi.
- **Bloquejat:** Esta pendent per un esdeveniment extern que l'ha fet bloquejar.  
	_Per Exemple:_
	- Esperar a que finalitzi un procés fill.
	- Una operació d'escritura o de lectura.
- **Llest/Preparat:** El procés no esta executan-se, però es candidat per pasar a actiu.El planificador es qui amb un criteri decideix quin procés serà el següent.
- **Finalitzat:** El procés ha acabat les instruccions i finalitza la seva execució.



