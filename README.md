![Logo](logo.png)

# Hi, I'm William Sleman

Electrical engineer working with embedded systems. I design ECUs and sensor boards for agricultural machinery and write the bare-metal firmware that runs on them. My boards end up in machines working in the field, where a firmware bug isn't a popup on a screen: it's a machine stopped in the middle of a harvest.

I like to understand things from the ground up. Most of my personal projects start with a Makefile, a linker script and an empty `.c` file. Read the datasheet, understand the peripheral, write the driver. No magic, no black boxes.

## What I work with

- **MCUs:** STM32 (F4), Renesas RA4M1, NXP S32K144, nRF52840
- **Firmware:** bare-metal C, ARM Assembly, bootloaders, DMA, UART, SPI, I2C
- **Hardware:** Altium Designer, KiCad, SPICE simulation
- **Tools:** GCC ARM, IAR, Make/CMake, J-Link/GDB, Renode, Git
- **Digging into right now:** C++ and automated testing

## Things I've built

- **[Blinky to Bootloader](https://github.com/slemanz/blinky-to-bootloader)**: started as a blinking LED, ended up as a full STM32F411 application with a 5-layer architecture and a UART bootloader written from scratch.
- **[Nina Project](https://github.com/slemanz/nina-project)**: hardware and firmware for a data acquisition device built around the nRF52840. Full cycle, from schematic to working board.
- **[RA4M1 Sandbox](https://github.com/slemanz/RA4M1-sandbox)**: bare-metal environment for the Renesas RA4M1. No Arduino framework, no CMSIS, just the reference manual.
- **[Advanced Embedded C](https://github.com/slemanz/advanced-embedded-c)**: design patterns, state machines, build systems and TDD, all applied to embedded C.

The test I apply to everything here is simple: if I can implement it, I understand it. If I can't, it's back to the reference manual.

## Elsewhere

<!-- - I write about embedded systems (and the occasional career post) at [slemanz.com](https://www.slemanz.com) -->
- My resume lives in [its own repo](https://github.com/slemanz/my-resume), written in LaTeX: [English](https://github.com/slemanz/my-resume/blob/main/build/resume_en.pdf) · [Português](https://github.com/slemanz/my-resume/blob/main/build/resume_pt.pdf)
- Say hi on [LinkedIn](https://www.linkedin.com/in/slemanz)

---

<p align="center">
  <img src="https://github-readme-streak-stats-xi-woad.vercel.app?user=slemanz&theme=dark" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sooty-two.vercel.app/api/top-langs/?username=slemanz&theme=dark&show_icons=true&hide_border=true&layout=compact&hide=jupyter%20notebook,html,css" />
</p>
