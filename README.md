# KRCal
Simple Website with my Calendar Embeded

## Deploying to Cloudflare Pages

Recommended settings to deploy this Jekyll site on Cloudflare Pages:

- Framework: Jekyll (auto-detected)
- Build command: `bundle exec jekyll build`
- Build output directory: `_site`

Notes:

- If Cloudflare's environment has a different Jekyll version already activated, using `bundle exec` ensures Bundler uses the versions in your Gemfile/Gemfile.lock.
- To pin exact versions, create a `Gemfile.lock` locally with `bundle install` and commit it. If you prefer not to commit a lockfile, the `Gemfile` now allows any Jekyll 4.x version (including 4.4.x) so Cloudflare's preinstalled Jekyll should work.

If you'd like, I can add a sample `pages` configuration, a `CNAME` for a custom domain, or create and commit a `Gemfile.lock` for strict reproducible builds.
# KRCal
Simple Website with my Calendar Embeded
