<!-- ================================================================
     README PROFIL ORGANISATION GITHUB
     Style fusion : Apple × Rockstar × Bethesda × JetBrains
     
     OÙ PLACER CE FICHIER :
     ton-org/.github/profile/README.md
     (le banner.svg va à côté, dans le même dossier)
     
     Chaque point à personnaliser est marqué MODIFIER
     ================================================================ -->


<!-- ======================== BANNER ======================== -->
<!-- MODIFIER : Remplace l'URL par la tienne :
     https://raw.githubusercontent.com/TON-ORG/.github/main/profile/banner.svg -->

<p align="center">
  <img src="banner.svg" alt="STUDIO" width="100%" />
</p>


<!-- ======================== SLOGAN ======================== -->

<p align="center">
  <em>
    <!-- MODIFIER : Slogan du studio -->
    Petite équipe. Grands mondes.
  </em>
</p>


<!-- ======================== LIENS RAPIDES ======================== -->

<p align="center">
  <!-- MODIFIER : Remplace les # par les vraies URLs -->
  <a href="#">🌐 Site</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#">🎮 Steam</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#">💬 Discord</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#">🐦 X / Twitter</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#">📧 Contact</a>
</p>

<br/>


<!-- ======================== BLOC CODE SIGNATURE ======================== -->

```ts
// studio.config.ts — ce qu'on est, sans le marketing

export const STUDIO = {
  name:       "STUDIO",                       // MODIFIER : nom du studio
  since:      2024,                           // MODIFIER : année de création
  team:       "petite, obsessionnelle",
  motto:      "des mondes faits pour durer",  // MODIFIER : slogan
  engine:     "Unity",
  stack:      ["C#", "VR/XR", "Netcode"],     // MODIFIER : ta stack
  compromise: null,
}
```

<br/>


<!-- ======================== À PROPOS ======================== -->

## `// about()`

<!-- MODIFIER : Description du studio (2-3 lignes) -->
On est un studio de jeux indépendant fondé par deux amis qui codent, créent et
recommencent jusqu'à ce que ça tienne debout. On ne fait pas beaucoup de jeux —
on fait ceux dont on n'arrive pas à se passer.

<br/>


<!-- ======================== STACK TECHNIQUE ======================== -->

## `// stack.dependencies()`

<!-- MODIFIER : Badges — change les textes et logos selon ta stack
     Format : https://img.shields.io/badge/TEXTE-COULEUR_FOND?style=for-the-badge&logo=NOM_LOGO&logoColor=COULEUR_LOGO
     Couleurs du site : magenta=#ff2e7e  violet=#b14bff  orange=#ff7a3c  fond=#0a0a0c -->

<p align="center">
  <img src="https://img.shields.io/badge/Unity-0a0a0c?style=for-the-badge&logo=unity&logoColor=b14bff" alt="Unity" />
  &nbsp;
  <img src="https://img.shields.io/badge/C%23-0a0a0c?style=for-the-badge&logo=csharp&logoColor=ff2e7e" alt="C#" />
  &nbsp;
  <img src="https://img.shields.io/badge/Meta_Quest-0a0a0c?style=for-the-badge&logo=meta&logoColor=ff7a3c" alt="Meta Quest" />
  &nbsp;
  <img src="https://img.shields.io/badge/OpenXR-0a0a0c?style=for-the-badge&logo=khronos&logoColor=b14bff" alt="OpenXR" />
  &nbsp;
  <img src="https://img.shields.io/badge/Blender-0a0a0c?style=for-the-badge&logo=blender&logoColor=ff7a3c" alt="Blender" />
  &nbsp;
  <img src="https://img.shields.io/badge/GitHub_Actions-0a0a0c?style=for-the-badge&logo=githubactions&logoColor=b14bff" alt="GitHub Actions" />
</p>

<br/>


<!-- ======================== FONDATEURS ======================== -->

## `// founders.load()`

<!-- MODIFIER : Noms, rôles, photos, pseudos GitHub -->

<table>
  <tr>

    <!-- MODIFIER : Fondateur 1 -->
    <td align="center" width="50%">
      <!-- MODIFIER : Photo — remplace par l'URL de ta photo ou ton avatar GitHub -->
      <img
        src="https://github.com/identicons/placeholder1.png"
        width="120"
        style="border-radius:16px"
      /><br/>
      <!-- MODIFIER : Nom -->
      <strong>Prénom Nom</strong><br/>
      <!-- MODIFIER : Rôle -->
      <sub>Co-founder · CEO</sub><br/>
      <sub>
        <!-- MODIFIER : Lien profil GitHub -->
        <a href="#">@pseudo</a>
      </sub>
    </td>

    <!-- MODIFIER : Fondateur 2 -->
    <td align="center" width="50%">
      <!-- MODIFIER : Photo -->
      <img
        src="https://github.com/identicons/placeholder2.png"
        width="120"
        style="border-radius:16px"
      /><br/>
      <!-- MODIFIER : Nom -->
      <strong>Prénom Nom</strong><br/>
      <!-- MODIFIER : Rôle -->
      <sub>Co-founder · CEO</sub><br/>
      <sub>
        <!-- MODIFIER : Lien profil GitHub -->
        <a href="#">@pseudo</a>
      </sub>
    </td>

  </tr>
</table>

<br/>


<!-- ======================== PROJETS ======================== -->

## `// projects.list()`

<!-- MODIFIER : Tes projets — ajoute / supprime des lignes
     Statuts : ⚪ concept  🟠 pré-prod  🔴 production  🟣 alpha
               🔵 beta  🔷 RC  🟢 gold  🟡 live  ⚫ en pause -->

| Statut | Projet | Description | Stack |
|:------:|--------|-------------|-------|
| 🔴 `production` | **Project One** | Le pitch en une ligne | `Unity` `C#` `VR` |
| 🟣 `alpha` | **Project Two** | Le pitch en une ligne | `Unity` `C#` `Netcode` |
| 🟠 `pré-prod` | **Project Three** | Le pitch en une ligne | `Unity` `C#` |

<br/>


<!-- ======================== CI/CD ======================== -->

## `// ci.pipeline()`

<!-- MODIFIER : Adapte selon tes workflows -->

```
📦 Build APK Quest    → GameCI + GitHub Actions (auto sur push main + tag)
🔔 Discord Notify     → Embeds custom push / PR / issues (toutes branches)
📅 Daily Digest       → Récap quotidien 21h Paris
🏆 Top Contributors   → Podium hebdo dimanche soir
```

<br/>


<!-- ======================== VALEURS ======================== -->

## `// values.core()`

<!-- MODIFIER : Tes valeurs -->

```ts
const VALUES = [
  "Le détail d'abord — un jeu plus petit mais sans angle mort",
  "Indépendance — personne pour nous dire quoi faire",
  "Joueur avant tout — l'expérience prime sur la feature list",
  "Code propre — si c'est moche dedans, c'est fragile dehors",
]
```

<br/>


<!-- ======================== CONTACT ======================== -->

## `// contact.ping()`

<!-- MODIFIER : Tes liens et emails -->

```
📧  hello@studio.com
🎮  steam.com/studio
💬  discord.gg/studio
🐦  x.com/studio
🌐  studio.github.io
```

<br/>


<!-- ======================== FOOTER ======================== -->

---

<p align="center">
  <sub>
    <!-- MODIFIER : Slogan final -->
    <em>On ne sort pas des jeux. On livre des mondes.</em>
  </sub>
</p>

<p align="center">
  <sub>
    <!-- MODIFIER : Nom du studio + année -->
    © 2024 — STUDIO
  </sub>
</p>
