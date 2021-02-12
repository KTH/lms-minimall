# LMS Mini-mall

A minimal template –_mall_ in Swedish \*badumtss\*– for Node.js web applications. It has:

- Developer dependencies and npm commands
- [skog](https://github.com/kth/skog) and [Pino](https://github.com/pinojs/pino) for logging
- [express](http://expressjs.com/), framework to create a server
- [dotenv](https://github.com/motdotla/dotenv) for reading `.env` files
- And a super-simple `src/app.js` file that does almost anything
- KTH-specific Docker-related files

## Getting started

[▶️▶️▶️▶️ Use this as a template!](https://github.com/kth/lms-minimall/generate)

And then…

- Install all dependencies

  ```
  npm install
  ```

- Run the app in development mode

  ```
  npm run dev
  ```

### 📝 Checklist for production

- [] Change the `name` (and author, if needed) in `package.json`
- [] Change the `IMAGE_NAME` in `docker.conf`
- [] Modify the `LICENSE` if needed

---

## Philosophy

This template does not make any assumptions on what kind of application you are building

### What does NOT contain?

Any **feature** or decision:

- Routes. It is up to you to decide how to organise routes and routers
- Template library. You decide if you **need** them and which one to use
- Session handling, authentication, access to database, etc.

### What does contain?

- Dev dependencies: prettier and eslint for formatting and linting; jest for testing
- NPM commands: `npm test`, `npm run format` and `npm run dev`
- KTH-specific Docker-related files: `Dockerfile`, `docker-compose-unit-tests.yml`, `.dockerignore`

## Contributing

You can contribute to this project by opening issue or PRs to it.
