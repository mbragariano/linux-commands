# Processos

## Listagem (ps)

### Todos os processos do terminal

```
$ ps
```

### Todos os processos além do terminal

```
ps -e
```

- Pode-se utilizar como alternativa a flag **A** no lugar do **e**.
- Para listar os processos com informações adicionais, utilizar a flag **f**.

### Processos + Filtragem

```
$ ps -ef | grep **{filtro}**
```

## Matar (kill)

```
$ kill **{PID}**
```

- O comando **kill** na verdade envia um sinal para o processo referente ao PID, por padrão é 15. Para consultar os sinais execute **kill -l**.
- Deve-se inserir o número do processos que deseja encerrar. Dessa forma o processo é encerrado de forma "amigável", para encerrar de maneira forçada utilizear a flag **-9**.

### Matar todos os processos de uma instância

```
$ killall **{nome_processo}**
```

- Assim como no **kill** pode-se utilizar a flag **9**.

## Listar processos e consumo

```
$ top
```

















