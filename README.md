git clone url
npm install
npx newman run collections/collection.json -e env/preprod.json -r cli,htmlextra
