# Community Tables

A single-page website for Community Tables, the monthly bilingual cooking classes run with the Sunday Friends Foundation in San Jose. Built as one self-contained `index.html` file, so it is easy to host for free on GitHub Pages.

## How to put it online (GitHub Pages)

1. Go to github.com and create a new repository named **community-tables** (keep it Public).
2. Click **Add file > Upload files**, then drag in everything from this folder (`index.html`, `README.md`, `.nojekyll`, and the `images` folder).
3. Commit the files.
4. In the repo, go to **Settings > Pages**.
5. Under "Build and deployment," set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, and Save.
6. Wait about a minute, then refresh. Your site will be live at:
   `https://YOUR-USERNAME.github.io/community-tables/`

That URL is what you put on your resume and LinkedIn.

## Photos

Five of your real class photos are built in (in the `images` folder), focused on the families and the food: one hero image and a four-photo gallery. They have been resized and compressed for fast loading.

Two things you can still add:
- Recipe close-up photos (ice cream, pinwheels, chickpea salad, spring rolls) for the recipe cards. Send them and I will slot each one onto its card.
- Recipe PDFs. Each recipe already has a hidden "View full recipe (PDF)" button built in. Send the PDF files and I will link them so they open from each recipe.

## How to add a new class or recipe

1. Open `index.html` and find the line `const CLASSES = [`.
2. Copy one of the existing class blocks and paste it as a new entry.
3. Change the `month`, `title`, `es` (Spanish name), `emoji`, `ingredients`, and `explored` values.
4. Save. The new recipe card and its pop-up appear automatically.

## Things to update

- **Grant amount:** the About section currently shows `$1,000` with a small "confirm" flag. Your old site said $500. Pick the correct number, then delete the flag text.
- **Names:** the About section has a dashed "Add volunteer & student leader names" chip. Replace it with the real names you want credited.
- **Spanish recipe names:** Ensalada de Garbanzos came straight from your site. The other three Spanish titles are reasonable translations you can adjust anytime.

## Credits

Founded by Kimi Yashar, 2024. In partnership with the Sunday Friends Foundation, San Jose, CA.
