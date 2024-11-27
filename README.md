
# SAMEri

SAMEri is a static website built using [Hugo](https://gohugo.io/), a fast and flexible static site generator. This project leverages the extended version of Hugo for advanced features like SCSS/SASS processing. It is deployed via [Netlify](https://www.netlify.com/).

[![Netlify Status](https://api.netlify.com/api/v1/badges/18429418-7f50-480c-850b-b2afb368d8b4/deploy-status)](https://app.netlify.com/sites/snazzy-zabaione-74705d/deploys)

## Features

- **Blazing Fast**: Built with Hugo for optimized performance.
- **Responsive Design**: Fully mobile-friendly theme.
- **Customizable**: Easily configurable using the `hugo.toml` file.
- **Netlify Integration**: Automatic deployment and continuous delivery.

## Getting Started

### Prerequisites

- Install [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.139.2 or later).
- A Git client for cloning the repository.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saleh-mehdikhani/sameri.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sameri
   ```

3. Run Hugo to start the local development server:
   ```bash
   hugo server
   ```

   By default, the site will be available at `http://localhost:1313`.

### Configuration

The site configuration is managed in the `hugo.toml` file. Customize it according to your project requirements.

### Building the Site

To generate the static site for deployment, run:

```bash
hugo
```

The built files will be located in the `public/` directory.

## Deployment

SAMEri is deployed on Netlify. The build settings are defined in the `netlify.toml` file. The production build command is:

```bash
hugo
```

### Netlify Badge

This site is automatically deployed to Netlify:
[![Netlify Status](https://api.netlify.com/api/v1/badges/18429418-7f50-480c-850b-b2afb368d8b4/deploy-status)](https://app.netlify.com/sites/snazzy-zabaione-74705d/deploys)

## Troubleshooting

- Ensure you are using the **extended version** of Hugo, as this project uses SCSS/SASS.
- If Netlify build fails, clear the build cache and redeploy.

## Repository

The source code for this project is available on GitHub: [SAMEri Repository](https://github.com/saleh-mehdikhani/sameri).

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Acknowledgements

- [Hugo](https://gohugo.io/)
- [Netlify](https://www.netlify.com/)
