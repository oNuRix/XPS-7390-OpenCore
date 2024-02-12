# XPS-7390-OpenCore-Sonoma
not stable

<img width="905" alt="Capture d’écran 2024-02-10 à 20 48 50" src="https://github.com/oNuRix/XPS-7390-OpenCore/assets/40405226/ec35c66c-64fb-4221-a764-3e0eabb46224">




## Specs

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Dell XPS 7390      |
| Processor           | Intel Core i7-10710U   |
| Memory              | 8GB 2133 LPDDR3 |
| NVME                | M.2 Nvme HFS256GD9TNG-62A0A | 
| Integrated Graphics | Intel UHD Graphics 630 |
| Monitor             | 4k 3840x2160 touchscreen (13.3") |
| Wireless Card       | Intel AX200 |

## Misc before install:

- [Gensmbios](https://github.com/corpnewt/GenSMBIOS) (better if you know MAC address for rom section in OC)
- [Unlock CFG ](https://dortania.github.io/OpenCore-Post-Install/misc/msr-lock.html#turning-off-cfg-lock-manually)

  BIOS Settings 
- System Configuration --> SATA Operation --> AHCI
- Security --> Absolute --> Disabled
- Security --> SMM Security Mitigation --> Disabled
- Security --> Intel SGX --> Disabled/Software Control
- Secure Boot --> Enable Secure Boot --> Toggle OFF
- Secure Boot --> Secure Boot Mode --> Deployed Mode
- POST Behavior --> Sign of Life --> Display Logo Sign of Life --> Toggle OFF
- Power Management --> Block Sleep --> Toggle ON (i use it with external screen)

  THANKS
- [sambow23](https://github.com/sambow23/Dell-XPS-13-7390-macOS)
- [meghan06](https://github.com/meghan06/XPS13-73902in1)
