# lalalavir.github.io

Personal academic homepage of Hongrui Zhu. Built with [Jekyll](https://jekyllrb.com/)
and hosted on GitHub Pages — live at <https://lalalavir.github.io>.

## Edit content

| What | Where |
|------|-------|
| Name, role, bio, interests, contact | `index.html` |
| Add / edit publications | `_data/publications.yml` |
| Colors, fonts, spacing | `assets/css/main.css` |
| Site title, email, links | `_config.yml` |

### Add a publication

Open `_data/publications.yml` and add a block:

```yaml
- title: "Your paper title"
  authors: "Hongrui Zhu, Co-Author*"   # your name is auto-bolded
  venue: "Submitted to Some Journal"
  status: "Under Review"
  links:
    - name: "PDF"
      url: "https://..."
    - name: "arXiv"
      url: "https://..."
```

## Preview locally

```bash
bundle install        # first time only
bundle exec jekyll serve
# open http://localhost:4000
```

## Deploy

Push to the `main` branch of the `lalalavir.github.io` repo. GitHub Pages
builds and publishes automatically within a minute.

```bash
git add -A
git commit -m "Update homepage"
git push
```
