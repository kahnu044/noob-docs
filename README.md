
# NoobDocs

NoobDocs is a beginner-friendly documentation site built using [Next.js](https://nextjs.org/) and [Nextra](https://nextra.vercel.app/). It provides an intuitive platform for developers to create and maintain technical documentation effortlessly.

## Features

- **Markdown Support:** Write documentation using Markdown files.
- **Search Functionality:** Easily search through your documentation.
- **Sidebar Navigation:** Nestable sidebar for clean navigation structure.
- **Responsive Design:** Fully responsive and optimized for all devices.
- **Customizable Themes:** Choose from a variety of themes to match your style.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v12.x or later)
- [Git](https://git-scm.com/)

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/kahnu044/noob-docs.git
    ```

2. Navigate into the project directory:

    ```bash
    cd noobdocs
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Deploying

You can easily deploy NoobDocs using platforms like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/). For a seamless deployment experience, follow the official documentation:

- [Vercel Deployment Docs](https://vercel.com/docs)
- [Netlify Deployment Docs](https://docs.netlify.com/)

## File Structure

```bash
├── public          # Static assets
├── pages
│   └── index.mdx   # Main entry point for the docs
├── styles          # Custom CSS or styling
├── components      # Custom components (if any)
└── next.config.js  # Next.js configuration file
```

## Customization

To add new documentation pages, simply create a new `.mdx` file inside the `pages` folder. You can configure your sidebar and navigation by updating `theme.config.js`.

For detailed customization, refer to the official [Nextra documentation](https://nextra.vercel.app/docs).

## Contributing

Contributions are welcome! If you'd like to contribute to NoobDocs, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit) file for details.

## Author
[kahnu044](https://github.com/kahnu044/)