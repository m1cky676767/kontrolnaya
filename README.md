# Music Streaming

База данных для музыкального стриминга. Сделано на MS SQL Server.

## Что есть в базе

Таблицы:
- roles — роли (admin, user, artist)
- labels — лейблы
- genres — жанры
- users — пользователи
- artists — артисты (привязаны к юзерам)
- tracks — треки
- albums — альбомы
- album_tracks — какие треки в каком альбоме
- playlists — плейлисты
- playlist_tracks — треки в плейлистах
- listenings — кто что слушал
