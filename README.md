# Hanuma Datacenter Simulator

Hanuma Datacenter Simulator — an interactive, browser-only data center shift simulation. Open `index.html` in a browser — no build step, no server needed.

## What is in it

- **Shift dashboard, first:** active tickets, rack alerts, maintenance tasks, and handover notes, in the flow: review tickets → inspect equipment → troubleshoot → resolve or escalate → document → hand over.
- **Dell PowerEdge trainer:** one interactive server. Break a server by fault code or by part, read the alert, find the part, and repair it step by step.
- **Whole rack, alongside the server:** a 14-unit 42U rack, top to bottom, power at the bottom. Break, restore, or create a ticket for any unit — patch panel, router, firewall, IDS/IPS, load balancer, core switch, servers, storage, KVM, backup, cooling, cable management, UPS, and PDU.
- **Day-in-the-life workflows:** shift tickets (priority first, then oldest, no time limit, a new ticket every 2 minutes), rack and stack by section, fiber test (inspection, cleaning, VFL, OTDR — testing and replacement only), DECOM, power and cooling walk, and outage drill.
- **Verification before closing a ticket:** server health check, link status check, and ticket update check, plus closure notes.

## Demo data only

All faults, temperatures, part specs, and counts in the trainer are demo data, not from a real site. Voltage and processor faults clear on first fix in the trainer, but in real life a remaining voltage fault means board replacement, and a recurring processor error means processor replacement.

## How to play

1. Open `index.html` in a browser (in-app previews may look empty because they do not run page scripts — use a real browser).
2. Start on the Shift dashboard, work the Next up ticket, and use Break a server / Whole rack to run more errors.
3. After a repair, tick all three verification checks and write closure notes before closing a ticket.
