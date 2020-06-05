![https://i.imgur.com/KEbg2dC.jpg](https://i.imgur.com/KEbg2dC.jpg)

# Airbnb Homepage build with Tailwind CSS

[View the tutorial here](https://web-crunch.com/posts/re-create-airbnbs-home-page-with-tailwind-css)

A simple starter project for playing around with Tailwind in a proper PostCSS environment. I used Airbnb as a source of inspiration to teach how to use the framework.

To get started:

1. Clone the repository:

    ```bash
    git clone https://github.com/justalever/tailwind-airbnb tailwind-airbnb

    cd tailwind-airbnb
    ```

2. Install the dependencies:

    ```bash
    # Using npm
    npm install

    # Using Yarn
    yarn
    ```

3. Start the development server:

    ```bash
    # Using npm
    npm run serve

    # Using Yarn
    yarn run serve
    ```

    Now you should be able to see the project running at localhost:8080.

4. Open `public/index.html` in your editor and start experimenting!

## Building for production

Even though this isn't necessarily a starter kit for a proper project, we've included an example of setting up both [Purgecss](https://www.purgecss.com/) and [cssnano](https://cssnano.co/) to optimize your CSS for production.

To build an optimized version of your CSS, simply run:

```bash
# Using npm
npm run production

# Using Yarn
yarn run production
```

After that's done, check out `./public/build/tailwind.css` to see the optimized output.
