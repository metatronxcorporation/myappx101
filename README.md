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

~]$ yum search x11

* Obs: Install others libs. If Case

* Now verify that if it is installed properly

~]$ xdpyinfo | grep version

~]$ make --version

~]$ cmake --version

~]$ pwd

/home/admin/metatronlabs

~]$ mkdir myappx101

~]$ vim myappx101.cpp

* copy code to myappx101.cpp

* https://github.com/metatronxcorporation/myappx101/blob/main/src/x101.cpp

* Type key escape (esc) to exit

* save text in vim with :x

:x

~]$ g++ -lX11 myappx101.cpp -o myappx101.cpp

~]$ ./myappx101.cpp

![Screenshot from 2023-03-08 01-16-35](https://user-images.githubusercontent.com/98597119/223482543-8fb7ebbb-dee3-41e6-ba43-09e112e3911b.png)

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

Guide > Tools Settings > GCC C++ Compiler 

Guide > Tools Settings > GCC C Compiler

Guide > Tools Settings > GCC C++ Linker

Guide > Tools Settings > GCC Assembler

Obs: ADD Command

Expert Settings:

${COMMAND} ${FLAGS} ${OUTPUT_FLAG} ${OUTPUT_PREFIX}${OUTPUT} ${INPUTS} ${EXTRA_FLAGS} -lX11

![Screenshot from 2023-03-08 01-34-45](https://user-images.githubusercontent.com/98597119/223487696-6909ef27-191a-4cc4-8c96-dca7aa1b9b2a.png)

* Menu: Project > Properties > C/C++ General > Paths and Symbols -> Configuration: [All Configuration]

Guide > includes > Languages: Assembly | Include directories: /usr/include/X11

Guide > includes > Languages: GNU C | Include directories: /usr/include/X11

Guide > includes > Languages: GNU C++ | Include directories: /usr/include/X11

![Screenshot from 2023-03-08 02-12-39](https://user-images.githubusercontent.com/98597119/223498872-30abc13e-6029-4db0-a8ee-04d9f04299ed.png)

* Obs: Compile and Run

![Screenshot from 2023-03-08 01-31-58](https://user-images.githubusercontent.com/98597119/223486857-3a6b6b3f-bf93-4fdf-bd1f-e4e5c5ab9d8e.png)

********************************************************************************************************************

## Students Reference Books

### Linux From Scratch
Version 11.3
Published March 1st, 2023

https://linuxfromscratch.org/lfs/view/stable/

********************************************************************************************************************

![1119578884](https://user-images.githubusercontent.com/98597119/223299621-9d354108-b24f-44ab-b825-61968cbc3914.jpg)

![1119700914](https://user-images.githubusercontent.com/98597119/223300267-cc89ab2f-5793-4418-b6d5-b4aa9efc57d2.jpg)

![1593272200 01 _SCLZZZZZZZ_SX500_](https://user-images.githubusercontent.com/98597119/223301127-314b4800-74e9-4bbf-aa91-b201d9775447.jpg)

********************************************************************************************************************

![s-l640-18714065](https://user-images.githubusercontent.com/98597119/223293794-e2be6ac4-62fb-4fc2-9183-c74c53411844.jpg)

![ShowCover-462818533](https://user-images.githubusercontent.com/98597119/223291700-8893f767-ce9c-4639-9cea-16accc15770e.jpg)

![main-qimg-fc0aa975deb9c5f75f1d0953bde55d41-3514297900](https://user-images.githubusercontent.com/98597119/223292105-7bb7dbb6-92d2-47cc-95c0-f157699409b8.jpg)

![5f6bea6a-eef6-473c-a563-1ff2b484331c_1 6968d9baf17245a77f381ed53c37e4eb](https://user-images.githubusercontent.com/98597119/223292548-575b321a-7031-4d0d-a6ef-3b4e4b646a44.jpeg)

![cover50](https://user-images.githubusercontent.com/98597119/223293095-554fb04d-9f3e-44af-b298-c3ac93812c43.jpg)

![41vUdzcR8cL _SX260_](https://user-images.githubusercontent.com/98597119/223288707-6f603658-79ec-4c16-a332-e2d1f0040fc7.jpg)

![5108SrrM+qL](https://user-images.githubusercontent.com/98597119/223290799-4d6ddec8-0969-42ed-afc7-35efe86e017d.jpg)

![5120pfeU95L _SX401_BO1,204,203,200_](https://user-images.githubusercontent.com/98597119/223268759-520caee2-4831-48b5-abda-deac58b11372.jpg)

![805567-L-2264703534](https://user-images.githubusercontent.com/98597119/223270854-54945532-dee9-42f5-a0a2-1cb7d7aa7c24.jpg)
