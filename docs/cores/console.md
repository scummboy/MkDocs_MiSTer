---
hide:
  - toc
---

Here is a list of the console cores that are in the MiSTer Github Repository.

| Core Name                                                                     | Systems                                                                                                 | /games/ Folder          | BIOS                                                                                                                                          | SDRAM    |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [AY-3-8500](https://github.com/MiSTer-devel/AY-3-8500-MiSTer)                 | "Pong-on-a-chip"                                                                                        | ./AY-3-8500             |                                                                                                                                               |          |
| [Arcadia](https://github.com/MiSTer-devel/Arcadia_MiSTer)                     | Emerson Arcadia 2001                                                                                    | ./Arcadia               |                                                                                                                                               |          |
| [Astrocade](https://github.com/MiSTer-devel/Astrocade_MiSTer)                 | Bally Astrocade                                                                                         | ./Astrocade             | boot.rom = Astrocade BIOS                                                                                                                     |          |
| [Atari2600](https://github.com/MiSTer-devel/Atari2600_MiSTer)                 | Atari 2600<br>Atari VCS                                                                                 | ./Atari2600             |                                                                                                                                               |          |
| [Atari5200](https://github.com/MiSTer-devel/Atari800_MiSTer)                  | Atari 5200 SuperSystem                                                                                  | ./Atari5200             |                                                                                                                                               |          |
| [Atari7800](https://github.com/MiSTer-devel/Atari7800_MiSTer)                 | Atari 7800 ProSystem<br>Atari 2600 Support                                                              | ./Atari7800             | boot0.rom = BIOS (optional)                                                                                                                   | ✔️       |
| [AtariLynx](https://github.com/MiSTer-devel/AtariLynx_MiSTer)                 | Atari Lynx                                                                                              | ./AtariLynx             | boot.rom = bootrom (lynxboot.img)                                                                                                             |          |
| [ChannelF](https://github.com/MiSTer-devel/ChannelF_MiSTer)                   | Fairchild Channel F                                                                                     | ./ChannelF              |                                                                                                                                               |          |
| [ColecoVision](https://github.com/MiSTer-devel/ColecoVision_MiSTer)           | ColecoVision<br>Sega SG-1000                                                                            | ./Coleco<br>./SG1000    |                                                                                                                                               | ✔️       |
| [GBA](https://github.com/MiSTer-devel/GBA_MiSTer)                             | Nintendo Game Boy Advance                                                                               | ./GBA                   | boot.rom = BIOS (recommended)                                                                                                                 | Optional |
| [GBA2P](https://github.com/MiSTer-devel/GBA_MiSTer/tree/GBA2P)                | 2x Game Boy Advance (2-Player)                                                                          | ./GBA2P                 | boot.rom = BIOS (recommended)                                                                                                                 | ✔️       |
| [GameBoy](https://github.com/MiSTer-devel/Gameboy_MiSTer)                     | Nintendo Game Boy                                                                                       | ./Gameboy               | boot1.rom = Gameboy Color BIOS<br>boot2.rom = autoload a game                                                                                 | ✔️       |
| [Gameboy2P](https://github.com/MiSTer-devel/Gameboy_MiSTer/tree/Gameboy2P)    | 2x Game Boy (2-Player)                                                                                  | ./Gameboy2P             | boot1.rom = Gameboy Color BIOS<br>boot2.rom = autoload a game                                                                                 | ✔️       |
| [Genesis](https://github.com/MiSTer-devel/Genesis_MiSTer)                     | Sega Genesis<br>Sega Mega Drive                                                                         | ./Genesis               |                                                                                                                                               | Optional |
| [Intv](https://github.com/MiSTer-devel/Intv_MiSTer)                           | Mattel Intellivision                                                                                    | ./Intellivision                  | boot0.rom = exec.bin<br>boot1.rom = grom.bin<br>boot2.rom = sp0256-012.bin<br>boot3.rom = ecs.bin                                    |          |
| [MegaCD](https://github.com/MiSTer-devel/MegaCD_MiSTer)                       | Sega CD<br>Sega Mega-CD                                                                                 | ./MegaCD                | boot.rom = BIOS<br>cd\_bios.rom = separate folder BIOS                                                                                        | ✔️       |
| [NES](https://github.com/MiSTer-devel/NES_MiSTer)                             | Nintendo Entertainment System<br>Famicom Disk System<br>NSF Music Player                                | ./NES                   | boot0.rom = FDS BIOS<br>boot1.rom = NES Cart (optional)<br>boot2.rom = blank FDS image (optional)<br>boot3.rom = .PAL Palette File (optional) | ✔️       |
| [NeoGeo](https://github.com/MiSTer-devel/NeoGeo_MiSTer)                       | SNK Neo Geo AES & MVS                                                                                   | ./NeoGeo                | 000-lo.lo<br>sfix.sfix<br>sp-s2.sp1 (MVS)<br>neo-epo.sp1 (AES)<br>uni-bios.rom                                                                | ✔️       |
| [Odyssey2](https://github.com/MiSTer-devel/Odyssey2_MiSTer)                   | Magnavox Odyssey 2<br>Philips Odyssey 2<br>Philips Videopac G7000                                       | ./Odyssey2              |                                                                                                                                               |          |
| [PSX](https://github.com/MiSTer-devel/PSX_MiSTer)                             | Sony Playstation                                                                                        | ./PSX                   | boot0.rom = Japanese BIOS<br>boot1.rom = English BIOS<br>boot2.rom = Europe BIOS                                                              | ✔️       |
| [SMS](https://github.com/MiSTer-devel/SMS_MiSTer)                             | Sega Master System<br>Sega Game Gear<br>Sega SG-1000                                                    | ./SMS<br>./SG1000       |                                                                                                                                               | ✔️       |
| [SNES](https://github.com/MiSTer-devel/SNES_MiSTer)                           | Super Nintendo Entertainment System<br>Nintendo Satellaview<br>SPC Music Player                         | ./SNES                  | bsx\_bios.rom = Satellaview ROM                                                                                                               | ✔️       |
| [TurboGrafx16](https://github.com/MiSTer-devel/TurboGrafx16_MiSTer)           | NEC TurboGrafx-16 / PC Engine<br>CD-ROM² / Super CD-ROM²<br>Duo / TurboDuo<br>SuperGrafx<br>Arcade Card | ./TGFX16<br>./TGFX16-CD | cd\_bios.rom = BIOS Place in tgfx16-cd                                                                                                        | Optional |
| [VC4000](https://github.com/MiSTer-devel/VC4000_MiSTer)                       | Interton VC4000<br>Acetronic MPU-1000<br>Occitane OC2000                                                | ./VC4000                |                                                                                                                                               |          |
| [Vectrex](https://github.com/MiSTer-devel/Vectrex_MiSTer)                     | Vectrex                                                                                                 | ./Vectrex               |                                                                                                                                               |          |
| [WonderSwan](https://github.com/MiSTer-devel/WonderSwan_MiSTer)               | Bandai WonderSwan<br>WonderSwan Color<br>SwanCrystal                                                    | ./WonderSwan            | boot.rom = WonderSwan bootrom<br>boot1.rom = WonderSwan Color bootrom                                                                         | ✔️       |