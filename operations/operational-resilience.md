# Operational Resilience  
*Because downtime costs more than your ego.*

Stability isn’t sexy. It doesn’t win awards. But it’s the difference between a company getting paid vs. waking up to a blown SLA.

At MarPhil, I lead with resilience first. We stabilize systems before chasing the next toy. The result? Uptime targets, fewer firefights, and teams that breathe again.

## What Resilience Means to Me
- 99.95% uptime is not overkill; it’s survival in a competitive market.  
- Automation is only helpful if failure modes are anticipated and controlled.  
- Recovery time matters more than how fast you go when everything is fine.  

## How I Build It
1. **Incident First Response** – Always have a “stop the bleed” protocol. Don’t let small faults cascade.  
2. **Postmortems > Blame** – Dissect what went wrong, document, and prevent recurrence.  
3. **Redundancy Layers** – Nothing single-threaded. Backup paths, failovers, circuit breakers.  
4. **Chaos Engineering Lite** – Occasional stress tests, simulations, and “what if” drills.  
5. **Signal Over Noise** – Not every alert warrants a page — tune your alerts so ops see what matters, not what clogs their day.  

## Example
In one client environment, a sudden DNS outage took down core functionality. Because layers were in place, the failover path picked up traffic almost instantly, minimizing customer impact. Later, the audit showed the DNS step wasn’t isolated — so we re-architected that path and added synthetic tests to catch it early.

## Lessons
- Resilience is built, not bought.  
- Systems fail. Plan that in.  
- When things break, your recovery writes your reputation.
