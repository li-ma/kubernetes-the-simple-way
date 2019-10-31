# Kubernetes The Simple Way

This work is mainly inspired by the awesome tutorial [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way). The tutorial I mentioned above assumes the reader has a Google Cloud Platform account. It teaches how to build a simple virtual network on the GCP for Kubernetes. However, for lots of none-GCP users, it is not intuitive and needs more work to do which is out of the scope of that tutorial. This is way I'd like to share the missing parts in this project, which aims to bootstraping a Virtualbox-powered Kubernetes environment by manual configuration.

Kubernetes The Simple Way is a learning guide for one-master-one-worker deployment pattern, which a Intel i5 laptop with 8GB memory is able to support. For multi-node high available cluster deployment, please refer to the tutorial I mentioned above.

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Component Version

* [virtualbox](https://www.virtualbox.org) 6.0.14
* [Ubuntu Server](https://ubuntu.com/download/server) 19.10
* [kubernetes](https://github.com/kubernetes/kubernetes) 1.15.3
* [containerd](https://github.com/containerd/containerd) 1.2.9
* [coredns](https://github.com/coredns/coredns) v1.6.3
* [cni](https://github.com/containernetworking/cni) v0.7.1
* [etcd](https://github.com/coreos/etcd) v3.4.0
