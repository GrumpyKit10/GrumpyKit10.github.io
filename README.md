# GrumpyKit10.github.io

This repository contains the source for my personal portfolio website, built with [Jekyll](https://jekyllrb.com/) and hosted via [GitHub Pages](https://pages.github.com/). The site is live at [https://infosecmatthew.com](https://infosecmatthew.com).

---

## About the Site

My portfolio showcases my projects and experience in **cybersecurity, server engineering, and IT infrastructure**. It also includes personal interests like **backpacking, cooking, and home tech projects**.

The site is designed with the **Minima Jekyll theme**, fully customizable, and built to be lightweight and responsive.

---

## Features

- **Jekyll-powered** static site generator for easy updates
- **Custom domain**: `infosecmatthew.com`
- **Projects and blog sections** to highlight technical work
- **Responsive layout** for desktop and mobile
- **Live reload support** during local development

---

## Getting Started

To run the site locally:

1. **Clone the repository**  
   ```bash
   git clone git@github.com:GrumpyKit10/GrumpyKit10.github.io.git
   cd GrumpyKit10.github.io
````

2. **Install dependencies**

   ```bash
   bundle install
   ```

3. **Serve locally with live reload**

   ```bash
   bundle exec jekyll serve --host 127.0.0.1 --port 4000 --livereload
   ```

4. Open your browser at `http://127.0.0.1:4000` to preview changes.

---

## Deployment

The site is deployed automatically via **GitHub Pages** from the `main` branch. The `_config.yml` file is configured with:

```yaml
url: "https://infosecmatthew.com"
baseurl: ""
theme: minima
```

The custom domain is set in GitHub Pages settings and via the `CNAME` file in the repository.

---

## Customization

* **Theme:** The site uses the `minima` theme. You can override CSS in `/assets/css/style.scss`.
* **Pages:** Add new pages by creating Markdown files with the correct Front Matter.
* **Projects:** Projects are listed under `/projects/` and can be updated directly in Markdown files.

---

## License

This project is open-source under the [MIT License](LICENSE).

---

## Contact

* Website: [https://infosecmatthew.com](https://infosecmatthew.com)
* GitHub: [@GrumpyKit10](https://github.com/GrumpyKit10)
* LinkedIn: [ZeroKeyMaster](https://www.linkedin.com/in/ZeroKeyMaster/)

