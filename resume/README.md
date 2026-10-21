# Resume page for charbelnasr.com

This folder is the page that goes at **https://charbelnasr.com/resume/**.

## Put it on the website

1. Copy this whole `resume` folder (`index.html` and the two PDFs) into your website folder,
   next to the `stockhub` and `services` folders.
2. Deploy the way you always do (from the website folder):

   ```
   netlify deploy --prod
   ```

3. Open https://charbelnasr.com/resume/ to check it.

## Add a link in the site menu (optional)

In your website's `index.html`, next to the other menu links (REAL PROJECTS, SERVICES, STOCKHUB...), add:

```html
<a href="/resume/">RESUME</a>
```

Copy the `class="..."` from the link next to it so it looks the same.

## Updating the resume later

Edit `index.html`, then make new PDFs by opening the page in Chrome and printing it
(Print > Save as PDF, paper A4, margins None, background graphics on).
Use `?theme=light` at the end of the address for the print version.
