# WPFThreads
## Utilizzo dei lock
Il lock è utilizzato quando nel codice più thread devono utilizzare la stessa risorsa, ma utilizzandola contemporaneamente comporterebbe errori nell'utilizzo di tale risorsa.
Il codice è il seguente:
```
Object obj = new();
lock(obj)
{
  count++;
}
```

Quindi il lock blocca il pezzo di codice contenente al suo interno al primo thread che arriva per poi quando finisce lasciarlo a quelli successivi

## Lambda expression
La lamba expression è utilizzata per contenere delle parti di codice da inserire poi ad esempio in dei metodi di alcune classi

La Lambda viene scritta in qusto modo.

```
()=>
{
  //Qui è dove bisogna inserire il codice
}
```
