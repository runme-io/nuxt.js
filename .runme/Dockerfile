FROM node:12-alpine
WORKDIR /app
RUN yarn create nuxt-app demo --answers "'{\"name\":\"demo\",\"description\":\"\",\"author\":\"\",\"language\":\"js\",\"pm\":\"yarn\",\"ui\":\"none\",\"server\":\"none\",\"runtime\":\"none\",\"features\":\"[]\",\"linter\":\"[]\",\"test\":\"none\",\"mode\":\"universal\",\"devTools\":\"[]\"}'"
RUN cd demo
CMD ["yarn", "dev"]
EXPOSE 3000