

cd <workshop dir>
git clone https://github.com/netwerk-digitaal-erfgoed/network-of-terms.git

cd netwerk-of-terms

Run the server using the local nodejs environment:

npm install

cd packages/network-of-terms-graphql
npm run dev

Or run the server within a docker container:

cd network-of-terms
docker compose run --service-ports --rm node
npm install

cd packages/network-of-terms-graphql
npm run dev

You will find the GraphQL API on http://localhost:3123

