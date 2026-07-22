# SIM APK Public

APK publico mais recente para teste no telefone.

## APK atualizado

- Arquivo: `sim-latest-arm64-v8a.apk`
- Build: release instalavel, ABI arm64-v8a, nao Google Play
- API: `http://167.179.109.137:3000`
- Rede de teste: HTTP liberado para `167.179.109.137`
- ABI: arm64-v8a
- Assinatura: Android Debug local usada como assinatura release operacional
- Versao Android: `1.0.0 (2034)`
- App commit: `80bac3518d6652dcb6cfc846aa1d92b1b2615fec`
- Servidor commit: `479b8ae12a1ef4857a54f66e54db4e3cbeb9e7da`
- Atualizado em: 2026-07-23
- SHA256: `525ca1e92ebda9835906c28dbfa85ec4a9d00a4bbc2c4e133a7457cdd1340d6a`

Baixar direto:

https://github.com/aulasonline18-blip/SIM-APK-PUBLIC/raw/main/sim-latest-arm64-v8a.apk

## APK lado a lado

Use este se o Android recusar atualizar o app principal por conflito de
assinatura com uma instalacao antiga.

- Arquivo: `sim-latest-side-by-side-arm64-v8a.apk`
- Package: `com.aulasonline.simtest`
- Build: release instalavel, ABI arm64-v8a, nao Google Play
- API: `http://167.179.109.137:3000`
- App commit: `b02084ac97bfaae071291ce6c688ddde46fb8787`
- SHA256: `5f194a59e81c2cf06eeeb0620eee7e333c3d96c43fb13fc5ac234eb132ecc948`

Baixar direto:

https://github.com/aulasonline18-blip/SIM-APK-PUBLIC/raw/main/sim-latest-side-by-side-arm64-v8a.apk

## Observacao

O APK foi gerado em modo release dividido por ABI, com
`SIM_ALLOW_HTTP_IN_OPERATIONAL_RELEASE=true`, para aceitar o servidor HTTP de
teste sem abrir como production HTTPS.
