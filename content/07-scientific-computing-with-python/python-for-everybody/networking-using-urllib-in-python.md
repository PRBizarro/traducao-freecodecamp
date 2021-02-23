---
id: 5e7b9f0d0b6c005b0e76f075
title: 'Rede: Utilizando urllib no Python'
challengeType: 11
videoId: 7lFM1T_CxBs
dashedName: networking-using-urllib-in-python
---

# --question--

## --text--

Qual será a saída impressa pelo código a seguir?:

```python
import urllib.request
fhand = urllib.request.urlopen('http://data.pr4e.org/romeo.txt')
for line in fhand:
    print(line.decode().strip())
```

## --answers--

Apenas o conteúdo de "romeo.txt".

---

Um cabeçalho e o conteúdo de "romeo.txt".

---

Um cabeçalho, rodapé, e o conteúdo de "romeo.txt".

## --video-solution--

1

