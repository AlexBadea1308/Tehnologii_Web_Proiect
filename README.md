# Tehnologii_Web_Proiect

Aplicatie de Gestionare a unei Echipe de Fotbal: 

 
1. Ideea Generala a Proiectului
Proiectul propune dezvoltarea unei aplicații web pentru gestionarea unei echipe de fotbal, oferind multiple funcționalități destinate diferitelor categorii de utilizatori. Aplicația va permite achiziționarea biletelor pentru meciuri, cumpărarea de accesorii ale echipei, vizualizarea statisticilor jucătorilor și gestionarea activităților zilnice pentru jucători. De asemenea, managerii și administratorii echipei vor avea posibilitatea de a administra lotul, strategia de joc și evenimentele legate de club.
2. Arhitectura Folosită pentru Stocare, Frontend și Backend
2.1. Stocare
Pentru gestionarea datelor, se utilizează un sistem de baze de date NoSQL și SQL:
•	MongoDB pentru stocarea informațiilor despre utilizatori, roluri și articolele din secțiunea de știri;
•	MySQL pentru gestionarea comenzilor de bilete și accesorii, evenimentelor echipei și statisticilor jucătorilor.
2.2. Backend
Backend-ul este realizat folosind Node.js cu Express.js, implementând un REST API pentru interacțiunea cu baza de date. Principalele funcționalități backend includ:
•	Autentificarea utilizatorilor și gestionarea sesiunilor;
•	Administrarea utilizatorilor și a rolurilor acestora;
•	Gestionarea produselor (bilete, accesorii, articole sportive);
•	Publicarea și administrarea evenimentelor echipei;
•	Gestionarea statisticilor și antrenamentelor jucătorilor.
2.3. Frontend
Interfața utilizator este dezvoltată folosind React.js cu stilizare oferită de Bootstrap. Aceasta include:
•	O pagină de login și înregistrare;
•	Dashboard personalizat pentru fiecare tip de utilizator;
•	Pagini pentru cumpărarea biletelor și accesoriilor;
•	Secțiunea de știri și articole despre echipă;
•	Panou de administrare pentru manageri și administratori.
3. Prezentarea in detaliu a Proiectului 
3.1. Tipuri de Utilizatori și Permisiunile acestora:
Aplicația include patru tipuri principale de utilizatori, fiecare având un set specific de permisiuni și funcționalități:
1. Utilizator Normal (Fan/Guest)
•	Poate cumpăra bilete pentru meciurile echipei;
•	Poate cumpăra accesorii (tricouri, fulare, căni, trofee replici etc.);
•	Poate vizualiza programul meciurilor;
•	Poate vizualiza sectiunea de About us (Istoria echipei);
•	Poate manegeria contul schimband datele;
•	Poate vizualiza pagina de Contact us;
•	Poate edita cosul de cumparaturi;
2. Jucător
•	Poate vedea contractul și salariul;
•	Poate accesa programul zilnic (ex. antrenamente, recuperare, meciuri);
•	Poate vedea statisticile individuale (goluri,asisturi,meciuri jucate, cartonase galbene, cartonase rosii);
3. Manager
•	Poate posta lotul pentru următorul meci;
•	Poate gestiona lista de antrenamente și planul de pregatire;
•	Poate edita programul de antrenamente.
•	Poate vedea statisticile tuturor jucatorilor (goluri,asisturi,meciuri jucate, cartonase galbene, cartonase rosii);
4. Administrator
•	Poate gestiona utilizatorii (creare, ștergere, modificare permisiuni);
•	Poate posta și edita evenimente legate de echipă (ex. data scoaterii biletelor la vânzare);
•	Poate adăuga și edita produse și accesorii (tricouri, fulare, căni etc.);
•	Poate modifica prețurile la bilete și accesorii;
•	Poate gestiona secțiunea de știri unde postează articole despre echipă, transferuri, analize ale meciurilor și interviuri cu jucătorii.
4. Concluzie
Această aplicație web oferă o soluție completă pentru gestionarea unei echipe de fotbal, combinând funcționalități de e-commerce, management sportiv și administrare de conținut. Prin integrarea mai multor tipuri de utilizatori și un sistem detaliat de permisiuni, proiectul aduce o experiență interactivă și eficientă atât pentru fani, cât și pentru jucători și staff-ul administrativ al echipei.
