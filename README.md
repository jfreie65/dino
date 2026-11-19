# 🦖 Dino Aventura – Puzzles, Taquin e Sequências

Jogo educativo online sobre dinossauros, em português, para crianças do 1.º e 2.º ciclos. Junta puzzles de encaixe, Taquin (peças deslizantes) e jogos de sequências, com pontos, níveis, estrelas e medalhas para motivar os alunos.

Todo o jogo está num único ficheiro (`index.html`), com as imagens incluídas. Não precisa de instalação nem de servidor e funciona mesmo sem Internet.

## 🎮 Modos de jogo

### 🧩 Puzzle de encaixe
Peças com recortes de encaixe, como num puzzle verdadeiro. Arrastam-se até ao tabuleiro e encaixam sozinhas quando ficam perto do sítio certo. Cada puzzle mostra o dinossauro e uma faixa com o seu nome.

| Nível | Peças | Filas |
|---|---|---|
| 🥚 Iniciante | 6 | 2 |
| 🐣 Fácil | 12 | 3 |
| 🦕 Médio | 20 | 4 |
| 🦖 Difícil | 30 | 5 |
| 👑 Mestre | 48 | 6 |

Ajudas: imagem de fundo no tabuleiro, modelo, dica (a peça e o seu lugar piscam) e botão para espalhar as peças.

### 🔲 Taquin
Quebra-cabeças de peças deslizantes, em 3×3, 4×4 ou 5×5, com quatro variantes:
- **Clássico**: só a imagem.
- **Com números**: cada peça mostra o seu número, para quem está a começar.
- **Contra o relógio**: é preciso resolver antes de o tempo acabar.
- **Filas giratórias**: não há espaço vazio; rodam-se filas e colunas inteiras.

Todos os Taquins têm solução, porque a mistura das peças só usa jogadas permitidas.

### 🔢 Sequências
- **Do mais pequeno ao maior**: ordenar os dinossauros pelo comprimento.
- **Linha do tempo**: ordenar do mais antigo ao mais recente (Triássico, Jurássico, Cretácico).
- **Memória Jurássica**: repetir sequências de rugidos cada vez mais longas.

### 📒 Caderneta e 🏅 medalhas
Cada puzzle ou Taquin resolvido desbloqueia a ficha do dinossauro na Caderneta, com o período, o comprimento, o peso, a alimentação e uma curiosidade. Há 6 níveis de experiência (do *Ovo de Dinossauro* ao *Mestre dos Dinossauros*) e 15 medalhas. O progresso fica guardado no navegador de cada aluno.

## 🦕 Os 14 dinossauros

Plateossauro, Celófise, Braquiossauro, Diplódoco, Estegossauro, Alossauro, Compsognato, Iguanodonte, Espinossauro, Parassaurolofo, Velociraptor, Anquilossauro, Tricerátopo e Tiranossauro rex.

## 🚀 Publicar no GitHub Pages

1. Cria um repositório novo (por exemplo `dino-aventura`) e envia para lá o `index.html` e este `README.md`.
2. Abre **Settings → Pages**.
3. Em **Branch**, escolhe `main` e a pasta `/ (root)`, e clica em **Save**.
4. Passado um ou dois minutos, o jogo fica disponível em:
   `https://O-TEU-UTILIZADOR.github.io/dino-aventura/`

## 🖥️ Integrar num blog (Blogger, WordPress, etc.)

Cola este código no editor HTML da publicação:

```html
<iframe src="https://O-TEU-UTILIZADOR.github.io/dino-aventura/"
        width="100%" height="900" style="border:0;border-radius:16px"
        allowfullscreen loading="lazy"></iframe>
```

Se o jogo parecer cortado, aumenta o valor de `height`.

## 🛠️ Tecnologia

- HTML, CSS e JavaScript simples, sem bibliotecas.
- As peças do puzzle são desenhadas em `<canvas>` com curvas de Bézier e têm um recorte diferente em cada jogo.
- Funciona com rato, ecrã tátil e teclado (setas no Taquin), em computador, tablet ou telemóvel.
- Botão de ecrã completo (⛶) no canto superior direito, ou tecla **F**. Dentro de um blog, o `iframe` precisa do atributo `allowfullscreen`.
- Os sons são gerados com a Web Audio API (sem ficheiros de som) e podem ser desligados.
- O progresso é guardado em `localStorage`.
- Usa os tipos de letra *Baloo 2* e *Nunito* do Google Fonts. Sem Internet, o navegador usa um tipo de letra de substituição.

## 📷 Créditos das imagens

As ilustrações são reconstituições científicas da [Wikimedia Commons](https://commons.wikimedia.org), usadas segundo as suas licenças livres. Foram reduzidas, recortadas e combinadas com texto para criar os puzzles.

| Dinossauro | Ficheiro original | Autor | Licença |
|---|---|---|---|
| Plateossauro | [PlateosaurusIllustration.png](https://commons.wikimedia.org/wiki/File:PlateosaurusIllustration.png) | D2Hills | CC BY-SA 4.0 |
| Celófise | [Coelophysis bauri illustration.jpg](https://commons.wikimedia.org/wiki/File:Coelophysis_bauri_illustration.jpg) | MakairodonX | CC BY-SA 4.0 |
| Braquiossauro | [Brachiosaurus DB.jpg](https://commons.wikimedia.org/wiki/File:Brachiosaurus_DB.jpg) | Dmitry Bogdanov | Domínio público |
| Diplódoco | [Diplodocus carnegii.jpg](https://commons.wikimedia.org/wiki/File:Diplodocus_carnegii.jpg) | Fred Wierum | CC BY-SA 4.0 |
| Estegossauro | [Stegosaurus stenops Life Reconstruction.png](https://commons.wikimedia.org/wiki/File:Stegosaurus_stenops_Life_Reconstruction.png) | Fred Wierum | CC BY-SA 4.0 |
| Alossauro | [Allosaurus Revised.jpg](https://commons.wikimedia.org/wiki/File:Allosaurus_Revised.jpg) | Fred Wierum | CC BY-SA 4.0 |
| Compsognato | [Compsognathus Conty.png](https://commons.wikimedia.org/wiki/File:Compsognathus_Conty.png) | Conty | CC BY-SA 4.0 |
| Iguanodonte | [Iguanodon bernissartensis (Davide Bonadonna).png](https://commons.wikimedia.org/wiki/File:Iguanodon_bernissartensis_(Davide_Bonadonna).png) | Davide Bonadonna | CC BY 4.0 |
| Espinossauro | [Spinosaurus durbed.jpg](https://commons.wikimedia.org/wiki/File:Spinosaurus_durbed.jpg) | Durbed | CC BY-SA 3.0 |
| Parassaurolofo | [Life reconstruction of Parasaurolophus walkeri.png](https://commons.wikimedia.org/wiki/File:Life_reconstruction_of_Parasaurolophus_walkeri.png) | Connor Ashbridge | CC BY-SA 4.0 |
| Velociraptor | [Velociraptor Restoration.png](https://commons.wikimedia.org/wiki/File:Velociraptor_Restoration.png) | Fred Wierum | CC BY-SA 4.0 |
| Anquilossauro | [Ankylosaurus magniventris reconstruction.png](https://commons.wikimedia.org/wiki/File:Ankylosaurus_magniventris_reconstruction.png) | Emily Willoughby | CC BY-SA 3.0 |
| Tricerátopo | [Triceratops liveDB.jpg](https://commons.wikimedia.org/wiki/File:Triceratops_liveDB.jpg) | Dmitry Bogdanov | CC BY 3.0 |
| Tiranossauro rex | [Rjpalmer tyrannosaurusrex 001.jpg](https://commons.wikimedia.org/wiki/File:Rjpalmer_tyrannosaurusrex_001.jpg) | RJPalmerArt | CC BY-SA 4.0 |

As versões adaptadas das imagens com licença CC BY-SA continuam sob a mesma licença (*Partilha nos Mesmos Termos*). Os créditos também aparecem dentro do jogo, no ecrã **Créditos das imagens**.

## 📄 Licença

- **Código** (HTML, CSS e JavaScript): podes usá-lo, adaptá-lo e partilhá-lo livremente para fins educativos, indicando a origem.
- **Imagens**: cada imagem mantém a licença do seu autor (ver a tabela acima).

---

Feito para aprender a brincar. Bons achados, jovens paleontólogos! 🦴
