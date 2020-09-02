你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Cluster API
## What is the Cluster API?

The Cluster API is a Kubernetes project to bring declarative, Kubernetes-style
APIs to cluster creation, configuration, and management. It provides optional,
additive functionality on top of core Kubernetes.

Note that Cluster API effort is still in the prototype stage while we get
feedback on the API types themselves. All of the code here is to experiment with
the API and demo its abilities, in order to drive more technical feedback to the
API design. Because of this, all of the prototype code is rapidly changing.

![Cluster API Architecture](architecture.png "Cluster API Architecture")

To learn more, see the [Cluster API KEP][cluster-api-kep].

## Get involved!

* Join the [sig-cluster-lifecycle](https://groups.google.com/forum/#!forum/kubernetes-sig-cluster-lifecycle)
Google Group for access to documents and calendars.

* Join our Cluster API working group sessions
  * Weekly on Wednesdays @ 10:00 PT on [Zoom][zoomMeeting]
  * Previous meetings: \[ [notes][notes] | [recordings][recordings] \]

* Provider implementer office hours
  * Weekly on Mondays @ 09:30 PT and Tuesdays @ 12:00 PT on [Zoom][zoomMeeting]
  * Previous meetings: \[ [notes][implementerNotes] \]

* Chat with us on [Slack](http://slack.k8s.io/): #cluster-api

## Provider Implementations

The code in this repository is independent of any specific deployment environment.
Provider specific code is being developed in separate repositories, some of which
are also sponsored by SIG-cluster-lifecycle:

  * AWS, https://github.com/kubernetes-sigs/cluster-api-provider-aws
  * AWS/Openshift, https://github.com/openshift/cluster-operator
  * Azure, https://github.com/platform9/azure-provider
  * DigitalOcean, https://github.com/kubernetes-sigs/cluster-api-provider-digitalocean
  * GCE, https://github.com/kubernetes-sigs/cluster-api-provider-gcp
  * OpenStack, https://github.com/kubernetes-sigs/cluster-api-provider-openstack
  * vSphere, https://github.com/kubernetes-sigs/cluster-api-provider-vsphere

## API Adoption

Following are the implementations managed by third-parties adopting the standard cluster-api and/or machine-api being developed here.

  * Machine-controller-manager, https://github.com/gardener/machine-controller-manager/tree/cluster-api
  * Kubermatic machine-controller, https://github.com/kubermatic/machine-controller/tree/master

## Getting Started
### Prerequisites
* `kubectl` is required, see [here](http://kubernetes.io/docs/user-guide/prereqs/).
* `clusterctl` is a SIG-cluster-lifecycle sponsored tool to manage Cluster API clusters. See [here](cmd/clusterctl)

[cluster-api-kep]: https://github.com/kubernetes/community/blob/master/keps/sig-cluster-lifecycle/0003-cluster-api.md
[notes]: https://docs.google.com/document/d/16ils69KImmE94RlmzjWDrkmFZysgB2J4lGnYMRN89WM/edit
[recordings]: https://www.youtube.com/playlist?list=PL69nYSiGNLP29D0nYgAGWt1ZFqS9Z7lw4
[zoomMeeting]: https://zoom.us/j/166836624
[implementerNotes]: https://docs.google.com/document/d/1IZ2-AZhe4r3CYiJuttyciS7bGZTTx4iMppcA8_Pr3xE/edit
