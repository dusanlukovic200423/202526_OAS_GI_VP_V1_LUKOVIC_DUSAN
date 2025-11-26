Ovo je neki tesktualni fajl.
gitPromena tesktualnog fajla...
## vezbe iz git-a

## Zadatak 1:
<p>git config --global user.name "Dusan Lukovic"
git config --global user.email "dusanlukovic.lukovic3@gmail.com"</p>
<p>git config --global core.editor "C:\Users\Dusan\Desktop\wp\vezbe\vezba_1\202526_OAS_GI_VP_V1_LUKOVIC_DUSAN --wait"</p>
<P>git config --global init.defaultBranch main</P>

## Zadatak 2 i 3:
<p>ulogovao sam se na gite-u i napravio repozitorijum: 202526_OAS_GI_VP_V1_LUKOVIC_DUSAN</p>
<p>koristio sam i komandu: git status</p>

## Zadatak 4:
<p>kreirao sam trazeni README.md fajl i koristio komandu: git status, kako bih ga pratio</p>
<p>git remote add gitea_1 https://gitea.grf.bg.ac.rs/dusan.lukovic/202526_OAS_GI_VP_V1_LUKOVIC_DUSAN.git</p>
<p> origin za udaljeni repozitorijum sam nazvao gitea_1</p>

## Zadatak 5:
<p>kreirao sam potrebne direktorijume i poddirektorijume, potvrdio ih sa: git commit -m "promena u app.py" </p>

## Zadatak 6:
<p>azurirao sam trazeni fajl i komitovao sa porukom "Ovo je druga verzija mog python fajla"</p>
<p>iskoristio sam: git add src, pa git push gitea_1 main, kako bih direktorijunm src sa lokalnog posalo na udaljeni repozitorijum</p>

## Zadatak 7:
<p>git add .</p>
<p>git commit -m ""</p>
<p>git push gitea_1 main </p>

## Zadatak 8:

<p>git restore  src/frontend/app.js </p>
<p>git checkout --scr/frontend/app.js</p>
<p>git commit-m "promena posle restore koraka</p>
<p></p>

## Zadatak 9:
<p>git restore src/frontend/app.js</p>
<p>git restore vraca promene koje nisu sacuvane</p>
<p>git checkout <hash_proslog_commita> --src/frontend/app.js</p>

## Zadatak 10:
<p>git reset --soft brise poseldnji commit, ali promene ostaju u staging area</p>
<p>git reset --mixed brise posednji commit, a promene ostaju samo u lokalnom direkorijumu</p>
<p>git reset --hard brise poslednji commit i sve ostalo iz lokalnog direktorijuma</p>

## Zadatak 11:
<p>git commit -m "ovo je treca verzija, drugo azuriranje"</p>
<p>git revert pravi potvrdu koja ponistava promene napravljene u nekoj prethodnoj potvrdi </p>

## Zadatak 12:
<p>git branch featu-
re/delete-student </p>
<p>git checkout master, prebaciivanje na master granu</p>
<p>koristi se komanda merge i onda se poruka javi i u master grani
</p>
<p>git commit-m "promena brisanja studenta"</p>

## Zadatak 13:
<p>git checkout main, git commit -m "azuriranje studenta commit"</p>
<p>komanda: git pull</p>
<p>posle prihvatanja pull requesta poruka "azuriranje studenta commit" se nalazi u main grani</p>


## Zadatak 14:
<p>fajlovi su nepraceni(untracked), git ignorise fajlove nakon dodatka .gitignore</p>

