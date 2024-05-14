# CeramicaPlan

Este projeto foi desenvolvido com o apoio da Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP). Seu intuito de criar uma interface para o uso da heurística proposta por [Belleboni,2016](#1) para o problema de empacotamento de peças de cerâmica em fornos tridimensionais. A interface é uma planilha a ser utilizada pelo *software* [LibreOffice](#2) versão 7.

O trabalho original de [Belleboni,2016](#1) teve como objetivo auxiliar a alocação de peças de cerâmica em um forno tridimensional. Nota-se que devido a característica do problema foi considerado que o forno poderia ser dividido em andares, de forma que o problema pudesse ser modelado como Nestings bidimensionais. Assim foi possível resolver o problema adaptando uma heurística *bottom-left*. A implementação da heurística se encontra [neste diretório](solver/bottom-left-heuristic-master/).

# Manual do Usuário


O Manual do Usuário contém um guia para a instalação e utilização do CeramicaPlan. Ele pode ser encontrado no diretório principal do projeto, porém ele pode ser baixado por meio [deste link](Manual%20de%20Uso.pdf).

Este manual é recomendado para aqueles que desejam utilizar o CeramicaPlan.

### TODO: atualizar o arquivo "Manual do Usuário.pdf" quando estiver revisado.


# Memorial Técnico

O Memorial Técnico contém detalhes de implementação do CeramicaPlan, incluindo descrição de algoritmos. Ele pode ser encontrado no diretório principal do projeto, porém ele pode ser baixado por meio [deste link](Memorial%20Técnico.pdf).

Este manual é recomendado para aqueles que desejam alterar o código-fonte do CeramicaPlan.

### TODO: adicionar o arquivo "Memorial Técnico.pdf" quando estiver revisado.

<!-- # Requisitos

## Instalação do LibreOffice

Primeiramente é necessário ter a suíte de escritório LibreOffice 7 instalado. Caso não possua em seu sistema operacional [este guia](https://pt-br.libreoffice.org/ajuda/instrucoes-de-instalacao/) pode auxiliar na instalação. **Caso o LibreOffice 7 não esteja instalado, o download do projeto não será realizado**.

Após o download do LibreOffice 7 é preciso dar permissão para que macros sejam executadas no *LibreOffice Calc*.  Abra o LibreOffice Calc e no menu superior escolha a opção "Ferramentas", em seguida "Opções...". Na nova janela, no canto esquerdo, selecione no menu com título "LibreOffice" a opção "Segurança". Aperte o botão "Segurança de macros...", escolha a opção "Baixa" e confirme apertando o botão "OK".


## Instalação do MikTeX de Terceiros

Para o uso da aplicação em sistemas Windows, é preciso instalar a versão completa do programa MikTeX. Para auxiliar na instalação, recomenda-se a seção de instalação da versão completa [deste guia](https://www.profmat.cefetmg.br/profmat/modelos-dissertacao/latex/instalacao-do-latex/).

# Download e Utilização da Aplicação

Ao clicar [neste link](https://github.com/thuzax/CeramicaPlan/archive/refs/heads/main.zip) os arquivos presentes neste repositório serão baixados como um arquivo *zip*.

Após o *download* descompacte o arquivo e mova-o para a pasta *Meus Documentos*. Para inicializar a aplicação basta acessar a pasta e abrir o arquivo *Fornada.ods* -->


# Licença

A licença de uso deste projeto pode ser encontrada [aqui](LICENSE.md).

# *Disclaimer*

## Códigos de terceiros

Este projeto se utiliza dos seguintes programas terceiros sem nenhuma modificação de seus códigos-fonte:

- PDFLatex
- MikTex

Por fim, este projeto também se utiliza do trabalho de [Belleboni,2016](#1) com modificações em seu código-fonte.

# Atualizações e Correções

Este projeto não prevê garantias de atualizações após sua conclusão. Os autores se isentam de qualquer responsabilidade de atualizar o Software, podendo ou não, de acordo com seu desejo, realizar modificações.

# Referências

<a id="1">Belleboni, Matheus G. S., 2016. </a> Aplicação web para empacotamento de peças de cerâmica em fornos tridimensionais. TCC (Graduação) - Bacharel em Ciência da Computação, Universidade de São Paulo, São Carlos - SP.

<a id="2">Foundation, T.D., 2023</a> LibreOffice Calc. Disponível em: https://hub.libreoffice.org/credits/ (Acessado em 04/01/2024).

# Autores

Arthur Henrique Sousa Cruz

Franklina M. B. Toledo
