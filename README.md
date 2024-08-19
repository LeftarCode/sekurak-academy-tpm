# Sekrety (nie)bezpieczeństwa TPM


## Konfiguracja środowiska
A tej sekcji znajduje się krótka opisowa instrukcja w jaki sposób należy skonfigurować sobie środowisko, aby móc przetestować napisane exploity. W trakcie szkolenie używaliśmy VirtualBox, ale jeżeli preferujesz alternatywne rozwiązanie to nic nie stoi na przeszkodzie.

Konfiguracja wirtualnej maszyny:
- Najlepiej Ubuntu 22.04+,
- Ustawienia VM > System > TPM > 2.0,
- Zainstaluj `tpm2-tools`:
```bash
sudo apt install tpm2-tools
```
- Happy hacking :)

## Lekturka do snu
[A Practical Guide to TPM 2.0: Using the Trusted Platform Module in the New Age of Security](https://www.amazon.com/Practical-Guide-TPM-2-0-Platform-ebook/dp/B0781D8J6W/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=) <br>
[Beyond BIOS: Developing with the Unified Extensible Firmware Interface, Third Edition](https://www.amazon.pl/Beyond-BIOS-Developing-Extensible-Interface/dp/1501514784) <br>
[Trusted Computing 1101: Introductory Trusted Platform Module (TPM) usage](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+TC1101_IntroTPM+2024_v1/about) <br>
## Slides
[Sekrety (nie)bezpieczeństwa TPM \[PL\]](https://github.com/LeftarCode/sekurak-academy-tpm/blob/main/MaLe_TPM_slides.pdf)
