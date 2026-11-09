## Lost Odyssey — Tradução PT-BR Feita com IA
CHATGPT 🤣🤣🤣🤣 (Fez o trabalho de tradução e edição de imagens para pt-br)

*USANDO A RECOMP DO FREEFRANK https://github.com/freefrank/LostOdysseyRecomp 
NÃO FOI TESTADA EM OUTRAS.*

Todos Discos traduzidos(Pode conter coisas para traduzir ainda, pois foi feito com IA)

Lost Odyssey — Tradução PT-BR 
Projeto independente de tradução para português do Brasil, desenvolvido para o LostOdysseyRecomp no Windows.
O pacote reúne os textos traduzidos, ajustes de interface e complementos em um único download, com instalador, desinstalador e backup automático.

O que foi feito
- Tradução e revisão de 537 tabelas JSON, incluindo diálogos, menus, itens, habilidades e descrições.
- Tradução de textos incorporados às imagens da interface.
- Atualização de 839 campos de cenário, incluindo nomes de localidades e comandos de interação.
- Tradução da abertura e dos 34 contos disponíveis nos arquivos analisados.
- Ajustes de largura, espaçamento e posição dos textos, incluindo títulos e palavras animadas.
- Correção dos 71 alertas de sobreposição identificados no último lote de contos.
- Inclusão de Português (Brasil) na seleção de idioma.
Os arquivos passaram por validação de estrutura, códigos, parâmetros e integridade. Nos contos, os tempos de aparição foram preservados.

## Correções 09/11/2026

**Nomes de área (issue #8)** — o menu mostrava o nome de outra região (ex.: Grandes Ruínas Ancestrais
aparecendo como Boa Branca, Mansão de Gongora com o nome trocado). A lista de nomes do menu pula
entradas vazias e 33 marcações de área que no original eram um espaço em branco tinham sido gravadas
como texto vazio; a partir do primeiro vazio cada área passava a exibir o nome da seguinte. As 33
entradas foram restauradas. Arquivo: `mods/pt-br-idioma/text/bin/xenon/loc/int/field/name_data.xmb.json`.

**Fontes do combate (issue #7)** — os rótulos Perfeito/Bom/Ruim, ERRO, DEFESA, PV, PM, DEFESA DANO,
DANO + e ATRASO estavam sem contorno e sem sombra. Foram redesenhados com o mesmo estilo dos originais
(fonte pesada, contorno preto e sombra), na mesma altura e linha de base. Arquivos:
`mods/lo-ptbr-interface-v160/overlay/textures/fp-1627668e252c2566.lotex2` e `fp-8b6461694cb2ad8b.lotex2`.

Nenhum texto traduzido foi reescrito: 2.508 chaves do cenário continuam as mesmas, com 33 valores
brancos restaurados, e as duas texturas mudaram apenas nas áreas dos rótulos.

## Instalação

1. Use LostOdysseyRecomp 1.0.6 ou posterior para Windows, com a base inglesa INT disponível. Este pacote não inclui o jogo.
2. Se usava a V159 com instalador, desinstale-a com o desinstalador daquele pacote antes de testar esta edição sobre arquivos originais. Somente apagar a pasta mods não desfaz alterações feitas anteriormente nos discos. Preserve seus saves.
3. Feche o jogo. Extraia este ZIP ao lado de LostOdysseyRecomp.exe. Isso coloca as pastas pt-br-idioma e lo-ptbr-interface-v160 dentro da pasta mods. Também pode copiar manualmente as duas pastas de dentro de mods para a pasta mods da sua instalação. Evite mods/mods.
4. Não deixe versões antigas da tradução/interface ativas junto com esta. Se já existe pt-br-idioma, guarde a pasta anterior separadamente e use a desta versão inteira.
5. Abra o jogo. Em Settings > System > Game language, selecione Português (Brasil), salve e reinicie.
6. Em Mods, deixe Lost Odyssey PT-BR - Interface e videos ativado. A pasta de idioma aparece como pacote de idioma, selecionado na opção Game language.

Compatibilidade e testes
A tradução foi feita para o recomp do Freefrank. Não foi testado em outros recomps.

Encontrou algum problema?
Abra uma Issue informando:
- Versão do LostOdysseyRecomp e do pacote de tradução.
- Área, cena ou conto em que ocorreu.
- Captura de tela e descrição do problema.
Projeto de fãs, sem vínculo oficial com os responsáveis por Lost Odyssey.
