# Peter Luo — Portfolio

The source code for Peter's portfolio. This starts from an existing prototype from Codex, with cursor-following eyes, a mouth-to-dreamscape scroll transition, project dialogs, responsive styling, and motion controls.

## Preview on your computer

Download this repository using **Code → Download ZIP**, extract it, then open `index.html` in a browser. No installation or build is required.

For a local web server, from the repository folder run:

```sh
python -m http.server 8000
```

On Windows, use `py -m http.server 8000` if `python` is unavailable. Visit http://localhost:8000 and press Ctrl+C in the terminal to stop the server.

## Files

| Path | Purpose |
| --- | --- |
| index.html | Page structure, illustrated assets, and page metadata |
| assets/styles.css | Layout, colors, responsiveness, and animation styles |
| assets/app.js | Cursor and scroll interactions, motion controls, project descriptions |
| AGENTS.md | Guidance for future code changes |

The portrait and project illustrations are placeholders. Project descriptions and biography should be reviewed before launch. No analytics, contact form, backend, or third-party dependencies are configured.

## Working with Codex

Use `perkhetive/portfolio` as the repository for future website changes. Ask Codex to inspect the current code, implement the change, and verify it. Use branches and pull requests for substantial changes after this initial setup.

A GitHub connector in ChatGPT provides repository access. A separate Codex environment, if used, must also be configured to use this repository; this repository setup does not create that environment.

## Validation

```sh
node --check assets/app.js
```

For visual changes, preview at desktop and mobile widths. Check the cursor-following eyes, scrolling transition, three project dialogs (including Escape to close), navigation, and Pause/Resume motion. Also check the operating system's reduced-motion setting.

## Hosting and a custom domain later

This repository contains deployable static files at its root. Hosting is not enabled by this setup.

One option is GitHub Pages. When ready to launch, open the repository's **Settings → Pages**, choose deployment from the `main` branch and `/ (root)`, and save. GitHub will display the site's URL once deployment completes. A static host connected to this repository is another option.

To use a custom domain, first choose and register the domain, then configure it with the selected host and update its DNS records at your domain provider using the host's current instructions. Enable HTTPS after domain verification. Do not add a placeholder CNAME file or speculative DNS records.

The website uses relative asset paths so it can work under a project URL or a custom domain. Add the final canonical URL, social sharing metadata, and sitemap when the public address is known.

## Inputs for the next design pass

- Portrait photo and preferred treatment: photo cutout or illustration.
- Projects to feature, with descriptions, images, links, and your role.
- Final biography and any public contact or social links.
- Domain name and registrar when you are ready to launch.
