Habilitar dados de entrada no Sublime Text2
================


Plugin para o "suplime text 2" que permite executar scripts que aceitam entrada. Como na imagem abaixo, por exemplo.

![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/first.png)

Digite<kbd>ctrl</kbd> + <kbd>b</kbd>. Sem o plugin, você teria o seguinte erro: `EOFError`. Ao invés disso, a saída do build aparece, aguardando a entrada do dado.

![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/second.png)

Para entrar, clique em <kbd>enter</kbd>. A seguinte janela aparece.

![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/third.png)

Ao digitar <kbd>enter</kbd> após entrar com seus dados, ou <kbd>esc</kbd> para abortar, você retorna à saída da compilação, agora pode fornecer mais informações.

![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/four.png)

![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/five.png)
![](https://github.com/JoanesAraujo/Joanes_Screenshot/blob/master/imagens_build-with-input-master/six.png)

OBS: No momento, não é possível que o texto sublime mostre as janelas de entrada e saída ao mesmo tempo..

---

Este plugin funciona corrigindo o código do arquivo `exec.py` . Normalmente, isso não acontece corretamente na inicialização. Como solução temporária, você pode forçar o sublimetext a recarregar o`exec_patcher.py` abrindo, editando e salvando novamente.

<br>


# 

**<u>Tutorial</u>**  


Basta baixar o arquivo “build-with-input-master” 
e inseri-lo na pasta “Sublime Text 2 \ Packages” entre todos os outros previamente instalados. 
O caminho exato da minha pasta é, no windows 10: **C:\Users\Joanes\AppData\Roaming\Sublime Text 2\Packages** (Obs:Mas pode ser outro caminho para você.)


<i>Créditos do plugin: eric-wieser</i>


