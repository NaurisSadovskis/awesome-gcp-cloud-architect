# 2.1 - Compute Engine

Compute Engine delivers virtual machines running in Google's innovative data centers and worldwide fiber network.

## Timeline
* September 2017 - [Meet Compute Engine’s new managed instance group updater](https://cloudplatform.googleblog.com/2017/09/meet-Compute-Engines-new-managed-instance-group-updater.html)
* September 2017 - [Committed use discounts for Google Compute Engine now generally available](https://cloudplatform.googleblog.com/2017/09/committed-use-discounts-for-Google-Compute-Engine-now-generally-available.html)
* February 2018 - [96 vCPU Compute Engine instances are now generally available](https://cloudplatform.googleblog.com/2018/02/96-vCPU-Compute-Engine-instances-are-now-generally-available.html)

## Resources
NEXT videos (YouTube):
* [Building high-performance, scalable VM environments with Google Compute Engine](https://www.youtube.com/watch?v=5BDz-npbnlE)
* [Saving Money on Compute Engine (Google Cloud Next '17)](https://www.youtube.com/watch?v=W3K3dM7NFxY)
* [Large scale and batch computing on Google Compute Engine (Google Cloud Next '17)](https://www.youtube.com/watch?v=Tq6JPXoKdcM)
* [Best practices for Identity and Access Management on Compute Engine (Google Cloud Next '17)](https://www.youtube.com/watch?v=qf_D92_yqbQ)

General documentation: 
* [**Compute Engine Documentation**](https://cloud.google.com/compute/docs/)
* [Concepts](https://cloud.google.com/compute/docs/concepts)
* [FAQ](https://cloud.google.com/compute/docs/faq)
* [Release Notes](https://cloud.google.com/compute/docs/release-notes)
* [Compute How-To Guides](https://cloud.google.com/compute/docs/how-to)
* [Compute Tutorials](https://cloud.google.com/compute/docs/tutorials)
* [Infrastructure software](https://cloud.google.com/compute/docs/infrastructure-software)
* [Pricing](https://cloud.google.com/compute/pricing)

## SDK
```sh
$ gcloud compute
ERROR: (gcloud.compute) Command name argument expected.
Usage: gcloud compute [optional flags] <group | command>
  group may be           accelerator-types | addresses | backend-buckets |
                         backend-services | commitments | disk-types | disks |
                         firewall-rules | forwarding-rules | health-checks |
                         http-health-checks | https-health-checks | images |
                         instance-groups | instance-templates | instances |
                         interconnects | machine-types | networks | operations |
                         os-login | project-info | regions | routers | routes |
                         shared-vpc | snapshots | ssl-certificates |
                         ssl-policies | target-http-proxies |
                         target-https-proxies | target-instances |
                         target-pools | target-ssl-proxies |
                         target-tcp-proxies | target-vpn-gateways | url-maps |
                         vpn-tunnels | xpn | zones
  command may be         config-ssh | connect-to-serial-port | copy-files |
                         reset-windows-password | scp | ssh
```

SDK reference docs can be found [here](https://cloud.google.com/sdk/gcloud/reference/compute/). 

## Summary
Flexibility: 10

Complexity: 7

Performance: 10

Cost: 3.5