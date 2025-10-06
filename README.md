# Minimal

Minimal is a simple, extensible [Bootstrap](https://getbootstrap.com/)-based
minimalist [Hugo](https://gohugo.io/) blog theme.

It is the successor of
[a same-named theme for Jekyll](https://github.com/ZhongRuoyu/jekyll-minimal).

## Usage

To use this theme, you can use one of the following methods.

### As a Git Submodule

1. Add the theme as a submodule to your Git-managed Hugo site:

   ```bash
   git submodule add https://github.com/ZhongRuoyu/hugo-minimal.git themes/minimal
   ```

2. Add the theme to your `hugo.toml`:

   ```toml
   theme = "minimal"
   ```

### As a Hugo Module

1. Initialize your site as a Hugo module (if not already done):

   ```bash
   hugo mod init github.com/<user>/<repo>
   ```

2. Add the theme to your `hugo.toml`:

   ```toml
   theme = "github.com/ZhongRuoyu/hugo-minimal"

   [module]
   [[module.imports]]
   path = "github.com/ZhongRuoyu/hugo-minimal"
   ```

3. Install the Hugo module:

   ```bash
   hugo mod get
   ```

## Live Demo

A live demo is available at <https://minimal.ruoyu.io>
([GitHub repository](https://github.com/ZhongRuoyu/hugo-minimal-demo)).

## License

Minimal is licensed under [MIT License](LICENSE).
