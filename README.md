# POS-System

## Cum pot incepe sa lucrez la proiect

Prima data trebuie clonat proiectul.<br>

<strong>Metoda 1: GitHub Desktop</strong><br>
    &nbsp;https://www.shorturl.at/CEL38<br>
<strong>Metoda 2: Git</strong><br>
    &nbsp;1. intrati pe repo si apasati pe butonul verde pe care scrie `Code`<br>
    &nbsp;2. copiati link-ul de https sau ssh<br>
    &nbsp;3. intrati in folderul unde vreti sa clonati si deschideti un command prompt<br>
    &nbsp;3. scrieti `git clone _linkul_copiat_`<br>


## Cum adaug un feature nou
Pentru a putea sa ne facem review-uri, trebuie sa lucram in branch-uri diferite fata de `main`.<br>

<strong>Metoda 1: GitHub Desktop</strong><br>
    &nbsp;1. Creeam un branch nou: https://www.shorturl.at/nHKU5<br>
    &nbsp;2. Scriem codul<br>
    &nbsp;3. Facem commit cu noul cod: https://www.shorturl.at/isNVY<br>
    &nbsp;4. Facem push pe github.
    <br>
<strong>Metoda 2: Git</strong><br>
    &nbsp;1. Updatam proiectul: `git pull --rebase`<br>
    &nbsp;2. Creeam un branch nou: `git branch _nume_branch_`<br>
    &nbsp;3. Intram pe branch: `git checkout _nume_branch_`<br>
    &nbsp;4. Scriem codul<br>
    &nbsp;5. Adaugam fisierele la git: `git add *` (pentru a adauga toate fisierele modificate)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `git add _nume_fisier_1_ _nume_fisier_2_ ... _nume_fisier_n_` (pentru a preciza doar fisierele pe care le vrem)<br>
    &nbsp;6. Creeam commit-ul: `git commit -m "descriere commit"`<br>
    &nbsp;7. Luam modificarile de pe github ca sa avem branch-ul up-do-date: `git pull --rebase`<br>
    &nbsp;8. Urcam branch-ul pe github: `git push origin HEAD`<br>

## Cum creez un PR (pull request)
&nbsp;1. Dupa ce ati dat push intrati pe GitHub si va va aparea un buton verde pe care il apasati.<br>
&nbsp;2. Dupa aceea ii dati PR-ului un nume corespunzator si daca e cazul adaugati o mica descriere.<br>
&nbsp;3. Apasati pe `Create PR` (sau ce scrie pe buton, am uitat :D)<br>

## Cum fac review si cand fac merge
 &nbsp;1. Cu `git pull --rebase` (sau echivaletul in GD,<br>
  &nbsp;&nbsp;   probabil apare un buton de PULL pe undeva) va veti putea updata proiectul.<br><br>
 &nbsp;2. Dupa aceea intrati pe branch-ul pe care se afla feature-ul<br>
  &nbsp;&nbsp;   si incepeti prin a-l testa si dupa sa cititi modificarile.<br>
  &nbsp;&nbsp;   (modificarile mai bine le cititi pe github sau cu `git diff`,<br>
 &nbsp;&nbsp;    posibil ca IDE-ul sa aiba o functie pt asta, informati-va depspre IDE-ul vostru)<br><br>
 &nbsp;3. Intrati pe PR, intrati la `Files changed` si in dreapta apasati pe `Review changes`<br><br>
 &nbsp;4. Bifati `aprove` sau `request changes` in functie de ce vreti.<br>
 &nbsp;&nbsp;    Daca cereti schimbari scrieti in casuta ce schimbari ati dori)<br><br>
 &nbsp;5. Daca PR-ul are deja un aprove si voi vreti sa ii dati aprove,<br>
  &nbsp;&nbsp;   puteti face asta, sau ii dati direct merge. (butonul e pe pagina `Conversation` a PR-ului)<br>









