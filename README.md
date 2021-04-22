# hasura-engine-benchmark

## How to install

- `npm install`
- `docker-compose up -d`
- `hasura console`
- Add api to remote schemas with url: `http://host.docker.internal:4000/graphql`
  ![Imgur](https://i.imgur.com/IRfY19z.png)

## How to benchmark

- Run `npm run benchmark-api` to benchmark API directly
- Run `npm run benchmark-hasura` to benchmark API as a remote schema of hasura engine.

## Result

- API

  ![Imgur](https://i.imgur.com/9ZKkP7z.png)

- Hasura

  ![Imgur](https://i.imgur.com/vykBgBi.png)
