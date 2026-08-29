# Study Notes

Daily notes from a 30-day habit: **1 hour DSA (NeetCode 75) + 1 hour System Design**, with 5-10 minutes of writing after each session.

Rough thinking (brute force ideas, wrong attempts, scratch work) stays on pen and paper and isn't part of this repo. What's here is the cleaned-up version: what I actually learned, written in my own words, after solving.

## Structure

~~~text
study-notes/
  README.md
  dsa/
    til.md
    arrays.md
    two-pointers.md
    sliding-window.md
    stack.md
    binary-search.md
    linked-list.md
    trees.md
    tries.md
    heap.md
    backtracking.md
    graphs.md
    dp.md
  system-design/
    til.md
    01-foundations.md
    02-storage-caching.md
    03-distributed-systems.md
    04-putting-together.md
    05-case-studies.md
~~~

- One file per **topic** (DSA) or **phase** (System Design) — not one file per question.
- Related problems/concepts stay grouped together so patterns are easy to spot later.
- `til.md` in each folder is a running list of small, specific things learned that don't belong to one problem or concept — language quirks, tool behavior, things that caused confusion.

## Workflow

1. Solve the problem / study the concept first, with no notes open.
2. For System Design specifically, draw the concept on paper before writing anything digital.
3. Once solved or understood, write one entry using the templates below.
4. Anything unexpected or easy to forget goes in that folder's `til.md`.

## Templates

### DSA Entry

Goes in the matching topic file, e.g. `dsa/arrays.md`.

~~~md
## <Problem name>

**Pattern:** <e.g. two pointers, sliding window, hashmap>

**Approach:** <2-3 sentences, own words, why it works>

**Time/Space:** O(?) / O(?)

**Gotcha:** <one thing that would've saved time going in>
~~~

### System Design Entry

Goes in the matching phase file, e.g. `system-design/01-foundations.md`.

~~~md
## <Concept name>

**What it solves:** <the actual problem this addresses>

**How it works:** <described the way it was drawn, in words>

**Tradeoffs:** <the real decision being made, not just a definition>

**Gotcha:** <what was wrong or confusing at first>
~~~

### System Design Case Study Entry

Days 28-30 go in `system-design/05-case-studies.md`.

~~~md
## <System name, e.g. URL Shortener>

**Requirements:** <what was asked>

**My design:** <what I drew, described in words>

**What I missed:** <gaps found comparing to a reference solution>
~~~

### TIL Entry

Goes in `dsa/til.md` or `system-design/til.md`.

~~~md
- <one line, specific fact>
~~~

Example:

~~~md
- `sorted()` returns a new list, doesn't sort in place
~~~

## Progress Log

Kept at the bottom of this README, updated daily.

~~~text
Day 1 - Aug 30 - DSA: Arrays & Hashing (2 problems) | SD: Client-server model, DNS/HTTP/TCP basics
Day 2 - Aug 31 - DSA: Arrays & Hashing (2 problems) | SD: APIs, latency vs throughput
~~~

## Why This Exists

Started after a long stretch of only building projects, with pen-and-paper concept study having lapsed.

The goal for the first 30 days is **building the habit of daily, deliberate study — not full mastery**.

DSA follows **NeetCode 75** in topic order with review days every 6 sessions.

System Design follows a 5-phase roadmap:

1. **Foundations**
2. **Storage & Caching**
3. **Distributed Systems Concepts**
4. **Putting It Together**
5. **Applied Case Studies**

The goal is simple: **solve, understand, write, repeat.**
