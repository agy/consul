---
layout: "docs"
page_title: "Guides"
sidebar_current: "docs-guides"
description: |-
  This section provides various guides for common actions. Due to the nature of Consul, some of these procedures can be complex, so our goal is to provide guidance to do them safely.
---

# Consul Guides

This section provides various guides for common actions. Due to the nature
of Consul, some of these procedures can be complex, so our goal is to provide
guidance to do them safely.

The following guides are available:

* [ACLs](/docs/guides/acl.html) - This guide covers Consul's Access Control List (ACL) capability, which can be used to control access to Consul resources.

* [Adding/Removing Servers](/docs/guides/servers.html) - This guide covers how to safely add and remove Consul servers from the cluster. This should be done carefully to avoid availability outages.

* [Autopilot](/docs/guides/autopilot.html) - This guide covers Autopilot, which provides automatic operator-friendly management of Consul servers.

* [Bootstrapping](/docs/guides/bootstrapping.html) - This guide covers bootstrapping a new datacenter. This covers safely adding the initial Consul servers.

* [Connect in Production](/docs/guides/connect-production.html) - This guide describes critical aspects of operating Consul Connect in Production.

* [Connect with Envoy](/docs/guides/connect-envoy.html) - This guide will describe how to setup a development-mode Consul server and two Envoy proxies on a single machine using Docker.

* [Consul with Containers](/docs/guides/consul-containers.html) - This guide describes critical aspects of operating a Consul cluster that's run inside containers.

* [Consul Template](/docs/guides/consul-template.html) - This guide covers the Consul template tool, which provides a programmatic method for populating values into the file system.

* [Consul-AWS](/docs/guides/consul-aws.html) - This guide covers the Consul-AWS tool, which syncs Consul's and AWS Cloud Map's service catalog.

* [Creating Certificates](/docs/guides/creating-certificates.html) - This guide describes how to setup CA and certificates to secure a Consul cluster with TLS.

* [Deployment Guide](/docs/guides/deployment-guide.html) - This deployment guide covers the steps required to install and configure a single HashiCorp Consul cluster as defined in the Consul Reference Architecture.

* [DNS Caching](/docs/guides/dns-cache.html) - Enabling TTLs for DNS query caching

* [DNS Forwarding](/docs/guides/forwarding.html) - Forward DNS queries from Bind to Consul

* [External Services](/docs/guides/external.html) - This guide covers registering an external service. This allows using 3rd party services within the Consul framework.

* Federation ([Basic](/docs/guides/datacenters.html) and [Advanced](/docs/guides/areas.html)) - Configuring Consul to support multiple datacenters.

* [Geo Failover](/docs/guides/geo-failover.html) - This guide covers using [prepared queries](/api/query.html) to implement geo failover for services.

* [Minikube with Consul](/docs/guides/minikube.html) - In this guide, you'll start a local Kubernetes cluster with minikube, install Consul,and then deploy two custom services.

* [Leader Election](/docs/guides/leader-election.html) - The goal of this guide is to cover how to build client-side leader election using Consul.

* [Monitoring Consul with Telegraf](/docs/guides/monitoring-telegraf.html) - This guide demonstrates how to setup Consul for monitoring with Telegraf.

* [Network Segments](/docs/guides/segments.html) - Configuring Consul to support partial LAN connectivity using Network Segments.

* [Outage Recovery](/docs/guides/outage.html) - This guide covers recovering a cluster that has become unavailable due to server failures.

* [Consul Reference Architecture](/docs/guides/deployment.html) - This document provides recommended practices and a reference architecture, including system requirements, datacenter design, networking, and performance optimizations for Consul production deployments.

* [Semaphore](/docs/guides/semaphore.html) - This guide covers using the KV store to implement a semaphore.

* [Sentinel](/docs/guides/sentinel.html) - This guide covers using Sentinel for policy enforcement in Consul.

* [Server Performance](/docs/guides/performance.html) - This guide covers minimum requirements for Consul servers as well as guidelines for running Consul servers in production.

* [Windows Service](/docs/guides/windows-guide.html) - This guide covers how to run Consul as a service on Windows.
