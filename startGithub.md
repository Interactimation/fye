
# Getting Started with Github

This workflow works on **Windows, Mac, and Chromebook** and requires no software installation.

## 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com).
2. Click **New repository**.
3. Give the repository a name.
4. Set it to **Public**.
5. Check **Add a README file**.
6. Click **Create repository**.

## 2. Create Your Web Page

1. In the repository, click **Add file → Create new file**.
2. Name the file:

   `index.md`

3. Add some Markdown:

   ```markdown
   # My Markdown Test

   This is a paragraph.

   ## A Subheading

   Here is **bold**, *italic*, and a [link](https://github.com).

   - Apples
   - Oranges
   - Lemons


4. Click **Commit changes**.
5. Commit the file to the `main` branch.

## 3. Turn On GitHub Pages

1. Open **Settings** for the repository.

2. Select **Pages**.

3. Under **Build and deployment**, choose:

   * **Source:** Deploy from a branch
   * **Branch:** `main`
   * **Folder:** `/(root)`

4. Click **Save**.

5. Refresh the **Pages** settings page after a moment.

GitHub will display your site address:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## 4. Open the Browser-Based Editor

Return to the main page of your repository.

Press:

`.`

GitHub will open the repository in **github.dev**, a browser-based version of VS Code.

No installation is required.

## 5. Edit Your Markdown

1. In the **Explorer** on the left, click `index.md`.
2. Edit the Markdown normally.
3. Save your changes.

## 6. Preview Your Markdown

To preview the page:

**Windows / Chromebook**

`Ctrl + Shift + V`

**Mac**

`Cmd + Shift + V`

You can edit the Markdown and preview the result before publishing it.

## 7. Publish Your Changes

1. Click the **Source Control** icon on the left.

2. Enter a short commit message, such as:

   `update page`

3. Click **Commit**.

4. Click **Sync Changes** or **Push** if requested.

GitHub Pages will rebuild the website automatically.

## 8. View Your Website

Return to:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

Refresh the page.

Your Markdown changes should now appear on the website.

---

The basic workflow is:

**Edit Markdown → Preview → Commit → Website**
