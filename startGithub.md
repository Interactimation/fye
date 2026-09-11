
# Getting Started with Github

This workflow works on **Windows, Mac, and Chromebook** and requires no software installation.

## Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a sign in (if you don't have one already!)
2. Click **New repository**.
3. Give the repository a name.
4. Set it to **Public**.
5. Check **Add a README file**.
6. Click **Create repository**.

### Create Your Web Page

1. In the repository, click **Add file → Create new file**.
1. Name the file:

   `index.md`

1. in the repo press the `.` (period) key —an editor will fills the screen

1. Add some Markdown:

   ```markdown
   # My Markdown Test

   This is a paragraph.

   ## A Subheading

   Here is **bold**, *italic*, and a [link](https://github.com).

   - Apples
   - Oranges
   - Lemons

### Preview Your Markdown

To preview the page:

**Windows / Chromebook**

`Ctrl + Shift + V`

**Mac**

`Cmd + Shift + V`

To go back into edit mode just click the page name (index.md) in the left sidebar

Now can edit the Markdown and preview the result before publishing it.

### Save Your Changes

1. Click **Commit changes**.
1. Commit the file to the `main` branch.

## Create Your Website

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

### Open the Browser-Based Editor

After you've admired your very first website (or your first GitHub Pages website) return to the main page of your repository (the back button on your browser will do this)

### Edit Your Markdown

Press `.` again and edit the markdown

1. In the **Explorer** on the left, click `index.md`.
2. Edit the Markdown normally.
3. Save your changes.


### Publish Your Changes

1. Click the **Source Control** icon on the left.

2. Enter a short commit message, such as:

   `update page`

3. Click **Commit**.

4. Click **Sync Changes** or **Push** if requested.

GitHub Pages will rebuild the website automatically.

### View Your Website

Return to:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

Refresh the page.

Your Markdown changes should now appear on the website (it will take a couple minutes)

---

---

## The Basic Workflow:

**Edit Markdown → Preview → Commit → Website**
