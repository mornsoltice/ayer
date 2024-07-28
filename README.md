# ayer
yet a simple os made with C and x86_64. btw the name is inspired from ayer from gbf

# building ayer

install this dependencies

```sh
yay -S gcc make bison flex libgmp-dev libmpc-dev libmpfr-dev texinfo nasm mtools qemu-system-x86 python3 scons
```

clone the repository
```sh
https://github.com/mornsoltice/ayer
cd ayer
```

run `python3 -m pip install -r requirements.txt`

and then just modify things on the toolchain and run with `scons run` to test ayer with qemu.

**NOTE**: ayer is currently on development mode lol.

