# Polymer 0.8 Benchmarks

A set of benchmarks for performance testing Polymer 0.8. As with all benchmarks your mileage mary vary, so please
do poke around and create your own - we would love to see them. 

Of particular interest will be the `medium-list` benchmark. This instantiates and stamps out templates for a few thousand 
nested custom elements and binds data down through each of them. It measures time to first paint. Please note that device
specs vary wildly, so the only useful comparisons to draw from these numbers are between 0.5 and 0.8.
