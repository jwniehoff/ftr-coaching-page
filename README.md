# FTR Coaching Landing Page

Static landing page for futurestradingrevolution.com/workwithjason, hosted via GitHub Pages.

## First-time setup (about 5 minutes)

1. Create a new repository on GitHub (public or private both work with Pages on paid plans; public works on free).
2. Upload everything in this folder to the repo. Easiest way: on the repo page, click "Add file" then "Upload files" and drag the whole contents in (index.html, the assets folder, this README, and the .nojekyll file). Commit.
3. In the repo, go to Settings, then Pages (left sidebar). Under "Build and deployment," set Source to "Deploy from a branch," pick the main branch and the root folder, and save.
4. Wait 1-2 minutes. Your site will be live at https://YOURUSERNAME.github.io/REPONAME/

## Swapping the headshot (the easy part)

The bio photo is the file: **assets/headshot.jpg**

To change it:
1. Prepare the new photo. Portrait orientation, 4:5 ratio ideally, at least 720px wide. Any decent photo works; it will be cropped to fit automatically.
2. Name the new file exactly **headshot.jpg**
3. In GitHub, open the assets folder, click "Add file" then "Upload files," and drag the new headshot.jpg in. GitHub replaces the old one since the name matches. Commit.
4. The live site updates automatically within a minute or two. Hard refresh (Ctrl+Shift+R) if you still see the old photo.

That is the entire process. No code editing required.

An alternate performance photo (assets/headshot-alt-performance.png) is included in the repo but not used on the page. To use it instead, rename it to headshot.jpg (and convert to jpg, or ask Claude to swap the reference).

## Editing text

All copy lives in index.html. Small text changes can be made directly in GitHub: open index.html, click the pencil icon, edit, commit. For bigger changes, paste the file into Claude and describe what you want.

## Custom domain (later)

To serve this at a subdomain like coaching.futurestradingrevolution.com:
1. Repo Settings, Pages, enter the subdomain under Custom domain.
2. At your DNS provider, add a CNAME record pointing the subdomain to YOURUSERNAME.github.io
3. Wait for DNS to propagate, then enable "Enforce HTTPS" in the Pages settings.

## Content notes

- George A.'s testimonial is staged pending his written confirmation. Do not point traffic at this page until he has replied yes.
- Attorney review items: overall page compliance pass, testimonial format, the phrase "the last trading education you'll ever need."
- Do not reintroduce any testimonial language about account returns (doubling or tripling an account).
- House style: no em-dashes anywhere in page copy.
