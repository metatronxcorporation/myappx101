# myappx101 on template project into Eclipse IDE

![th-3336817074](https://user-images.githubusercontent.com/98597119/223263693-42ea8807-24c2-4800-90ed-af216324ab79.jpg)

![440px-X-client-libraries](https://user-images.githubusercontent.com/98597119/223265466-8ba47392-ff99-4a74-a6c2-3f01703967cb.png)

### Getting started with Xlib - C Language X Interface on Centos Linux

The X Window System is a network-transparent window system that was designed at MIT. X display servers run on computers with either monochrome or color bitmap display hardware. The server distributes user input to and accepts output requests from various client programs located either on the same machine or elsewhere in the network. Xlib is a C subroutine library that application programs (clients) use to interface with the window system by means of a stream connection. Although a client usually runs on the same machine as the X server it is talking to, this need not be the case.

Xlib --- C Language X Interface is a reference guide to the low-level C language interface to the X Window System protocol. It is neither a tutorial nor a user's guide to programming the X Window System. Rather, it provides a detailed description of each function in the library as well as a discussion of the related background information. Xlib --- C Language X Interface assumes a basic understanding of a graphics window system and of the C programming language. Other higher-level abstractions (for example, those provided by the toolkits for X) are built on top of the Xlib library. For further information about these higher-level libraries, see the appropriate toolkit documentation. 

### Requirements

* C++ Compile

### Centos:

~]$ sudo yum -y install vim gcc g++ gdb make cmake

~]$ xdpyinfo | grep version

~]$ yum search x11

* Obs: Install others libs. If Case

* Now verify that if it is installed properly

~]$ make --version

~]$ cmake --version

~]$ vim myappx101.cpp

* copy code to myappx101.cpp

* https://github.com/metatronxcorporation/myappx101/blob/main/src/x101.cpp

* Type key escape (esc) to exit

* save text in vim with :x

:x

~]$ g++ -lX11 myappx101.cpp -o myappx101.cpp

~]$ ./myappx101.cpp

# Install eclipseIDE 2022-12 on CentOS

* Enable snaps on CentOS and install Eclipse

* https://snapcraft.io/install/eclipse/centos

## EclipseIDE 2022-12

~]$ su - 

~]# yum install snapd

~]# systemctl enable --now snapd.socket

~]# ln -s /var/lib/snapd/snap /snap

~]# snap install eclipse --classic

~]# exit

## Install Pkg-config support for Eclipse CDT 1.0.0

* Menu: Help > Eclipse Marketplace -> Search -> Find - pkg-config - Click Button, GO

## Configure Project myappx101 -lX11 in Eclipse C/C++ IDE CDT

* Menu: Project > Properties > C/C++ Build > Settings -> Configuration: [All Configuration]

* Guide > Tools Settings > GCC C++ Compiler 

* Guide > Tools Settings > GCC C Compiler

* Guide > Tools Settings > GCC C++ Linker

* Guide > Tools Settings > GCC Assembler

ADD Command:

Expert Settings:

![Screenshot from 2023-03-06 18-04-52](https://user-images.githubusercontent.com/98597119/223276745-c91b0dbb-100a-4a21-8156-a5c7c25d9cd3.png)

*Obs: ${COMMAND} ${FLAGS} ${OUTPUT_FLAG} ${OUTPUT_PREFIX}${OUTPUT} ${INPUTS} ${EXTRA_FLAGS} -lX11

![Screenshot from 2023-03-06 18-00-20](https://user-images.githubusercontent.com/98597119/223276430-aec5bd45-f1a9-45bc-8f43-f3d4ba077d4b.png)

## Students Reference Books

![5120pfeU95L _SX401_BO1,204,203,200_](https://user-images.githubusercontent.com/98597119/223268759-520caee2-4831-48b5-abda-deac58b11372.jpg)

![805567-L-2264703534](https://user-images.githubusercontent.com/98597119/223270854-54945532-dee9-42f5-a0a2-1cb7d7aa7c24.jpg)
