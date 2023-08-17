# clone-tabnews
Projeto de implementação do https://www.tabnews.com.br

Estrutura básica do Projeto:

 Node: 
    - Verificando as versões do node.js LTS
        nvm ls

    - lts/hydrogen -> v18.16
        nvm install lts/hydrogen

    - Define a versão padrão a ser utilizada no shell
        nvm alias default version  (nvm apelido padrão ??? "pra qual versão?")
        nvm alias default lts/hydrogen

        Mesmo se eu feixar a instância do codespace ou reiniciar o terminal, ele sempre terá instalado a versão lts/hydrogen instalada.

    - Quando mais pessoas entrar no meu repositório para contribuir, como elas irão saber a versão do node.js que recomendamos utilizar? 

        Criar um arquivo: .nvmrc ("rc" = Run commands)
            É um arquivo de boas práticas contendo instruções de inicialização.

        - Dentro do arquivo digitar: 
            lts/hydrogen
            "enter para pular uma linha" <- por hora é preciso fazer isso

        - No terminal, digitar: 
            nvm install

            Ele mostra que encontrou esse arquivo especial e vai instalar a versão específicada.


    