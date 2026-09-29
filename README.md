# TP React 2026 — corrections

Corrections pas à pas du TP React (CPE ASI2).

**Sujet du TP :** https://github.com/loiclegoff/irc-react-2026

Ce dépôt ne contient que le code. L'énoncé est dans le dépôt ci-dessus, pour
éviter d'avoir deux copies du même document qui divergent.

## Étapes

Chaque branche est l'état du projet à la fin de l'étape correspondante.

| Branche | Étape |
|---|---|
| [`step0-first_app`](../../tree/step0-first_app) | Step 0 — premier composant |
| [`step1-first_app_with_bootstrap_components`](../../tree/step1-first_app_with_bootstrap_components) | Step 1 — composants react-bootstrap |
| [`step2-1_robot_img_video`](../../tree/step2-1_robot_img_video) | Step 2 — un robot |
| [`step3-list_of_robots_img_video`](../../tree/step3-list_of_robots_img_video) | Step 3 — liste de robots |
| [`step4-list_of_robots_with_related_parts`](../../tree/step4-list_of_robots_with_related_parts) | Step 4 — pièces associées |
| [`step4bis-list_of_robots_with_related_parts_and_right_panel`](../../tree/step4bis-list_of_robots_with_related_parts_and_right_panel) | Step 4 bis — panneau de détail |
| [`step5-list_of_robots_with_related_parts_redux`](../../tree/step5-list_of_robots_with_related_parts_redux) | Step 5 — Redux |

La branche `dev` est une reprise plus granulaire des mêmes étapes.

## Lire les diffs

Les liens `compare/...` du sujet montrent l'écart entre deux étapes. Les
lockfiles ont été retirés de l'historique pour que ces diffs ne contiennent
que le code.

## Stack

React 19 · Vite 8 · Redux 5 · react-redux 9 · Node 24 (voir `.nvmrc`)

```bash
nvm use && npm install && npm run dev
```

API : https://robot-cpe.cleverapps.io
