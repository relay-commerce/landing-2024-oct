# Relay Pages & Banners

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Deploy

```bash
npm run deploy
```


# Variants
* http://127.0.0.1:8080/?variant=A&grant-access-url=<url> (variant A, default, for handpicked approved users, need to provide URL to grant access)
* http://127.0.0.1:8080/?variant=B (variant B, for other users)
* http://127.0.0.1:8080/?variant=C (variant C, user filled a form and waiting for Fomo action)

[example](http://127.0.0.1:8080/?variant=A&grant-access-url=https://volha-chuvak-dev-store.myshopify.com/admin/oauth/authorize?client_id=f9e95888283be514bbbe6e2fd3f68bb2&scope=read_products%2Cread_orders%2Cread_customers%2Cwrite_script_tags%2Cwrite_themes%2Cunauthenticated_read_product_inventory%2Cunauthenticated_read_product_listings%2Cread_all_orders%2Cread_draft_orders%2Cread_inventory%2Cread_marketing_events%2Cread_product_listings%2Cread_reports&redirect_uri=https%3A%2F%2Ffomo.ngrok.io%2Fshopify_integration%2Fauth_callback&state=LMe5QsDhBBoQk5C&grant_options%5B%5D=)