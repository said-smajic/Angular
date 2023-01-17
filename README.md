# Angular

To run the app:
- Open your terminal
- Navigate to your folder in terminal
- Run following commands:
  - docker build --pull --rm -f "Todo-App/Dockerfile" -t angular:latest "Todo-App" 
  - docker run --rm -d -p 80:80/tcp angular:latest
  - Navigate to your browser and search for: localhost:80

After all is installed, just run **ng serve --open** to open app in your browser.
