# Samarbejde på GitHub

### 1. Begreberne kort fortalt

* **Fork:** Din personlige kopi af et projekt **på GitHub**. Her kan du eksperimentere uden at ødelægge originalen.
* **Clone:** Kopiering af projektet fra GitHub **ned til din egen computer**.
* **Pull Request (PR):** En anmodning om at få flettet dine ændringer (fra din fork) ind i det originale projekt.
* **Merge:** Når ejeren af originalen godkender og indlemmer ændringerne fra en PR.

### 2. Standard Workflow

1. **Fork** projektet på GitHub til din egen profil.
2. **Clone** din fork ned til din computer (hvis du koder lokalt).
3. **Commit & Push** dine ændringer til din egen fork.
4. **Opret en Pull Request** fra din fork til det originale repository.
5. **Merge** (ejeren gør dette): Hvis der er **Merge Conflicts**, skal de løses manuelt ved at vælge, hvilke linjer kode der skal overleve.

### 3. De 3 gyldne regler

* **Adskillelse:** Din fork og originalen er adskilte, indtil du aktivt laver en *Pull Request* eller en *Sync*.
* **Konflikter:** Sker når den samme linje er rettet to forskellige steder. De skal altid løses manuelt.
* **Synkronisering:** Husk jævnligt at "Sync fork" på GitHub, så din kopi ikke bliver forældet i forhold til originalen.

---

## Par-øvelse: GitHub Workflow

### Fase 1: Oprettelse og Fork

* **Person A:**
1. Opret et nyt repository på din profil (kald det f.eks. `github-test`).
2. Vælg "Public" og sæt flueben ved **"Add a README file"**.
3. Skriv en enkelt linje i README: *"Dette er Person A's projekt."*


* **Person B:**
1. Gå ind på Person A’s nye repo.
2. Klik på **"Fork"** øverst til højre.
3. Du har nu din egen kopi (`PersonB/github-test`).



### Fase 2: Ændringer og Pull Request

* **Person B:**
1. Gå ind i README-filen i **din fork**.
2. Klik på blyanten (Rediger) og tilføj linjen: *"Person B har været her og foreslår en ændring."*
3. Klik på **"Commit changes..."** for at gemme.
4. Gå til fanen **"Pull requests"** og klik på den grønne knap **"New pull request"**.
5. Klik på **"Create pull request"**, skriv en besked, og send den afsted til Person A.



### Fase 3: Modtagelse og Merge

* **Person A:**
1. Gå til dit originale repo og klik på fanen **"Pull requests"**.
2. Klik på Person B's anmodning.
3. Klik på den grønne knap **"Merge pull request"** og derefter **"Confirm merge"**.
4. Tjek din README – nu står begge linjer der!



### Fase 4: Udfordringen (Merge Conflict) 🌶️

* **Person A:** Rediger linje 2 i README til: *"A ejer denne linje!"* og commit.
* **Person B:** Rediger linje 2 i **din egen fork** til: *"B vil hellere bestemme her!"* og commit.
* **Person B:** Prøv nu at lave en ny **Pull Request** til Person A.
* **I fællesskab:** Se hvordan knappen nu er rød pga. en konflikt. Klik på **"Resolve conflict"** og find ud af, hvordan filen skal se ud for at begge er glade.

---

**Succeskriterium:** Når I er færdige, skal **Person A's** repository indeholde de endelige rettelser, I blev enige om under konfliktløsningen.

Rigtig god fornøjelse med øvelsen! Hvem starter som Person A?
