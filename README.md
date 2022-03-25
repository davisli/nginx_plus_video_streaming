# Topics <p>
Real challenges of video streaming such as latency and frozen frames. <br>
Look at a re-design of traffic flow in NGINX perspective and mimicking a "CDN-like" architecture. <br>
Tested scenarios and learning points we encountered. <br> 
NGINX configurations are included for your lab test. <br>
How to overcome frames freezing up after a failed LB/Cache node gets UP again. <br>
Failover has no impact to video streaming, it is when a failed node recovered we see an issue with HLS. (DASH is fine) <br>

Documentation Contents
  Challenges
  Fact finding customer’s current architecture
  Enhanced Streaming Distribution Design with NGINX Plus
    Benefits of NGINX Plus
  Learnings
    HLS Behaviour in a Worker Node Failover Scenario
    HLS Behaviour – Frames out of Sync/Frozen Frame after down instance UP again
    Possible operation improvement to address high availability
    Details of fragments out-of-sync observed
  Our Testing Environment
    Start Video Broadcast (10 minutes video)
      Stream script
      At Worker 1 and 2, you will see the fragments being populated.
  Launch Video Client
    Prove caching from JMeter Test
    Show NGINX Plus Dashboard
  Simulate Failover
    Stop nginx process in Worker 1 to simulate a failure
  NGINX Plus Configurations
    Ingest Server
    Worker Nodes (Same for all Nodes)
    LB/Cache Nodes (“Peace” Time)
    LB/Cache Nodes (“Failover” Time)
  JMeter Setup – Load Testing, Concurrent Users/Threads Test
  Grafana Dashboard (Optional)
