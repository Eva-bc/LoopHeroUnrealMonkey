Dans ce jeu, le pion se déplace avec des dés, le résultat détermine la case d'arrivée.
On retrouve une case dialogue : le joueur si il tombe sur cette case aura accès à un dialogue ou Johnny Kiki lui demande de ramener une banane (condition de victoire).
Pour gagner, le joueur devra attérir sur la case avec la banane, si il l'atteint, la banane disparait et un menu de victoire s'ouvre avec comme option rejouer (ce qui relance le jeu) et quitter.
Si, le joueur tombe sur la case rouge, c'est un Game Over immédiat (condition de défaite).
Si le joueur tombe sur la case multicolore, un effet particule se lance.
Une musique de fond a été mise en place et le level design créer via le mode landscape.

Dans le mini jeu sans IA :

Lorsque le joueur arrive sur la case bleu turquoise il est envoyé vers le level du mini jeu : 

Dans mon mini jeu unreal, on retrouve un level design : une salle de travail. On peut voir 1 singe assis au bureau, il lance la quête de récolter les bananes perdues, en appuyant sur la touche E, le joueur pour lui parler, cela déclenche un dialogue et un sound design. Le joueur doit simplement chercher dans les bureaux où sont cachées les bananes multicolores et les récolter. Une fois toutes les bananes prisent, la porte s’ouvre avec une animation et bruit se déclenche indiquant au joueur qu’elle s’est ouverte.
La porte est ouverte et un widget apparaît pour signifier au joueur qu’il va être redirigé vers la Map du Loop Hero, un délai se lance et la map du Loop Hero se lance.

Dans le mini jeu avec IA :

Pour y accéder le joueur devra aller sur la case verte fluo, il entre dans un level. Un long couloir avec au fond une banane posée sur une table, son but prendre la banane. Mais attention, Johnny Kiki est présent et ne le laissera pas faire. Il a une fonction de patrouille et une fonction d'attaque. Si le joueur s'approche trop près de lui, il perd. Et si Johnny Kiki le détecte et l'attrape il perd aussi. Pour gagner, il suffit seulement de prendre la banane ce qui lancera un widget de victoire et ramènera le joueur au level de base (Loop Hero).
