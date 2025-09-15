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
   - Hem creat un **diagrama de xarxa** de l’empresa, mostrant els servidors, routers, firewalls i els fluxos de connexió interns i externs.
   - Hem desenvolupat un **mockup de l’aplicació web interna** amb les següents funcionalitats:
     - Autenticació d’usuaris.
     - Creació d’usuaris.
     - Creació de departaments.
     - Panell administratiu on validar un usuari i assignar-lo a un departament.
     - Registre de monitorització dels equips de l’empresa.
     - Panell de control per veure els logs d’incidents.

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
