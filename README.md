# AuthorIntro Widget for Wowchemy

_[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio, generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs._

## 🌈 Add the Widget to your Site

1. Install the shortcode in your site by referencing it at the bottom of your `config/_defaults/config.toml`:
   ```toml
   # At the bottom of your `config.toml` is a Module section:
   [module]

     # Your existing modules will appear here.

     [[module.imports]]
       path = "github.com/Chrede88/wowchemy-shortcode-figArray"
   ```
2. Use the shortcode:
   ```markdown
   {{< github-Chrede88-figArray numCols=<numCols> srcArray="image1.jpg,image2.jpg,image3.jpg" thumbCaption="thumb1,thumb2,thumb3" figCaption="figCaption" >}}
   ```

