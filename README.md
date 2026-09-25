# Convertor Extrase PDF → CSV — Releases

Repository dedicat **descărcărilor** pentru aplicația **Convertor Offline Extrase PDF → CSV**.

- Ultima versiune: **v1.5.3** (vezi tab-ul [Releases](https://github.com/DrawbridgeOfficial/ConvertorExtrasOffline-Releases/releases))

## Ce face aplicația

Transformă extrasele de cont în format PDF (nativ, nu scanări) în fișiere CSV unificate, compatibile Excel românesc:

- **Bănci suportate:** ING, Raiffeisen, Banca Transilvania, BCR, CEC, Libra Bank, Intesa Sanpaolo Bank (ISPRO online banking)
- **100% offline** — datele bancare nu părăsesc calculatorul
- Detectare automată a băncii, procesare batch, drag & drop
- CSV: delimitator `;`, UTF-8 cu BOM, virgulă zecimală
- Include sold inițial / final și sold intermediar pe fiecare tranzacție

## Instalare

1. Descarcă `Convertor_Extrase_PDF_CSV.exe` din [ultima release](https://github.com/DrawbridgeOfficial/ConvertorExtrasOffline-Releases/releases/latest)
2. Rulează fișierul — nu necesită instalare (Python inclus în executabil)

### Verificare integritate (opțional)

Compară SHA-256 al fișierului descărcat cu valoarea din `Convertor_Extrase_PDF_CSV.exe.sha256`:

```powershell
Get-FileHash .\Convertor_Extrase_PDF_CSV.exe -Algorithm SHA256
```

## Confidențialitate

- Aplicația procesează PDF-urile **local**, fără conexiune la internet
- Nu colectăm date; executabilul nu conține date de client (verificat automat la build)

## Licență

Utilizare internă.
