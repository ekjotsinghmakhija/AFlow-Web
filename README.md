<h1 align="center" style="border-bottom: none">AFlow Web<br>
⭐️ The Notion Alternative ⭐️
</h1>
<p align="center"> Use AFlow right in <a href="/">your browser</a><br>
</p>


<p align="center">
Bring projects, wikis, and teams together with AI
</p>
<p align="center">
    <a href="/"><b>Web</b></a> •
    <a href="/">Apps</a> •
    <a href="/"><b>Discord</b></a> •
    <a href="/"><b>Twitter</b></a> •
    <a href="/"><b>Reddit</b></a> •
    <a href="/"><b>Forum</b></a>
</p>


## Use cases
- Build and maintain a knowledge base for your team
- Create and publish documentation for your customers and audience
- Write, publish, and manage content with AI
- Manage tasks and projects for yourself and your team

## Features
- Write beautiful documents with rich content types
- Add a Quick Note to jot down lists, ideas, or to-dos
- Invite members to your workspace for seamless collaboration
- Create multiple public and private spaces to better organize your content

## Built with 🛠️
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## Development

For local development, please follow the steps below:
1. Install [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/)
2. Clone the AFlow Cloud repository.
3. Copy deploy.env to .env, then run `docker-compose up -d`.
4. The AFlow Cloud API should be running on localhost:80, and allow CORS from localhost:3000 by default.
5. Setup at least one sign in method: SMTP for magic link, or using an OAuth provider. Refer to AFlow Cloud repository for more details.

### Running AFlow Web Locally
1. Copy .development.env to .env. The default value assumes that AFlow Cloud is deployed on localhost. If not, please update the value of the API endpoints.
2. Make sure `npm` has been installed on your dev environment, then run the following:
```
# npm install pnpm@8.5.0
pnpm install

pnpm run dev
```

Open your browser to visit localhost:3000

## Deployment
Once AFlow Cloud has been setup, you can follow the [deployment guide](/)
to deploy AFlow Web.

## License
Distributed under the AGPLv3 License. See [`LICENSE.md`](/) for
more information.
