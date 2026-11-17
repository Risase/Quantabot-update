# Quantabot-update

Software update page for Quantabot robots (Quantum Prints).

This repository is the public "update page" the robots check. It holds only two kinds of files, both made by the Quantabot Update Publisher on the owner's computer:

- `manifest.json` (and `manifest-early.json` for test builds): the signed description of the newest version
- the program file(s) it points to (`*.bin`)

Robots accept an update only if the signature matches the key built into their firmware, so nothing else here can change a robot.

Address once GitHub Pages is on (Settings > Pages > Deploy from branch > `main` / root):
`https://risase.github.io/quantabot-update/`

Do not put keys, passwords or other secrets in this repository. It is public.
