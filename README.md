# Projeto Cerâmica

Este projeto foi desenvolvido com o apoio da Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP). Seu intuito de criar uma interface para o uso da heurística proposta por [Belleboni,2016](#1) para o problema de empacotamento de peças de cerâmica em fornos tridimensionais. A interface é uma planilha a ser utilizada pelo *software* [LibreOffice](#2) versão 7.

O trabalho original de [Belleboni,2016](#1) teve como objetivo auxiliar a alocação de peças de cerâmica em um forno tridimensional. Nota-se que devido a característica do problema foi considerado que o forno poderia ser dividido em andares, de forma que o problema pudesse ser modelado como Nestings bidimensionais. Assim foi possível resolver o problema adaptando uma heurística *bottom-left*. A implementação da heurística se encontra [neste diretório](solver/bottom-left-heuristic-master/).

# Requisitos

## Instalação do LibreOffice

Primeiramente é necessário ter a suíte de escritório LibreOffice 7 instalado. Caso não possua em seu sistema operacional [este guia](https://pt-br.libreoffice.org/ajuda/instrucoes-de-instalacao/) pode auxiliar na instalação. **Caso o LibreOffice 7 não esteja instalado, o download do projeto não será realizado**.

Após o download do LibreOffice 7 é preciso dar permissão para que macros sejam executadas no *LibreOffice Calc*.  Abra o LibreOffice Calc e no menu superior escolha a opção "Ferramentas", em seguida "Opções...". Na nova janela, no canto esquerdo, selecione no menu com título "LibreOffice" a opção "Segurança". Aperte o botão "Segurança de macros...", escolha a opção "Baixa" e confirme apertando o botão "OK".


## Instalação do MikTeX de Terceiros

Para o uso da aplicação em sistemas Windows, é preciso instalar a versão completa do programa MikTeX. Para auxiliar na instalação, recomenda-se a seção de instalação da versão completa [deste guia](https://www.profmat.cefetmg.br/profmat/modelos-dissertacao/latex/instalacao-do-latex/).

# Download e Utilização da aplicação

Ao clicar [neste link](https://github.com/thuzax/CeramicaPlan/archive/refs/heads/main.zip) os arquivos presentes neste repositório serão baixados como um arquivo *zip*. Para utilizá-los basta descompactar o arquivo baixado e acessar a planilha *Fornada.ods* dentro da pasta.

# *Disclaimer*

## Códigos de terceiros

Este projeto se utiliza dos seguintes programas terceiros sem nenhuma modificação de seus códigos-fonte:

- PDFLatex
- MikTex

Por fim, este projeto também se utiliza do trabalho de [Belleboni,2016](#1) com modificações em seu código-fonte.

# Licença

A licença de uso deste projeto pode ser encontrada [aqui](LICENSE).

# Atualizações e Correções

Este projeto não prevê garantias de atualizações após sua conclusão. Os autores se isentam de qualquer responsabilidade de atualizar o Software, podendo ou não, de acordo com seu desejo, realizar modificações.


# Para Desenvolvedores

Para um guia de compilação do código-fonte ou para detalhes para desenvolvedores, acesse [este diretorio](https://github.com/thuzax/Projeto-Ceramica-Dev/blob/main/docs/).


# Links para guias

- Guia de instalação do LibreOffice: https://pt-br.libreoffice.org/ajuda/instrucoes-de-instalacao/

# Referências

<a id="1">Belleboni, Matheus G. S., 2016. </a> Aplicação web para empacotamento de peças de cerâmica em fornos tridimensionais. TCC (Graduação) - Bacharel em Ciência da Computação, Universidade de São Paulo, São Carlos - SP.

<a id="2">Foundation, T.D., 2023</a> LibreOffice Calc. Disponível em: https://hub.libreoffice.org/credits/ (Acessado em 04/01/2024).
