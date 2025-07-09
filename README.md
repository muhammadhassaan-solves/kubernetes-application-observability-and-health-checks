<h1>Kubernetes Application Observability and Health Checks</h1>


<h2>Description</h2>
This project demonstrates Kubernetes health checks using liveness, readiness, and startup probes. It covers resource monitoring with Metrics Server and practical debugging of failing Pods. The goal is to build reliable, observable applications with production-grade probe configurations and monitoring tools.
<br />


<h2>Languages and Utilities Used</h2>

- Kubernetes  
- kubectl  
- YAML  
- Metrics Server  
- NGINX  


<h2>Project Walk-through</h2>

<p align="center">
Implemented liveness probe to auto-restart unhealthy containers <br />
<img src="https://i.postimg.cc/JhYJfkW7/1.jpg"/>
<br />
<br />
Added readiness probe to control traffic flow to containers <br/>
<img src="https://i.postimg.cc/DzKgwsW2/2.jpg"/>
<br />
<br />
Configured startup probe for slow-initializing apps <br/>
<img src="https://i.postimg.cc/7YF1K7ng/3.jpg" />
<br />
<br />
Enabled Metrics Server to monitor CPU and memory usage  <br/>
<img src="https://i.postimg.cc/ZqcrYQtc/4.jpg"/>
<br />
<br />
Simulated a failing Pod and debugged using kubectl logs and describe <br/>
<img src="https://i.postimg.cc/jqWZvsrY/5.jpg" />
<br />
<br />
Deployed a multi-replica Deployment for observability testing <br/>
<img src="https://i.postimg.cc/76j1j2y8/7.jpg" />
<br />

</p>

