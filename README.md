### EAF NetEase Cloud Music
<p align="center">
  <img width="800" src="./screenshot.png">
</p>

### Load application

```Elisp
(add-to-list 'load-path "~/.emacs.d/site-lisp/eaf-netease-cloud-music/")
(require 'eaf-netease-cloud-music)
```

NetEase Cloud Music application for the [Emacs Application Framework](https://github.com/emacs-eaf/emacs-application-framework).

### The keybinding of EAF Netease Cloud Music.

| Key   | Event   |
| :---- | :------ |
| `<f12>` | open_devtools |
| `<up>` | eaf--netease-cloud-music-move-song-up |
| `<down>` | eaf--netease-cloud-music-move-song-down |
| `SPC` | netease-cloud-music-pause-or-continue |
| `<return>` | eaf--netease-cloud-music-switch-enter |
| `C-n` | js_scroll_up |
| `C-p` | js_scroll_down |
| `M-v` | js_scroll_up_page |
| `M-V` | js_scroll_down_page |
| `M-<` | js_scroll_to_begin |
| `M->` | js_scroll_to_bottom |
| `M-f` | netease-cloud-music-switch-next-page |
| `M-b` | netease-cloud-music-switch-prev-page |
| `M-n` | js_scroll_playlist_up |
| `M-p` | js_scroll_playlist_down |
| `q` | netease-cloud-music-back |
| `Q` | netease-cloud-music-quit |
| `r` | netease-cloud-music-change-repeat-mode |
| `x` | netease-cloud-music-kill-current-song |
| `/` | eaf--netease-cloud-music-play-with-index |
| `n` | js_play_next |
| `N` | netease-cloud-music-random-play |
| `p` | js_play_prev |
| `P` | netease-cloud-music-playlist-play |
| `c` | netease-cloud-music-change-lyric-type |
| `d` | eaf--netease-cloud-music-delete-song-from-playlist |
| `D` | netease-cloud-music-delete-playing-song |
| `<` | netease-cloud-music-seek-backward |
| `>` | netease-cloud-music-seek-forward |
| `k` | netease-cloud-music-clear-playlist |
| `w` | eaf--netease-cloud-music-write-mode-enter |
| `s` | eaf--netease-cloud-music-switch-playlist |
| `f` | netease-cloud-music-search-song |
| `F` | netease-cloud-music-search-playlist |
| `a` | eaf--netease-cloud-music-add-to-playlist |
| `A` | netease-cloud-music-switch-add-page |
| `C` | netease-cloud-music-create-playlist |
| `m` | netease-cloud-music-change-playlist-name |
| `M` | netease-cloud-music-delete-playlist |
| `g` | eaf--netease-cloud-music-cancel-search |
| `l` | netease-cloud-music-login |
| `e` | netease-cloud-music-get-recommend-songs |
| `E` | netease-cloud-music-get-recommend-playlists |
| `j` | netease-cloud-music-storage-song |
| `J` | netease-cloud-music-add-storage-to-current-playlist |
| `o` | netease-cloud-music-show-storage |
| `O` | netease-cloud-music-delete-song-from-storage |
| `K` | netease-cloud-music-clear-storage |

