<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4776E6,100:1E3C72&height=210&section=header&text=PopClicker&fontSize=48&fontAlignY=38&fontColor=ffffff&desc=Alba-rosa.cz&descAlignY=60&descSize=16&animation=fadeIn" alt="PopClicker" width="100%"/>
</p>

# Alba-rosa.cz · PopClicker

> Jednoduchá klikací (idle/clicker) hra.

🌐 **Živý web:** <https://alba-rosa.cz/popclicker/>  
📂 **Kolekce:** Alba-rosa.cz  
👤 **Autor:** [@jurapascal](https://github.com/jurapascal)

---

## O projektu

Odpočinková klikací hra běžící jako podsložka domény `alba-rosa.cz`.

## Technologie

- **HTML / CSS / JavaScript**

## Nasazení

Nasazuje se **automaticky přes GitHub Actions** (workflow `Deploy`) po každém pushi do `main`. Nahrávají se jen změněné soubory přes vlastní FTP účet `w237642_ghpopclicker`, který vidí jen složku `/www/domains/alba-rosa.cz/popclicker/`; výsledek přijde na Discord. Co se nenahrává a co je jen na serveru, je v `.github/deploy.json`.

FTP na Wedos, podsložka `/popclicker/`.
