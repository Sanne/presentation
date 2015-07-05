# Experiments
Playground to experiment with presentation frameworks

1. Install [Node.js](http://nodejs.org/) and [Grunt](http://gruntjs.com/getting-started#installing-the-cli)
   On Fedora:
  ```sh
   $ sudo dnf install npm nodejs-grunt
   ```

2. Install dependencies of this project (run within the git checkout):
   ```sh
   $ npm install
   ```

3. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

4. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

