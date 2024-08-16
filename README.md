# Boulder High Landsharks Website

[![Fancy Deploy](https://github.com/Team1157/site/actions/workflows/deploy.yml/badge.svg)](https://github.com/Team1157/site/actions/workflows/deploy.yml)
[![Dependabot Updates](https://github.com/Team1157/site/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/Team1157/site/actions/workflows/dependabot/dependabot-updates)
[![Pages Build Deployment](https://github.com/Team1157/site/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Team1157/site/actions/workflows/pages/pages-build-deployment)

> [!Note]  
> The website is temporarily available at [https://1157.adabit.org](https://1157.adabit.org) until the actual domain is renewed.

## Getting Started

Follow these steps to get a local copy of the project up and running for development.

### Prerequisites

Ensure you have a suitable version of [Node.js](https://nodejs.org/), [npm](https://www.npmjs.com/), [python3](https://www.python.org/), [pil](https://pypi.org/project/image/), and [pnpm](https://pnpm.io/) installed

- if you're running arch just install it all with ```yay -S npm pnpm python3 python-image node```

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Team1157/site
   ```

2. **Navigate to the project directory:**

   ```bash
   cd site
   ```

3. **Install dependencies:**

   ```bash
   pnpm install
   ```

### Development

- **Start the development server:**

  ```bash
  pnpm src:dev
  ```

> [!TIP]
> Prettier will automatically format your code upon committing.

> [!TIP]
> To add photos to the photos page put them in ```public/img/archive``` and they'll automatically be added to the page on commit.
