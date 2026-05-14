# TODO — Histórico

## Concluído
- [x] **Case Sunbright** adicionado abaixo dos depoimentos em vídeo (Seção 4) com gráfico clicável que abre na lightbox.
- [x] **Botão "Ver criativos reais →"** no Card 1 (Criativos) da Seção 6 abre modal com 2 tabs (Imagens · Vídeos).
- [x] Removida a Seção 7 antiga (galerias horizontais de criativos) — criativos agora ficam só no botão.
- [x] Removidos da Seção 12: 4 mini-cards (Mais eficiência, Processo previsível, Menos dependência, Escalabilidade) e o banner "Nós cuidamos de todo o processo".
- [x] Removidos da Seção 13: blocos "COMO VAMOS FAZER ISSO?", "RESULTADOS QUE GERAMOS", "Mais que uma agência" e o CTA final "QUERO ACELERAR MINHA EMPRESA". Site termina no badge `TRAZER MAIS FATURAMENTO`.

## Pendente
_(nada — encerrar a sessão)_

## Notas técnicas
- Os IDs de YouTube nos vídeos do modal e do carrossel da Seção 4 são placeholders (`V7sNO3Px6NJ`, `9PD_5ZCt-bc`, `LLZuynuktqps`, `atfqQ5Owm0s`) extraídos do site público da 1Nort. Verificar/substituir quando tiver os reais.
- CSS órfão (dead code) que pode ser limpo no futuro: `.creatives-block`, `.creatives-gallery`, `.creative-thumb`, `.metrics-perks`, `.metrics-banner`, `.metrics-cta`, `.final-block`, `.final-card`, `.final-result`, `.final-partnership`, `.final-cta-wrap`, `.rev-features`, `.rev-feature`. Funciona normal com eles, só ocupa espaço.
- Imagens próprias adicionadas em `assets/images/`: `ad1-5.png` (criativos) e `sunbright-resultados.png` (gráfico do case).
