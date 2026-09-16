# SPIDER // TRAINING

PWA pessoal, mobile-first, para calistenia sem equipamento. Feita para abrir no Safari do iPhone e ser adicionada à Tela de Início.

## Recursos

- Foundation, Beginner, Intermediate e Advanced.
- Mantém as rotinas originais: Push + Core, Cindy Adaptado, Pernas + Core e Costas + Braços + Core.
- Adiciona Spider Core, Calistenia Full Body e Skill & Controle.
- Biblioteca com exercícios para peito, ombros, tríceps, bíceps auto-resistido, pernas, glúteos, panturrilhas, abdômen/core, costas e cadeia posterior.
- Guia de execução para cada movimento.
- Manequim 3D projetado em Canvas e animado por keyframes, sem bibliotecas externas.
- Coach de voz com Web Speech API: anuncia exercício, séries, descanso, próximos movimentos e contagem ritmada de repetições.
- Vibração quando disponível.
- Progressão adaptativa pelo esforço percebido.
- Histórico, streak, consistência, XP, fotos de check-in locais e backup JSON.
- Offline-first via Service Worker.
- Nenhum login, servidor ou API externa obrigatória.

## GitHub Pages

Este repositório inclui `.github/workflows/pages.yml`.

Depois que o código estiver no GitHub:

1. Abra **Settings → Pages**.
2. Em **Build and deployment / Source**, selecione **GitHub Actions**.
3. Aguarde o workflow **Deploy PWA to GitHub Pages** ficar verde.
4. Abra a URL publicada no Safari do iPhone.
5. Toque em **Compartilhar → Adicionar à Tela de Início**.

Depois da primeira carga, os arquivos principais ficam em cache e o app pode funcionar offline.

## Observação sobre voz no iPhone

A voz usa as vozes disponibilizadas pelo próprio iOS/Safari. O app prioriza `pt-BR`. A naturalidade exata depende das vozes instaladas no aparelho. O navegador pode exigir uma interação do usuário antes da primeira fala.

## Segurança do treino

O app não substitui avaliação médica ou fisioterapêutica. O programa pede progressão gradual e orienta parar em caso de dor aguda, tontura ou perda importante da técnica. Exercícios de costas sem equipamento fortalecem escápulas, lombar e cadeia posterior, mas não substituem completamente exercícios de puxada com barra/elástico.
