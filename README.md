# Otimizador de Bases (B&D Sistemas)


Programa criado em Delphi(Pascal 2010) para solucionar o problema de lentidão
    comumente causada pelo excesso de informações na coluna XML da tabela tbl_nfcevendas.
# Passo a Passo
  - Programa Verifica a data que foi feita a otimização pela ultima vez
  - Se a diferença da data da ultima otimização e da data atual for maior do que 1 mes.
  - O programa irá Fazer todo o processo, caso não. O programa é encerrado e só ativara na proxima inicialização
  - Após a verificação o programa cria um backup(.SQL), compacta-o(.ZIP) e depois deleta o .SQL
  - Backup feito o programa ira buscar na tabela tbl_nfcevendas notas de quando a diferença da data da emissão e data atual for maior do que 3 meses e inserir valor ' ' na coluna XML das notas retornadas
  - Após isso o programa Irá rodar o comando OPTMIZE TABLE em todas as tabelas 
  - Fim do programa 




### Importante

```
Para correto funcionamento do programa deve- se colocar o mesmo na pasta do programa B&D
e colocar um atalho na inicialização do windows(shell:startup)
```


License
----

MIT



