# travel-together-site

The public site for Travel Together at www.traveltogether.now, served by GitHub Pages with its built-in Jekyll.

- `index.html` is the landing page. `privacy.md` and `delete-account.md` use `_layouts/page.html`, which `_config.yml` makes the default for every page.
- Styles are in `assets/css/site.css`. The colors and type come from the app's design handoff (`travel-together-app/design_handoff_travel_together`).
- Fonts are self-hosted from `assets/fonts`, so visitors don't send a request to Google. They're subsets of Instrument Serif and Geist, both under the OFL (licenses next to the files).
- `assets/screens/*.webp` are screenshots from the Android emulator, taken with the app running against the local Supabase demo trip (Osaka). The status bar and gesture handle are painted out, and the images are scaled to 720×1600.

## Preview locally

```sh
docker run --rm -v "$PWD":/srv/jekyll -p 4000:4000 jekyll/jekyll:3.8 jekyll serve
```
