##### PLAY 12

## Use data to drive decisions

At all stages of a digital project, we should measure how well our service is working for our users. This includes measuring how well a system performs and how people are interacting with the system in real time. Our teams and agency leadership should carefully watch these metrics to proactively spot issues and identify which improvements should be prioritized. In addition to monitoring tools, a feedback mechanism should be in place for people to report issues directly.

#### checklist
1. Monitor system-level resource utilization in real time
2. Monitor system performance, measuring response time, latency, throughput, and error rates in real-time
3. Ensure monitoring in place can measure median, 95th percentile and 98th percentile performance
4. Create automated alerts based on this monitoring
5. Track concurrent users in real time, and monitor user behaviors (in the aggregate) to determine how well the service is meeting user needs 
6. Publish metrics internally
7. Publish metrics externally 
8. Use an experimentation tool that supports multivariate testing in production


#### key questions
- What are the key metrics for the service?
- How have these key metrics performed over the life of the service?
- What system monitoring tool(s) are in place?
- What is your target for your service’s average response time for your service? What percent of requests take more than 1 second, 2 seconds, 4 seconds, and 8 seconds?
- What is the average response time and percentile breakdown (percent of requests taking more than 1s, 2s, 4s, and 8s) for your service’s top 10 transactions?
- What is your service’s monthly uptime target?
- What is your service’s monthly uptime percentage including scheduled maintenance? Excluding scheduled maintenance?
- How does your team receive automated alarms when incidents occur? 
- What is the volume of each of your service’s top 10 transactions? What is the percentage of transactions started vs. completed?
- What tool(s) are in place to measure user behavior?
- What tool/technology is used for A/B testing?
- How do you measure customer satisfaction?
