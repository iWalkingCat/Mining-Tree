# Mining-Tree
A small tree eventually grows into a large tree, its branches growing thick foliage...

## Настройка хранилища кошельков

Для хранения кошельков нужно создать каталог <code>wallets</code> в домашнем каталоге вашего локального компьютера <code>~/</code>, далее создать внутри каталога <code>wallets</code> документ с именем монеты, например <code>alph</code> или <code>zeph</code> и поместить в этот документ адрес кошелька:
```
cd ~/
mkdir wallets
echo "randomwalletaddress29858239072352" > ~/wallets/alph
```
**Внимание! Название монеты нужно брать из таблицы поддерживаемых монет!**
Поддерживается               | В разработке  | В планах     
-----------------------------|---------------|------------
gram                         | SpectreX      | 
Spectre                      | Future        |          
zeph                         | Future        |         
