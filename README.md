# El-Nesr Orbital Ladder

An interactive classroom game for learning **electron configurations**: the order in which sublevels fill, and the three rules for placing electrons in orbitals.

**▶ Play it here: [drnesr.github.io/ANA_Chem](https://drnesr.github.io/ANA_Chem/)**

Runs in any browser on a laptop, tablet, Chromebook or phone. Students don't need an account, an install, or a login.

---

## What students do

Each round gives the student one element and its electrons.

### Step 1: Build the energy ladder
The sublevel tiles (`1s`, `2s`, `2p`, `3s`, …) arrive shuffled. The student taps them from **lowest to highest energy** to stack them on the ladder.
A wrong pick is rejected, and the feedback shows that tile's **n + ℓ** value so the student can see why it doesn't come next yet.

### Step 2: Place the electrons
The student picks a spin (↑ or ↓) and taps an orbital box to place one electron at a time. Every placement is checked against the three rules:

| Rule | What the game enforces |
|---|---|
| **Aufbau principle** | Fill the lowest-energy sublevel before moving up. |
| **Pauli exclusion principle** | At most two electrons per orbital, and they must have opposite spins. |
| **Hund's rule** | Within a sublevel, one electron in each orbital with the same spin before any pairing. |

A move that breaks a rule is refused, and the feedback names the rule and the reason.

### Step 3: Result
When every electron is placed, the game shows:
- the electron configuration (e.g. `1s² 2s² 2p⁴`)
- the number of unpaired electrons
- a 1–3 star score based on the number of mistakes

## Features for the teacher

- **Three levels:** H to Ne (Z = 1–10), Na to Ar (Z = 11–18), K to Kr (Z = 19–36).
- **Random or chosen element:** students can get a random atom or pick a specific one.
- **Mistake tally by rule** (Order, Aufbau, Pauli, Hund) so you can see which rule a student struggles with.
- **Hint panel:** an n + ℓ chart colored by energy, plus a summary of the rules. It opens automatically after two ordering mistakes.
- **One extra sublevel tile** appears in each round beyond what the atom needs, so students see that the electrons run out before the ladder fills.
- **Undo** and **Restart** buttons.
- **English and Arabic** interface (right-to-left in Arabic), switched with one button.
- Light and dark mode follow the device's setting.

## Note on chromium and copper

Real Cr and Cu are exceptions to the Aufbau order (`4s¹ 3d⁵` and `4s¹ 3d¹⁰`). The game teaches the configuration the Aufbau order predicts, so these two are left out of random selection. If a student picks one manually, a note explains the exception.

## Ideas for class use

- **Warm-up:** each student completes three random atoms from the current level before the lesson.
- **Exit ticket:** students screenshot their final configuration and star score.
- **Discussion:** compare the mistake tallies. Hund's rule errors usually lead to a good conversation about why electrons spread out before pairing.

## Running it offline

The whole game is a single file, `index.html`, with no dependencies. Download it and open it in any browser. Without internet the fonts fall back to system fonts; everything else works the same.

## Files

| File | Purpose |
|---|---|
| `index.html` | The complete game (HTML, CSS and JavaScript in one file). |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is. |

---

## نبذة بالعربية

لعبة تعليمية تفاعلية لتعليم التوزيع الإلكتروني.

يرتّب الطالب المستويات الفرعية من الأقل طاقة إلى الأعلى، ثم يوزّع الإلكترونات في الأوربتالات وفق مبدأ أوفباو ومبدأ باولي للاستبعاد وقاعدة هوند. ترفض اللعبة أي خطوة خاطئة وتشرح القاعدة التي خولفت.

تعمل اللعبة في المتصفح على أي جهاز، دون حساب أو تثبيت، وتدعم العربية والإنجليزية.

رابط اللعبة:

https://drnesr.github.io/ANA_Chem/

---

Created by **Dr. Mohammad Elnesr** for science classes at Al-Noor Academy.
