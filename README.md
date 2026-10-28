# Pradeep Venkatachalam — Portfolio

A React 19 + Vite portfolio styled as a REST API console. All portfolio content is managed in `src/data/portfolio.js`.

## Run Locally

```bash
npm install
npm run dev
```

## Available Commands

```bash
npm run lint
npm run build
```

The production build is generated in the `dist/` directory.

## Project Structure

- `src/components/Sections.jsx` — Navbar, Hero, About, Skills, Projects, Deployment, Experience, Achievements, Education, Contact and Footer.
- `src/data/portfolio.js` — Portfolio content and data.
- `src/App.css` — Layout and component styles.
- `src/index.css` — Global styles, design tokens and reset.
- `public/` — Profile image, resume PDF and favicon.
- `Dockerfile` — Multi-stage Docker build using Node.js and Nginx.

## Deployment

This portfolio can be containerized with Docker and deployed to cloud platforms such as AWS and Microsoft Azure.

### Build the Docker Image

```bash
docker build -t pradeep-portfolio .
```

### Run the Container

```bash
docker run -d -p 8080:80 --name portfolio pradeep-portfolio
```

Open [http://localhost:8080](http://localhost:8080) to view the portfolio.

## Technologies

- React 19
- Vite
- JavaScript
- CSS
- Docker
- Nginx
- AWS and Azure deployment fundamentals
