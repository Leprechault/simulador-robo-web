# Simulador Web – Robô terrestre desviando de cultivos

Simulador 2D com LiDAR simulado, desvio reativo (VFH-like) e teleoperação WASD. Ideal para turmas: cada aluno abre o link e tem sua própria instância.

## Publicação rápida (GitHub Pages)
1. Crie um repositório público (ex.: `simulador-robo-web`).
2. Envie estes arquivos para a branch `main`.
3. Em *Settings → Pages*, configure `Deploy from a branch` (branch `main`, pasta `/root`).
4. Acesse `https://<seu-usuario>.github.io/simulador-robo-web/`.

## Uso
- Clique no mapa para definir o objetivo (*goal*).
- WASD/Setas para teleop; `Espaço` pausa.
- Ajuste velocidade, raios LiDAR, ruído e layout (linhas de cultivo, grade, aleatório).
- Exporte CSV de telemetria para análise.

## PWA
Manifest + service worker inclusos. Ao abrir via HTTPS, pode instalar como app (mobile/desktop).

## Licença
MIT
