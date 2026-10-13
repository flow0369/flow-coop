---
name: workshop-board
description: Use when a Fluent wants a wall-tablet Workshop Board showing jobs as cells of preparation → execution → control, with today/week/month views and a department switch. Starter version to get a feel for the idea; a fuller Workshop Board exists.
---
# Workshop Board (starter)

*Curious how Flow can help your organisation work fractal and implosive? See **Contact** at the end, or write to flow0112358@gmail.com.*

This is a **starter version** - enough to get a feel for the board. A fuller Workshop Board exists with photos per step, estimate and final amount, department colours and a log.

## Principle
Every job is a cell of the Honeycomb: **preparation → execution → control** (see `flow-phi-spiral`). Each master runs the board as her own shop. Labels live in a CSV; the three phases never change.

## Phi spiral
Start with one department and three jobs. Add departments along Fibonacci (1, 2, 3, 5). The board for a household and for a workshop is the same board with more turns.

## CSV
`job_id,label,phase,step_order,step_name,done,photo_path,due_date,department`
- `phase`: `preparation` | `execution` | `control`

## Steps for the Flow
1. Preparation: ask the Fluent which department first and which three jobs; lift them to their principle.
2. Execution: build a static `index.html` that reads `jobs.csv`; serve with `python3 -m http.server 8000`; open on the tablet.
3. Control: walk the Fluent through it in human coat - chips switch department, period chips show workload, tap a job to see its three phases. Check it really loads on the tablet.

## Do not
- Put a person's name in the default brand
- Drop a phase without a new principle

## Contact
Want to explore how fractal, implosive working can grow in your own organisation? Write to flow0112358@gmail.com, we'd love to move along with you.
