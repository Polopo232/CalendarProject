# 🚀 MS Project ja ProjectLibre õppematerjalid

See projekt on loodud eesmärgiga pakkuda selgeid ja samm-sammulisi juhiseid projektijuhtimise tarkvarade kasutamiseks. Veebileht koondab nii **Microsoft Projecti** kui ka **ProjectLibre** peamised funktsioonid.

## 📑 Sisukord
1. [Projekti ülevaade](#-projekti-ülevaade)
2. [Branchide struktuur](#-branchide-struktuur)
3. [Kasutatud tehnoloogiad](#-kasutatud-tehnoloogiad)
4. [Koodinäide (Navigatsioon)](#-koodinäide)

---

## ✅ Tehtud tööd
- [x] Üldise veebistruktuuri loomine (HTML5).
- [x] Ühtse disainisüsteemi väljatöötamine (CSS3).
- [x] MS Projecti juhendite koostamine (Kalender, Valemid, Diagrammid).
- [x] ProjectLibre võrdleva juhendi lisamine.
- [x] Interaktiivse navigatsioonimenüü seadistamine.

## 📂 Branchide struktuur

| Branch | Sisu kirjeldus |
| :--- | :--- |
| `main` | Projekti koondvaade ja pealeht. |
| `projectlibre-branch` | ProjectLibre: tarkvara erisused ja võrkdiagramm. |

## 📂 Failide struktuur

| Fail | Sisu kirjeldus |
| :--- | :--- |
| `index.html` | Projekti avaleht ja MS Projecti kalendri seadistamise juhend. |
| `valem.html` | MS Projecti kohandatud arvutusväljade ja valemite õpetus. |
| `diagramm.html` | MS Projecti aruannete ja visuaalsete diagrammide loomise juhend. |
| `style.css` | Ühtne disainilahendus, mis juhib kogu veebilehe visuaalset stiili. |

## ✨ Funktsionaalsused
Projekt ühendab endas järgmised tehnilised lahendused:
* **Multi-platvormne juhend:** Katab nii tasulise (MS Project) kui ka tasuta (ProjectLibre) tarkvara [^1].
* **Struktureeritud õpe:** Kasutaja liigub läbi loogiliste sammude (01, 02, 03).
* **Visuaalne tugi:** Iga samm on varustatud selgitava ekraanitõmmisega.

> [!TIP]
> Parima kasutajakogemuse saamiseks alusta juhendi lugemist kalendri seadistamisest.

> [!IMPORTANT]
> Kõik veebilehe osad on kohandatud vastavalt TARpv24 rühma õppekavale.

---

## 💻 Koodinäide
Näide ühisest navigatsioonimenüüst, mis seob kõik lehed tervikuks:

```html
<nav>
  <a href="index.html">📅 Uue kalendri loomine</a>
  <a href="valem.html">🔢 Arvutusvälja lisamine</a>
  <a href="diagramm.html">📊 Diagrammide loomine</a>
</nav>
