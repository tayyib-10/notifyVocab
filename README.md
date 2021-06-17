# notifyVocab

- _pip/pip3 install notifyVocab_

a small library that notifies you of a new word and its meaning every time you run it 

__you can also use task schedular(for windows) to notify you with a new word (inorder to increase you vocabulary while you are working on desktop)__

Developed by Mohammad.Tayyib (c) 2021

## Examples of How To Use

importing it and calling the function (its that simple!!)

```python
import notifyVocab

notifyVocab()

```

__you can also pass the *timeout*(int) as an arguement so that notification may live for more time__

```python
import notifyVocab

timeout = 15 #default 10s
notifyVocab(timeout)

```