# mesa-19.0.1_source_griggorii_mit_patent_llvm-7 , tty repair
mesa , source , griggorii , mit , patent , llvm-7 , tty repair

$ sudo rm -rf /usr/include/x86_64-linux-gnu/bits/mman-linux.h && sudo cp mman-linux.h /usr/include/x86_64-linux-gnu/bits

$ sudo cp r300_pci_ids.h /usr/include

$ sudo apt update

$ sudo apt install llvm-7 -y

$ sudo tar xvpfj llvm-7.tar.bz2 -C /

$ sudo tar xvpfj llvm-5.tar.bz2 -C /

$ sudo ln -s /usr/include/locale.h /usr/include/xlocale.h

----------------------------------------------------------------------------
Example python3.8 not python3.8? 

$ sudo ln -s /usr/bin/python3.8 /usr/bin/python

python2.7?

$ sudo ln -s /usr/bin/python2.7 /usr/bin/python

----------------------------------------------------------------------------

run folder tizonia run in folder terminal tizonia

$ sudo apt update && sudo dpkg -i *.deb

$ sudo apt install -f -y 

----------------------------------------------------------------------------

sudo apt  update && sudo apt --reinstall install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt install libd3dadapter9-mesa-dev llvm clang make -y && sudo apt --reinstall install libgcrypt20-dev libxcb-present-dev python-mako libxshmfence-dev libxext-dev libxdamage-dev libx11-xcb-dev libexpat1-dev libxxf86vm-dev libva-dev libclc-dev libdrm-dev libegl-dev libgbm-dev libgl-dev libgl1-mesa-dev libgles-dev libglvnd-dev libglx-dev libopengl-dev libpthread-stubs0-dev libvdpau-dev libvkd3d-dev libvkd3d-utils1 libvulkan-dev libx11-dev libxau-dev libxdmcp-dev mesa-opencl-icd nvidia-cg-dev -y && sudo apt --reinstall install liblzma-dev libxine2-bin libxcb-shm0-dev libxcb-xv0-dev libxcb-xvmc0-dev meson ninja-build -y && sudo apt --reinstall install libxrandr-dev libzstd-dev libmirwayland-dev wayland-protocols libsensors4-dev xserver-xorg-video-intel -y && sudo apt purge xserver-xorg-video-intel -y && sudo apt --reinstall install libgccjit0 -y && sudo apt --reinstall install libgccjit-9-dev -y && sudo apt --reinstall install libmesa-dev -y

----------------------------------------------------------------------------

$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/9/include-fixed/bits

$ sudo rm /usr/include/libdrm/intel_aub.h

$ sudo cp intel_aub.h /usr/include/libdrm

Download my include SPIRV https://github.com/Griggorii/vulkan_19.04-1_amd64.deb install vulkan_19.04-1_amd64.deb

AMD VULKAN SUPPORT clang-3.9 clang-3.8 install

Download install clang-3.8 , llvm-3.8 https://yadi.sk/d/2VipwyfXWQsE0w

Download install clang-3.9 , llvm-3.9 https://yadi.sk/d/rJpPhb6QveP6HA

$ make -j16

$ sudo make install

Test https://www.shadertoy.com/view/3lsSzf replace my fix if #if HW_PERFORMANCE==0

Check info mesa

$ glxinfo

Готовый пакет mesa скачать тут https://www83.zippyshare.com/v/F6u7getL/file.html 

Готовый пакет заменяет mesa , libegl1-mesa-dev , mesa-common-dev , libgles2-mesa-dev , libosmesa6-dev , libgl1-mesa-dri:amd64 , libgl1-mesa-dri:i386 , libgbm-dev

И состоит в группах video , games , users , kvm , voice , colord , pulse , pulse-access , bluetooth , rdma , irc

Но лучше сами устанавливайте через make что бы избежать при обновлении ошибок потому что я не директор каноникал и они там могут не понимать что структура у пользователя изменена , но когда установленно через make install то в будущем при обновлении ни каких проблем не будет.

Вы можете перевести эту mesa на другой компилятор более новый или старый открыв сначала config.status найдите там строчку /usr/lib/llvm-7/include и измените её на свой компилятор после откройте makefile и проделайте то же самое.

Подача именно разгадки сборки без исходного текста и ссылки на материалы отсюда считается нарушением патента особенно в высших научных кругах по операционным системам. 

-------------------------------------------------------------------------------------------------------------------------
                                                                   Конфигурация под новые llvm


                                                           riggorii@gmail.com new command

Mesa gallium x11 vulkan drm

$$ ./configure --prefix=/usr --includedir=/usr/include --mandir=/usr/share/man --infodir=/usr/share/info --sysconfdir=/etc --localstatedir=/var --exec-prefix=/usr/lib/x86_64-linux-gnu --enable-glx-tls --enable-xvmc --enable-omx-bellagio --enable-driglx-direct --with-platforms=x11,wayland,drm,surfaceless --enable-xa --enable-texture-float --enable-osmesa --enable-gles1 --enable-gles2 --enable-opencl-icd --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-dri-searchpath=/usr/lib/x86_64-linux-gnu/dri:\\\$\${ORIGIN}/dri:/usr/lib/dri --enable-autotools --with-gallium-drivers=r600 --enable-vdpau --enable-va --enable-gles1 --enable-gles2 -enable-gles --with-gallium-drivers=r300,r600,radeonsi,nouveau,virgl,svga,swrast --with-vulkan-drivers=intel

Easy configuration linux OS8.0

$$ ./configure --prefix=/usr --exec_prefix=/usr --libdir=/usr/lib/x86_64-linux-gnu --includedir=/usr/include --enable-glx-tls --enable-driglx-direct --enable-xa --enable-texture-float --enable-osmesa --enable-gles1 --enable-gles2 --enable-opencl-icd --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-gallium-drivers=r300,r600,radeonsi,svga,swrast --enable-autotools --with-gallium-drivers=r600 --disable-gallium-llvm --with-vulkan-drivers=intel

$$ make -i -j16

$$ sudo make -i install

xvmc problem generate --disable-xvmc and ignore example ( make -i -j16 ) (sudo make -i install )

----------------------------------------------------------------------------------------------------------------------------


Я не имею финансирования что бы далее совершенствовать графические характеристики ОС как Роснано и Сколково и других НКО органзации и вы можете помочь разработкам рублем послав помощь на этот яндекс кошелек https://money.yandex.ru/to/410014999913799 в теме указать на разработку или за разработку.

Tennology Griggorii@gmail.com
