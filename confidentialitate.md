---
description: Documente legale pentru etruvio — aplicația de bunăstare digitală pentru familie, de la CODE4ALL SRL.
---

# Politica de confidențialitate — etruvio

**Ultima actualizare:** 16 septembrie 2026
**Data intrării în vigoare:** 16 septembrie 2026

[English](./) · [Suport](suport)

Această Politică de confidențialitate descrie modul în care **CODE4ALL SRL** („noi", „nouă" sau „etruvio") colectează, utilizează și protejează datele cu caracter personal atunci când folosiți aplicația mobilă **etruvio** pentru Android și iOS („Aplicația") și serviciul aferent dedicat bunăstării digitale a familiei.

Suntem stabiliți în România și prelucrăm datele cu caracter personal în conformitate cu Regulamentul General privind Protecția Datelor al UE (RGPD/GDPR), Legea nr. 190/2018 și normele aplicabile privind confidențialitatea copiilor.

---

## 1. Cine suntem

**Operator de date:** CODE4ALL SRL
**CUI / TVA:** RO44417884
**Registrul Comerțului:** J2021000917152
**Sediu social:** Str. Stejarului 128 F, Sat Ulmi, jud. Dâmbovița, cod poștal 137455, România
**Email:** privacy@etruvio.ro
**Website:** https://etruvio.ro

Dacă aveți întrebări despre această politică sau doriți să vă exercitați drepturile, contactați-ne la adresa de email de mai sus.

---

## 2. Cine folosește etruvio

etruvio este un **serviciu dedicat bunăstării digitale a familiei**. Există două categorii de utilizatori:

- **Părinți (titulari de cont)** — adulți care creează un cont, administrează unul sau mai mulți copii și configurează regulile.
- **Copii** — minori ale căror dispozitive sunt administrate de un părinte. Copiii nu își creează cont propriu; ei primesc un profil de copil, creat și controlat de părintele lor.

Aplicația **nu se adresează copiilor sub 16 ani care acționează în nume propriu**. Copiii folosesc Aplicația exclusiv printr-un profil configurat și supravegheat de un părinte sau tutore legal.

---

## 3. Ce date colectăm

### 3.1 De la părinți

Când un părinte își creează un cont sau folosește Aplicația, prelucrăm:

- **Date de cont:** adresa de email, parola (stocată sub formă de hash de către furnizorul nostru de autentificare), numele afișat, avatarul (opțional)
- **Autentificare prin Google:** dacă părintele alege să se autentifice cu contul său Google, primim de la Google adresa de email, numele și fotografia de profil (domeniile standard `openid email profile`). **Nu** solicităm acces la Gmail, Drive, Contacte sau la orice alt serviciu Google.
- **Token-uri de autentificare** (sesiuni)
- **Datele familiei:** numele familiei, setările și preferințele pe care le configurați
- **Misiuni, privilegii și reguli:** sarcinile, punctele/privilegiile și regulile de timp de ecran create de părinte
- **Invitații:** dacă părintele invită un alt adult (tutore/partener) în familie, prelucrăm adresa de email a persoanei invitate și un token de invitație de unică folosință, pentru a livra invitația
- **Mesaje și notițe în aplicație:** mesajele schimbate în interiorul familiei între părinte și copil prin inbox-ul din aplicație, inclusiv notițele atașate misiunilor și mesajele scurte atașate achizițiilor de privilegii. Aceste mesaje sunt vizibile doar membrilor familiei și nouă, în calitate de operator al serviciului; ele nu sunt partajate cu nimeni altcineva.
- **Date de asociere a dispozitivelor:** identificatorii dispozitivelor pe care le conectați la familie
- **Comunicări:** mesajele pe care ni le trimiteți către suport

### 3.2 De la copii (introduse de părinte)

Pentru fiecare profil de copil, părintele furnizează:

- Prenumele (sau o poreclă)
- Data nașterii sau grupa de vârstă
- Avatarul (ales dintr-un set fix de pictograme ilustrate — nu acceptăm fotografii încărcate)
- Programul, limitele de timp de ecran și regulile configurate de părinte

În timp ce copilul folosește Aplicația pe dispozitivul său, etruvio stochează și:

- **Starea de gamificare:** soldul de puncte, nivelul, experiența totală (XP) și seria zilnică. Acestea sunt puncte *fictive*, utilizate exclusiv în interiorul etruvio — nu au valoare monetară, nu pot fi schimbate în bani reali și nu există achiziții în aplicație.
- **„Portofelul" de privilegii:** privilegiile deblocate de copil cu punctele sale (tipul de privilegiu, statusul și, opțional, un mesaj scurt atașat de copil).
- **Notițe/mesaje** pe care copilul le scrie când trimite o misiune spre aprobare sau când solicită un privilegiu (a se vedea §3.1).
- **Token-uri de autentificare** pentru sesiunea de pe dispozitivul copilului (separate de token-urile părintelui).

### 3.3 De pe dispozitivul administrat al copilului (Android)

Când etruvio este instalat pe dispozitivul Android al unui copil, prelucrăm (pentru iOS, a se vedea §3.9):

- **Date de utilizare a aplicațiilor** (ce aplicații rulează în prim-plan și pentru cât timp), folosite **exclusiv** pentru a aplica regulile stabilite de părinte — de exemplu pentru a bloca o aplicație restricționată sau pentru a contoriza timpul de ecran. Acestea sunt colectate prin permisiunea Android `PACKAGE_USAGE_STATS`.
- **Lista aplicațiilor instalate**, folosită pentru ca părintele să poată alege ce aplicații sunt permise sau restricționate (`QUERY_ALL_PACKAGES`).
- **Coduri de asociere** scanate cu camera dispozitivului (a se vedea §3.4).
- **Identificatorul dispozitivului:** valoarea `ANDROID_ID` furnizată de sistemul de operare (un identificator specific fiecărei aplicații și fiecărui dispozitiv, limitat la etruvio; pe Android 8 și versiunile ulterioare diferă între aplicații). Îl folosim pentru a recunoaște același dispozitiv în fluxurile de asociere, astfel încât un părinte să nu asocieze din greșeală același dispozitiv de două ori.
- **Informații despre dispozitiv:** producătorul, modelul, numele platformei („Android") și versiunea sistemului de operare, transmise în momentul asocierii, pentru ca părintele să poată deosebi dispozitivele copiilor în panoul de control.
- **Semnal periodic de stare (heartbeat):** nivelul bateriei, starea de încărcare, numele pachetului aplicației aflate în prim-plan și statusul permisiunilor acordate. Acesta este trimis periodic în timp ce copilul folosește dispozitivul, pentru ca panoul de control al părintelui să poată arăta dacă dispozitivul este online, dacă se încarcă și ce aplicație este deschisă. **Nu** înregistrăm conținutul ecranului, tastele apăsate, sunetul sau orice altceva din aplicația aflată în prim-plan — doar numele pachetului acesteia.
- **Istoricul de activitate:** o evidență a evenimentelor din aplicație care afectează familia (misiune trimisă/aprobată/respinsă, privilegiu cumpărat, program modificat, blocare de urgență activată, membru adăugat/eliminat etc.), pentru ca părintele să poată consulta cronologia. Evidența conține tipul evenimentului, marca temporală, membrul familiei care l-a efectuat și orice schimbare de stare implicată (de exemplu, soldul de puncte înainte/după). **Nu** conține conținut din afara etruvio.
- **Locația dispozitivului (opțional, la cerere):** dacă părintele a activat permisiunea opțională de Locație pe dispozitivul copilului, etruvio poate prelua o **singură** poziție (latitudine, longitudine și acuratețe aproximativă) a acelui dispozitiv, **doar atunci când părintele o solicită explicit** din panoul său de control — de exemplu pentru a găsi un telefon rătăcit. Locația nu este **niciodată** colectată continuu sau în fundal. Se stochează doar cea mai recentă poziție, pentru ca părintele să o poată vedea pe hartă (printr-un link Google Maps); aceasta este suprascrisă la următoarea solicitare și ștearsă când dispozitivul sau familia este eliminată. Locația este obținută prin permisiunea Android `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`, care este **dezactivată implicit** și trebuie acordată explicit (a se vedea §3.7).
- **Nu** colectăm **ID-ul de publicitate (Advertising ID)**, **IMEI**, **adresa MAC**, **IMSI** sau **numărul de serie hardware**.
- **Date de diagnosticare** strict necesare pentru funcționarea serviciului: marcaje temporale ale evenimentelor legate de reguli, jurnale de erori (fără conținutul mesajelor).

**Nu** accesăm:
- Fotografii, videoclipuri sau fișiere de pe dispozitiv
- Contacte, calendar sau jurnale de SMS-uri/apeluri
- Microfonul sau sunetul
- Istoricul de navigare sau conținutul web
- Conținutul mesajelor sau al notificărilor din alte aplicații

### 3.4 Camera

Aplicația solicită acces la cameră **exclusiv** pentru a scana un cod QR la asocierea dispozitivului unui copil cu familia părintelui. Imaginile captate de cameră sunt procesate local, pe dispozitiv, de Google ML Kit (pe dispozitiv, offline) și **nu** sunt niciodată încărcate, înregistrate sau stocate.

### 3.5 Serviciul de accesibilitate

Aplicația declară un serviciu Android de accesibilitate. Acesta este folosit **exclusiv** pentru a detecta momentul în care o aplicație restricționată ajunge în prim-plan, astfel încât etruvio să poată afișa ecranul de blocare și să aplice regulile configurate de părinte. Serviciul **nu** citește textul de pe ecran, nu captează datele introduse în formulare, nu copiază conținutul din clipboard și nu transmite niciun eveniment de accesibilitate către serverele noastre.

### 3.6 Suprapunerea peste alte aplicații

Aplicația solicită permisiunea de a afișa conținut peste alte aplicații (`SYSTEM_ALERT_WINDOW`) **exclusiv** pentru a afișa ecranul de blocare atunci când este deschisă o aplicație restricționată. Nu se afișează publicitate sau conținut care nu are legătură cu regulile de bunăstare digitală configurate de părinte.

### 3.7 Toate permisiunile sensibile se acordă explicit

Permisiunile descrise la §3.3 – §3.6 — **Acces la utilizare** (`PACKAGE_USAGE_STATS`), **Serviciul de accesibilitate**, **Afișare peste alte aplicații** (`SYSTEM_ALERT_WINDOW`), **Camera** și permisiunea opțională de **Locație** (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`) — sunt considerate permisiuni „speciale" sau „de rulare" în Android. Niciuna nu este acordată în mod tacit la instalarea Aplicației. Pentru fiecare dintre ele, părintele trebuie să:

1. Deschidă Aplicația pe dispozitivul copilului,
2. Apese pe mesajul afișat, care explică la ce servește permisiunea și de ce are etruvio nevoie de ea,
3. Fie redirecționat către ecranul corespunzător din Setările Android și
4. Activeze manual permisiunea pentru etruvio.

Părintele poate revoca oricând oricare dintre aceste permisiuni, din aceleași ecrane ale Setărilor Android. Când o permisiune este revocată, funcționalitatea aferentă încetează să funcționeze, dar nicio altă dată cu caracter personal nu este afectată.

### 3.8 Notificări push

Pentru a livra notificări pe dispozitivul unui părinte sau al unui copil chiar și când Aplicația este închisă (de exemplu, „o misiune așteaptă aprobare" sau „ai o misiune nouă"), etruvio folosește **Firebase Cloud Messaging (FCM)**, un serviciu furnizat de Google. Aceasta presupune:

- **Token-ul push:** la pornirea Aplicației, dispozitivul obține de la Firebase un **token de înregistrare** unic. Stocăm acest token — asociat contului de părinte sau profilului de copil și dispozitivului asociat — **exclusiv pentru a direcționa notificările către dispozitivul corect**. Nu este un identificator de publicitate și nu este folosit pentru urmărire sau profilare. Token-ul este șters când dispozitivul este disociat, când familia sau contul este șters sau când token-ul devine invalid.
- **Conținutul notificărilor:** textul unei notificări poate include **prenumele** unui membru al familiei și **titlul misiunii sau al privilegiului** la care se referă (de exemplu, *„{copil} a trimis «{misiune}» spre aprobare"*) și — în cazul unei invitații în familie care este refuzată — **adresa de email** a persoanei invitate. Acest conținut trece prin serverele FCM ale Google exclusiv pentru a livra notificarea pe dispozitivul destinatarului. Nu este stocat de noi dincolo de intrarea corespunzătoare din inbox-ul aplicației, descrisă la §3.1.
- **Mesaje silențioase de „trezire":** pentru evenimente de aplicare a regulilor (o modificare a regulilor, o sincronizare la cerere sau o solicitare de locație la cerere), etruvio trimite un mesaj care conține doar date, format dintr-un singur cuvânt-cheie ce indică tipul evenimentului și **nicio dată cu caracter personal**.

Pe Android 13 și versiunile ulterioare, afișarea notificărilor necesită și permisiunea de rulare **Notificări**, pe care utilizatorul o poate acorda sau refuza. Folosim notificările push **exclusiv pentru funcționarea serviciului** — nu trimitem niciodată notificări de marketing sau de publicitate.

### 3.9 Pe iOS (iPhone / iPad)

Versiunea pentru iOS a Aplicației funcționează diferit față de Android, deoarece Apple nu permite aplicațiilor terțe să observe alte aplicații. Pe un dispozitiv iOS prelucrăm:

- **Identificatorul dispozitivului:** valoarea `identifierForVendor` furnizată de iOS (un identificator limitat la aplicațiile CODE4ALL de pe acel dispozitiv; se resetează când toate aplicațiile noastre sunt dezinstalate). Îl folosim pentru a recunoaște același dispozitiv în fluxurile de asociere.
- **Informații despre dispozitiv:** modelul, numele platformei („iOS") și versiunea sistemului de operare, transmise la asociere, pentru ca părintele să poată deosebi dispozitivele.
- **Semnal periodic de stare (heartbeat):** nivelul bateriei, starea de încărcare și permisiunile de sistem acordate Aplicației, transmise periodic cât timp copilul folosește Aplicația. Pe iOS **nu** primim aplicația aflată în prim-plan și **nu** citim lista aplicațiilor instalate.
- **Regulile de timp de ecran și de concentrare** sunt aplicate prin cadrul **Screen Time** al Apple (Family Controls, Device Activity, Managed Settings). Acest cadru rulează pe dispozitiv și nu ne dezvăluie niciodată ce aplicații folosește copilul sau pentru cât timp; Aplicația primește de la serverul nostru doar minutele de timp de ecran acordate de părinte și le aplică local.
- **Camera:** folosită exclusiv pentru scanarea codului QR de asociere, procesată pe dispozitiv de scanerul de sistem; imaginile nu sunt niciodată încărcate sau stocate.
- **Notificările push** sunt livrate prin **Apple Push Notification service** (APNs), direcționate prin Firebase Cloud Messaging conform §3.8.
- **Sign in with Apple:** dacă părintele alege această opțiune, primim de la Apple un identificator de utilizator stabil, numele (doar la prima autentificare) și fie adresa de email reală, fie o adresă de redirecționare „Hide My Email" de la Apple.
- **Locația nu** este colectată pe iOS.

---

## 4. Cum folosim datele

Folosim datele de mai sus exclusiv pentru a:

1. **Furniza serviciul** — a crea conturi, a conecta dispozitive, a aplica regulile, a calcula timpul de ecran, a livra misiunile și privilegiile configurate de părinte și — dacă permisiunea opțională de Locație este activată — a localiza un dispozitiv administrat atunci când părintele solicită acest lucru în mod explicit.
2. **Securiza serviciul** — a detecta abuzurile, a preveni accesul neautorizat, a audita acțiunile administrative.
3. **Oferi suport** — a răspunde întrebărilor dumneavoastră când ne contactați.
4. **Respecta legea** — a răspunde solicitărilor legale legitime.

**Nu** folosim datele cu caracter personal pentru publicitate, pentru profilare în scopuri de marketing sau pentru vânzare către terți.

---

## 5. Temeiuri legale (art. 6 / 8 RGPD)

| Scop | Temei legal |
|---|---|
| Furnizarea serviciului către părinte | Contract (art. 6 alin. (1) lit. b)) |
| Prelucrarea datelor copiilor în numele părintelui | Autoritatea părintească și consimțământul (art. 6 alin. (1) lit. a) / art. 8) |
| Securizarea conturilor și detectarea abuzurilor | Interes legitim (art. 6 alin. (1) lit. f)) |
| Localizarea unui dispozitiv administrat la cererea părintelui (opțional) | Autoritatea părintească și consimțământul (art. 6 alin. (1) lit. a) / art. 8) și interesul legitim privind siguranța familiei (art. 6 alin. (1) lit. f)) |
| Obligații legale | Art. 6 alin. (1) lit. c) |

**Părintele** este responsabil să verifice că deține autoritatea părintească asupra copilului al cărui profil îl creează.

---

## 6. Partajare și persoane împuternicite

Nu vindem și nu închiriem date cu caracter personal. Partajăm date exclusiv cu următoarele persoane împuternicite de operator, fiecare fiind obligată printr-un acord de prelucrare a datelor:

| Persoană împuternicită | Scop | Regiune de găzduire |
|---|---|---|
| **Supabase** (Supabase Inc. / Supabase Ireland) | Autentificare, bază de date, edge functions, canale realtime | Elveția — Zürich (Europa Centrală) |
| **Google Identity Services** (Google Ireland Ltd.) | Autentificarea opțională „Sign in with Google" pentru părinți — primește adresa de email, numele și fotografia de profil ale contului Google | UE / global |
| **Google Play Services** | Distribuția aplicației, actualizări în aplicație, verificări de integritate | UE / global |
| **Firebase Cloud Messaging** (Google Ireland Ltd. / Google LLC) | Livrarea notificărilor push către dispozitivele părinților și ale copiilor (a se vedea §3.8) | UE / global |
| **Apple** (Apple Distribution International Ltd.) | Distribuția prin App Store; autentificarea opțională „Sign in with Apple" pentru părinți (identificator de utilizator, nume, email sau adresă de redirecționare); Apple Push Notification service pentru livrarea notificărilor pe dispozitivele iOS (a se vedea §3.9) | UE / global |
| **Resend** (Resend, Inc.) | Livrarea emailurilor tranzacționale: verificarea contului, resetarea parolei, invitațiile în familie | UE (Irlanda) |
| **Hostinger** (Hostinger International Ltd.) | Găzduirea website-ului, verificarea deep-link-urilor | UE |

Când un părinte alege să deschidă pe hartă ultima locație cunoscută a unui dispozitiv, coordonatele sunt transmise către **Google Maps** (Google) de către dispozitivul propriu al părintelui, pentru a afișa harta; etruvio nu divulgă în alt mod locația către terți.

În prezent nu folosim servicii terțe de analiză, SDK-uri de publicitate sau servicii de raportare a erorilor (crash reporting).

---

## 7. Transferuri internaționale

O parte dintre datele pe care le prelucrăm sunt stocate pe servere situate în **Elveția** (operate de Supabase). Elveția nu este membră a Spațiului Economic European, însă Comisia Europeană a emis o **decizie de adecvare** pentru Elveția (Decizia de punere în aplicare (UE) 2024/2493 a Comisiei, care reînnoiește decizia anterioară), ceea ce înseamnă că datele cu caracter personal pot fi transferate acolo la același nivel de protecție garantat în interiorul SEE, fără garanții suplimentare.

Pentru orice alt transfer de date cu caracter personal în afara Spațiului Economic European, ne bazăm pe Clauzele contractuale standard ale UE (Decizia de punere în aplicare (UE) 2021/914 a Comisiei) și pe garanții suplimentare, conform cerințelor RGPD.

---

## 8. Păstrarea datelor

| Date | Perioadă de păstrare |
|---|---|
| Datele familiei (profiluri de copii, reguli, istoricul timpului de ecran) | Până când părintele șterge familia din Aplicație, apoi sunt șterse imediat |
| Contul părintelui (email, credențiale de autentificare) | Se șterge imediat când părintele își șterge contul din Aplicație (**Setări → Securitate → Șterge contul meu**) sau în termen de 30 de zile de la o solicitare prin email |
| Profilurile copiilor | Se șterg automat când părintele șterge familia sau contul |
| Evenimente de timp de ecran și de utilizare | Până la 12 luni, într-o fereastră glisantă, apoi sunt agregate sau șterse |
| Locația dispozitivului (ultima poziție preluată la cerere) | Se stochează doar cea mai recentă poziție; este suprascrisă la fiecare nouă solicitare și ștearsă când dispozitivul sau familia este ștearsă |
| Token-ul pentru notificări push | Până când dispozitivul este disociat, familia/contul este șters sau token-ul devine invalid |
| Jurnalele de autentificare | Până la 12 luni |
| Mesajele către suport | Până la 24 de luni |
| Copiile de siguranță | Criptate, rotite în termen de 30 de zile |

Puteți solicita oricând ștergerea anticipată (a se vedea §10).

---

## 9. Securitate

Protejăm datele prin:

- HTTPS/TLS pentru tot traficul dintre client și server
- Criptare în repaus (gestionată de Supabase)
- Politici Row-Level Security la nivelul bazei de date
- Credențiale separate pentru sesiunile părinților și cele ale copiilor
- Acces restricționat la sistemele de producție, strict pe baza necesității de a cunoaște

Niciun sistem nu este perfect sigur. Dacă luăm cunoștință de o încălcare a securității datelor cu caracter personal care vă afectează, vă vom notifica pe dumneavoastră și autoritatea de supraveghere competentă, conform legii.

---

## 10. Drepturile dumneavoastră

În temeiul RGPD, dumneavoastră (iar în cazul unui copil, părintele în numele acestuia) aveți dreptul la:

- **Acces** la datele cu caracter personal pe care le deținem despre dumneavoastră
- **Rectificarea** datelor inexacte
- **Ștergerea** datelor („dreptul de a fi uitat")
- **Restricționarea** prelucrării sau **opoziția** față de aceasta
- **Portabilitatea** — primirea datelor dumneavoastră într-un format structurat, care poate fi citit automat
- **Retragerea consimțământului** în orice moment, acolo unde prelucrarea se bazează pe consimțământ
- **Depunerea unei plângeri** la Autoritatea Națională de Supraveghere a Prelucrării Datelor cu Caracter Personal (ANSPDCP, https://www.dataprotection.ro/)

Pentru a exercita oricare dintre aceste drepturi, scrieți-ne la **privacy@etruvio.ro**. Răspundem în termen de 30 de zile.

Puteți șterge familia și toate datele din interiorul acesteia direct din Aplicație: **Setări → Familii → Șterge familia**. Puteți șterge și contul propriu-zis (emailul și credențialele de autentificare, împreună cu familiile pe care le dețineți) din Aplicație: **Setări → Securitate → Șterge contul meu** — ștergerea este imediată. Dacă preferați, contactați-ne la **privacy@etruvio.ro** și îl vom șterge în termen de 30 de zile.

---

## 11. Confidențialitatea copiilor

etruvio este conceput pentru a fi utilizat de un părinte care deține autoritatea asupra copilului ale cărui date sunt prelucrate.

- Nu afișăm niciodată publicitate copiilor.
- Nu folosim niciodată datele copiilor pentru marketing sau profilare.
- Părintele poate consulta, modifica și șterge profilul copilului oricând, din Aplicație.
- Datele unui copil sunt șterse automat atunci când părintele șterge profilul copilului sau contul părintelui.

Dacă aveți motive să credeți că în serviciul nostru a fost creat un profil de copil fără consimțământul părintelui, contactați **privacy@etruvio.ro**, iar noi vom investiga și îl vom șterge.

---

## 12. Permisiuni — rezumat pe înțelesul tuturor

### 12.1 Android

| Permisiune | De ce are etruvio nevoie de ea | Ce nu facem niciodată |
|---|---|---|
| Camera | Scanarea unui cod QR pentru asocierea dispozitivului unui copil | Fotografiem, înregistrăm video, încărcăm imagini |
| Acces la utilizare (`PACKAGE_USAGE_STATS`) | Detectarea aplicației aflate în prim-plan, pentru aplicarea regulilor | Citim conținutul aplicațiilor, istoricul de navigare, mesajele |
| Interogarea aplicațiilor instalate | Pentru ca părintele să aleagă ce aplicații să restricționeze | Trimitem lista aplicațiilor dumneavoastră altundeva decât pe serverul nostru, în formă criptată, pentru a fi consultată de părinte |
| Afișare peste alte aplicații | Afișarea ecranului de blocare când se deschide o aplicație restricționată | Afișăm reclame sau conținut fără legătură cu regulile familiei privind bunăstarea digitală |
| Serviciul de accesibilitate | Detectarea unei aplicații restricționate care ajunge în prim-plan | Citim textul de pe ecran, captăm datele introduse, înregistrăm tastele apăsate |
| Locație (opțional) | Preluarea unei singure poziții atunci când un membru al familiei o solicită, pentru a putea găsi dispozitivul | Urmărim locația continuu sau în fundal ori păstrăm un istoric al locațiilor |
| Serviciu în prim-plan și notificări | Menținerea regulilor în funcțiune și informarea utilizatorului | Trimitem notificări de marketing |
| Pornire la boot | Reactivarea regulilor după repornirea dispozitivului | Trezim dispozitivul din orice alt motiv |

### 12.2 iOS

| Permisiune | De ce are etruvio nevoie de ea | Ce nu facem niciodată |
|---|---|---|
| Camera | Scanarea unui cod QR pentru asocierea dispozitivului unui copil | Fotografiem, înregistrăm video, încărcăm imagini |
| Notificări | Informarea părintelui și a copilului (misiune de aprobat, misiune nouă, privilegiu acordat) | Trimitem notificări de marketing |
| Screen Time (Family Controls) | Aplicarea ferestrelor de concentrare și a limitelor de timp de ecran stabilite de părinte pe dispozitivul copilului | Citim ce aplicații folosește copilul sau trimitem către serverele noastre utilizarea altor aplicații |
| Reîmprospătare în fundal | Menținerea la zi a regulilor și a notificărilor | Urmărim locația sau rulăm orice altceva fără legătură cu regulile familiei |

Pe iOS, părintele acordă explicit accesul la Screen Time pe dispozitivul copilului și îl poate revoca oricând din **Setări → Timp de utilizare**; după revocare, regulile nu mai sunt aplicate, iar nicio altă dată cu caracter personal nu este afectată.

---

## 13. Modificări ale acestei politici

Dacă modificăm în mod semnificativ această politică, vom notifica utilizatorii în Aplicație și prin emailul asociat contului de părinte, cu cel puțin 14 zile înainte ca modificarea să intre în vigoare.

---

## 14. Contact

CODE4ALL SRL
Str. Stejarului 128 F, Sat Ulmi, jud. Dâmbovița, cod poștal 137455, România
**privacy@etruvio.ro**
https://etruvio.ro
