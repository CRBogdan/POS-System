# POS-System

## Cum pot incepe sa lucrez la proiect
<pre>
Prima data trebuie clonat proiectul.<br>

<strong>Metoda 1: GitHub Desktop</strong>
    https://www.shorturl.at/CEL38
    <br>
<strong>Metoda 2: Git</strong>
    1. intrati pe repo si apasati pe butonul verde pe care scrie `Code`
    2. copiati link-ul de https sau ssh
    3. intrati in folderul unde vreti sa clonati si deschideti un command prompt
    3. scrieti `git clone _linkul_copiat_`
</pre>

## Cum adaug un feature nou
<pre>
Pentru a putea sa ne facem review-uri, trebuie sa lucram in branch-uri diferite fata de `main`.<br>

<strong>Metoda 1: GitHub Desktop</strong>
    1. Creeam un branch nou: https://www.shorturl.at/nHKU5
    2. Scriem codul
    3. Facem commit cu noul cod: https://www.shorturl.at/isNVY
    <br>
<strong>Metoda 2: Git</strong>
    1. Updatam proiectul: `git pull --rebase`
    2. Creeam un branch nou: `git branch _nume_branch_`
    3. Intram pe branch: `git checkout _nume_branch_`
    4. Scriem codul
    5. Adaugam fisierele la git: `git add *` (pentru a adauga toate fisierele modificate)
                                 `git add _nume_fisier_1_ _nume_fisier_2_ ... _nume_fisier_n_`
                                    (pentru a preciza doar fisierele pe care le vrem)
    6. Creeam commit-ul: `git commit -m "descriere commit"`
    7. Luam modificarile de pe github ca sa avem branch-ul up-do-date: `git pull --rebase`
    8. Urcam branch-ul pe github: `git push origin HEAD`
</pre>

## Cum creez un PR (pull request)
<pre>
1. Dupa ce ati dat push intrati pe GitHub si va va aparea un buton verde pe care il apasati.
2. Dupa aceea ii dati PR-ului un nume corespunzator si daca e cazul adaugati o mica descriere.
3. Apasati pe `Create PR` (sau ce scrie pe buton, am uitat :D)
</pre>

## Cum fac review si cand fac merge
<pre>
 1. Cu `git pull --rebase` (sau echivaletul in GD,
     probabil apare un buton de PULL pe undeva) va veti putea updata proiectul.
 2. Dupa aceea intrati pe branch-ul pe care se afla feature-ul
     si incepeti prin a-l testa si dupa sa cititi modificarile.
     (modificarile mai bine le cititi pe github sau cu `git diff`,
     posibil ca IDE-ul sa aiba o functie pt asta, informati-va depspre IDE-ul vostru)
 4. Intrati pe PR, intrati la `Files changed` si in dreapta apasati pe `Review changes`
 5. Bifati `aprove` sau `request changes` in functie de ce vreti.
     Daca cereti schimbari scrieti in casuta ce schimbari ati dori)
 6. Daca PR-ul are deja un aprove si voi vreti sa ii dati aprove,
     puteti face asta, sau ii dati direct merge. (butonul e pe pagina `Conversation` a PR-ului)
</pre>









