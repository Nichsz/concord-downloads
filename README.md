# Concord — Downloads

Instaladores do **Concord**, app de chat de voz, vídeo e texto feito para um grupo de amigos.

## Baixar

| Sistema | Arquivo |
| --- | --- |
| Windows 10 / 11 | [Concord-win.exe](https://github.com/Nichsz/concord-downloads/releases/latest/download/Concord-win.exe) |
| Linux (qualquer distribuição) | [Concord-linux.AppImage](https://github.com/Nichsz/concord-downloads/releases/latest/download/Concord-linux.AppImage) |
| Ubuntu / Debian / Mint | [Concord-linux.deb](https://github.com/Nichsz/concord-downloads/releases/latest/download/Concord-linux.deb) |

Se preferir, dá para usar direto no navegador: https://concord-steel.vercel.app

## Como instalar

### Windows

1. Baixe o `Concord-win.exe` e abra.
2. Se aparecer **"O Windows protegeu seu PC"**, clique em **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece porque o instalador não tem assinatura digital paga, e não significa que o arquivo seja perigoso.
3. Siga o instalador. Um atalho do Concord vai aparecer na área de trabalho e no menu Iniciar.

### Linux (AppImage)

Dê permissão de execução e abra:

```bash
chmod +x Concord-linux.AppImage
./Concord-linux.AppImage
```

Se não abrir, instale o `libfuse2` (no Ubuntu 24.04 o pacote se chama `libfuse2t64`):

```bash
sudo apt install libfuse2
```

### Linux (.deb)

```bash
sudo apt install ./Concord-linux.deb
```

## Como funciona

- O app abre o site do Concord numa janela própria. Por isso precisa de internet, e as atualizações do site chegam sozinhas, sem reinstalar.
- Ao fechar a janela, o Concord continua rodando na **bandeja do sistema** (perto do relógio), para a voz não cair. Para sair de verdade, clique com o botão direito no ícone e escolha **Sair**.
- No GNOME (Linux), o ícone da bandeja só aparece com a extensão **AppIndicator** instalada.

## Problemas?

Abra uma [Issue](https://github.com/Nichsz/concord-downloads/issues) aqui no repositório ou fale com o dono do grupo.
