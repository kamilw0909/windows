### co zrobić jak nie mogę zmniejszyć
- zrób defragmentowanie dysku **defraggler**
- konwersja partycji fat32 na ntfs
- `chkdsk` --> sprawdzenie czy dysk nie ma błędów
- usuń punkt przywracania systemu / system restore
  - CTRL + R --> `systempropertiesprotection.exe` --> dysk --> wyłącz --> apply
- wyłączenie hiberfile --> cmd jako admin --> `powercfg /hibernate off`
- wyłączenie pagefile --> CTRL + R --> `systempropertiesadvanced.exe` --> zaawansowane --> ustawienia --> zaawansowane --> zmień --> bez pliku pagefile --> ustaw 
