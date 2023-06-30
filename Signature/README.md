# Signature

## About the Challenge
Diberikan sebuah file dengan nama chall, kita diminta untuk membuka file tersebut.

![preview](images/problem.png)

## Solution
- Saya mencoba mencari kata kunci yaitu "ctf signature file" dan saya menemukan sebuah situs yang membahas tentang itu.
- Lalu saya melihat bahwa signature file image jpeg dan juga diberikan header hex penanda dia adalah jpeg.
![preview](images/ctfSignature.png) 
- Selanjutnya saya membuka hex editor online [url : https://hexed.it/] dan mengubah header hex dari file chall dan di export.
![preview](images/editHex.png) 
- File image dapat dibuka dan flag ditemukan.
![preview](images/result.jpeg) 


```
ForestyCTF{ezzzz123!!!}
```
