<p align="center">
  <a href="https://dnddiceroller.com"><img src="img/logo.png" alt="DnD Dice Roller" width="360"></a>
</p>

<p align="center">
  <b>Roll dice. Keep the receipt.</b><br>
  Public tools, specs and engineering notes from the team behind <a href="https://dnddiceroller.com">dnddiceroller.com</a>.
</p>

<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d4-dark.png"><img src="img/d4.png" alt="d4" width="44"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d6-dark.png"><img src="img/d6.png" alt="d6" width="44"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d8-dark.png"><img src="img/d8.png" alt="d8" width="44"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d10-dark.png"><img src="img/d10.png" alt="d10" width="44"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d12-dark.png"><img src="img/d12.png" alt="d12" width="44"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/d20-dark.png"><img src="img/d20.png" alt="d20" width="44"></picture>
</p>

<p align="center">
  <a href="https://dnddiceroller.com"><img src="https://img.shields.io/badge/roll-dnddiceroller.com-b91c1c?style=flat-square" alt="Roll at dnddiceroller.com"></a>
  <a href="https://x.com/dnddiceroller"><img src="https://img.shields.io/badge/follow-%40dnddiceroller-111?style=flat-square&logo=x" alt="@dnddiceroller on X"></a>
  <img src="https://img.shields.io/badge/randomness-NIST%20beacon%20%2B%20drand-2f6f4f?style=flat-square" alt="Randomness: NIST beacon and drand">
</p>

---

A dice roller should be fast enough for the game table, and rigorous enough that anyone curious can see what happened.

On True Randomness, every block of rolls ends with a receipt: the public beacon pulse the numbers came from, its hash, and a certificate page that checks that hash against the beacon itself. Scan the QR at the table and see for yourself.

### Open the box

| Repo | What's inside |
| --- | --- |
| [roll-verification-spec](https://github.com/dnddiceroller/roll-verification-spec) | What a roll receipt means, how a certificate is checked, and what it does not prove |
| [dice-probability-tools](https://github.com/dnddiceroller/dice-probability-tools) | Exact odds for 4d6-drop-lowest, advantage, "can I hit DC 15?" and friends |
| [examples](https://github.com/dnddiceroller/examples) | Small runnable scripts: verify a receipt against the beacon, turn a hash into a fair die face |

### What we care about

Verifiable digital dice · cryptographically secure randomness · dice probability and simulation · reproducible roll verification · RNG testing · developer tools for tabletop games

<sub>The production platform is maintained privately. What lives here is what we're happy to prove in public.</sub>


<img width="1467" height="864" alt="Screenshot 2026-10-03 at 1 12 26 pm" src="https://github.com/user-attachments/assets/24162337-f36a-4f1a-8d93-dfdf88067b54" />

