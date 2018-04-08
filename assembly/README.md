# Tutorial Assembly

Hello World in Assembly in different platforms.

## Ubuntu LTS 16.04
	* nasm -f elf64 tutorial.asm
	* ld -s -o tutorial tutorial.o
	* ./tutorial (It should print on the screen)
