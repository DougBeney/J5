![J5 Logo](/static/img/favicon.png =50x50)

# J5 -  A Jekyll, Pug, Sass, and Livereload HTML5 Boilerplate

## How To Install:

1. Clone this git repository into your project directory.
2. In your terminal, change into your project directory.
3. Type the command `bundle install`

## How To Run

Type the command `bundle exec jekyll serve` or simply `jekyll serve`.


## Project Structure

- **(root directory)** - In your root directory, you can create pages like regular. You can also create Pug pages - just make sure you add YAML front-matter or Pug won't be rendered
- **_layouts** - In this folder you can add your layouts like usual. Pug is supported. Unlike in your root directory, you do not need to provide YAML front-matter with Pug layouts.
- **static** - The static folder is meant for css, js, and images. The css folder supports sass files by default.

## Jekyll Plugins Used

- [**Jekyll-Pug by Doug Beney**](https://github.com/DougBeney/jekyll-pug) - This is what allows us to process Pug within Jekyll. Please read the [Github page](https://github.com/DougBeney/jekyll-pug) to understand all the ins-and-outs of this plugin.
- [**Jekyll-Livereload by Robert DeRose**](https://github.com/RobertDeRose/jekyll-livereload) - Allows browser livereload when running a jekyll server.

## Final Notes

**I hope this helps you increase productivity while coding!**
