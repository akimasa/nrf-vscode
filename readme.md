# USAGE 
    mv gdb-openocd/gdb_wrapper.json ${workspaceroot}/
    mv .vscode ${workspaceroot}/.vscode

- `go build` to build gdb-openocd/
- put built binary in C:\\Users\\akima\\Documents\\gdb-openocd\\gdb-openocd.exe or change launch.json
## other file needed
- make.exe at ${HOME}/Downloads/gnu-mcu-eclipse-build-tools-2.11-20180428-1604-win32/GNU MCU Eclipse/Build Tools/2.11-20180428-1604/bin/make.exe
- arm-none-eabi-gcc at C:/Program Files (x86)/GNU Tools ARM Embedded/4.9 2015q3/bin/arm-none-eabi-gcc
- putty is installed.
- openocd with [patch](http://openocd.zylin.com/#/c/4055/8) has setup in rpizero.
# Open Issue if you don't know how to use
Feel free to ask me any questions. Maybe I can help you.