# WordPress Playground - WooCommerce & Slim SEO

A pre-configured WordPress Playground blueprint with WooCommerce (setup wizard skipped, sample products imported) and Slim SEO plugins.

## Quick Start

### Direct URL

```
https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/lemonroti/vipro-wp-plyground-bp/main/blueprint.json
```

### Run Locally with wp-now

```bash
npx @wp-now/wp-now start --blueprint=blueprint.json
```

### Embed in HTML

```html
<iframe
  src="https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/lemonroti/vipro-wp-plyground-bp/main/blueprint.json"
  width="100%"
  height="600">
</iframe>
```

## What's Included

### Plugins

| Plugin | Description |
|--------|-------------|
| WooCommerce | E-commerce platform (setup wizard skipped) |
| Slim SEO | Lightweight SEO optimization |
| Code Snippets | Add custom PHP code snippets |
| WordPress Importer | Data import support |

### Sample Products (15 total)

| Category | Products |
|----------|----------|
| Hoodies | Hoodie (variable), Hoodie with Logo, Hoodie with Pocket, Hoodie with Zipper |
| Tshirts | T-Shirt, T-Shirt with Logo, Polo, Long Sleeve Tee, V-Neck T-Shirt |
| Accessories | Beanie, Belt, Cap, Sunglasses |
| Music | Single (virtual), Album (downloadable) |

### Store Configuration

- Currency: USD
- Country: United States (California)
- Address: 123 Demo Street, San Francisco, CA 94103

### Login Credentials

- Username: `admin`
- Password: `password`

## Environment

- PHP: 8.3
- WordPress: Latest
- Networking: Enabled
- Landing Page: `/wp-admin/`
