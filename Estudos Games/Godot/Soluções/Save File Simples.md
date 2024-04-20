Existem muitas formas de se fazer save files, a própria documentação da Godot Explica de uma forma bem detalhada e completa:
- [Saving games](https://docs.godotengine.org/en/stable/tutorials/io/saving_games.html)
Mas eu irei pegar uma abordagem mais simples de início:

<iframe width="560" height="315" src="https://www.youtube.com/embed/lXO5Jt957BA?si=_vRfVKoHRvJRNCJa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

É bem simples na verdade, igual lidar com arquivos em C ou em Python.
- Primeiro, definimos o caminho do arquivo:
	- ![[Save Game Path.png]]
- Aí criamos a função de criar e escrever o arquivo:
	- ![[Save Game Write.png]]
- E por fim, criamos a função de ler o arquivo:
	- ![[Save Game Read.png]]

Isso aqui pode ser uma solução para casos mais simples, em que pouca coisa é salva, mas já funciona.
