# Verziókezelés alapjai 
## Git letöltése  
- [git for windows](https://gitforwindows.org )  
- [git scm](git-scm.com)  
 ## 2. Konfiguráció parancsok  
  - git config --global.name szephalmiaron  
  - git config --global user.email szephalmi.aron@students.jedlik.eu  
  - git config --global credential.helper wincred   
## 3. Repository létrehozása   
- git init    
## 4. Állomány hozzáadása a stage-hez(staging area)    
>A stagen lévő állományokról tudunk állapotfelvételt (commi-ot) készíteni  
> Üres mappa nem kerül a stage-re  
- git add állomány_neve  
- git add . (összes állomány és mappa hozzáadása)  
## 5. Állapotfelvétel (commit) készítése  
- git commit -m "commit message"  