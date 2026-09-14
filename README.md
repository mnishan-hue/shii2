# For Shiyu

A static cinematic experience. `index.html` is the original uploaded `shiyu_full_experience_V3_CINEMATIC.html`, unchanged; its CSS, JavaScript, wording, and scene behavior are preserved.

## Open locally

Open `index.html` in a modern browser. For an HTTP preview, run `npx --yes serve .` from this repository and open the local URL it prints. Internet access is needed for Google Fonts; system fonts provide fallbacks.

## Deploy on Vercel

Import `mnishan-hue/shii2` into Vercel and use `main` as the production branch. Keep the repository root as the Root Directory and select the Other framework preset. No build or installation step is needed. `vercel.json` sets the output directory to `.` and disables the build command. Deploy; subsequent pushes to `main` trigger deployments when the Git integration is connected. No environment variables are required.

See https://vercel.com/docs/builds/configure-a-build for static build settings.

## Optional media

The HTML already references these relative, case-sensitive paths:

- `assets/photos/moment-01.webp` through `assets/photos/moment-07.webp`
- `assets/memories/award-video.mp4`
- `assets/memories/award-poster.webp`

The directories are tracked using `.gitkeep` files. The media files themselves are not included in the supplied HTML. Existing photo and video placeholders remain until matching files are added; missing media requests may return 404. Add the real files with these exact lowercase names to populate the existing slots. Do not rename JPEG files to `.webp`; convert them first.
