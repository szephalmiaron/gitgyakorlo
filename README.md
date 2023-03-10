# Verziókezelés alapjai

## Git letöltése

- [git for windows](https://gitforwindows.org)
- [git scm](git-scm.com)

## 2. Konfiguráció parancsok

- git config --global.name szephalmiaron
- git config --global user.email szephalmi.aron@students.jedlik.eu
- git config --global credential.helper wincred

## 3. Repository létrehozása

- git init

## 4. Állomány hozzáadása a stage-hez(staging area)

> A stagen lévő állományokról tudunk állapotfelvételt (commi-ot) készíteni  
> Üres mappa nem kerül a stage-re

- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)

## 5. Állapotfelvétel (commit) készítése

- git commit -m "commit message"

## 6.Git állapot és log lekérdezése

- git status
- git log

## 7. Lokális változások szinkronizálása a távoli repóba

- git push

## 8. Távoli repó másolása (klónozása) a lokális repóba

- git clone "távoli repó URL címe"  
## 9. Ágak (branches) kezelése 
 >Lokális ágak listázása  
 - git branch 
> lokális és távoli ágak listázása
- git branch -av
- git checkout -b új_ág_neve
> Ág létrehozása
- git branch új_ág_neve
> Váltás egy másik ágra
- git checkout másik_ág_neve 
> Ág törlése (aktuális ág nem törölhető)
- git branch -d törlendő_ág_neve
> Változások átvezetése (merge)
- git checkout ág_ahova_kerülnek_a_változások
- git merge ág_ahonnan_áthozzuk_a változásokat