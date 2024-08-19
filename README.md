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

## Slides

[Sekrety (nie)bezpieczeństwa TPM \[PL\]](https://github.com/LeftarCode/sekurak-academy-tpm/blob/main/MaLe_TPM_slides.pdf)
