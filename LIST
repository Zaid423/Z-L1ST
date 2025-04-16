// Get all the song buttons
const songButtons = document.querySelectorAll('.song-button');

// Get the audio player and its source element
const audioPlayer = document.getElementById('audio-player');
const audioSource = document.getElementById('audio-source');

// Add event listener to each song button
songButtons.forEach(button => {
  button.addEventListener('click', () => {
    const songUrl = button.getAttribute('data-song');
    audioSource.setAttribute('src', songUrl);
    audioPlayer.load();
    audioPlayer.play();
  });
});
