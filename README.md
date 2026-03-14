# Bir Bikram Dey Portfolio

This project is a static website built with plain HTML, CSS, and local media assets. It is ready to host on GitHub Pages.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
5. Save the settings and wait for the first deploy.

GitHub Pages will give you a default site URL like:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Use your Squarespace domain

Once the GitHub Pages site is live:

1. In GitHub, open `Settings` > `Pages` > `Custom domain`.
2. Enter your domain, for example:
   - `www.example.com`
   - or `example.com`
3. In Squarespace domain DNS settings, point the domain to GitHub Pages.

Common DNS pattern for GitHub Pages:

- For `www`: add a `CNAME` record pointing to `YOUR-USERNAME.github.io`
- For the root domain: add `A` records for:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`

After DNS propagates, enable HTTPS in GitHub Pages settings.

## Notes

- `.nojekyll` is included so GitHub Pages serves the site as-is.
- `404.html` redirects missing routes back to the homepage.
- If you want to use a custom domain, add a root-level `CNAME` file containing only your final domain name.

## Optional next step

If you send me your exact domain name, I can add the `CNAME` file for you now.
