# Topics <p>
Real challenges of video streaming such as latency and frozen frames. <br>
Look at a re-design of traffic flow in NGINX perspective and mimicking a "CDN-like" architecture. <br>
Tested scenarios and learning points we encountered. <br> 
NGINX configurations are included for your lab test. <br>
How to overcome frames freezing up after a failed LB/Cache node gets UP again. <br>
Failover has no impact to video streaming, it is when a failed node recovered we see an issue with HLS. (DASH is fine) <br>

<p> Documentation Contents
  <br> Challenges
  <br> Fact finding customer’s current architecture
  <br> Enhanced Streaming Distribution Design with NGINX Plus
  <br> Benefits of NGINX Plus
  <br> HLS Behaviour in a Worker Node Failover Scenario
  <br> HLS Behaviour – Frames out of Sync/Frozen Frame after down instance UP again
  <br> Possible operation improvement to address high availability
  <br> Details of fragments out-of-sync observed
  <br> Our Testing Environment
  <br> Prove caching from JMeter Test
  <br> Show NGINX Plus Dashboard
  <br> Simulate Failover
  <br> NGINX Plus Configurations
  <br> JMeter Setup – Load Testing, Concurrent Users/Threads Test
  <br> Grafana Dashboard (Optional)
