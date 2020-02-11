
# Edgernetes

### 1. Goal

To run resilient compute loads at the edge with little to no intervention, automated setup and enrollment, and easy/scalable management by a small team. The initial design will be focused on IoT workloads, but should be able to also run pure application workloads.


### 2. Philosophies

1.  KISS (why did we choose k8s????)
2.  Zero manual intervention (edge cases… oh god)
3.  Re-use as many other Open Source packages as possible (don't reinvent the wheel)

### 3. Assumptions

1.  Hardware must be minimal (4GB or less of RAM etc)
2.  Must be able to run on a single device at the edge
3.  No control over the local network (DNS
4.  Internet access is available, but intermittent
5.  Bandwidth is either very thin (micro-edge mode, tiny exfiltration) or very fat (complete exfiltration of logs/data)

### 4. Todos

1. Build a roadmap and distill it to JIRA
2. Start weekly meetings / sprints
