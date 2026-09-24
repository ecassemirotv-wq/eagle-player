# EaglePlayer20.apk — análise da extração

## Artefato analisado

- APK: EaglePlayer20.apk
- Tamanho: 13,687,248 bytes
- Arquivos internos extraídos: 510
- WebApp interna: assets/webapp/
- Nome identificado em base.json: eagle-player-app
- Versão identificada: 1.1.5

## Estrutura encontrada

A extração contém:

- AndroidManifest.xml
- classes.dex, classes2.dex, classes3.dex, classes4.dex e classes5.dex
- resources.arsc
- res/
- lib/
- kotlin/
- assets/webapp/

A WebApp contém HTML, CSS, JavaScript, bibliotecas de reprodução e assets visuais.

## Reprodução

Foram identificadas bibliotecas relacionadas a HLS e MPEG-TS, incluindo os bundles hls e mpegts presentes em assets/webapp/assets/.

## Base para desenvolvimento

O APK é compilado e não representa o código-fonte original. Por isso, o material extraído deve ser tratado como base de reconstrução/personalização. O bundle WebApp é a parte mais diretamente aproveitável.

## Próximos passos

1. Recuperar os bundles/assets restantes para o repositório.
2. Organizar a WebApp em uma estrutura de projeto editável.
3. Identificar componentes, rotas, player, importação de listas e configurações.
4. Substituir gradualmente identidade visual e nome do produto por Taurus Player.
5. Validar build e reprodução antes de remover qualquer componente existente.

> Esta análise não inclui engenharia para burlar DRM, autenticação, licenciamento ou mecanismos de proteção do aplicativo.
