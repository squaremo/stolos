# Stolos (fleet) controller

A controller for bulk configuration in Kubernetes clusters, built on Flux.

This is a rewrite of the [fleeet controller][fleeet] I developed at Weaveworks a few
years ago, to

 - port it to GitOps Toolkit (all the packages used for Flux controllers) 
 - rebase the design on an abstraction of tenancy
 
[fleeet]: https://github.com/weaveworks-experiments/fleeet

## Roadmap

 - [ ] port the designs from Fleeet over and rewrite them to account for tenancy
 - [ ] implement the designs using the Flux controller runtime packages
