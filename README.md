# 📌 Projecte ASX2-A/B – projecte-asx2A-B--Nicol-s-Y-Albert

## 👥 Integrants
- Albert (@QuercusJS)
- Nicolás (@bergesita)
  
## 🎯 Descripció del projecte
Aquest projecte forma part del mòdul de ciberseguretat ASX2.  
L’objectiu és dissenyar i defensar la infraestructura d’una **empresa fictícia**, que inclou:
- Active Directory amb usuaris i polítiques.
- Una aplicació web amb BBDD SQL i NoSQL.
- Honeypots per a cada servei exposat.
- WAF per protegir la web.
- (Opcional) SIEM / n8n + IA per centralitzar i analitzar logs.

## 📆 Fases inicials del projecte
1. **Disseny + AD base**  
   - Diagrama de xarxa, AD/Samba4 amb OU, usuaris i GPO.

2. **Consolidació AD**  
   - Polítiques de seguretat i proves de login remot.

3. **Aplicació web I**  
   - Web bàsica amb login i rols, contenidor Docker inicial.

4. **Aplicació web II**  
   - Integració de BBDD SQL i NoSQL.

5. **Honeypots Web/AD/SMB/LDAP**  
   - Deploy inicial de honeypots per a serveis crítics.

## 📋 Organització del treball
El seguiment del projecte es fa amb **GitHub Projects**:  
➡️ [https://github.com/bergesita/projecte-asx2A-B--Nicol-s-Y-Albert-](URL_DEL_PROJECT)

Columnes: `Backlog` → `En Progrés` → `Fet`  
Cada tasca ha de tenir un responsable assignat i una data prevista.

## 📂 Estructura inicial del repositori
```
/docs/              → Documentació i informes
/src/               → Codi de l’aplicació web
/config/            → Configuracions (AD, WAF, Honeypots)
/scripts/           → Scripts de suport
```

## 📝 Llicència
Indicar si el projecte és lliure o només per ús acadèmic.
esto es mi readme, añade que hemos hecho un diagrama de red de una empresa y un mockup con estos puntos:
Autenticació d'usuaris.
Creació d'usuaris.
Creació departaments.
Panell administratiu on validar un usuari i assignar-lo a un departament.
Registre de monitoritzacio dels equips de lempresa.
Panell de control on veure els logs de incidents.
