# espydock

Dynamic screen recorder using modern web technologies.

## Technologies

- **Runtime**: React 19, React Router v7 (framework mode, fs-router, SSG)
- **State**: Redux Toolkit (+ RTK Query)
- **UI**: Mantine v7, CSS Modules, Phosphor Icons
- **Media**: getDisplayMedia, getUserMedia, MediaRecorder API, Media Capture and Streams API, File System API
- **Encoding**: ffmpeg.wasm (VP9/H.264/GIF export)
- **DevX**: TypeScript, Biome (lint + format), Vite, Vitest, Yarn, DotENV

## Features

- **Add automatic zoom**: Pick part of your video to be zoomed in following mouse cursor
- **Export in vertical mode**: Pick desired aspect ratio. All animations will be adjusted instantly.
- **Generate transcript**: In captions section, click "Generate transcript" to add captions to your video
- **Export video**: Select output format and size you need and compression preset
- **Smooth mouse movement**: Shaky and rapid movement of your cursor is transformed into a smooth and beautiful glide.
- **Change cursor size**: Make your video easier to follow by changing the size of the cursor even after you have finished recording.
- **Edit your video quickly**: Simply drag your zooms on the timeline. All the heavy lifting is done automatically. No manual work is required.
- **Change style of your video**: Easily change the background or spacing around your video.
- **Cut & Speed up**: Easily trim, cut or speed up parts of your recording.
- **Record and adjust your webcam**: Your selfie overlays the video and slightly zooms out to avoid covering your mouse cursor.
- **Enhance audio quality**: Voice volume is normalized, and background noise is removed automatically.
- **Record system audio**: Record system audio from all your apps or just selected ones. Creating audio tutorials just got a lot easier.
- **Crop your recording**: Focus on a specific part of your screen or hide parts of the UI.

## Prior Art

- <https://screen.studio/>
- <https://cursorful.com/>
- <https://github.com/wulkano/Kap>
- <https://github.com/CapSoftware/Cap>
- <https://github.com/contrastio/recorder>
