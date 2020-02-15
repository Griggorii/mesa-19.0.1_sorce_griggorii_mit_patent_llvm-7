# mesa-19.0.1_sorce_griggorii_mit_patent_llvm-7
mesa , sorce , griggorii , mit , patent , llvm-7

sudo rm -rf /usr/include/x86_64-linux-gnu/bits/mman-linux.h && sudo cp -r mman-linux.h /usr/include/x86_64-linux-gnu/bits

sudo cp r300_pci_ids.h /usr/include

sudo apt update

sudo apt install llvm-7 -y

sudo tar xvpfj llvm-7.tar.bz2

sudo tar xvpfj llvm-5.tar.bz2

----------------------------------------------------------------------------

run folder tizonia run in folder terminal tizonia

sudo dpkg -i *.deb && sudo apt update -y && sudo apt install -f -y

----------------------------------------------------------------------------

make -j16

sudo make install

Дальше смотрим если будет останавливаться компиляция то ищем эти зависимости и докачиваем после компиляция должна продолжится

Готовый пакет mesa скачать тут https://www83.zippyshare.com/v/F6u7getL/file.html 

Вы можете перевести эту mesa на другой компилятор более новый или старый открыв сначала config.status найдите там строчку /usr/lib/llvm-7/include и измените её на свой компилятор после откройте makefile и проделайте то же самое.

Tennology Griggorii@gmail.com
