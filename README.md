# Slides for an Hibernate Search / Infinispan Query presentation

Best seen by running a local node.js server:

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

Optional. If `grunt` is not found, you might need to install it explicitly:
   ```sh
   $ sudo npm install -g grunt-cli
   ```

4. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

