<!-- Repo has been edited to be static, see comments for dynamic calls. -->
hello! here's a little about me:

<h1>
  i really like music :headphones:
</h1>

<!-- Nothing weird to see here -->
<p align="center">
  <!-- Mostrando "Wreck of the Hesperus" de George Harrison estáticamente -->
  <a href="https://open.spotify.com/track/5YDGyLZAchC6B9BkK3O6T5?si=6d6b1a1d5b3c4a1d" target="_blank">
    <!-- Tarjeta estática de la canción -->
    <img src="https://raw.githubusercontent.com/andyruwruw/andyruwruw/master/example/now-playing.svg" alt="Now Playing">
    <br>
    <strong>🎵 Now Playing:</strong><br>
    <strong>Wreck of the Hesperus</strong><br>
    <em>by George Harrison</em><br>
    <small>From the album "Cloud Nine" (1987)</small>
  </a>
</p>

<!-- Versión alternativa con más estilo -->
<style>
  .now-playing {
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    border-radius: 12px;
    padding: 20px;
    max-width: 400px;
    margin: 0 auto;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-left: 5px solid #1DB954;
  }
  .song-title {
    font-size: 1.5em;
    font-weight: bold;
    color: #333;
    margin-bottom: 5px;
  }
  .artist {
    color: #666;
    font-size: 1.1em;
    margin-bottom: 10px;
  }
  .album {
    color: #888;
    font-size: 0.9em;
    font-style: italic;
  }
  .spotify-link {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 16px;
    background-color: #1DB954;
    color: white;
    text-decoration: none;
    border-radius: 20px;
    font-size: 0.9em;
    transition: background-color 0.3s;
  }
  .spotify-link:hover {
    background-color: #1ed760;
  }
</style>

<div class="now-playing">
  <div class="song-title">Wreck of the Hesperus</div>
  <div class="artist">George Harrison</div>
  <div class="album">Cloud Nine (1987)</div>
  <p style="margin-top: 15px; color: #555; font-size: 0.95em;">
    "Wreck of the Hesperus" es una canción de George Harrison de su exitoso álbum "Cloud Nine", lanzado en 1987. La canción muestra el característico estilo de guitarra slide de Harrison.
  </p>
  <a href="https://open.spotify.com/track/5YDGyLZAchC6B9BkK3O6T5?si=6d6b1a1d5b3c4a1d" 
     target="_blank" 
     class="spotify-link">
    🎵 Escuchar en Spotify
  </a>
</div>
