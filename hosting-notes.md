# Hosting Notes for the HTML Version

## Recommended default
Use Cloudflare Pages for a simple shareable `pages.dev` link.

Why:
- Free for a small static page
- Very simple deployment
- Clean URL
- Easy to update by re-uploading the same folder

## Option 1: Cloudflare Pages
1. Create a new Pages project.
2. Choose direct upload or connect a Git repository.
3. Upload the contents of this folder.
4. Ensure `index.html` is at the top level.
5. Share the generated `*.pages.dev` link.

Official docs:
- https://developers.cloudflare.com/pages/
- https://developers.cloudflare.com/pages/framework-guides/deploy-anything/

## Option 2: Netlify
1. Create a new site.
2. Drag and drop the folder or connect a Git repository.
3. Publish the site.
4. Share the generated Netlify URL.

Official docs:
- https://docs.netlify.com/deploy/create-deploys/

## Important note
This is suitable for easy internal sharing through an unlisted link.
It should not be presented as secure or confidential hosting.
