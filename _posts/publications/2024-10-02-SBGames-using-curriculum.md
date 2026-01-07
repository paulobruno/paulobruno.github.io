---
title: "Using Curriculum to Train Multisensory Foraging DRL Agents"
subtitle: "XXIII Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/using-curriculum.jpg
header:
    teaser: /assets/images/using-curriculum.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SBGames
---

*XXIII Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*

[Rômulo Freire Férrer Filho](https://romulofff.github.io/)<sup>1</sup>
  [Alexandre Magno Monteiro Santos](https://github.com/magnomont12)<sup>1</sup>
  [Halisson Rodrigo Rodrigues](https://www.linkedin.com/in/halisson-rodrigo-7b803651)<sup>1</sup>  
[Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)<sup>1</sup>
  [Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)<sup>1</sup>
  [Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)<sup>1</sup>  
[Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)<sup>2</sup>

<p style="font-size:0.7em">
    <sup>1</sup>Department of Computing (DC), Federal University of Ceará (UFC)<br>
    <sup>2</sup>Computer Science, Gran Sasso Science Institute (GSSI)
</p>

![Curriculum](/assets/images/using-curriculum.jpg)

---

Paper: [[SBC](https://sol.sbc.org.br/index.php/sbgames/article/view/32330)]


### Abstract

<p style="text-align:justify;">
Deep reinforcement learning has shown great success in developing agents that can solve complex game tasks. However, most game agents use only visual sensors to gather information about the environment. More recent works have shown that agents that use audio sensors can perform better than vision-only agents. In this paper, we propose a curriculum-based training strategy to develop agents that effectively use audio as a source of information in foraging-based scenarios. First, we demonstrate that agents with both vision and hearing capabilities perform similarly to agents with only a visual sensor, indicating that the first ones ignore the audio. Then, we show that by using a gradually increasing difficult curriculum the agent effectively uses the audio information available, making it more robust to survive in scenarios where visual information is not available. Our results indicate that agents can be trained to effectively use audio as a source of information by using a curriculum based training strategy, improving their ability to deal with more tasks than agents with only vision.
</p>


### BibTeX

<p style="text-align:left">
  <a  href="/assets/citations/ferrer2024using.bib">Download</a>
</p>

```
@inproceedings{ferrer2024using,
  title = {Using Curriculum to Train Multisensory Foraging {DRL} Agents},
  author  = {F\'{e}rrer Filho, R\^{o}mulo Freire and
    Santos, Alexandre Magno Monteiro and
    Rodrigues, Halisson Rodrigo and
    Nogueira, Yuri Lenon Barbosa and
    Vidal, Creto Augusto and
    Cavalcante-Neto, Joaquim Bento and
    Serafim, Paulo Bruno Sousa},
  booktitle = {Anais do XXIII Simpósio Brasileiro de Jogos e Entretenimento Digital (SBGames)},
  publisher = {SBC},
  address = {Porto Alegre, RS, Brasil},
  pages = {456--473},
  year = {2024},
  doi = {10.5753/sbgames.2024.241119}
}
```
