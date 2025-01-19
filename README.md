# XPS-7390-OpenCore-Sonoma


<img width="318" alt="mba" src="https://github.com/user-attachments/assets/b2fa7e4a-35f0-4592-b378-cb447c8e66a7" />


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
- Power Management --> Block Sleep --> Toggle ON (i use it with external screen)

  AFTER INSTALL
- use commande : sudo pmset -a disablesleep 1
- if not screen flicking after wake.
- wifi not work after wake too
  
  THANKS
- [sambow23](https://github.com/sambow23/Dell-XPS-13-7390-macOS)
- [meghan06](https://github.com/meghan06/XPS13-73902in1)
- [theJayTea](https://github.com/theJayTea/XPS-13-7390-Hackintosh)
