Perfekt 🙌 Här är quizet i ren Markdown så att du kan klistra in det i e# 📝 Git Quiz

Ett quiz om `clone`, `add`, `commit` och `push`.

---

## ❓ Fråga 1: Clone
Du hittar ett spännande projekt på GitHub som du vill jobba med på din egen dator.  
Vilket kommando använder du för att hämta ner hela projektet?  

- a) `git copy`  
- b) `git clone <url>`  
- c) `git download <url>`  
- d) `git pull <url>`  

<details>
<summary>✅ Facit</summary>
<b>b) git clone &lt;url&gt;</b>  
Detta kopierar hela repot till din dator och sparar en lokal version.
</details>

---

## ❓ Fråga 2: Add
Du har ändrat i en fil som heter `index.html`. Vad gör kommandot:  

```bash
git add index.html

a) Sparar filen permanent i GitHub

b) Lägger filen i staging area (markerar den för nästa commit)

c) Tar bort filen från projektet

d) Skapar en ny commit


<details>
<summary>✅ Facit</summary>
<b>b) Lägger filen i staging area</b>  
`git add` betyder att du markerar vilka filer som ska sparas i nästa commit.
</details>
---

❓ Fråga 3: Commit

Du kör kommandot:

git commit -m "Fixade en bugg"

Vad händer?

a) En ny version skapas lokalt med beskrivningen "Fixade en bugg"

b) Filen skickas direkt till GitHub

c) Filerna tas bort från staging area

d) Ingenting händer utan git push


<details>
<summary>✅ Facit</summary>
<b>a) En ny version skapas lokalt</b>  
Commits sparar en snapshot av ditt arbete på din dator.
</details>
---

❓ Fråga 4: Push

Du har gjort flera commits lokalt. Hur gör du för att skicka dem till GitHub?

a) git upload

b) git send

c) git push origin main

d) git pull origin main


<details>
<summary>✅ Facit</summary>
<b>c) git push origin main</b>  
Detta skickar dina commits till fjärrlagret på GitHub i grenen <code>main</code>.
</details>
---

❓ Bonus: Rätt ordning

Sätt kommandona i rätt ordning när du jobbar med ett projekt:

1. ___ → Hämta projektet från GitHub


2. ___ → Markera filer som ska sparas


3. ___ → Skapa en ny version lokalt


4. ___ → Skicka upp dina ändringar till GitHub



<details>
<summary>✅ Facit</summary>1. git clone


2. git add


3. git commit


4. git push



</details>
```
---
