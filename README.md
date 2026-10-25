# BIOL125 simulations

Interactive simulations for **Introduction to Neuroscience (BIOL125)**. Each simulation is a single self-contained web page that runs in any modern browser, with no installation or accounts needed.

## Simulations

| Simulation | Lecture | Folder |
|---|---|---|
| Spinal cord lesion simulator | Lecture 9: Somatosensation and Pain | `spinal-cord-lesions/` |
| Building a center–surround receptive field | Lecture 10: Vision | `retina-center-surround/` |

## Links

Once GitHub Pages is on, the site lives at:

- Course page: `https://<your-account>.github.io/<repo-name>/`
- Each simulation: `https://<your-account>.github.io/<repo-name>/<folder>/`

## Turning on GitHub Pages (one time)

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set the source to **Deploy from a branch**, the branch to `main`, and the folder to `/ (root)`, then click **Save**.
3. After a minute or two, the site's address appears at the top of that page.

## Adding a new simulation

1. Create a new folder with a short, lowercase name using hyphens (for example `action-potential`).
2. Put the simulation in that folder as `index.html`.
3. In the top-level `index.html`, copy one `<li class="sim">` block, paste it below the others, and change the folder name, lecture, title and description.
4. Add a row to the table above.

## Updating a simulation

Upload the new version into the same folder with the same name (`index.html`). The address stays the same, so links in Canvas keep working. Changes appear on the live site within a minute or two.

Avoid renaming or moving folders once students have the links.

## Notes

- The repository needs to be public for GitHub Pages on a free plan.
- To keep a record of what students used in a given semester, create a release (for example `fall-2026`) from the repository's **Releases** page.
