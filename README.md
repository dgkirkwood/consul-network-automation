# consul-network-automation

Sample code snippets to demonstrate how Consul helps automate network infrastructure changes. 

## Prerequisites

* consul
* consul-template


## Demo Environment

These examples were designed to be used with [https://demo.consul.io](https://demo.consul.io)


## Getting started

1. Clone this repository

```
git clone https://github.com/kecorbin/consul-network-automation
cd consul-network-automation
export CONSUL_HTTP_ADDR=https://demo.consul.io
```

2. Review the .sh files, these create the templates for rendering device/tool/API specific configurations, as well as invoke consul-template to render them.  

**NOTE**: consul-template can also supervisor a process and automatically restart it with generated configs. 

