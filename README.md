# LightNote para Android

O app de celular do **LightNote**: as notas do seu espaço de trabalho no telefone, gravadas e
lidas pelo **mesmo núcleo** do aplicativo do computador. Este repositório guarda só os
**downloads** do app Android; o código-fonte é mantido num repositório privado.

> ⚠️ **Esta é uma prévia gratuita, distribuída só por aqui.** Quando o LightNote chegar à
> **Google Play**, ele será um app **pago, com preço único** (ainda não definido). A prévia
> não dá direito à versão da loja, e os APKs deste repositório podem deixar de ser
> atualizados depois do lançamento.

## ⬇️ Baixar

- **[Versão mais recente](https://github.com/nglczr/LightNote-Android/releases/latest)** —
  o arquivo `LightNote-Android-<versão>.apk`.
- Requisitos: **Android 9 ou mais novo**, celular **ARM de 64 bits** (praticamente todos os
  atuais).

### Instalar

1. Baixe o `.apk` pelo navegador do celular e toque nele.
2. O Android pede para **permitir a instalação** de apps pelo navegador ou pelo gerenciador
   de arquivos; permita só para esta instalação, se preferir.
3. O **Play Protect** pode avisar sobre um desenvolvedor desconhecido, porque o app não vem
   da Play. Confira a assinatura abaixo antes de seguir.

### Conferir a assinatura

Todo APK do LightNote é assinado com a mesma chave. A impressão digital SHA-256 do
certificado é:

```
30:E0:EB:DF:F7:CE:FC:62:45:7B:57:83:D7:17:3A:78:A0:AE:11:CE:11:AB:8B:3B:DB:A5:A4:F6:1C:7F:B0:F3
```

Confira com `apksigner verify --print-certs LightNote-Android-<versão>.apk` (build-tools do
Android SDK) ou num app como o AppVerifier. Cada release também traz o `SHA256SUMS.txt`.

### Atualizar

Instale o APK novo **por cima** do antigo: as notas ficam. **Não desinstale para
atualizar** — desinstalar apaga os espaços que não foram sincronizados por Git nem exportados
por *Exportar vault (.zip)*.

Para ser avisado das versões novas, adicione o endereço deste repositório
(`https://github.com/nglczr/LightNote-Android`) ao [Obtainium](https://github.com/ImranR98/Obtainium).

## 📖 Ajuda

- **Ajuda do app Android:** <https://lightnote.com.br/app>
- **Levar as notas do computador para o celular** (Git e QR code):
  <https://lightnote.com.br/ajuda#celular>

## 💬 Bugs e sugestões

As conversas ficam num lugar só, no repositório da comunidade:

- **Encontrou um bug?** Abra uma [issue](https://github.com/nglczr/LightNote-Community/issues/new/choose)
  e escolha *Android* no campo de plataforma.
- **Sugestões e dúvidas:** [Discussions](https://github.com/nglczr/LightNote-Community/discussions).

## 📄 Licença

A prévia segue os termos da edição gratuita do LightNote — uso **pessoal e não comercial**:
[Português](https://github.com/nglczr/LightNote-Community/blob/main/LICENSE.pt-BR.md) (versão
autoritativa) · [English](https://github.com/nglczr/LightNote-Community/blob/main/LICENSE.en.md).

---

## English

**LightNote for Android** — your LightNote notes on the phone, written and read by the same
core as the desktop app. This repository only hosts the Android **downloads**.

> ⚠️ **This is a free preview, distributed only here.** When LightNote reaches **Google
> Play**, it will be a **paid app with a one-time price** (not yet set). The preview does not
> include the store version, and the APKs in this repository may stop being updated after
> the launch.

- **Download:** [latest release](https://github.com/nglczr/LightNote-Android/releases/latest)
  — Android 9 or newer, 64-bit ARM phone.
- **Install:** open the `.apk` on the phone and allow installing from your browser or file
  manager; Play Protect may warn about an unknown developer. Check the certificate
  fingerprint above first.
- **Update:** install the new APK over the old one — **do not uninstall**, which deletes the
  spaces not synced by Git nor exported. [Obtainium](https://github.com/ImranR98/Obtainium)
  can watch this repository for new versions.
- **Help:** <https://lightnote.com.br/app-en>
- **Bugs and ideas:** [issues](https://github.com/nglczr/LightNote-Community/issues/new/choose)
  and [Discussions](https://github.com/nglczr/LightNote-Community/discussions) in the
  community repository.
- **License:** the free edition terms (personal, non-commercial use):
  [LICENSE.en.md](https://github.com/nglczr/LightNote-Community/blob/main/LICENSE.en.md).

© 2026 NGLCZR · [lightnote.com.br](https://lightnote.com.br)
