Build with input
================

Um plugin para o suplime text 2 que permite executar scripts que aceitam entrada. Como na imagem abaixo, por exemplo.

![](https://raw.github.com/eric-wieser/build-with-input/screenshots/first.png)

Digite<kbd>ctrl</kbd> + <kbd>b</kbd>. Sem o plugin, você teria o seguinte erro: `EOFError`. Ao invés disso, a saída do build aparece, aguardando a entrada do dado.

![](https://raw.github.com/eric-wieser/build-with-input/screenshots/second.png)

Para entrar, clique em <kbd>enter</kbd>. A seguinte janela aparece.

![](https://raw.github.com/eric-wieser/build-with-input/screenshots/third.png)

Ao digitar <kbd>enter</kbd> após entrar com seus dados, ou <kbd>esc</kbd> para abortar, você retorna à saída da compilação, agora pode fornecer mais informações.

![](https://raw.github.com/eric-wieser/build-with-input/screenshots/fourth.png)

![](https://raw.github.com/eric-wieser/build-with-input/screenshots/fifth.png)

OBS: No momento, não é possível que o texto sublime mostre as janelas de entrada e saída ao mesmo tempo..

---

Este plugin funciona corrigindo o código do arquivo `exec.py` . Normalmente, isso não acontece corretamente na inicialização. Como solução temporária, você pode forçar o sublimetext a recarregar o`exec_patcher.py` abrindo, editando e salvando novamente.