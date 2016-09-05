# Somado
Program "Somado" umożliwia optymalizację dostaw towarów; wykorzystuje dane OpenStreetMap. Problem marszrutyzacji (VRP) rozwiązywany przy użyciu biblioteki JSprit. Wyświetlanie map przy użyciu biblioteki JXMapViewer2.

*Aplikacja była częścią pracy dyplomowej inż. obronionej na Politechnice Warszawskiej (06.2016)*
### Baza danych przestrzennych
W folderze dist umieszczono skompresowany plik bazy SQLite + Spatialite, zawierającej dane sieci drogowej woj. mazowieckiego, przygotowane na podstawie danych OpenStreetMap (dist/roads.sqlite.zip)

### Konfiguracja
- Import bazy danych MySQL (plik mysql_dump.sql.zip w folderze dist)
- Ustawienie dostępu do bazy MySQL, ew. serwera TMS w /resources/conf.properties w archiwum dist/Somado.jar 
- Windows: rozpakowanie bibliotek DLL do katalogu z archiwum jar (plik dist/windows_dll.zip)

----------
