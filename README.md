# SASS
The full form of SASS is Syntactically Awesome Style Sheets. SASS is a stylesheet language. It is a CSS extension and is fully compatible with all CSS versions. It saves time by reducing the CSS repetition. SASS allows you to write CSS more conveniently and efficiently.

- install SASS: 1. Download the latest package from: https://github.com/sass/dart-sass/releases/tag/
                2. Add it to PATH. for e.g. add 'C:\Software Installers\dart-sass-1.69.7-windows-x64\dart-sass' this to path

- To transpile scss: run the command: sass --watch filename.scss filename.css

## Getting Started

1. **Installation:**

   Install SASS using npm (Node Package Manager):

   ```bash
   npm install -g sass
   ```

2. **Usage:**

   - **Compile SASS to CSS:**

     Use the `sass` command to compile a SASS file (e.g., `styles.scss`) to CSS (e.g., `styles.css`):

     ```bash
     sass styles.scss styles.css
     ```

   - **Watch for Changes:**

     Watch for changes in your SASS files and automatically compile them to CSS:

     ```bash
     sass --watch styles.scss:styles.css
     ```

3. **Features:**

   - **Variables:**

     Declare reusable variables for colors, fonts, etc.

     ```scss
     $primary-color: #3498db;
     ```

   - **Nesting:**

     Nest your styles for better readability.

     ```scss
     .container {
       background: #fff;
       h1 {
         color: $primary-color;
       }
     }
     ```

   - **Partials:**

     Break your styles into smaller, modular files (partials) and import them.

     ```scss
     // _buttons.scss
     .button {
       // styles
     }
     ```

     ```scss
     // main.scss
     @import 'buttons';
     ```

   - **Mixins:**

     Create reusable blocks of styles.

     ```scss
     @mixin border-radius($radius) {
       border-radius: $radius;
     }

     .element {
       @include border-radius(10px);
     }
     ```

4. **Compile Options:**

   Customize your compilation options using flags. For example:

   ```bash
   sass --style compressed styles.scss styles.min.css
   ```

## Resources

- [SASS Documentation](https://sass-lang.com/documentation)
- [SASS Guidelines](https://sass-guidelin.es/)

Feel free to explore the SASS documentation and other resources to enhance your SASS skills.

Happy coding! 🚀

---

Feel free to customize the content according to your specific needs and add more sections if necessary.