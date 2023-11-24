## Relatório 02 de Fortamtação de Sistemas Operacionais
## Aula 05 
## Diciplina: Manutenção e Montagem de Computadores
## Ana Paula Oliveira Lago

## Tipos de Partição

Partição primária é a partição do disco rígido onde o sistema operacional Windows e outros dados podem ser armazenados, e é a única partição que pode ser definida como ativa. Ela pode ser definida como ativa para que o BIOS possa localizá-la, e os arquivos de inicialização salvos na partição primária devem ser definidos como ativos. Caso contrário, o Windows não poderá ser inicializado. Além disso, apenas uma partição primária em um disco rígido pode ser definida como ativa por vez. Um disco MBR só pode conter, no máximo, 4 partições primárias ou 3 partições primárias e 1 partição estendida.

Uma partição lógica é um volume criado dentro de uma partição estendida em um disco básico baseado em MBR (registro de inicialização de master).
Partições lógicas são semelhantes a partições primárias. No entanto, embora apenas quatro partições primárias possam existir em um único disco, o número de partições lógicas que podem existir em um disco é ilimitado. Uma partição lógica pode ser formatada e atribuída uma letra de unidade.
Uma partição lógica deve ser criada dentro de uma partição estendida. Se uma partição estendida ainda não existir no disco ou o tamanho especificado da unidade lógica exceder a partição estendida, nenhuma partição será criada.

Uma partição swap (pelo menos 256 MB) — partições swap são usadas para suportar a memória virtual. Em outras palavras, os dados são gravados numa partição swap quando não há memória RAM suficiente para armazenar os dados que seu sistema está porocessando.








## Referências

https://www.minitool.com/pt/particao-disco/particao-primaria-x-unidade-logica.html

WINDOWS-DRIVER-CONTENT. Tipo. Microsoft.com. Disponível em: <https://learn.microsoft.com/pt-br/windows-hardware/customize/desktop/unattend/microsoft-windows-setup-diskconfiguration-disk-createpartitions-createpartition-type>. Acesso em: 27 out. 2023.


PRODUCT SIGNING (GPG) KEYS. 9.15.5. Esquema de particionamento recomendado. Disponível em: <https://access.redhat.com/documentation/pt-br/red_hat_enterprise_linux/6/html/installation_guide/s2-diskpartrecommend-x86>. Acesso em: 23 nov. 2023.