# My Hugo Blog

A static blog powered by [Hugo](https://gohugo.io/) and hosted on [Netlify](https://www.netlify.com/), with the [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke) theme.

## Setup

### Prerequisites
- [Hugo](https://gohugo.io/installation/) - Static site generator
- [Git](https://git-scm.com/) - Version control

### Local Development

1. Clone this repository
2. Install git submodules (the theme):
   ```bash
   git submodule update --init --recursive
   ```
3. Start the development server:
   ```bash
   hugo server -D
   ```
4. Open http://localhost:1313 in your browser

### Creating New Posts

```bash
hugo new content/posts/your-post-title.md
```

Edit the created file in `content/posts/your-post-title.md`

### Deployment

This site is automatically deployed to Netlify when you push to the main branch.

## Configuration

Edit `hugo.toml` to customize:
- `baseURL` - Your site's URL
- `title` - Site title
- `author` - Your name
- `description` - Site description

## Theme Customization

The Ananke theme is used as a git submodule in `themes/ananke`. To update the theme:
```bash
cd themes/ananke
git pull origin main
```

See [Ananke documentation](https://github.com/theNewDynamic/gohugo-theme-ananke) for customization options.
