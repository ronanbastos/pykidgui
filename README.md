```
______________________________________________________________________
| ######  #     # #    #    ###   ######   #####    #     #   ###       | 
| #     #  #   #  #   #      #    #     # #         #     #    #        |
| #     #   # #   #  #       #    #     # #         #     #    #        |
| ######     #    ###        #    #     # #    ###  #     #    #        |
| #          #    #  #       #    #     # #      #  #     #    #        |
| #          #    #   #      #    #     # #      #  #     #    #        |
| #          #    #    #    ###   ######   #####    #####     ###       |
|_______________________________________________________________________|
2025 1.5V

```

PyKidGUI é uma biblioteca Python que visa facilitar a criação de interfaces gráficas de usuário (GUIs) para aplicações desktop simples. Seu foco é em aplicações para crianças e iniciantes em programação, proporcionando uma API simples e intuitiva que permite a criação de janelas, botões, caixas de texto, imagens e outros elementos visuais de forma fácil e rápida.

## Instalação

Para instalar a biblioteca, basta executar o seguinte comando:

bash
```
pip install pykidgui
```

## Como Usar
```
Para começar a usar a PyKidGUI, importe a classe Gui do módulo pykidgui e crie uma instância da classe:



from pykidgui import Gui

gui = Gui("Minha Janela")

Em seguida, use os métodos da classe para adicionar elementos visuais à janela:



gui.add_label("Olá, mundo!")
gui.add_button("Clique aqui!")

Você também pode adicionar imagens à janela usando o método add_image:



gui.add_image("imagem.png")

E utilizar o método add_scrollbar para adicionar uma barra de rolagem a um frame:

Para adicionar um botão na janela, podemos utilizar o método add_button da classe Gui. Esse método recebe um texto que será exibido no botão e uma função que será executada quando o botão for clicado:

from pykidgui import Gui

def click_button():
    print("Botão clicado!")

gui = Gui("Minha janela", "500x500")
gui.add_button("Clique aqui", click_button)

scrollbar:

frame = gui.add_frame()
scrollbar = gui.add_scrollbar(frame)
```

## Documentação

Para mais informações sobre os métodos e parâmetros disponíveis na PyKidGUI, consulte a documentação.


## Contribuição

Contribuições para a biblioteca são sempre bem-vindas! Caso queira contribuir, abra uma issue para discutir o que você deseja adicionar ou consertar na biblioteca, e submeta um pull request com suas alterações.

## Licença

PyKidGUI é distribuída sob a licença MIT. Veja o arquivo LICENSE para mais informações.

## ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Um desenvolvedor** - *Trabalho Inicial* - [ronanbastos](https://gist.github.com/ronanbastos)

