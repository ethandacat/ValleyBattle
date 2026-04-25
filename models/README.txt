Drop your local model files in this folder.

Expected filenames:
- player.glb
- boss.glb

Notes:
- If you open `index.html` directly with `file://`, browsers will block GLB loading. Serve the project over `http://localhost` instead.
- Quick option on this machine: run `python -m http.server 8000` in `C:\Users\ethan\OneDrive\Desktop\ICFInal`, then open `http://localhost:8000/`.
- The player loader works best with a rigged GLB. If it contains animation clips named "Idle" and "Run", the game will use them automatically.
- If either file is missing or fails to load, the game falls back to its built-in placeholder mesh for that character.
