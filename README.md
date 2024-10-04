# Studiul Filtrelor Pasive RC

## Prezentare Generală a Proiectului

Acest proiect implementează două filtre RC pasive și studiază comportamentul acestora. Atât filtrul trece-jos, cât și filtrul trece-sus folosește o **rezistență de 18 kOhmi** și un **condensator de 10 nF**. Proiectul studiază cum răspunde fiecare filtru la două semnale sinusoidale de intrare cu frecvențe diferite (100 Hz și 1 kHz) și vizualizează rezultatele prin intermediul graficelor MATLAB.

### Componente

- **Filtru Trece-Jos**: Permite semnalelor cu o frecvență mai mică decât frecvența limită de tăiere să treacă, atenuând frecvențele mai mari.
- **Filtru Trece-Sus**: Permite semnalelor cu o frecvență mai mare decât frecvența limită de tăiere să treacă, atenuând frecvențele mai mici.

### Specificații ale Semnalului

- **Frecvențe de Intrare**: 100 Hz și 1 kHz (poate fi modificată după preferință)
- **Amplitudine Semnal**: 5 Vpp (2.5 V amplitudine)
- **Frecvența de Eșantionare**: 50 kHz

## Utilizare

1. **Cerințe**: Programul MATLAB este necesar, împreună cu extensia Control System Toolbox.
2. **Deschiderea fișierului**: Deschideți fișierul `filtre_pasive.mlx` în MATLAB.
3. **Rulați Scriptul**: Executați scriptul pentru a genera semnalele de intrare, a aplica filtrele și a vizualiza rezultatele.

## Licență

Acest proiect este licențiat sub Licența MIT.
