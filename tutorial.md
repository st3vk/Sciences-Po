# Tutorial

Welcome to tutorial where you'll learn how to edit your website. You'll only need a **basic understanding of computers** to be able to follow this tutorial.

## Let's get started!

Your website is powered by your Github repository for which you have received an invitation to collaborate. We suggest you to assign **one member** of your group to be **in charge of managing this repository and your website**. To get started this _tech representative_ of your group needs to have signed up for a free account on Github and to have accepted an invitation to collaborate.


Your repository is at `https://github.com/TheGreatTransition/[group_id]` and your website is at `https://thegreattransition.github.io/group[group_id]` where `[group_id]` is your group's secret ID.

**Do not share this ID (and your website's address) with others if you wish to protect your project material before the final submission.**



Go to your Github repository and you'll find the following files.
```
[group_id]/
|
|__  _layout/
|    |__  default.html
|__  assets/
|    |__  css/
|    |    |__ style.scss
|    |__  images/
|    |    |__ cover.jpg
|    |    |__ logo.jpg
|    |__  pdf/
|    |    |__ a4.pdf
|    |    |__ powerpoint.pdf
|__  .gitignore
|__  README.md
|__  _config.yml
|__  about.md
|__  cheatsheet.md
|__  index.md
|__  resources.md
|__  tutorial.md
```

## Claim your project's name and image!
To start, click on `_config.yml` and click **edit** (the diagonal pencil icon). Once in the edit mode change `title`, `subtitle`, and `description` to a title (up to 5 words) and subtitle (around 10 words) and short description (up to 280 characters) for your project. For now, leave `menu` as is. To save your changes scroll down the page and click **Commit changes**.

> **NOTE: Any commit (change in your repository) might take up to a minute to become effective, so be patient :)**


Meanwhile, go to the `assets/images/` folder. Once there click on **Upload files** and upload your own cover and logo images to replace the existing ones. **The file names MUST be `cover.jpg` and `logo.jpg`**.


## Change your first page!

Now go back to the root of your repository. You'll notice there are by default a few files with names ending with `.md`. **Each of these files contain the content of one of your website's pages with the same name** (except `README.me`). For example `tutorial.md` is the file behind this current page you are seeing.

Start by editing the `index.md` to change the home page of your website. Head down to:
*   [Cheat sheet](cheatsheet.md) to learn how to style your page content.
*   [Resources](resources.md) to learn how to put different media on your pages.



## Create a new page!

You can add and remove as many such files/pages as you like.

To create a new page, you simply need to create a new `.md` (or if you're familiar with HTML `.html`) file in the root of your repository.

There, click on **Create new file** and enter a name (without any space) ending with `.md`: for example `vision.md` which will be accessible at [vision](vision)


## Change the menu!

To change your website's **menu** (the top navigation bar), open the `_config.yml` file and edit `menu: [...]`.

Look at the existing entries to learn how to create a new one. Each entry is represented by a `{...}`, where `display_name` is the label of the entry and `page_name` is the name of the page that it links to (which is the same as the name without `.md` of a file in the root of your repository).

For example, `{"display_name": "Home", "page_name": "index"}` adds Home to the menu which links to the `index` page (created by `index.md` file)


* * *

Eventually you'd want to delete  `Tutorial`, `Cheat Sheet`, and `Resources` from your website's menu. You can also delete the corresponding files (`tutorial.md`, `cheatsheet.md`, and `resources.md`) from your repository.


## Feeling adventurous?
Only if you feel comfortable enough with web development, you may change the structure of the pages in `_layouts/default.html` and the design in `assets/css/style.scss`.
