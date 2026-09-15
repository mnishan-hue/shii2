# For Shiyu

A static cinematic experience. `index.html` is the original uploaded `shiyu_FINAL_STABLE_ENVELOPE_CINEMATIC.html`, unchanged; its CSS, JavaScript, wording, and scene behavior are preserved.

## Open locally

Open `index.html` in a modern browser. For an HTTP preview, run `npx --yes serve .` from this repository and open the local URL it prints. Internet access is needed for Google Fonts; system fonts provide fallbacks.

## Deploy on Vercel

Import `mnishan-hue/shii2` into Vercel and use `main` as the production branch. Keep the repository root as the Root Directory and select the Other framework preset. No build or installation step is needed. `vercel.json` sets the output directory to `.` and disables the build command. Deploy; subsequent pushes to `main` trigger deployments when the Git integration is connected. No environment variables are required.

See https://vercel.com/docs/builds/configure-a-build for static build settings.

## Media

This version does not reference the previous optional `assets/` media paths. The existing asset directories are retained for future use.
