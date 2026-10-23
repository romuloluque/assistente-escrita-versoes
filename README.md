# Assistente de Escrita — versões

Aqui ficam só os instaladores e as atualizações do **Assistente de Escrita** para Mac.
O código do app não fica neste repositório.

## Instalar

1. Baixe a versão mais recente: [Assistente-de-Escrita.dmg](https://github.com/romuloluque/assistente-escrita-versoes/releases/latest/download/Assistente-de-Escrita.dmg)
2. Abra o arquivo e arraste o app para a pasta Aplicativos.
3. Antes de abrir o app pela primeira vez, abra o Terminal e cole:

   ```
   xattr -dr com.apple.quarantine "/Applications/Assistente de Escrita.app"
   ```

   (Esta versão de teste ainda não tem o selo da Apple; o comando libera o app uma vez só.)
4. Abra o app e dê a permissão de Acessibilidade quando ele pedir.

## Atualizações

Depois de instalado, o app confere sozinho a cada 6 horas se saiu versão nova e mostra
"Atualizar para a versão…" no menu do ícone e nas Configurações. As atualizações são
assinadas: o app só instala o que vier daqui, com a assinatura certa.
