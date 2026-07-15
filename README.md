# Network Latency Server

Container image:
akcun002/network-latency-server:latest

Required network access:
- TCP port 5014
- UDP port 5014

Environment variable:
OTLP_ENDPOINT=http://3.70.114.43:4317

The Kubernetes Service configuration needs to be adapted
to the networking and external exposure configuration of the
target cluster.