# Bryce.codes

A personal website and technical blog built with Hugo and the Blowfish theme, showcasing my journey as a Cloud Native Infrastructure Engineer.

## About

This is the source code for my personal website at [bryce.codes](https://bryce.codes), where I document my experience with:

- **Cloud Infrastructure** - OpenStack, Ceph, and cloud-native technologies
- **Python Development** - Automation tools and infrastructure management
- **Ansible Automation** - Infrastructure as Code implementations
- **Career Journey** - From traditional IT support to cloud engineering

## Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Theme**: [Blowfish](https://blowfish.page/)
- **Go Module**: github.com/brycenicholls/bryce-codes
- **Content**: Markdown files with Hugo front matter

## Project Structure

```
├── config/          # Hugo configuration files
├── content/         # Website content (markdown)
│   ├── docs/        # Technical documentation
│   └── posts/       # Blog posts
├── themes/blowfish/ # Blowfish theme files
├── static/          # Static assets
├── layouts/         # Custom layout overrides
└── public/          # Generated static site
```

## Development

### Prerequisites

- Go 1.24.4 or later
- Hugo (extended version recommended)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/brycenicholls/bryce-codes.git
   cd bryce-codes
   ```

2. Start the Hugo development server:
   ```bash
   hugo server
   ```

3. Open your browser to `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The generated site will be in the `public/` directory.

## Content Organization

- **About Page** (`content/about.md`) - Professional background and experience
- **Documentation** (`content/docs/`) - Technical guides organized by topic:
  - Ansible automation
  - Ceph storage
  - Python development
  - Learning resources
- **Posts** (`content/posts/`) - Blog posts and articles

## Theme Customization

This site uses the Blowfish theme with custom configurations in:
- `config/_default/params.toml` - Theme parameters
- `config/_default/menus.en.toml` - Navigation structure
- `config/_default/languages.en.toml` - Language settings

## License

Content is personal and proprietary. The Hugo framework and Blowfish theme have their own respective licenses.