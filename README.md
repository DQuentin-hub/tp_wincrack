# tp_wincrack

# Sujet 2 : Débugger et désassembler des programmes compilés

## Hello World

Programme "Hello World" en C
```
#include <stdio.h>

int main(void)
{
    printf("Hello World!\n");
    return 0;
}
```

decompilation du programme en C
![](https://i.imgur.com/JalXNqs.png)


## Winrar crack

On utilise le logiciel xdbg pour decompiler le programme de winRAR

on cherche dans le programmme le jump qui dirige vers la version d'evaluation.

![](https://i.imgur.com/Co9CEgl.png)


On modifie la valeur du jump a rien pour qu'il ne s'effectue pas puis on sauvegarde le resultat dans un nouveau executable qui sera compter comme une version payante.

![](https://i.imgur.com/UbnX3im.png)


Puis la version payante et donc active avec aucune liscence.

![](https://i.imgur.com/iBCnC9v.png)
