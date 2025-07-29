# Demand and Capacity Healthcare Model

This repository contains the source code and configuration for **The Strategy Unit’s Demand and Capacity Healthcare Model** website, built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Features

- Light/dark mode toggle
- Custom branding and color palette
- Responsive design
- Easy navigation with a dynamic Table of Contents

## Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/getting-started/install/) (extended version recommended)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Nat-Stephenson/Info.Page.Draft.git
   cd Info.Page.Draft
   ```

2. **Run the development server:**
   ```sh
   hugo server
   ```

3. Open [http://localhost:1313](http://localhost:1313) in your browser.

### Customization

- **Branding:**  
  Edit `_SUBrand.toml` for organization name, logo, and color palette.
- **Menus:**  
  Update `hugo.toml` under `[[menu.main]]` for navigation.
- **Theme variables:**  
  Adjust CSS in `assets/css/core/theme-vars.css`.

## Deployment

To build the site for production:

```sh
hugo
```

The generated static files will be in the `public/` directory.

## License

## Credits

- [The Strategy Unit](https://www.strategyunitwm.nhs.uk/)
- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)

---
*For questions or contributions, please open an issue or pull request*
