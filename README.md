Zotify: ¡Descarga tu música favorita desde Spotify! 🎧✨

Zotify es una herramienta de línea de comandos que te permite descargar canciones, álbumes y listas de reproducción directamente desde Spotify, ¡sin complicaciones!

🎵 Ejemplos de uso

- Descargar una canción específica (ejemplo con ruta Termux):

```bash
zotify --album-library="/data/data/com.termux/files/home/storage/shared/zotify/" --output-album "{album_artist}.{album}.{track_number}. {artists} - {title}" --ffmpeg-args "-b:a 320k" --download-quality high --audio-format mp3 "$url"
```

📦 Instalación [zotify](https://github.com/DraftKinner/zotify)

```bash
python -m pip install git+https://github.com/DraftKinner/zotify.git@dev
```
¡Disfruta de tu música favorita en cualquier momento y lugar! 🎧✨
