# Mural dos Elementos do Estado — Como usar

## Estrutura de arquivos

```
index.html          → o site
images/              → as 12 imagens do mural (já incluídas)
audio/               → coloque aqui os áudios de audiodescrição (mp3)
```

## Como adicionar os áudios narrados

O site está pronto para tocar um áudio de audiodescrição para cada imagem,
igual ao "▶ Ouvir audiodescrição" do Mural da Democracia (Instituto Sivis).

Para cada imagem, grave (ou gere com uma ferramenta de texto-pra-voz) um
arquivo .mp3 com a narração da descrição e da legenda, e salve na pasta
`audio/` com o nome exato abaixo:

| # | Arquivo esperado                  | Imagem                                  |
|---|------------------------------------|------------------------------------------|
| 1 | audio/01_impeachment_dilma.mp3      | Impeachment da Dilma (2016)              |
| 2 | audio/02_diretas_ja.mp3              | Movimento Diretas Já (1983–1984)         |
| 3 | audio/03_capitanias.mp3             | Mapa das Capitanias Hereditárias (séc.XVI)|
| 4 | audio/04_palmas.mp3                 | Questão de Palmas (1895)                 |
| 5 | audio/05_quinta_boa_vista.mp3        | Quinta da Boa Vista (1808–1831)          |
| 6 | audio/06_vargas_suicidio.mp3         | Suicídio de Getúlio Vargas (1954)        |
| 7 | audio/07_constituicao_1988.mp3       | Promulgação da Constituição (1988)       |
| 8 | audio/08_proclamacao_republica.mp3   | Proclamação da República (1889)          |
| 9 | audio/09_independencia.mp3           | Independência do Brasil (1822)           |
| 10| audio/10_petroleo_nosso.mp3          | Campanha "O Petróleo É Nosso" (1953)     |
| 11| audio/11_feb_italia.mp3              | FEB na Itália (1944–1945)                |
| 12| audio/12_tratado_paz.mp3             | Tratado de Paz Brasil-Portugal (1825)    |

Depois de colocar os arquivos com esses nomes na pasta `audio/`, o player
de cada imagem funcionará automaticamente ao clicar na imagem e abrir o
modal — o aviso "Adicione o arquivo..." pode ser removido se quiser
(está na linha imediatamente abaixo de cada `<audio>` no `index.html`).

## Como visualizar

Abra o arquivo `index.html` em qualquer navegador. Para publicar online,
basta subir a pasta inteira (index.html + images/ + audio/) em qualquer
serviço de hospedagem estático (GitHub Pages, Netlify, Vercel, etc.).
