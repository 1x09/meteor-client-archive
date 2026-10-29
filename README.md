# Meteor Client Archive

Unofficial archive of [Meteor Client](https://github.com/MeteorDevelopment/meteor-client) (GPL-3.0).

- `versions/` source zip for every tagged release
- `meteor-client-full-history.bundle` full git history (`git clone meteor-client-full-history.bundle`)
- `index.html` the GitHub Pages site (search, filters, jar and source downloads)
- `.github/workflows/build-jars.yml` builds the jars (see below)

Enable Pages: Settings > Pages > Deploy from branch > `main` / `(root)`.

## Getting the jars
1. Go to the **Actions** tab, pick **Build jars**, click **Run workflow**.
2. Wait for it to finish (about 10 to 20 minutes). Jars land in the **jars** release.
3. The website's Jar buttons then work. Some old versions may fail to build; that is normal.

Also enable Actions write access: Settings > Actions > General > Workflow permissions > Read and write.
