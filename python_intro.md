# Introducció a Python 

## Què és Python?

Python és un llenguatge de programació interpretat d'alt nivell i de propòsit general. 
Python es caracteritza per ser de tipatge dinàmic i suportar diversos paradigmes de programació com programació orientada a objectes, imperativa o funcional.

### Què vol dir tot això?

#### Interpretat vs compilat

En lleguatges compilats, per fer un programa, primer s'escriu el codi en un editor de text i després, amb un altre programa (el compilador), s'interpreta el text pla i es transforma a llenguatge de màquina (o codi binari). Aquest conté totes les instruccions traduïdes al llenguatge natural pel processador (el llenguatge amb el qual ha estat ideat per funcionar). Els llenguatges compilats encara són útils i cobreixen un gran nombre de necessitats com per exemple computació d'alt rendiment.

En canvi, en els llenguatges interpretats, les instruccions són interpretades de manera directa i lliure sense ser prèviament compilades a llenguatge de màquina. L'intèrpret executa el programa traduint cada declaració a seqüències de subrutines (programes petits) que ja han estat compilats a llenguatge de màquina.

```python
a = 2           #---------> Interpreter --------> memory locatio 0x001 = assign.exe (2)
b = 7           #---------> Interpreter --------> memory locatio 0x002 = assign.exe (7)
result = a * b  #---------> Interpreter --------> result in 0x003 = multiply.exe (0x001, 0x002)
```

L'exemple anterior es purament orientatiu i no reflexe el funcionament de l'interpret de Python"

Com a conseqüència, podem visualitzar la sortida del programa sobre la marxa, com aquí:
