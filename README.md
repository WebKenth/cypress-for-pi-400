docker build -t cypress-test .


docker run -v $(pwd)/video:/app/cypress/videos --rm cypress-test npx cypress run
