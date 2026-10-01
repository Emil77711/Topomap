# TopoMap

Проект готов к сборке через GitHub Actions (см. инструкцию в чате). Файл workflow: .github/workflows/build.yml

Карты (.mbtiles) кладите в: Android/data/com.example.topomap/files/maps/

## Профиль рельефа (SRTM)
- Скачайте файлы `.hgt` (SRTM1 3601x3601 или SRTM3 1201x1201), распакованные, с именами вида `N45E006.hgt`.
- Положите их в: Android/data/com.example.topomap/files/srtm/
- Долгое нажатие на карте — точка A, второе — точка B, профиль появится внизу.
  Третье долгое нажатие начинает новую линию; кнопка "Сброс" убирает линию.
