# skeleton-react-docker

## To create a new React app
```
docker-compose run app npx create-react-app .
docker-compose run app npx create-react-app . --template typescript

docker-compose run app yarn create vite . --template react-ts
```

## to start yarn start
```
docker-compose up
```

## to use yarn in project
```
docker-compose run web yarn "scripts"
```

## to open your project in browser
http://localhost:3001/



## ESLINT
npx eslint --init

## Husky
yarn add -D husky

## Storybook
npx storybook init
yarn add --dev @storybook/builder-vite
yarn add -D storybook-addon-pseudo-states


## Vite Test
yarn add -D vitest

## Tailwind
yarn add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
