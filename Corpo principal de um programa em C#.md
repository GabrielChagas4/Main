# Main
Primeiramente abra o seu explorador de arquivos, você vai ver lá encima o botão exibir( ou vizualizar no Windows 11) e vá em "Mostrar", marque a opção "Extensão de nomes de arquivos( isso serve pros 2 Windows, tanto o 10 quanto o 11)


Segundo Passo: clique com o botão direito do mouse ou mousepad na área de trabalho,em seguida vá em novo e clique em documento de texto, nesse documento você pode colocar o nome que quiser, vamos por exemplo chamar o arquivo de "hello", em seguida após o nome vai estar escrito "hello.txt", mude para "hello.cs".Depois disso clique com o botão direito encima do arquivo e vá em "Abrir com" e seleciona bloco de notas.Ao abrir o bloco de notas você vai escrever o seguinte comando:

using System

class HelloWorld
{
      static void Main (string[] args)
      {
            Console.WriteLine("aqui você escreve o que quiser");
      }
}


Atenção: para dar os espaçamentos grandes pressione a tecla "TAB" do seu teclado( tecla essa que tem uma setinha indo e uma voltando, ou pode estar escrito "TAB" mesmo :) )! 


Terceiro Passo: vá ao explorador de arquivos do seu Windows(o meu é o 11 então pode estar diferente do seu, mas é pouquíssima coisa), na aba vertical da esquerda clique em "Este Computador", logo depois clique em "Disco Local (C:)", depois em "Windows", depois em "Microsoft.NET", depois em "Framework", depois vai na versão mais atualizada( no caso a minha é "v4.0.3.0.319").Logo depois disso você vai ver acima dos arquivos uma barra na horinzontal mostrando todos os procedimentos feitos no passo 2, você clica uma vez com o botão esquerdo do mouse pra deixar tudo marcado,depois você vai executar o comando CTRL + C(mantém o CTRL apertado e da um clique no C).

Quarto       Passo: vá na aba de pesquisa do seu Windows e procure pelo nome "Prompt de Comando" e abre o aplicativo, logo após isso digite o comando "cd Desktop" e aperte "ENTER", logo em seguida voce vai executar o comando CTRL + V(mantém o CTRL apertado e dá um clique no V).

Vai estar assim :
C:\Users\nome do seu usuário\Desktop\C:\Windows\Microsoft.NET\Framework\v4.0.30319>

Digite o comando csc.exe hello.cs(só vai ser "hello" se você nomeou ele assim lá nos passos anteriores)

Vai ficar assim:
C:\Users\nome do seu usuário\Desktop\C:\Windows\Microsoft.NET\Framework\v4.0.30319>csc.exe hello.cs 

Aperta enter,se tudo ocorrer certo enão aparecer nenhuma mensagem "error", vau aparecer um arquivo .exe na sua área de trabalho, o meu por exemplo apareceu como "hello.exe"

Quinto passo: volte no "Prompt de Comando" e digite o comando  "cls", vai ficar assim:
C:\Users\nome do seu usuário\Desktop>cls

aperta no "ENTER" e vai limpar todos os seus comandos anteriores!

Sexto e útimo passo: ainda no "Prompt de Comando" digite "hello.cs" (novamente, só vai ser "hello" se você denomeou "hello" no seu também)
Vai ficar assim:
C:\Users\nome do seu usuário\Desktop>hello.cs

aperta o "ENTER" e se tudo ocorrer vai aparecer o comando WriteLine executado, vai estar mais ou menos assim:

Hello, World!


FIM!

Qualquer dúvidas me chama!
