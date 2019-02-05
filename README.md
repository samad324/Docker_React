This project was an example of Docker with React.

## Available Scripts

If you want to run it on development environment then, In the project directory, you can run:

### `docker-compose up`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

You will also see any lint errors in the console.

For only docker,

### ` docker build -f Dockerfile.dev . `

then copy the image id and then, 

### `docker run -p 3000:3000 <image_id>`

If you want to create build and run your project in Production,

### `docker build .`

then, 

### 'docker run -p 3000:80 <image_id>'

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.



