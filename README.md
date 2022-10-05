# Plasma-OS
## _Made by Plasma_

[Plasma Discord Server](https://discord.gg/92RFjFyFHH)

# What's PlasmaOS?
_PlasmaOS is a minimal and collaborative kernel written in Assembly (nasm)._

# Why PlasmaOS?
_When I was a kid i always dreamed to create an operating system, finally, this dream became true, it's not easy to create this type of thing but I did it! If you want to support my work download it and give it a try! I'm sure that it's not like Windows or Linux but im proud of it!_

# CHANGELOG
- Still nothing here

# GOALS
- Still nothing here

# BOOTING
- [x] QEmu needed
- [x] nasm needed
## Linux
- nasm kernel.asm -f bin -o kernel.bin
- qemu-system-x86_64 -drive format=raw,file=kernel.bin,index=0,if=floppy -m 128M
## Windows
- nasm kernel.asm -f bin -o kernel.bin
- qemu-system-x86_64.exe -drive format=raw,file=kernel.bin,index=0,if=floppy -m 128M

# CREDITS
_Thanks to our developers for working on the system!
gabmeow: Senior Developer and founder of Plasma Company
Cora: Developer working on the system
FedEx: Developer working on the system
Want to help us? [Join the Plasma Discord Server](https://discord.gg/92RFjFyFHH)_
