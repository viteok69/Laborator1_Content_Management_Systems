
> Realizat de studentul: Badia Victor \
> Grupa: I2301
> \
> Verificat de N. Nartea

## Scopul lucrării
Să înveți cum să instalezi WordPress într-un mediu local, să te familiarizezi cu panoul de administrare, să modifici aspectul site-ului prin teme și să extinzi funcționalitatea acestuia cu ajutorul plugin-urilor.

## Condiții
* Pasul 1. Pregătirea mediului
1. Instalează XAMPP (sau un stack similar: OpenServer, MAMP, Docker)
<img width="826" height="536" alt="image" src="https://github.com/user-attachments/assets/bdae318d-e27d-4e19-b7b0-63860f79b361" />

2. Pornește modulele Apache și MySQL. Asigură-te că http://localhost se deschide.
<img width="1836" height="854" alt="image" src="https://github.com/user-attachments/assets/3a8cc286-a32b-4a1d-b8b5-f436bb247dca" />

3. În phpMyAdmin, creează o bază de date nouă, de exemplu wp_lab2.
<img width="744" height="315" alt="image" src="https://github.com/user-attachments/assets/8bbba9ee-c90f-4513-9105-ae31c9c37d29" />

* Pasul 2. Instalarea WordPress
1. Descarcă WordPress de pe wordpress.org.
<img width="211" height="73" alt="image" src="https://github.com/user-attachments/assets/194d1fbb-24b7-4662-a737-0e89beadcc8a" />

2. Dezarhivează fișierele în folderul htdocs (sau echivalentul acestuia pentru stack-ul tău).
<img width="479" height="225" alt="image" src="https://github.com/user-attachments/assets/c7ff4cc7-4e2f-4948-a24b-9362aff848f2" />

3. În browser, deschide http://localhost/wp_lab2 și parcurge procesul de instalare.
Alegem limba:
<img width="1841" height="878" alt="image" src="https://github.com/user-attachments/assets/cb14fa52-ecef-4993-8ab7-fcf20a9c41c2" />

Introducem datele necesare:
<img width="1016" height="846" alt="image" src="https://github.com/user-attachments/assets/d5d752ce-3382-4e59-a18a-aff15b8984b7" />

Incepem procesul de instalare:
<img width="1003" height="401" alt="image" src="https://github.com/user-attachments/assets/8a98e2b7-69d2-4e54-aba4-1a5e0a3265ff" />

Introducem datele necesare:
<img width="962" height="861" alt="image" src="https://github.com/user-attachments/assets/46477931-2bbd-46e7-885a-ee825a7762a0" />

Mesajul de succes:
<img width="1018" height="546" alt="image" src="https://github.com/user-attachments/assets/446243f1-81b1-408b-a8b9-bc0b9b27c1e8" />

Dashboard:
<img width="1866" height="882" alt="image" src="https://github.com/user-attachments/assets/1d36601f-4983-43f3-b38f-8c23b344f729" />

* Pasul 3. Setările inițiale ale site-ului
1. În panoul de administrare, accesează secțiunea Settings → General. Schimbă numele site-ului și fusul orar.
Numele site-ului:
<img width="754" height="140" alt="image" src="https://github.com/user-attachments/assets/4eb6d5d7-5a25-4967-967e-d83a1d140f6e" />
Fusul orar:
<img width="1066" height="153" alt="image" src="https://github.com/user-attachments/assets/d8818970-b6a7-459f-bdb3-15b46ad8a387" />

2. În Settings → Permalinks, selectează opțiunea Post name pentru link-uri mai prietenoase.
<img width="490" height="103" alt="image" src="https://github.com/user-attachments/assets/48512613-b625-4254-9c0d-84ecbb6b9874" />

* Pasul 4. Lucrul cu teme
1. Deschide secțiunea Appearance → Themes.
2. Instalează o temă nouă din catalogul oficial (de exemplu, „Astra”).
<img width="1633" height="822" alt="image" src="https://github.com/user-attachments/assets/e581b029-8fc4-4358-8613-7713f10d94a8" />

3. În meniul Appearance → Customize, configurează:
- logoul site-ului:
<img width="1849" height="883" alt="image" src="https://github.com/user-attachments/assets/caa3f7d9-5870-474f-84da-034821f37260" />

- schema de culori:
<img width="1864" height="880" alt="image" src="https://github.com/user-attachments/assets/08224999-7706-4343-83e5-f97b8725f0c9" />

- titlul și descrierea:
<img width="1867" height="878" alt="image" src="https://github.com/user-attachments/assets/42153c45-bc62-48ce-87e5-62d28d51eee1" />

* Pasul 5. Lucrul cu plugin-uri
1. Accesează secțiunea Plugins → Add New.
2. Instalează și activează:
-pluginul Classic Editor (pentru editorul clasic de postări);
-pluginul Contact Form 7 (pentru adăugarea unui formular de contact).
<img width="1612" height="158" alt="image" src="https://github.com/user-attachments/assets/6c9b370a-19f7-4821-a56c-de61b8829234" />

3. Verifică noile funcționalități în panoul de administrare.
- adăugarea unei postări cu Classic Editor:
<img width="1659" height="718" alt="image" src="https://github.com/user-attachments/assets/34aa7d4a-f3da-48e3-ae2f-3e260515d97f" />

- crearea unui formular cu Contact Form 7:
<img width="1863" height="840" alt="image" src="https://github.com/user-attachments/assets/139e7fa2-53dc-40fe-a1ed-8197bba77730" />

4. În Plugins → Installed Plugins, dezactivează unul dintre plugin-uri și asigură-te că funcționalitatea acestuia a dispărut.
<img width="261" height="77" alt="image" src="https://github.com/user-attachments/assets/d00f7b49-f7a7-446a-9d4c-f92f24666501" />
<img width="1866" height="884" alt="image" src="https://github.com/user-attachments/assets/d1e68865-ea7b-4213-be51-909ffc837f59" />

* Pasul 6. Crearea de conținut
1. Creează o pagină simplă „Contacte” și inserează formularul de contact.
<img width="1865" height="880" alt="image" src="https://github.com/user-attachments/assets/33a71bed-112c-4a10-a3f3-49a99a8c6a05" />

2. Creează câteva postări pe blog cu conținut diferit (text, imagini).
<img width="1868" height="848" alt="image" src="https://github.com/user-attachments/assets/a0612699-c17a-4411-9ffd-50969da04331" />
<img width="1868" height="879" alt="image" src="https://github.com/user-attachments/assets/b9441612-1fc6-4c5b-be56-7fe90e7f438f" />

3. Verifică modul în care este afișat conținutul pe site.

## Întrebări de control
1. Ce face o temă în WordPress și ce face un plugin?
Tema definește designul și estetica vizuală (culori, fonturi, așezare), în timp ce un plugin adaugă funcționalități specifice, cum ar fi formularele de contact sau securitatea.

2. De ce nu se pierde conținutul site-ului atunci când se schimbă tema?
Conținutul este stocat separat într-o bază de date, astfel încât schimbarea temei modifică doar „stratul de haine” vizual, nu și datele salvate.

3. Cum se poate modifica aspectul site-ului fără a edita codul?
Putem folosi instrumente vizuale precum Customizer pentru setări de bază, editorul de blocuri sau plugin-uri, pentru construcția paginilor.
