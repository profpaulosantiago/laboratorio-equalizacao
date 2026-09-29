# Laboratório de Equalização

Ferramenta didática de Acústica para o Ensino Médio. O estudante escolhe uma amostra de som, aplica presets ou ajustes próprios em um equalizador de 10 bandas e acompanha, em tempo real, o espectro e o espectrograma.

**Acesse:** https://profpaulosantiago.github.io/laboratorio-equalizacao/

## O que tem

- 10 amostras sintetizadas no próprio navegador (sem gravações, sem direitos autorais): música completa, bateria, baixo e acordes, vogais, nota com harmônicos, cinco tons puros, ruído rosa, ruído branco, varredura de 20 Hz a 20 kHz e tom ajustável.
- Equalizador gráfico de 10 bandas (31 Hz a 16 kHz, ±12 dB) e filtros passa-altas e passa-baixas.
- Presets comerciais (Neutro, Reforço de Graves, Reforço de Agudos, Vocal, Pop, Rock, Jazz, Clássico, Eletrônico, Hip-Hop, Podcast, Acústico, Loudness, Personalizado) e didáticos (Só graves, Sem graves, Só médios, Sem médios, Telefone, Rádio AM, Som do vizinho).
- Botão para comparar o som equalizado com o original.
- Espectro em barras de 1/3 de oitava ou linha detalhada, com a curva do equalizador sobreposta.
- Espectrograma rolando em tempo real.
- Jogo em grupo para 1 a 4 jogadores: três níveis, 3 jogadas seguidas por jogador em cada nível, 3 pontos por acerto e 1 pela faixa vizinha, com placar final.
- Espectrograma com régua de tempo, leitura de frequência, nível e tempo sob o mouse, marca para medir intervalos e botão Congelar.

## Publicação

Basta o arquivo `index.html` na raiz do repositório e o GitHub Pages ativado em **Settings → Pages → Deploy from a branch → main / (root)**.

Feito com a Web Audio API, sem bibliotecas externas.
