# Laborator1_Content_Management_Systems

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
<img width="1842" height="887" alt="image" src="https://github.com/user-attachments/assets/5cca2d19-fbec-42b1-b430-74fc196540b1" />

3. Activează tema și compară cum s-a schimbat aspectul site-ului.
<img width="1865" height="871" alt="image" src="https://github.com/user-attachments/assets/d36f442b-2886-4262-9e35-e76a93369661" />

4. În meniul Appearance → Customize, configurează:
logoul site-ului:
<img width="210" height="199" alt="image" src="https://github.com/user-attachments/assets/d6070528-2d02-4ed3-96d2-4edce4b02d1a" />

schema de culori:
<img width="1799" height="818" alt="image" src="https://github.com/user-attachments/assets/a6907f72-9c9d-4798-a976-d6230c1e48e3" />

titlul și descrierea:
<img width="1613" height="653" alt="image" src="https://github.com/user-attachments/assets/a681fc5b-eb40-438e-92d3-7c22de81593f" />

* Pasul 5. Lucrul cu plugin-uri
1. Accesează secțiunea Plugins → Add New.
<img width="1648" height="839" alt="image" src="https://github.com/user-attachments/assets/ee53b75e-30c9-43c0-847d-502ad3c62180" />

2. Instalează și activează:
pluginul Classic Editor (pentru editorul clasic de postări):
<img width="776" height="295" alt="image" src="https://github.com/user-attachments/assets/e2144152-1146-484c-83a2-6cf9b77d2388" />

pluginul Contact Form 7 (pentru adăugarea unui formular de contact):
<img width="772" height="344" alt="image" src="https://github.com/user-attachments/assets/27db10b8-17b5-4e93-8c97-ba963e68c65b" />

3. Verifică noile funcționalități în panoul de administrare (adăugarea unei postări cu Classic Editor și crearea unui formular cu Contact Form 7).

