# Coletor de dados

**Trabalho em Grupo Modulo 2, Resilia.**
 
## Squad 10 

- (Pessoa Co-facilitadora)<a href="https://www.linkedin.com/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">

- (Pessoa Gestora de Gente e Engajamento)<a href="https://www.linkedin.com/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
        
- (Pessoa Gestora de Conhecimento)<a href="https://www.linkedin.com/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">

- João Vitor Cunha Chinato (Pessoa Colaboradora 1) <a href="https://www.linkedin.com/in/joao-vitor-cunha-chinato/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">

- (Pessoa Colaboradora 2) <a href="https://www.linkedin.com/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">



## Evidência de Entrega:

Desenvolvemos um coletor de dados utilizando a programação orientada a objetos em Python. Nosso código permite a coleta e armazenamento de informações como idade, gênero e respostas a quatro perguntas em um arquivo CSV.
Através dele, é possível coletar, armazenar e exportar informações de forma eficiente e organizada. Essa solução tem o potencial de ser utilizada em diferentes contextos onde a coleta de dados é necessária.
Estamos satisfeitos com o resultado alcançado e confiantes de que nosso coletor de dados será uma ferramenta útil e eficaz para a obtenção de informações importantes.

## Instalação:

Para a execução do programa é necessario baixar os dois arquivos contidos na Pasta "Código" em uma mesma pasta no seu terminal para que a importação de dados não seja comprometida.

## Uso:
Execute o arquivo Main na IDE de sua preferência. Ao iniciar será solicitado sua idade a seguir gênero e as respostas para 4 perguntas, todas com as opções (! - Sim), (2 - Não), (3 - Não sei responder), caso você utilize qualquer caracter ou número diferente dos informados, irá aparecer uma mensagem dizendo que a opção é inválida e que você deve colocar uma das opções válidas, ao cometer esse erro o código já volta imediatamente para a pergunta que você estava colocando a resposta, não sendo necessário reiniciar toda a pesquisa. Para encerrar a pesquisa é necessário que você digite 00 (Na opção idade ou gênero), que assim o arquivo CSV vai ser gerado. Para modificar o nome do arquivo CSV, antes de iniciar a pesquisa é necessário que você entre no arquivo "POOBIBLIOTECA" e na função "salvar_resultados" "arquivo_csv = "nome" " fazer a alteração para o nome que você queira.

## Bibliotecas: 

numpy==1.24.3

pandas==2.0.1

python-dateutil==2.8.2

pytz==2023.3

six==1.16.0

tzdata==2023.3