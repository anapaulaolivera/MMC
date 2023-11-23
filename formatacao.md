## Relatório 01 de Formatação de sistemas Operacionais
## Aula 06
## Diciplina: Manutenção e Montagem de Computadores
## Ana Paula Oliveira Lago

Um Master Boot Record (MBR), em português Registro Mestre de Inicialização, é um tipo especial de setor de inicialização no início de dispositivos de armazenamento em massa particionados de computadores, como discos fixos ou unidades removíveis destinadas para uso em sistemas compatíveis com IBM PC e demais. O conceito de MBRs foi introduzido ao público em 1983 com o PC DOS 2.0.
O MBR armazena as informações sobre como as partições lógicas, contendo sistemas de arquivos, são organizadas nessa mídia. O MBR também contém código executável para funcionar como um carregador para o sistema operacional instalado - geralmente passando o controle para o segundo estágio do carregador ou em conjunto com o registro de inicialização de volume (VBR) de cada partição. Esse código MBR é geralmente chamado de carregador de inicialização (boot loader).

 O GRUB é um sistema de de multiboot, com ele é possível selecionar qual sistema operacional você deseja iniciar, caso você tenha mais de um Sistema Operacional instalado no computador. Neste artigo iremos apresentar o GRUB, suas configurações, instalação e recuprecação do mesmo, em casos de falhas.

  O boot é um termo utilizado para a realização do processo de inicialização forçada de um computador ao pressionar o botão “Ligar” da máquina, até o total carregamento do sistema operacional, seja ele Windows, Linux ou Mac.
  Ele só pode ser considerado quando é realizado por uma pessoa pressionando o botão principal. Caso contrário, é considerado uma inicialização padrão do computador.




## Referências
WIKIPEDIA CONTRIBUTORS. Master Boot Record. Wikipedia, The Free Encyclopedia. Disponível em: <https://pt.wikipedia.org/w/index.php?title=Master_Boot_Record&oldid=66591806>.

LAGE, Bruno. Conhecendo o GRUB. DevMedia. Disponível em: <https://www.devmedia.com.br/conhecendo-o-grub/18698>. Acesso em: 27 out. 2023.

No title. Disponível em: <https://www.buscape.com.br/notebook/conteudo/o-que-e-boot>. Acesso em: 23 nov. 2023.