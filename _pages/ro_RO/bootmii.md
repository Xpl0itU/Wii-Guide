---
title: "Copie de rezerva BootMii"
---

{% include toc title="Table of Contents" %}

Dacă ai nevoie de ajutor pentru orice legat de acest tutorial, te rugăm să te alături [serverului de discord RiiConnect24](https://discord.gg/rc24) (recomandat) sau [scrie-ne un email la support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![Logo-ul BootMii](/images/bootmii.png)

Ai nevoie de un **card SD** pentru a crea o copie de rezervă NAND folosind BootMii. Dacă nu ai una, poți sări această pagină, însă este foarte recomandat să creezi una dacă poți.
{: .notice--warning}

BootMii ca boot2 este recomandat, dar poate fi instalat doar pe build-uri vechi de Wii-uri. Altfel, poate fi instalat ca un IOS.
{: .notice--info}

Unele din cele mai importante funcții ale BootMii-ului este abilitatea de a face o copie de rezervă și de a restaura memoria NAND a consolei tale Wii. Vom trece peste cum să efectuezi o copie de rezervă NAND. Poți apoi să restaurezi din acea copie de rezervă pentru orice anume motiv. Este o idee bună să faci o copie de rezervă NAND în mod regulat sau înainte să faci ceva riscant cu consola ta (și dacă știi ce faci, nu va trebui să faci nimic riscant).

#### Ai nevoie de
* Un card SD cu cel puțin 512MB de spațiu liber

#### Instrucțiuni
Dacă ai BootMii instalat ca boot2 va trebui să porniți BootMii prin repornirea consolei. Sari peste pașii 1 și 2 dacă acesta este cazul.
{: .notice--info}
1. Pornește Homebrew Channel.
2. Apasă butonul HOME, apoi selectează "Launch BootMii" (Pornește BootMii).

    Navigarea prin BootMii nu este posibilă folosind un Wii Remote. Trebuie sa folosești butoanele POWER și RESET de pe consolă, sau un controller GameCube conectat în port 1. Pentru a naviga printre opțiuni, apasă butonul POWER de pe consola Wii (sau dreapta pe +Control Pad-ul pe un controller GameCube). Pentru a selecta o opțiune, apasă butonul RESET de pe consola Wii sau A pe controllerul tău GameCube.
    {: .notice--info}


    Dacă ecranul rămâne negru și lumina albastră a cititorului de discuri clipește încontinuu, lipsesc fișierele BootMii din cardul tău SD. Descărcați [acest zip](https://static.hackmii.com/bootmii_sd_files.zip) și extrage-l în rădăcina cardului tău SD, iar apoi mai încearcă odată.
    {: .notice--warning}

3. Selectează butonul Opțiuni (cel cu rotițele).
4. Selectează butonul BackupMii (cel cu săgeata verde).
- Procesul de creere a unei copii de rezervă NAND va incepe. Poți urmări progresul pe ecran.
- "Bad Block-urile" (Blocurile proaste) sunt normale. Nu te îngrijora dacă vezi unele într-o copie de rezervă NAND.
- După acest pas, va verifica copia de rezervă. Chiar dacă este recomandat, poate fi omis prin apăsarea butonului EJECT de pe consola ta Wii.
5. După ce copia de rezervă este gata, ieși din ecranul de backup NAND prin apăsarea oricărui buton.
6. Pentru a ieși din BootMii, apasă butonul Înapoi (cel cu săgeata) iar apoi poți apasă ori butonul Wii Menu ori butonul Homebrew Channel pentru a ieși unde vrei.


<!---
To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the button right next to BackupMii with a red arrow).
{: .notice--info}
-->

[Continuă la instalarea Priiloader](priiloader) Priiloader adaugă un nivel de protecție anti-brick, și îl recomandăm, în special dacă ai putut să instalezi numai BootMii IOS.
{: .notice--info}
