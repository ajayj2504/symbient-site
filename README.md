# SYMBIENT

A clean starter workspace. Replace this section with your project overview and goals.

## Structure

- `src/`: your source code
- `.vscode/`: editor settings and recommended extensions
- `.github/`: workspace automation/config

## Next steps

- Decide your project type (e.g., Python, Node, .NET)
- Initialize version control and dependencies
- Add a minimal Hello World in `src/`

## Deploy to <https://symbient.in> via GitHub Pages

1. Create a GitHub repository and push this folder (root contains `.github/`, `web/`). Use `main` as the default branch.
2. In GitHub: Settings → Pages → Build and deployment → Source: GitHub Actions.
3. DNS for `symbient.in`:
	- A records (apex): 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
	- Optional: CNAME `www` → `symbient.in`
4. The workflow `.github/workflows/deploy-pages.yml` deploys the `web/` folder.
5. Custom domain is set via the `web/CNAME` file. TLS cert will auto-provision (may take minutes).

Sitemap: <https://symbient.in/sitemap.xml> (already updated). Robots: <https://symbient.in/robots.txt>.
