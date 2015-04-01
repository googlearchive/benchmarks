# Polymer 0.8 Benchmarks

A set of benchmarks for performance testing Polymer 0.8. As with all benchmarks your mileage mary vary, so please
do poke around and create your own - we would love to see them. 

Of particular interest will be the `medium-list` benchmark. This instantiates and stamps out templates for a few thousand 
nested custom elements and binds data down through each of them. It measures time to first paint. Please note that device
specs vary wildly, so the only useful comparisons to draw from these numbers are between 0.5 and 0.8.

## Running benchmarks

The benchmarks can be run online over on [GitHub pages](http://polymerlabs.github.io/benchmarks/).

To run the benchmarks locally, you’ll need a basic HTTP server to serve your pages. If you have Python installed, you can run one of the following commands in the top level of the checked out benchmarks repo:

Python 2.x:

```
python -m SimpleHTTPServer
```

Python 3.x:

```
python -m http.server
```

If you don't have Python and just have Node/npm:

```
# install http-server
npm install -g http-server
# to serve the current directory
http-server
```

Once the root page has been served, click the `Run medium-list` link to begin running the benchmarks.
