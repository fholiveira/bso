Bash script organizer
===

Utilitário que permite organizar seus scripts bash em múltiplos arquivos.

## Como funciona

Com o bso você pode dividir scripts grandes em pequenos scripts usando um esquema de importação.
Defina no início de cada arquivo os scripts que ele deve importar e o sbo faz o trabalho de montar o script final.

## Instalação

Baixe o script [bso](bso) e o coloque em ~/bin.

## Exemplos

**Usando os arquivos da pasta exemplos**

* Rodar os scripts
  
  bso run b

* Obter um relatório de erros na execução de um script
  
  bso run b --error-report

* Gerar script final para distribuição

  bso build b -o final_script
  
## Corrigindo erros

  Se houver algum erro na execução do script, o bso irá indicar a linha e o arquivo em que o erro ocorre
