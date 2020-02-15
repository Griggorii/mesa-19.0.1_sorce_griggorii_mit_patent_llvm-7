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

$ sudo apt install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt libmesa-dev -y && sudo apt install libd3dadapter9-mesa-dev -y

$ sudo rm /usr/include/libdrm/intel_aub.h

$ sudo cp intel_aub.h /usr/include/libdrm

Download my include SPIRV https://github.com/Griggorii/vulkan_19.04-1_amd64.deb install vulkan_19.04-1_amd64.deb

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

Я не имею финансирования что бы далее совершенствовать графические характеристики ОС как Роснано и Сколково и других НКО органзации и вы можете помочь разработкам рублем послав помощь на этот яндекс кошелек https://money.yandex.ru/to/410014999913799 в теме указать на разработку или за разработку.

Tennology Griggorii@gmail.com
