# GoTouchGrass

App para reduzir o tempo de tela dos utilizadores: bloqueio de apps, bloqueio de funções e sensibilização.
Projeto da unidade curricular Projeto de Computação Móvel Avançada (PCMA), IPCA Vila Verde, 2026/2027.

Autor: Vinccent Cintra.

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `android-kotlin/` | App Android nativa (Kotlin + Jetpack Compose). Abrir esta pasta no Android Studio. |
| `web-react/` | Backoffice web (React + Vite), deploy no Firebase Hosting. |
| `functions/` | Firebase Cloud Functions (lógica de servidor, quando necessária). |
| `docs/` | Documentação do projeto: análise, requisitos, UML, modelo Firestore, testes. |

Backend: Firebase (Auth, Firestore, Storage, Hosting).

## Requisitos

- JDK 21 (Android Studio / Gradle)
- Android Studio com o Android SDK (API 37)
- Node.js 20+ e npm (para `web-react/` e `functions/`)
- Firebase CLI (`npm i -g firebase-tools`)

## Como executar

Android:
```bash
cd android-kotlin
./gradlew assembleDebug
```

Web e Functions: instruções serão adicionadas quando as pastas forem criadas.

## Estado

Em desenvolvimento. Estrutura inicial criada.
