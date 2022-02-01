# IPAdress
Finds the IPv4 and IPv6 addresses for a given host. Written in C

Compilation is pretty easy. Just go to the directory where main.c is in a commandline and type: 
```
gcc -o IPAdress main.c
```
You can use compilers other than gcc. You can also name it something other than IPAdress by changing the "IPAdress" part of the command above.
This would also affect the example usage below.

example usage:
```
IPAdress www.google.com
```

# Türkçe
Verilen sunucu isminin IPv4 ve IPv6 adreslerini bulan basit bir komut istemcisi programı. C dili ile yazılmıştır.

Derlemesi gayet basit. komut istemcisinde buradan çektiğiniz main.c dosyasının olduğu konuma gidin ve şu komutu girin:
```
gcc -o IPAdress main.c
```
gcc yüklü olması lazım. gcc dışında derleyiciler de kullanabilirsiniz. programı IPAdress dışında kendi istediğiniz bir isimle çalıştırmak için
yukarıdaki kodda "IPAdress" yazan kısmı istediğiniz isme değiştirebilirsiniz. Bu durumda aşağıdaki örnek kullanımda da "IPAdress" yerine kullandığınız
ismi girmeniz lazım.

Örnek kullanım:
```
IPAdress www.google.com
```
