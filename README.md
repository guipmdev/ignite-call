<!-- ===== HEADER ===== -->
<p align="right">
  <img
    src="https://img.shields.io/badge/lang-en-gray?style=flat-square&labelColor=202024"
    alt="lang-en"
  />
  <a href="./README.pt-br.md" title="Ler o README em português brasileiro">
    <img
      src="https://img.shields.io/badge/lang-pt--br-green?style=flat-square&labelColor=202024"
      alt="lang-pt-br"
    />
  </a>
</p>

<h1 align="center">
  <a
    href="https://guipmdev-ignite-call.vercel.app/"
    title="Go to the web application"
    >Ignite Call</a
  >
</h1>

<p align="center">
  <img
    src="https://img.shields.io/github/languages/count/guipmdev/ignite-call?color=%2304D361&labelColor=202024"
    alt="Repository language count"
  />
  <img
    src="https://img.shields.io/github/repo-size/guipmdev/ignite-call?labelColor=202024"
    alt="Repository size"
  />
  <img
    src="https://img.shields.io/github/commit-activity/m/guipmdev/ignite-call?color=black&labelColor=202024"
    alt="Commit activity"
  />
  <a
    href="https://github.com/guipmdev/ignite-call/commits/main"
    title="View repository commits"
  >
    <img
      src="https://img.shields.io/github/last-commit/guipmdev/ignite-call?labelColor=202024"
      alt="Last commit"
    />
  </a>
  <a href="./LICENSE" title="View project license">
    <img
      src="https://img.shields.io/badge/license-MIT-brightgreen?labelColor=202024"
      alt="Project license"
    />
  </a>
  <a href="https://www.rocketseat.com.br/" title="Go to the Rocketseat website">
    <img
      src="https://img.shields.io/badge/Layout_by-Rocketseat-8257e5?labelColor=202024"
      alt="Layout designer"
    />
  </a>
</p>

![Screenshot of the application initial page](./src/assets/images/cover.webp)

<p align="center">
  <a href="https://guipmdev-ignite-call.vercel.app/"
    >Go to the web application ↗</a
  >
</p>

<details>
  <summary>
    <h2>📒 Table of Contents</h2>
  </summary>

- [📍 Overview](#-overview)
- [✨ Features](#-features)
- [🤖 Demo](#-demo)
- [🎨 Layout](#-layout)
- [🛠 Technologies](#-technologies)
  - [Website](#website)
  - [Back-end](#back-end)
  - [Utils](#utils)
- [🚀 Getting Started](#-getting-started)
  - [✔️ Prerequisites](#️-prerequisites)
  - [📦 Installation](#-installation)
  - [⚙️ Usage](#️-usage)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)
</details>

<!-- ===== PROJECT INFOS ===== -->

## 📍 Overview

This project is a scheduling web application developed in _Next.js_ and _TypeScript_ that allows users to create and manage their schedules. It offers features such as user registration, profile management, connection to Google Calendar and creation of scheduling events.

The application aims to simplify the agenda management process and ensure that users have an efficient and organized way of managing their time. Its value proposition lies in its seamless integration with Google Calendar, its user-friendly interface and its robust scheduling and availability management functionality.

## ✨ Features

🏷 **Reserve your username** for later

📅 Seamlessly sync your agenda with **Google Calendar integration**

👥 Personalize your experience with easy **user registration and profile management**

➕ **Create scheduling events without conflicts** and add them into your Google Calendar

🔗 **Share your link** and watch events pops right into your agenda.

## 🤖 Demo

## 🎨 Layout

The layout of the application was designed by **Rocketseat** and is available on [Figma](<https://www.figma.com/file/5NSfvvfsVxKatf19vsoshN/Ignite-Call-(Community)>).

<p align="center">
  <img
    src="./src/assets/images/layout-cover.webp"
    alt="Web application layout image cover"
    width="50%"
  />
</p>

## 🛠 Technologies

The following tools were used to build the project:

### Website

<p>
  <a href="https://nextjs.org/">
    <img
      src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js"
      alt="Next.js"
    />
  </a>
  <a href="https://www.typescriptlang.org/">
    <img
      src="https://img.shields.io/badge/TypeScript-white?style=for-the-badge&logo=TypeScript"
      alt="TypeScript"
    />
  </a>
  <a href="https://eslint.org/">
    <img
      src="https://img.shields.io/badge/ESLint-101828?style=for-the-badge&logo=ESLint"
      alt="ESLint"
    />
  </a>
  <a href="https://github.com/rocketseat/eslint-config-rocketseat">
    <img
      src="https://img.shields.io/badge/Rocketseat_ESLint_config-gray?style=for-the-badge"
      alt="Rocketseat ESLint config"
    />
  </a>
</p>

<p>
  <a href="https://axios-http.com/">
    <img
      src="https://img.shields.io/badge/Axios-373747?style=for-the-badge&logo=Axios"
      alt="Axios"
    />
  </a>
  <a href="https://react-hook-form.com/">
    <img
      src="https://img.shields.io/badge/React_Hook_Form-060e21?style=for-the-badge&logo=react-hook-form"
      alt="React Hook Form"
    />
  </a>
  <a href="https://github.com/colinhacks/zod">
    <img
      src="https://img.shields.io/badge/Zod-3068b7?style=for-the-badge&logo=zod"
      alt="Zod"
    />
  </a>
  <a href="https://next-auth.js.org/">
    <img
      src="https://img.shields.io/badge/NextAuth.js-black?style=for-the-badge&logo=data:image/webp;base64,UklGRgwJAABXRUJQVlA4WAoAAAAQAAAAQAAARwAAQUxQSPwBAAABkGzbtmlXc58kz7Zt20acUlJ6tlmybdt+Jdu2bdu41rm+9+y91g9ExARAbeVJb0xvJ1cB13abPnp8ofqnze3o5et96p/XF633/6neeQlVm/bQ6ZPpeDS9GgUtfttn3Sdf/7wtXlNSoP9Zk0+96Wy/fHJE9RmPnD6qzofTqxrJnLbri+6jrX/eFh8bofjIy2YfT9PZ/vmBts9cPs7Ohy2++rifMbM7b2J3mt8pfif/8/vLbuYZdp1Ws0sYz01v0JmbqXQzL7MPuQq7md3VhIXZIeALs2XATWbDgZ3MUoFRvFw1gDa8vuQF8rpYXRMAfrHaCAA3WA0PWcrJ2zokntPPQiHZHYwuiRC8ZDQPYdczSgsXz+df8XBxFjZnRThcYTMWEftxcdeLlNPO5H5cJFxjMgNR9uLhbhhNVjOLG7HRYDeLkYi6rs7gT4no8IDBehjMoOdqZER7R+6YMILu1PSOMKw9InZUM4YWdlKOxpAoNpPaBKnlvhD6WVoOBhMaCslxh8gcj5WFcu+IfK0I+WlWEu50KBSjSEyB0tiVBLbHqEHmXcoOZYfq3LsVHcoJ9Tk3KTmQExQzLdDlrc8KmrGD/kpyjAZZ0eqWlOdJoJx/ns2QvrYQaGstjxq4lAj6MRmXorjXPRNYxqXstvp8PvuR9KxgK6pP2D2uNhQDVlA4IOoGAACwIgCdASpBAEgAAAAAJbACEHCSek/hT+yX96+TGk/yz7hfr9/fsxT5f/sH5Mf4z2M+kF/SD+s/kB/MOEj/E/6B/kP7p7QH8z6wD+f/0LrEfQA/Y/1SP7v/1f8b8C36//7f/T/v/9BP8x/n/+14ADrVe1D/K9EokLxR2uOS3fP/8/+W+qQfbB6pPDC/vX5VfAf4zexL5q9gT+Pfx/++/2b9u/77//+Ue/VU6Z11eW5x3Mibsbt9o7G0CcY3DYaYy/YXJYBAYn+9XvA+2uzW5/ymapo+PNjdfN6yY0JDL9hw8g3hx+6dtY5wPTFkOYMl9faWNciws1SYmNdIuYozfgSHPcPW12pndGEdRjr18fCxLPDsoeJz/y2WVYjczeQAAP7/9pqCNXfYqlk9mLD00uMTyl9iFv1+CAOY83AvpGqxn8x3q6JqOqvtGsd9pRcxlp7j9zamC+RQxovd1NZu+cCke6POf//yo4h5lv5Ngg1SaUczFAG54xVhOhlbJ+hAvPV1OkEOya+6tbPkAY0uZD2mlKz9dN89xc+EDlnB1VC+jzMeSbk7Y+Q3boT0x/Kh9y8CTCWOtEp1LYaEtXcptWKtYGz01g58reVuzqutwEYkQUCz+qEiot/f35XVMF6Fmg4V7gNMv0xrPjEAZ7mFue4yifSidH02526q+yzzD3p8m0j1pa89n6BwDg4xOWA4iZg0UcfrktdIUdfo3H+REGXyosn7KTeugiG45RrtED1K+g9x2pdCVji5uq0kpu/k8BvU9SeOsPQ/09P4W4Pi8XuL4GO0R88fM2FKKu2xwVQWs6EZQv7gvqi/xneGmfyaB2x8ZQCudlkKHe3ojPmeBOdpO09KNIJJ6F0TLUe828XCa9oaS//8vFFBpqJ+mgi4ct/mAGS71233QfzuSWOc69+dySxz1mEpsNzolHOH4QYWH3Viit2sFoFnJpbO4xXABjuxYJlET6yRgsdOLMAUmmE6rGryX/hQc3smNEj/Yz+YyFagjKMAwl9f/YCOw4JTDEglKupLyVGWL+UFd5e8VFuaS16vJkV/FtWoaHhDvqsQ1lUZnGP/AhI4L7qpNVF21CfS+L3ppK2a0bJoNEHOJkOHH/F3zv4ivc+fgJvH9fl1gW0pCZrVUmRgVp4MMU1XhYSPspMHnbjgEYnRPgrGdVhTUb5iRIrqDVKzSCOztjVPoNDcHioIs7FRRX5YsHX7YvxvC6cH9Of/Pgaq5g134MzG7y9yB2PCu+EnjR91xXWj/dl/z+eaxhm+XpIhKhsjl0KymYGs8Y7vss9ACh38xaWA2OX3XjqsH0hZl491vr614biAnfg/zX5f4N9ppVMHwEmp5RysT85nZfhHLCVM4UJy07DRbL067dEH5vqJ8wAfQEk0MAsXIwUfsJX3zp/F+dGynEDxMUyQZh2Lg9kbVMty10qKXZjE0/H+xS+JVKGoWT7q3oR1iImdIhpAyMJZBKZ7+Dbk7ECzROCDtCDm+qb0a/jeLBt3ieex732+dX8sL12OokT9Da8JM3fcCbAOBQWSae1syvkeVPbCBB2kjSjNwcEYPQ3iSc6+fHk+TvwsfBwd9V6sBfv4C/rMQDpnh7p0Ede6JA60EYdb/DBwk/g5tRSAGeAH3DZfXsjVHG5fcBoLd9vvtMKh4rAdfvSxc2Pvb8JzS2IZVvMbqCciAASdvUMyViZRvP1e1+yvWFQ+ybzij8SHIsM3LNaSn/T2GDPW6JTgOJbCjuoROIf/+XkN4eiAuOcAcIEzo3JDzx4xrBLnZjJqvhqsStJ0IE2t0N3sjAVRWrPy23DdpsdLfGEmCbfKaD4cKz4Wg/o8Aicz/6qlpwCP91x2dwyNG90b6HLzvnNphIXfKigjxo5lyVJSD+m4ibGgxCvfNImUWpUHW5oAo58rIq0lkGaHu9OPnz/4q72h4IwOur4KC+noNW1wzqtDpTPeGj3fPIgdKIGevKi4EvDLPdr5LMHA/Y//lKHtng5BeNaD8rHQNYTxbkXtNxZrPOevQMRm2qOggsBRTeZFsJgV7iMJNh8w/OdAZYoRPYZLg51mf+GmD7/47/7Y35R+W7NzEKXun4rVXGQK7dP+h4udaJ9mArPmfE4nnoNbPFMvo5Xmu5Ny1QMgTfD/zhM/iuku97Sb+E8wLchNqsa/9JnYZvSNs2uUJ5SEpMRGezD+2kaxVLeBe19CXT+4BbhqWC1QbCD3i7oojwkXA+Gy2ZHF6AMMFh2/kxk/1eF+1PRjImfaa7peb+Rj4M+amwAmXPgDfEvsnqJK32UaRyouxy9X0oAamwvX1iPgaboPiqGbD4ZC6Z19NOLkWLmS6Wd1yLOE0hwb//Rrk5xqTgz41v5tQQAAAAA="
      alt="NextAuth.js"
    />
  </a>
  <a href="https://day.js.org/">
    <img
      src="https://img.shields.io/badge/Day.js-ff5f4c?style=for-the-badge"
      alt="Day.js"
    />
  </a>
  <a href="https://github.com/garmeeh/next-seo">
    <img
      src="https://img.shields.io/badge/Next SEO-gray?style=for-the-badge"
      alt="Next SEO"
    />
  </a>
</p>

<p>
  <a href="https://phosphoricons.com/">
    <img
      src="https://img.shields.io/badge/Phosphor_Icons-eeeae3?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzMiIGhlaWdodD0iNDQiIHZpZXdCb3g9IjAgMCAzMyA0NCIgZmlsbD0ibm9uZSIKICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogIDxwYXRoIGQ9Ik0xNy4xMDI2IDAuMDUwMjU3NUgxLjQ5NDM0QzEuMTk0NDYgMC4wNTAyNTc1IDAuOTA2ODU5IDAuMTY5MzggMC42OTQ4MTUgMC4zODE0MjVDMC40ODI3NyAwLjU5MzQ3IDAuMzYzNjQ3IDAuODgxMDU2IDAuMzYzNjQ3IDEuMTgwOTNWMjguOTE4OUMwLjM2NzQ2NCAzMi44OTQ4IDEuOTQ3OTMgMzYuNzA3IDQuNzU4NDUgMzkuNTE5M0M3LjU2ODk3IDQyLjMzMTYgMTEuMzgwMSA0My45MTQ1IDE1LjM1NjEgNDMuOTIwOUMxNS41MDQ1IDQzLjkyMDkgMTUuNjUxNiA0My44OTE3IDE1Ljc4ODcgNDMuODM0OEMxNS45MjU5IDQzLjc3OCAxNi4wNTA2IDQzLjY5NDcgMTYuMTU1NiA0My41ODk3QzE2LjI2MDYgNDMuNDg0NyAxNi4zNDM4IDQzLjM2MDEgMTYuNDAwNyA0My4yMjI5QzE2LjQ1NzUgNDMuMDg1NyAxNi40ODY3IDQyLjkzODcgMTYuNDg2NyA0Mi43OTAyVjMwLjA0OTVIMTcuMDkzQzE5LjA4NTQgMzAuMDg1MiAyMS4wNjQ5IDI5LjcyMzYgMjIuOTE2IDI4Ljk4NThDMjQuNzY3MSAyOC4yNDgxIDI2LjQ1MjYgMjcuMTQ4OSAyNy44NzQyIDI1Ljc1MjVDMjkuMjk1OSAyNC4zNTYxIDMwLjQyNSAyMi42OTA1IDMxLjE5NTkgMjAuODUyOUMzMS45NjY3IDE5LjAxNTMgMzIuMzYzNyAxNy4wNDI2IDMyLjM2MzcgMTUuMDQ5OUMzMi4zNjM3IDEzLjA1NzIgMzEuOTY2NyAxMS4wODQ1IDMxLjE5NTkgOS4yNDY4N0MzMC40MjUgNy40MDkyOCAyOS4yOTU5IDUuNzQzNjYgMjcuODc0MiA0LjM0NzI4QzI2LjQ1MjYgMi45NTA4OSAyNC43NjcxIDEuODUxNzMgMjIuOTE2IDEuMTEzOTVDMjEuMDY0OSAwLjM3NjE2OCAxOS4wODU0IDAuMDE0NTcyMyAxNy4wOTMgMC4wNTAyNTc1SDE3LjEwMjZaTTE0LjIxNTcgNDEuNjExNEMxMS4yNDQzIDQxLjM0MTIgOC40NjE1OSA0MC4wMzc4IDYuMzUxNzggMzcuOTI4QzQuMjQxOTcgMzUuODE4MSAyLjkzODU2IDMzLjAzNTQgMi42NjgzMiAzMC4wNjRIMTQuMjE1N1Y0MS42MTE0Wk0xNC4yMTU3IDI0LjEzMTVMMy4zMjc0OSAyLjMxMTYxSDE0LjIzNUwxNC4yMTU3IDI0LjEzMTVaTTE3LjEwMjYgMjcuNzg4MkgxNi40OTY0VjIuMzExNjFIMTcuMTAyNkMxOC43OTYyIDIuMjc4NjkgMjAuNDc5NCAyLjU4Mzg2IDIyLjA1MzcgMy4yMDkyM0MyMy42MjggMy44MzQ2IDI1LjA2MTggNC43Njc2MyAyNi4yNzEyIDUuOTUzNzVDMjcuNDgwNiA3LjEzOTg3IDI4LjQ0MTMgOC41NTUyNyAyOS4wOTcyIDEwLjExNzFDMjkuNzUzIDExLjY3OSAzMC4wOTA4IDEzLjM1NTkgMzAuMDkwOCAxNS4wNDk5QzMwLjA5MDggMTYuNzQzOSAyOS43NTMgMTguNDIwOCAyOS4wOTcyIDE5Ljk4MjdDMjguNDQxMyAyMS41NDQ1IDI3LjQ4MDYgMjIuOTU5OSAyNi4yNzEyIDI0LjE0NkMyNS4wNjE4IDI1LjMzMjEgMjMuNjI4IDI2LjI2NTIgMjIuMDUzNyAyNi44OTA2QzIwLjQ3OTQgMjcuNTE1OSAxOC43OTYyIDI3LjgyMTEgMTcuMTAyNiAyNy43ODgyWiIgZmlsbD0iY3VycmVudENvbG9yIi8+Cjwvc3ZnPgo="
      alt="Phosphor Icons"
    />
  </a>
</p>

### Back-end

<p>
  <a href="https://www.prisma.io/">
    <img
      src="https://img.shields.io/badge/Prisma-2d3748?style=for-the-badge&logo=prisma"
      alt="Prisma"
    />
  </a>
  <a href="https://tanstack.com/query/">
    <img
      src="https://img.shields.io/badge/TanStack_Query-111827?style=for-the-badge&logo=react-query"
      alt="TanStack Query"
    />
  </a>
  <a href="https://github.com/googleapis/google-api-nodejs-client">
    <img
      src="https://img.shields.io/badge/Google_APIs-white?style=for-the-badge&logo=google"
      alt="Google APIs"
    />
  </a>
  <a href="https://github.com/maticzav/nookies">
    <img
      src="https://img.shields.io/badge/nookies-gray?style=for-the-badge"
      alt="nookies"
    />
  </a>
</p>

_\* See the [<kbd>package.json</kbd>](./package.json) file_

### Utils

<p>
  <a href="https://git-scm.com/">
    <img
      src="https://img.shields.io/badge/Git-f1f1e9?style=for-the-badge&logo=git"
      alt="Git"
    />
  </a>
  <a href="https://nodejs.org/">
    <img
      src="https://img.shields.io/badge/Node.js-233056?style=for-the-badge&logo=node.js"
      alt="Node.js"
    />
  </a>
  <a href="https://figma.com/">
    <img
      src="https://img.shields.io/badge/Figma-white?style=for-the-badge&logo=figma"
      alt="Figma"
    />
  </a>
  <a href="https://fonts.google.com/">
    <img
      src="https://img.shields.io/badge/Google_Fonts-white?style=for-the-badge&logo=google-fonts"
      alt="Google Fonts"
    />
  </a>
  <a href="https://code.visualstudio.com/">
    <img
      src="https://img.shields.io/badge/VSCode-005293?style=for-the-badge&logo=visual-studio-code"
      alt="VSCode"
    />
  </a>
  <a href="https://www.docker.com/">
    <img
      src="https://img.shields.io/badge/Docker-white?style=for-the-badge&logo=docker"
      alt="Docker"
    />
  </a>
</p>

<p>
  <a href="https://planetscale.com/">
    <img
      src="https://img.shields.io/badge/PlanetScale-111111?style=for-the-badge&logo=planetscale"
      alt="PlanetScale"
    />
  </a>
  <a href="https://vercel.com/">
    <img
      src="https://img.shields.io/badge/Vercel-0a0a0a?style=for-the-badge&logo=vercel"
      alt="Vercel"
    />
  </a>
</p>

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following tools installed on your machine: [Git](https://git-scm.com/downloads), [Node.js](https://nodejs.org/en/download). It's also good to have an editor to work with the code, such as [VSCode](https://code.visualstudio.com/Download).

### 📦 Installation

1. Clone the repository:

```sh
git clone https://github.com/guipmdev/ignite-call/
```

2. Change to the project directory:

```sh
cd ignite-call
```

3. Install the dependencies:

```sh
npm install
```

### ⚙️ Usage

1. Create a SQL database and note down the connection details

   - This can be a local database, a remote database, or even a [Docker](https://www.docker.com/) container

2. Visit [Google Cloud Console](https://console.cloud.google.com/apis/dashboard), create a project, enable Google Calendar API, and, under Credentials, create an OAuth 2.0 client ID, configure the consent screen, and get Client ID and Secret

3. Generate a secure secret key for NextAuth.js

   - If you’re on a UNIX system, you can use the command `openssl rand -base64 32` to generate this key

4. Rename the file `.env.example` to `.env` and insert the necessary information:

```sh
mv .env.example .env
```

5. Generate the migrations, if necessary:

```sh
npx prisma migrate dev
```

6. Push the migrations to the database:

```sh
npx prisma db push
```

7. Start the web application:

```sh
npm run dev
```

8. Access http://localhost:3000/ to view the application

## 📄 License

This project is licensed under the terms of the `MIT` license. See the
[LICENSE](./LICENSE) file for additional info.

## 👏 Acknowledgments

> - Many thanks to [Rocketseat](https://www.rocketseat.com.br/) for the layout and tips when putting this project together

<!-- ===== FOOTER ===== -->

---

<p align="center">
  Made with 💙 by
  <a href="https://www.guipm.dev/"> @guipm.dev </a>
  - Feel free to
  <a href="mailto:guipm.dev@gmail.com">contact me</a>!
</p>

<br />

<p align="center">
  <a href="#top">
    <b>↑&nbsp;&nbsp; Return to the top &nbsp;&nbsp;↑</b>
  </a>
</p>
