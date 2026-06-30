VÍDEO DO HERO — HT (via YouTube)
================================
O hero agora usa um vídeo do YouTube como fundo (autoplay, mudo, loop,
sem controles, cobrindo a tela toda).

COMO TROCAR O VÍDEO
-------------------
1. Suba o vídeo no YouTube (pode ser "não listado" — não precisa ser público).
   - Use takes da empresa, SEM depender do áudio (o autoplay roda mudo).
   - Imagens estáveis; o texto fica por cima com um overlay escuro.
2. Pegue o ID do vídeo:
   - Em https://youtu.be/abc123XYZ            -> o ID e' abc123XYZ
   - Em https://youtube.com/watch?v=abc123XYZ -> o ID e' abc123XYZ
3. No index.html, dentro de <section class="lp-hero">, troque os DOIS
   "YOUTUBE_ID" pelo seu ID (um no /embed/ e outro em &playlist=...).
   O "playlist" e' o que faz o loop funcionar.

OBSERVAÇÕES
-----------
- O autoplay só funciona com o vídeo MUDO (já está mute=1).
- Vídeos muito longos demoram a iniciar; ideal 10–30s.
- Enquanto o ID não for trocado, o hero mostra o fundo escuro com a grade
  técnica (degrada com elegância — nada quebra).

ALTERNATIVA: ARQUIVO LOCAL (MP4)
--------------------------------
Se preferir hospedar o arquivo no próprio site (sem YouTube), dá pra voltar
ao <video> com assets/hero/hero.mp4 + poster.jpg. É só pedir que eu troco.
