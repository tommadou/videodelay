# Video Delay

Minimal, local-only browser video delay for PE / movement feedback.

## GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. In **Settings → Pages**, deploy from the `main` branch / root.
4. Open the HTTPS GitHub Pages URL and allow camera access.

## Use
- Tap **Start camera**.
- Choose delay from **1–120 seconds** with the vertical slider.
- You can change the delay while the buffer is running, including jumping farther back in the retained ~2-minute window.
- Settings: Performance (~480p), Standard (~720p), High (~1080p); front/back camera; mirror.
- No video is uploaded or intentionally saved. The rolling buffer lives in browser memory and is discarded when stopped/reloaded.

## Notes
Camera access requires HTTPS (GitHub Pages provides this). Long 1080p buffers can be demanding on older phones/tablets; Standard is the recommended default.
