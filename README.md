# mesa-19.0.1_sorce_griggorii_mit_patent_llvm-7
mesa , sorce , griggorii , mit , patent , llvm-7

$ sudo rm -rf /usr/include/x86_64-linux-gnu/bits/mman-linux.h && sudo cp mman-linux.h /usr/include/x86_64-linux-gnu/bits

$ sudo cp r300_pci_ids.h /usr/include

$ sudo apt update

$ sudo apt install llvm-7 -y

$ sudo tar xvpfj llvm-7.tar.bz2

$ sudo tar xvpfj llvm-5.tar.bz2

$ sudo ln -s /usr/include/locale.h /usr/include/xlocale.h

----------------------------------------------------------------------------

run folder tizonia run in folder terminal tizonia

$ sudo dpkg -i *.deb && sudo apt update -y && sudo apt install -f -y 

----------------------------------------------------------------------------

$ sudo apt install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev valgrind valgrind-dbg -y

$ sudo rm /usr/include/libdrm/intel_aub.h

$ sudo cp intel_aub.h /usr/include/libdrm

$ make -j16

Дальше смотрим если будет останавливаться компиляция то ищем эти зависимости и докачиваем после компиляция должна продолжится

$ sudo make install

Check info mesa

$ glxinfo

Готовый пакет mesa скачать тут https://www83.zippyshare.com/v/F6u7getL/file.html 

Готовый пакет заменяет mesa , libegl1-mesa-dev , mesa-common-dev , libgles2-mesa-dev , libosmesa6-dev , libgl1-mesa-dri:amd64 , libgl1-mesa-dri:i386 , libgbm-dev

И состоит в группах video , games , users , kvm , voice , colord , pulse , pulse-access , bluetooth , rdma , irc

Но лучше сами устанавливайте через make что бы избежать при обновлении ошибок потому что я не директор каноникал и они там могут не понимать что структура у пользователя изменена , но когда установленно через make install то в будущем при обновлении ни каких проблем не будет.

Вы можете перевести эту mesa на другой компилятор более новый или старый открыв сначала config.status найдите там строчку /usr/lib/llvm-7/include и измените её на свой компилятор после откройте makefile и проделайте то же самое.

Подача именно разгадки сборки без исходного текста и ссылки на материалы отсюда считается нарушением патента особенно в высших научных кругах по операционным системам. 

Tennology Griggorii@gmail.com
